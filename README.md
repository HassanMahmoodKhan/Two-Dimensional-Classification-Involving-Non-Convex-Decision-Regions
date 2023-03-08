# Two-Dimensional-Classification-Involving-Non-Convex-Decision-Regions
Two-dimensional binary classification problem involving non-convex decision regions i.e., C1 &amp; C2. 
The proposed solution employs a Back Propagation and Counter Propagation Network to distinguish whether an input pattern belongs to class C1 or C2.
The distribution of pattern classes is as shown below.

![image](https://user-images.githubusercontent.com/97694796/219873717-c88e9656-69f4-4fad-8f7f-6b56b777dbd7.png)

Class C1 consists of pattern points marked inside the area marked C1 and class C2 consisits of pattern points inside the area marked C2.
The dataset generated for the task in resemblence to the one provided in the problem statement is as follows:

![image](https://user-images.githubusercontent.com/97694796/223731272-454b83ff-68ab-4fb8-81a9-f09ae8c4ad15.png)

The proposed solution evaluates the network based on a number of metrics i.e., accuracy, loss, confusion matrix. Furthermore, I discuss the comparative performance of each model on the problem at hand.
In this regard, I have plotted error curves for training and validation sets and studied the impact of varying model hyperparamters on the performance.

![image](https://user-images.githubusercontent.com/97694796/223730630-8fc399d7-8101-4315-b3f2-57a65bb306aa.png)

Overall, it was observed that the BPN performed significantly well when compared to the CPN, however, it took a considerable amount of time to train on the dataset. In addition, both models have oscillate with varying number of epochs and are prone to overfitting.
