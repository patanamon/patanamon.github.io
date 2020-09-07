---
layout: paper
date: 2020-09-10 00:00:00
title:  "Predicting Defective Lines Using a Model-Agnostic Technique"
authors: "Supatsara Wattanakriengkrai, Patanamon Thongtanunam, Chakkrit Tantithamthavorn,Hideaki Hata, and Kenichi Matsumoto"
venue: "IEEE Transaction on Software Engineering"
pubyear: 2020
acceptance: 
preprint: https://www.researchgate.net/publication/344149308_Predicting_Defective_Lines_Using_a_Model-Agnostic_Technique
s_venue: TSE
abstract: "Defect prediction models are proposed to help a team prioritize source code areas files that need Software Quality Assurance (SQA) based on the likelihood of having defects. However, developers may waste their unnecessary effort on the whole file while only a small fraction of its source code lines are defective. Indeed, we find that as little as 1%-3% of lines of a file are defective. Hence, in this work, we propose a novel framework (called LINE-DP) to identify defective lines using a model-agnostic technique, i.e., an Explainable AI technique that provides information why the model makes such a prediction. Broadly speaking, our LINE-DP first builds a file-level defect model using code token features. Then, our LINE-DP uses a state-of-the-art model-agnostic technique (i.e., LIME) to identify risky tokens, i.e., code tokens that lead the file-level defect model to predict that the file will be defective. Then, the lines that contain risky tokens are predicted as defective lines. Through a case study of 32 releases of nine Java open source systems, our evaluation results show that our LINE-DP achieves an average recall of 0.61, a false alarm rate of 0.47, a top 20%LOC recall of 0.27, and an initial false alarm of 16, which are statistically better than six baseline approaches. Our evaluation shows that our LINE-DP requires an average computation time of 10 seconds including model construction and defective identification time. In addition, we find that 63% of defective lines that can be identified by our LINE-DP are related to common defects (e.g., argument change, condition change). These results suggest that our LINE-DP can effectively identify defective lines that contain common defects while requiring a smaller amount of inspection effort and a manageable computation cost. The contribution of this paper builds an important step towards line-level defect prediction by leveraging a model-agnostic technique.
"

---
@inproceedings{Al-WattanakriengkraiTSE2020,
	Author={Wattanakriengkrai, Supatsara and Thongtanunam, Patanamon and Tantithamthavorn, Chakkrit
	Hata, Hideaki and  Matsumoto, Kenichi},
	Title = {Predicting Defective Lines Using a Model-Agnostic Technique},
	Booktitle = {IEEE Transaction on Software Engineering},
	Pages = {to appear},
	Year = {2020},
	doi = {}
}

