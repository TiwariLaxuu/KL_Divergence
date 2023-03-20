# KL_Divergence

To measure the difference between two probability distributions over the same variable x, a measure, called the Kullback-Leibler divergence, or simply, the KL divergence, has been popularly used in the data mining literature. The concept originated in probability theory and information theory.

Very often in Probability and Statistics we'll replace observed data or a complex distribution with a simpler, approximating distribution. KL Divergence helps us to measure just how much information we lose when we choose an approximation.

Gibbs' inequality, also known as the Shannon-Kolmogorov Information inequality, states that the Kullback-Leibler divergence is always positive.

The primary goal of information theory is to quantify how much information is in data.  

If we have two probability distributions, P and Q, we typically write the KL divergence using the notation KL(P || Q), which means “P’s divergence from Q.”

We calculate it using the following formula:

KL(P || Q) = ΣP(x) ln(P(x) / Q(x))

If the KL divergence between two distributions is zero, then it indicates that the distributions are identical.

