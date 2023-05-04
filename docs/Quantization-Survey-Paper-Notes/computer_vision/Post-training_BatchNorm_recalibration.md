# Post-training BatchNorm recalibration

## Summary

Summary: The paper shows that recalibration of batch normalization layers' running mean and running variance statistics can recover model performance. The paper also revisits non-blocking simultaneous multithreading (NB-SMT) and explains that NB-SMT trades accuracy for performance by occasionally accommodating multiple threads into a shared MAC unit.


## Target Task

computer vision

## Content

<Abstract: >We show that substantial model performance can be recouped by post-training recalibration of the batch normalization layers’ running mean and running variance statistics, given the presence of NB-SMT. We revisit non-blocking simultaneous multithreading (NB-SMT) introduced previously by Shomron and Weiser. NB-SMT trades accuracy for performance by occasionally "squeezing" more than one thread into a shared multiply-and-accumulate (MAC) unit.



---

