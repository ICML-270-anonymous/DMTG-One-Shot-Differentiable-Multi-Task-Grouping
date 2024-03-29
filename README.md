# DMTG: One-Shot Differentiable Multi-Task Grouping
This is a demo showing the dynamic grouping process of tasks of our proposed DMTG method on CelebA-9, CelebA-40, and Taskonomy-5 datasets. DMTG will initialize a group matrix whose rows and columns represent tasks and groups, respectively, and optimize it using the Gumbel softmax to obtain a discrete one-hot vector for each column.

**1. Dynamic task grouping on CelebA-9.**
![alt Dynamica grouping on CelebA-9](img/celeba9_0.4.gif "Dynamica grouping on CelebA-9")

**2. Dynamic task grouping on CelebA-40.**
![alt Dynamica grouping on CelebA-40](img/celeba40_0.4.gif "Dynamica grouping on CelebA-40")

**3. Dynamic task grouping on Taskonomy-5.** 
![alt Dynamica grouping on Taskonomy-5](img/taskonomy5_0.4.gif "Dynamica grouping on Taskonomy-5")
