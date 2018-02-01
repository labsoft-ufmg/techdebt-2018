## About study

<p align="justify">This web page presents a large-scale empirical study (based on more than 3 thousand systems) to investigate whether and how thresholds vary among systems of different domains. We argue that the definition of appropriate thresholds needs to be tailored to each metric by the software domain. Therefore, we defend the idea of domain-specific thresholds, given that systems from different domains may have distinct characteristics and, it may impair the derived metric thresholds. As consequence, it can increase the number of false positive anomalies, for instance.</p> 


<p align="justify">This study relies on fifteen software domains composed of object-oriented Java systems. We apply to each system a set of eight well-known source code metrics. After applying the measurements, we derived 90% and 95% thresholds for each metric per domain, compared, and analyzed them. For instance, we compared the thresholds among domains and analyzed the effectiveness of God Class detection between domain-specific and generic thresholds. </p>

## Research Questions for Code Smell Analysis

For each system of our Smell Dataset, we built an oracle of true positive instances. First, we run three well-known code smell detection tools (JDeodorant, JSpirit, and PMD) for all target systems and build a list with possible anomalies pointed by these tools. Then, at least a pair of authors analyzed each class pointed as God Class to validate our oracle manually. This manual validation consisted of the answer of four questions below.

```markdown
RQ1. Does the class have more than one responsibility?

RQ2. Does the class have functionality that would fit better into other classes?

RQ3. Do you have problems summarizing the class responsibility in one sentence?

RQ4. Would splitting up the class improve the overall design?
```

## Downloads

**All data used in this study are available.**

Click here to download the Reference List of God Class. <a href="https://github.com/labsoft-ufmg/techdebt-2018/raw/master/Data/Oracle.pdf" download="Download"><img src="https://cdn2.iconfinder.com/data/icons/snipicons/5000/download-alt-48.png" /></a>

Click here to see the raw data, which contains metrics of each software domains used in this study. <a href="https://github.com/labsoft-ufmg/techdebt-2018/tree/master/Data/Metrics" target="_blank"><img src="https://cdn2.iconfinder.com/data/icons/snipicons/5000/download-alt-48.png" /></a>
