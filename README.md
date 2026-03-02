## 🧠 Problem Framing & Machine Learning Approach


Before building any model, it is crucial to identify the right learning approach. We must define the following:

**1. The Objective:** What specific value will this model generate, and who is the end-user?
**2. The Core Functionality:** Which of the following tasks is most useful to achieve that goal?
* **A.** Predicting a continuous metric (*Regression*).
* **B.** Predicting a specific label or category (*Classification*).
* **C.** Grouping similar elements based on features (*Clustering*).
* **D.** Optimizing a process through trial and error (*Reinforcement Learning*).

> 🎯 **Project Focus:** This repository will primarily focus on options **A** and **B**, diving deep into **Supervised Learning** algorithms and applications.


## 🎯 Grounding the Supervised Learning Problem


To effectively build a model, we must first frame the problem with precision by answering these key questions:

**1. What type of value are you trying to predict?**
* **A.** Continuous (Regression tasks).
* **B.** Discrete (Classification tasks).

**2. What is your definition of a successful prediction?**
* Establishing the specific metrics to evaluate the model's performance (e.g., Accuracy, RMSE, Precision).

**3. What data will you have available to make this prediction?**
* Identifying the features (input variables) and the historical dataset we can rely on to train the algorithm.

**4. Does the problem belong to a specific domain or discipline?**
* Understanding the context of the problem to guide the analysis.

**5. Based on your domain intuition, can the data actually predict the target?**
* Evaluating whether the available data contains enough underlying patterns (signal) to make a reliable prediction, or if it's mostly random (noise).



Tabular Data.
<img width="497" height="361" alt="image" src="https://github.com/user-attachments/assets/66a8796a-48d4-4cc7-a692-95aac4537445" />

## 🧮 Mathematical Representation of Data

In Machine Learning, we translate tabular data into mathematical structures—matrices and vectors—to feed them into our algorithms. The standard notation is as follows:

* **Feature Matrix ($X$):** The 2D grid containing all our input variables.
  * **Row = Example (or Observation/Sample):** Each horizontal line represents a single, independent instance (e.g., a specific movie).
  * **Column = Feature:** Each vertical line represents a measurable attribute of that example.
  * **Data Dimensionality:** The total number of columns (features) dictates the mathematical dimension of our dataset.

* **Target Vector ($y$):** A 1D array (a single column) containing the dependent variable or label we aim to predict (e.g., the revenue of the movie).

* **The Output:** When we feed the Feature Matrix ($X$) and the Target Vector ($y$) into a Machine Learning algorithm, the resulting output is what we call a **Model**.


Foto Ciclo de Machine Learning



