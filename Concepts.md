# Concepts
### The following is a summary of the concepts I had to study to replicate the solutions. I am not including any concepts I am already familiar with. I also include references.


<b>Label smoothing:</b> Label smoothing is a regularization technique used in the context of classification neural networks. Specifically, it aims to reduce the "over-confidence" in the training data as, theoretically, it reduces the generalization ability to test samples. The following is the standard formula used when performing label smoothing. We convert the 
$$
\displaystyle
y_{smooth}=(1-\alpha )\cdot y_{hot}+\alpha/\kappa
$$


## References
### 