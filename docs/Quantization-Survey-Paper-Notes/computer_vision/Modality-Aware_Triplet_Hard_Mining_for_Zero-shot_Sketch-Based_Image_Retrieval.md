# Modality-Aware Triplet Hard Mining for Zero-shot Sketch-Based Image Retrieval

## Summary

<Summary: >The paper focuses on Zero-Shot Sketch-Based Image Retrieval (ZS-SBIR) problem and introduces a cross-modality metric learning approach for it. The metric learning viewpoint is helpful in improving ZS-SBIR in two aspects, i.e., through good practices in deep metric learning and ensuring modality gap suppression. They propose a new method named Modality-Aware Triplet Hard Mining (MATHM) that enhances the baseline with three types of pairwise learning and an adaptive weighting method. The experimental results confirm that MATHM brings significant improvement based on the strong baseline and sets up new state-of-the-art performance.


## Target Task

computer vision

## Content

<Abstract: >This paper tackles the Zero-Shot Sketch-Based Image
Retrieval (ZS-SBIR) problem from the viewpoint of cross-
modality metric learning. This task has two characteristics:
1) the zero-shot setting requires a metric space with good within-class compactness and the between-class discrepancy for recognizing the novel classes and 2) the sketch query and the photo gallery are in different modalities. The metric learning viewpoint benefits ZS-SBIR from two aspects. First, it facilitates improvement through recent good practices in deep metric learning (DML). By combining two fundamental learning approaches in DML, e.g., classification training and pairwise training, we set up a strong baseline for ZS-SBIR. Second, it provides an insight that properly suppressing the modality gap is critical. To this end, we design a novel method named Modality-Aware Triplet Hard Mining (MATHM). MATHM enhances the baseline with three types of pairwise learning, e.g., a cross-modality sample pair, a within-modality sample pair, and their combination. We also design an adaptive weighting method to balance these three components during training dynamically. Experimental results confirm that MATHM brings another round of significant improvement based on the strong baseline and sets up new state-of-the-art performance.



---

