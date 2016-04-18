### Unsupervised-Clustering

* What is the assumption of K-Means?

Answer: K-Means actually implicitly assumes that the importance of variance is the same across different dimensions, otherwise the distance measure will fail.

* When does K-Means fail?

Answer: K-Means will fail for non-spherical shapes. In that case, GMM or density based methods will work. 
