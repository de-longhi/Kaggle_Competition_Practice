# Concepts
<hr/>

### The following is a summary of the concepts I had to study to replicate the solutions. I am not including any concepts I am already familiar with. I also include references.

<hr/>

<b>Label smoothing:</b> Label smoothing is a regularization technique used in the context of classification neural networks. Specifically, it aims to reduce the "over-confidence" in the training data as, theoretically, it reduces the generalization ability to test samples. The problem occurs, because the cross-entropy loss is minimized when the full probability is assigned to the correct class. This means that the backpropagation will try to achieve a perfect one-hot encoding in terms of probabilities. This creates a sense of overconfidence. The following is the standard formula used when performing label smoothing. 
$$
\displaystyle
y_{smooth}=(1-\alpha )\cdot y_{hot}+\alpha/\kappa
$$

The following is the formula for cross-entropy loss with label smoothing:
$$
\displaystyle
loss=(1-\epsilon )\cdot ce(i)+\epsilon\sum\frac{ce(j)}{N}
$$


<b> Kolmogorov-Arnold Networks: </b>
## References
### 