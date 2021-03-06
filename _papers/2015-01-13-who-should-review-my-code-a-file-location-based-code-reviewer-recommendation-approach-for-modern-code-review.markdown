---
layout: paper
date:   2015-01-13 00:00:00
title:  "Who Should Review My Code? A File Location-Based Code-Reviewer Recommendation Approach for Modern Code Review"
authors: "<u>Patanamon Thongtanunam</u>, Chakkrit Tantithamthavorn, Raula Gaikovina Kula, Norihiro Yoshida, Hajimu Iida, Ken-ichi Matsumoto"
venue: "The 22nd IEEE International Conference on Software Analysis, Evolution, and Reengineering (SANER2015)"
pubyear: 2015
acceptance: "32% (46/144)"
s_venue: SANER
preprint: https://www.researchgate.net/publication/273699454_Who_Should_Review_My_Code_A_File_Location-Based_Code-Reviewer_Recommendation_Approach_for_Modern_Code_Review
abstract: "Software code review is an inspection of a code change by an independent third-party developer in order to identify and fix defects before an integration. Effectively performing code review can improve the overall software quality. In recent years, Modern Code Review (MCR), a lightweight and tool-based code inspection, has been widely adopted in both proprietary and open-source software systems. Finding appropriate code-reviewers in MCR is a necessary step of reviewing a code change. However, little research is known the difficulty of finding code-reviewers in a distributed software development and its impact on reviewing time. In this paper, we investigate the impact of reviews with code-reviewer assignment problem has on reviewing time. We find that reviews with code-reviewer assignment problem take 12 days longer to approve a code change. To help developers find appropriate code-reviewers, we propose RevFinder, a file location-based code-reviewer recommendation approach. We leverage a similarity of previously reviewed file path to recommend an appropriate code-reviewer. The intuition is that files that are located in similar file paths would be managed and reviewed by similar experienced code-reviewers. Through an empirical evaluation on a case study of 42,045 reviews of Android Open Source Project (AOSP), OpenStack, Qt and LibreOffice projects, we find that RevFinder  accurately recommended 79% of reviews with a top 10 recommendation. RevFinder also correctly recommended the code-reviewers with a median rank of 4. The overall ranking of RevFinder is 3 times better than that of a baseline approach. We believe that RevFinder could be applied to MCR in order to help developers find appropriate code-reviewers and speed up the overall code review process."
slides: //www.slideshare.net/slideshow/embed_code/45430752
addition: "<label>Replication Data:</label> <a href='https://github.com/patanamon/revfinder'>available at GitHub</a>"
---
@inproceedings{ThongtanunamSANER2015,
	Author={Patanamon Thongtanunam and  Chakkrit Tantithamthavorn and  Raula Gaikovina Kula and  Norihiro Yoshida and  Hajimu Iida and  Ken-ichi Matsumoto},
	Title = {Who Should Review My Code? A File Location-Based Code-Reviewer Recommendation Approach for Modern Code Review},
	Booktitle = {Proceeedings of the the 22nd IEEE International Conference on Software Analysis, Evolution, and Reengineering (SANER)},
	Pages = {141--150},
	Year = {2015}
}