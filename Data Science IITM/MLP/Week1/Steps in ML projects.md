# Week 1  

### Steps in ML projects
1. Look at the big picture.
2. Get the data.
3. Discover and visualize the data to gain insights.
4. Prepare the data for Machine Learning algorithms.
5. Select a model and train it.
6. Fine-tune your model.
7. Present your solution.
8. Launch, monitor and maintain your system.

#### Step 1: Look at the big picture
1. Frame the problem
2. Select a performance measure
3. List and check the assumptions

**1.1 Frame the problem**
  * What is input and output?
  * What is the business objective? How does company expects to use and benefit from the model?
  * What is the current solution (if any)?
  * provides a useful baseline

> **Design consideration in problem framing**
> * Is this a **supervised, unsupervised or a RL** problem?
> * Is this a **classification, regression** or some other tast?
> * What is the nature of the output: **single** or **multiple** outputs?
> * Does system need **continuous learning** or **periodic updates**?
> * What would be the learning style: **batch** or **online**?

**1.2 Selection of performance measure**
* Regression
  * Mean Squared Error (MSE) or
  * Mean Absolute Error (MAE)
* Classification
  * Precision
  * Recall
  * F1-score
  * Accuracy
  
**1.3 Check the assumptions**
* List down various assumptions about the task.
* Review with domain experts and other teams that plan to consume ML output.
* Make sure all assumptions are reviewed and approved before coding!

> It's a good idea to understand significance of each feature by consulting the experts.