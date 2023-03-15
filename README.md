# Cross-Lingual-Sentiment-Analysis-Project

Sentiment analysis of test data analyses text, extracts features and tries to identify the emotion behind the sentence. 
Sentiment analysis on monolingual datasets have been performed to great extent with satisfying accuracy.
In a country like India, which has multiple spoken languages, we often encounter ourselves with code-mixed sentences.
This acts as a barrier to monolingual NLP models that cannot perform well on such code-mixed data.
We focus mainly on Kannada-English code-mixed dataset taken directly from “Dravidian-CodeMix-FIRE 2021" challenge

# Architecture

![architecture](https://user-images.githubusercontent.com/96068461/225291967-d7ea6d33-5ef1-4e76-9dbe-eb8b7b09d2d1.png)

# Preprocessing Stages

![preprocessing](https://user-images.githubusercontent.com/96068461/225292071-ce00af48-82e9-4566-90f0-cac371c2faf0.png)

# Implementation

Preprocessing of data was done as follows:

![i1](https://user-images.githubusercontent.com/96068461/225293124-b6db12d8-4644-4eca-834c-799c90399142.png)

Kannada translation Function:

![i2](https://user-images.githubusercontent.com/96068461/225293389-c8181231-683b-402c-a8a8-67b5cd61b534.png)

Conversion to Kannada text:

![i3](https://user-images.githubusercontent.com/96068461/225293364-90a30597-03e6-46a9-a965-e461185a5903.png)

This is how the text looks after each stage of Processing:

![i4](https://user-images.githubusercontent.com/96068461/225293500-8a17a76e-da93-45a0-9735-2a2b9f203a01.png)

BERT Model:

![i5](https://user-images.githubusercontent.com/96068461/225293507-eb1eeaa3-9e67-4568-b926-f9b7d09547f7.png)

Training in the form of epochs:

![i6](https://user-images.githubusercontent.com/96068461/225293508-da77d68b-4809-46b6-af31-8e8e44c5b77a.png)

# Results

Summary of the results of all models employed are as follows:

![Summary of res](https://user-images.githubusercontent.com/96068461/225303157-4c10f16b-a69c-499b-b323-6573805f4146.png)

The results of the BERT model are as follows:

![bert res](https://user-images.githubusercontent.com/96068461/225294770-915755f1-d2ba-41ef-b1e9-3b514b3ef634.png)

The results of the ML models are as follows:

1. SVC(Linear Kernel)

![svc_linear](https://user-images.githubusercontent.com/96068461/225295146-f22143b7-e52e-4236-90ad-9cb22acff51e.png)

2. SVC(RBF Kernel)

![svc_rbf](https://user-images.githubusercontent.com/96068461/225295337-1d4435f4-70cb-411f-b3c6-d73894e4fe62.png)

3. SVC(Sigmoid Kernel)

![svc_sigmoid](https://user-images.githubusercontent.com/96068461/225295406-45860958-c416-4b46-bd49-de28fc280b27.png)

4. SVC(Polynomial Kernel)

![svc_polynomial](https://user-images.githubusercontent.com/96068461/225295505-fe1ecdf3-5421-4a3f-af92-2113e9519b59.png)

5. Decision Tree:

![dt res](https://user-images.githubusercontent.com/96068461/225295639-7a735e29-2359-4172-a0e1-2f234f9bb974.png)

6.Random Forest:

![rf res](https://user-images.githubusercontent.com/96068461/225295705-af6f7d69-077b-4693-8c03-71b603f47f0b.png)
