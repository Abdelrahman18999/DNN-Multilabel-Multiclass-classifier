# DNN-Multilabel-Multiclass-classifier
- Using "Functional API method" to build an architecture of multi-label multi-class classifier.
- The functional API method gives us the ability to design this architecture without adding any post-logic.
- In this case, we want to replace the output layer(which consists of 7 outputs) with `Two parallel output layers`.
- One for the first set of classes (age categories), and one for the second set of classes (gender).

## Input features are:
- Height
- Weight
- Nose surface area

## Output:
The O/P will be two classes :
- Age category(baby, toddler, preteen, etc...)
- Gender (male, female)

![multiclass](https://user-images.githubusercontent.com/59202700/206857063-6cf753ea-80d7-4f11-8da7-07046bd01549.jpeg)
