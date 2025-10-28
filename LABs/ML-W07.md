
# ML.W07.01  

---

#### **Task Description**

You are required to apply **Bayes’ Theorem** to analyze a simple classification problem.
Given a dataset with categorical variables, you must:

1. **Define all relevant events** (e.g., class labels and features).
2. **Compute the prior probabilities** of each class based on the given data.
3. **Compute the conditional probabilities** of the features given each class.
4. **Apply Bayes’ Theorem** to calculate the **posterior probability** for a given observation.
5. **Interpret the result** — explain which class is more likely and why.

#### **Formula Reminder**

$$
P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
$$


Where:

* (P(A)): Prior probability of class (A)
* (P(B|A)): Likelihood of evidence (B) given class (A)
* (P(B)): Marginal probability of evidence (B)
* (P(A|B)): Posterior probability of class (A) after observing (B)

#### **Example Scenario (for guidance)**

Suppose we have data on whether a student passes an exam based on whether they study or not:

| Study | Pass |
| ----- | ---- |
| Yes   | Yes  |
| Yes   | Yes  |
| No    | Yes  |
| No    | No   |
| Yes   | No   |

Compute:

1. $$(P(\text{Pass = Yes})) and (P(\text{Pass = No}))$$ — *prior probabilities*
2. $$(P(\text{Study = Yes} | \text{Pass = Yes}))$$ — *conditional probability*
3. $$(P(\text{Pass = Yes} | \text{Study = Yes}))$$ — *posterior probability using Bayes’ theorem*

#### **Deliverables**

* A short written report (1–2 pages) including:

  * Step-by-step calculation of all probabilities
  * The formula derivation and application
  * A brief conclusion interpreting the final results

REFs:  
- https://www.geeksforgeeks.org/maths/bayes-theorem/

# ML.W07.02 - k-NN (k-nearest neighbors algorithm)
- https://machinelearningcoban.com/2017/01/08/knn/
- https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm
- https://vinbigdata.com/kham-pha/tat-tan-tat-ve-thuat-toan-k-nearest-neighbors-knn-trong-hoc-may.html
- https://codelearn.io/sharing/thuat-toan-k-nearest-neighbors-knn
- https://viblo.asia/p/knn-k-nearest-neighbors-1-djeZ14ejKWz
