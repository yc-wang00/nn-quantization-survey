# Characterizing generalization under out-of-distribution shifts in deep metric learning

## Summary

Summary: The paper introduces the out-of-distribution deep metric learning (ooDML) benchmark to test zero-shot generalization performance for different train-test splits. The study finds that some deep metric learning methods can retain performance better as out-of-distribution shifts increase. The paper proposes few-shot deep metric learning to improve generalization for future unknown test shifts presented in ooDML.


## Target Task

computer vision

## Content

<Abstract: >Deep Metric Learning (DML) aims to find representations suitable for zero-shot transfer to a priori unknown test distributions. However, common evaluation protocols only test a single, fixed data split in which train and test classes are assigned randomly. In this work, we systematically construct train-test splits of increasing difficulty and present the ooDML benchmark to characterize generalization under out-of-distribution shifts in DML. Based on our new benchmark, we conduct a thorough empirical analysis of state-of-the-art DML methods. We find that while generalization tends to consistently degrade with difficulty, some methods are better at retaining performance as the distribution shift increases. Finally, we propose few-shot DML as an efficient way to consistently improve generalization in response to unknown test shifts presented in ooDML.



---

