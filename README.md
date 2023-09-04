# Insurance


The insurance company Protect Your Tomorrow wants to solve some tasks with the help of machine learning and you need to evaluate the possibility of doing so.


* Task 1: Find customers similar to a particular customer. This will help the company's agents with marketing tasks.
* Task 2: Predict whether a new customer is likely to receive an insurance payout. Can a prediction model be better than a dummy model?
* Task 3: Predict the number of insurance payments a new customer is likely to receive using a linear regression model.
* Task 4: Protect customers' personal data without spoiling the model from the previous task.

It is necessary to develop a data transformation algorithm that would make it difficult to recover personal information if the data fell into the wrong hands. This is called data masking or data obfuscation. But the data must be protected in such a way that the quality of the machine learning models does not deteriorate.



![C:\\Users\\Guilherme\\Downloads\\newplot.png](https://github.com/Gui-Sitton/Insurance/blob/main/newplot%20(1).png?raw=true)"
_graphic used in the project notebook_


**Conclusions**
* There are no very clear groups, but in a 3d graph you can get a better idea of how the dataframe behaves.
* Data scaling improves the performance of Knn, and usually of all tests.
* Proof that REQM does not change with data obfuscation has been provided.
