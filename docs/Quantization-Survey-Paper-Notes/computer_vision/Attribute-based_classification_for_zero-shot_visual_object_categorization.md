# Attribute-based classification for zero-shot visual object categorization

## Summary

Summary: The paper discusses zero-shot learning, in which an object is recognized with no training examples, through attribute-based classification. This approach uses semantic attributes to prelearn classifiers independently and identify new classes based on their attribute representation without requiring a new training phase. The paper also introduces a new data set, Animals with Attributes, of over 30,000 images of 50 animal classes, annotated with 85 semantic attributes. The experiments on this data set and two more show that attribute-based classification is successful in categorizing images without access to any training images of the target classes.


## Target Task

computer vision

## Content

<Abstract: >We study the problem of object recognition for categories for which we have no training examples, a task also called zero-data or zero-shot learning. This situation has hardly been studied in computer vision research, even though it occurs frequently;the world contains tens of thousands of different object classes, and image collections have been formed and suitably annotated for only a few of them. To tackle the problem, we introduce attribute-based classification: Objects are identified based on a high-level description that is phrased in terms of semantic attributes, such as the object’s color or shape. Because the identification of each such property transcends the specific learning task at hand, the attribute classifiers can be prelearned independently, for example, from existing image data sets unrelated to the current task. Afterward, new classes can be detected based on their attribute representation, without the need for a new training phase. In this paper, we also introduce a new data set, Animals with Attributes, of over 30,000 images of 50 animal classes, annotated with 85 semantic attributes. Extensive experiments on this and two more data sets show that attribute-based classification indeed is able to categorize images without access to any training images of the target classes.



---

