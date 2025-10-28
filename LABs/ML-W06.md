
# ML.W06. Naïve Bayesian Classification

- https://machinelearningcoban.com/2017/08/08/nbc/
- https://200lab.io/blog/tim-hieu-naive-bayes-classification-phan-1
- https://www.geeksforgeeks.org/machine-learning/naive-bayes-classifiers/
- https://www.ibm.com/think/topics/naive-bayes
- https://www.kdnuggets.com/2020/06/naive-bayes-algorithm-everything.html

## Code  
- https://scikit-learn.org/stable/modules/naive_bayes.html
- https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html
- https://www.datacamp.com/tutorial/naive-bayes-scikit-learn
- https://towardsdatascience.com/bernoulli-naive-bayes-explained-a-visual-guide-with-code-examples-for-beginners-aec39771ddd6/
- https://jakevdp.github.io/PythonDataScienceHandbook/05.05-naive-bayes.html
- https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/

## Formula



[
P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
]

---


[
\text{Posterior} = \frac{\text{Likelihood} \times \text{Prior}}{\text{Evidence}}
]

> 🔹 *Prior* = niềm tin ban đầu - Prior Probability (Xác suất tiên nghiệm)
> 🔹 *Likelihood* = bằng chứng ủng hộ - Likelihood (Khả năng xảy ra của bằng chứng nếu giả thuyết đúng)
> 🔹 *Evidence* = độ phổ biến của bằng chứng - Marginal Probability (Xác suất bằng chứng) 
> 🔹 *Posterior* = niềm tin sau khi cập nhật - Posterior Probability (Xác suất hậu nghiệm) dựa trên Hypothesis (Giả thuyết) khi đã có Dữ liệu hoặc quan sát mà ta có được trước đó

---

