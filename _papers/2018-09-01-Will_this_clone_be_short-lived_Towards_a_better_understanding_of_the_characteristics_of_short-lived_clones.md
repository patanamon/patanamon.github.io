---
layout: paper
date: 2018-09-01 00:00:00
title:  "Will this clone be short-lived? Towards a better understanding of the characteristics of short-lived clones"
authors: "<u>Patanamon Thongtanunam</u>, Weiyi Shang, Ahmed E. Hassan"
venue: "The Journal of Empirical Software Engineering (EMSE)"
pubyear: 2018
acceptance: 
s_venue: EMSE
preprint: https://www.researchgate.net/publication/327419089_Will_this_clone_be_short-lived_Towards_a_better_understanding_of_the_characteristics_of_short-lived_clones
abstract: "Code clones are created when a developer duplicates a code fragment to reuse existing functionalities. Mitigating clones by refactoring them helps ease the long-term maintenance of large software systems. However, refactoring can introduce an additional cost. Prior work also suggest that refactoring all clones can be counterproductive since clones may live in a system for a short duration. Hence, it is beneficial to determine in advance whether a newly-introduced clone will be short-lived or long-lived to plan the most effective use of resources. In this work, we perform an empirical study on six open source Java systems to better understand the life expectancy of clones. We find that a large number of clones (i.e., 30% to 87%) lived in the systems for a short duration. Moreover, we find that although short-lived clones were changed more frequently than long-lived clones throughout their lifetime, short-lived clones were consistently changed with their siblings less often than long-lived clones. Furthermore, we build random forest classifiers in order to determine the life expectancy of a newly-introduced clone (i.e., whether a clone will be short-lived or long-lived). Our empirical results show that our random forest classifiers can determine the life expectancy of a newly-introduced clone with an average AUC of 0.63 to 0.92. We also find that the churn made to the methods containing a newly-introduced clone, the complexity and size of the methods containing the newly-introduced clone are highly influential in determining whether the newly-introduced clone will be short-lived. Furthermore, the size of a newly-introduced clone shares a positive relationship with the likelihood that the newly-introduced clone will be short-lived. Our results suggest that, to improve the efficiency of clone management efforts, practitioners can leverage our classifiers and insights in order to determine whether a newly-introduced clone will be short-lived or long-lived to plan the most effective use of their clone management resources in advance."

---
@article{thongtanunam2018emse,
	Author={Patanamon Thongtanunam and Weiyi Shang and Ahmed E. Hassan},
	Title = {Will this clone be short-lived? Towards a better understanding of the characteristics of short-lived clones},
	Booktitle = {Empirical Software Engineering (EMSE)},
    volume = {},
    number = {},
	pages = {In press},
	Year = {2018},
    doi = {10.1007/s10664-018-9645-2}
}

