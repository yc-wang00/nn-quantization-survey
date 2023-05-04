# Generalized zero-shot learning for action recognition with web-scale video data

## Summary

<Summary: >The paper discusses the challenges in efficient action recognition in surveillance videos due to the large number of action classes and limitations in collecting real-world footage. It explores the potential of zero-shot learning in addressing these issues and proposes a method for action recognition using generalized zero-shot learning to transfer knowledge from web videos for detecting anomalous actions in surveillance videos. The paper also evaluates existing zero-shot learning approaches under the generalized zero-shot setting and highlights their limitations.


## Target Task

computer vision

## Content

<Abstract: >Action recognition in surveillance video makes our life safer by
detecting the criminal events or predicting violent emergencies. However, efficient action recognition is not free of difficulty. First, there are so many action classes in daily life that we cannot pre-define all possible action classes beforehand. Moreover, it is very hard to collect real-word videos for certain particular actions such as steal and street fight due to legal restrictions and privacy protection. These challenges make existing data-driven recognition methods insufficient to attain desired performance. Zero-shot learning is potential to be applied to solve these issues since it can perform classification without positive example. Nevertheless, current zero-shot learning algorithms have been studied under the unreasonable setting where seen classes are absent during the testing phase. Motivated by this, we study the task of action recognition in surveillance video under a more realistic generalized zero-shot setting, where testing data contains both seen and unseen classes. To our best knowledge, this is the first work to study video action recognition under the generalized zero-shot setting. We firstly perform extensive empirical studies on several existing zero-shot leaning approaches under this new setting on a web-scale video data. Our experimental results demonstrate that, under the generalize setting, typical zero-shot learning methods are no longer effective for the dataset we applied. Then, we propose a method for action recognition by deploying generalized zero-shot learning, which transfers the knowledge of web video to detect the anomalous actions in surveillance videos.



---

