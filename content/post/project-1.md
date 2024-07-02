---
date: 2024-06-27
description: "A weighted ensemble logistic model that predicts whether one drug could be used to treat for a new treatment based on how similar the biological effects are between pairs of drugs."
featured_image: "/images/drug_repurposing_cover.jpg"
tags: ["computational biology", "data science", "drug repurposing"]
title: "Predicting New Indications for Known Drugs Based on Similarity in Drug Signatures"
---

 Drug repurposing offers a quicker and potentially more cost-effective approach to finding new treatments by repositioning existing drugs with known safety profiles for alternative therapeutic indications. To accelerate the discovery of drug repurposing, the LINCS 1000 project has measured the in vitro effect of hundreds of drugs on gene expression across many cancer cell lines. Using this data, we propose a new approach to facilitating the discovery of new indications of known drugs. Our exploratory analysis revealed that drugs that share an indication caused similar changes in gene expression. However, we found that this was only true for samples that had a high transcriptional activity score (TAS). Therefore, we developed a method that predicts new indications for a drug based on both similarity in gene expression and TAS. Our premise is that when two drugs cause high TAS in a cell line, and cause similar changes in expression, they may treat the same conditions. Our ensemble approach integrates predictions from multiple cell lines. Finally, we evaluate this method’s ability to predict new indications of known drugs using data from clinical trials.

* [Video Overview of Project](https://drive.google.com/file/d/1TbS_vYcOG7l2CkxO_X6ZclnxegiBjkzI/view?usp=sharing)
* [Poster Overview of Project](https://drive.google.com/file/d/1zaT1cC6QiFU8lyMQw7n7pVucjD2awz50/view?usp=sharing)
* [Link to GitHub Repository](https://github.com/kthuang20/LINCS_dataset)


If you have any additional questions regarding this project or want to follow up, feel free to reach out to 
Katie_Huang@student.uml.edu or Rachel_Melamed@uml.edu.