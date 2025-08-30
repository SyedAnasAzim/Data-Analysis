# Linear Regression
* Linear regression means fitting a straight line in a data.
* Widely used learning algorithm.
* It’s a **supervised learning** algorithm.
- It finds a straight line (or hyperplane in higher dimensions) that best fits the relationship between **input (X)** and **output (Y)**.
Let's talk about a dataset of house prices in Portland.
here,
input is House Size in $ft^2$.
output is House prize in dollars($).
![[Pasted image 20250830152815.png]]
* There are other models to address regression and classification problems.

One way of looking at the data that could be useful is *Data Table*.
![[Pasted image 20250830173114.png]]

### Terminologies:
#### 1. Training Data:
The data that is used to train the model is called training data.
* Like  a clients house data is not in the data because it is not yet sold so, we will train the model and it will predict the prize.

#### 2. Testing Data:
The data that is used to test the model is called testing data.

![[WhatsApp Image 2025-08-30 at 22.28.34_d3cee87a.jpg]]

### Process:
* We give training data to the learning algorithm.
* It gives a function $f$ (which historically called as hypothesis).
* This function takes a feature $x$ and give an estimate $\hat{y}$ whose value may or may not be equal to the target $y$.
* This function is also called model.
* So, you give model a feature and it gives you a prediction.
![[Pasted image 20250830231229.png]]
#### How to represent $f$?
The key question when designing a model, how are we going to represent function $f$ or what is the math formula we are going to use to compute $f$.
						$f_{w,b}(x) = wx + b$
$f$ is a function that takes $x$ as input, depending on $w$ and $b$, gives some value of a prediction $\hat{y}$.  
This function is for **linear regression with one variable** which is also called **univariate linear regression.**
![[Pasted image 20250830231213.png]]
