# Deep semisupervised zero-shot learning with maximum mean discrepancy

## Summary

<Summary: >The paper proposes a novel deep semisupervised learning method for zero-shot learning by replacing original labels with textual descriptions to capture category semantics better. The method also minimizes the distribution difference by considering the heterogeneity gap between different modalities and the correlation among unimodal instances, achieving significant improvements over previous methods on benchmark datasets CU200-Birds and Oxford Flowers-102.


## Target Task

computer vision

## Content

<Abstract: >Due to the difficulty of collecting labeled images for hundreds of thou-
sandsofvisualcategories,zero-shotlearning,whereunseencategoriesdo
not have any labeled images in training stage, has attracted more atten-
tion. In the past, many studies focused on transferring knowledge from
seentounseencategoriesbyprojectingallcategorylabelsintoasemantic
space. However, the label embeddings could not adequately express the
semanticsofcategories.Furthermore,thecommonsemanticsofseenand
unseen instances cannot be captured accurately because the distribution
of these instances may be quite different. For these issues, we propose
a novel deep semisupervised method by jointly considering the het-
erogeneity gap between different modalities and the correlation among
unimodal instances. This method replaces the original labels with the
correspondingtextual descriptions to better capture the category seman-
tics. This method also overcomes the problem of distribution difference
by minimizing the maximum mean discrepancy between seen and un-
seeninstancedistributions.Extensiveexperimentalresultsontwobench-
mark data sets, CU200-Birds and Oxford Flowers-102, indicate that our
methodachievessignificantimprovementsoverpreviousmethods.



---

