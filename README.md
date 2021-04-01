# COMPARE

<br/>

![alt text](figures/taxonomy.png "Taxonomy of Comparison Discussions in Peer Reviews" | width=100)
<br/>

## Exemplar sentences for each aspect and subcategory
|Sentence                                                                                                                                                                                                      |Aspect  |Subcategory|
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|-----------|
|It would be nice if the authors include results on a dataset like ImageNet.                                                                                                                                   |Dataset |D0_Neg     |
|The data is derived from an online repository of around 1500 Android apps, which makes the data realistic and very respectable in terms of the scale.                                                         |Dataset |D1_Pos     |
|The experimental validation is not extensive since comparison to SOTA is not included.                                                                                                                        |Baseline|B0_Neg     |
|The authors do not compare against some relevant, recent work like Falkner et al 2017.                                                                                                                        |Baseline|B1_Neg     |
|I would like to see an ablation analysis of all the differences between the base model and the proposed one.                                                                                                  |Baseline|B2_Neg     |
|The comparison is a bit unfair since the proposed method performs pooling over images, while the baseline (average mask) is not translation invariant.                                                        |Baseline|B3_Neg     |
|I appreciate that the authors added a detailed comparison to Bartlett et al 2017 bound.                                                                                                                       |Baseline|B4_Pos     |
|The authors present a convincing set of results over many translation tasks and compare with very competitive baselines.                                                                                      |Baseline|B5_Pos     |
|The paper would also be significantly more compelling if the strategy was applied to more varied tasks.                                                                                                       |Task    |T0_Neg     |
|It is expected to see whether the proposed method is also effective for image classification.                                                                                                                 |Task    |T1_Neg     |
|To provide a better understanding, the paper evaluates the performance on synthesized digit sequence data as well as several sentence-encoding tasks.                                                         |Task    |T2_Pos     |
|The distance metrics that are considered are only L_inf and L1, whereas it would be interesting to see more relevant "perceptual losses" such as those used in style transfer and domain adaptation with GANs.|Metric  |M0_Neg     |
|Furthermore, the paper provides power measurements, which is really the main metric that anyone working seriously in that space cares about.                                                                  |Metric  |M1_Pos     |
