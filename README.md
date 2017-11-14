# Replication Package for "Towards Just-in-time Suggestions for Log Changes"

Heng Li, Weiyi Shang, Ying Zou, and Ahmed E. Hassan  
**[Empirical Software Engineering Journal, vol. 22, issue 4, 2017](https://doi.org/10.1007/s10664-016-9467-z)**

Abstract: Software developers typically insert logging statements in their source code to record runtime information. However, providing proper logging statements remains a challenging task. Prior approaches automatically enhance logging statements, as a post-implementation process. Such automatic approaches do not take into account developers’ domain knowledge; nevertheless, developers usually need to carefully design the logging statements since logs are a rich source about the field operation of a software system. The goals of this paper include: i) understanding the reasons for log changes; and ii) proposing an approach that can provide developers with log change suggestions as soon as they commit a code change, which we refer to as “just-in-time” suggestions for log changes. In particular, we derive a set of measures based on manually examining the reasons for log changes and our experiences. We use these measures as explanatory variables in random forest classifiers to model whether a code commit requires log changes. These classifiers can provide just-in-time suggestions for log changes. We perform a case study on four open source projects: Hadoop, Directory Server, Commons HttpClient, and Qpid. We find that: (i) The reasons for log changes can be grouped along four categories: block change, log improvement, dependence-driven change, and logging issue; (ii) our random forest classifiers can effectively suggest whether a log change is needed: the classifiers that are trained from within-project data achieve a balanced accuracy of 0.76 to 0.82, and the classifiers that are trained from cross-project data achieve a balanced accuracy of 0.76 to 0.80; (iii) the characteristics of code changes in a particular commit and the current snapshot of the source code are the most influential factors for determining the likelihood of a log change in a commit.

## BibTeX

```bibtex
@Article{Li2017,
author="Li, Heng
and Shang, Weiyi
and Zou, Ying
and E. Hassan, Ahmed",
title="Towards just-in-time suggestions for log changes",
journal="Empirical Software Engineering",
year="2017",
month="Aug",
day="01",
volume="22",
number="4",
pages="1831--1865",
issn="1573-7616",
doi="10.1007/s10664-016-9467-z",
url="https://doi.org/10.1007/s10664-016-9467-z"
}
```

## Data and Scripts

The package encompasses:
- Replication data
- Correlation analysis results
- Regular expressions for identifying log changes

You can find the latest version [here](https://github.com/SAILResearch/replication-jit_log_suggestions/releases/latest)
