
Author: X.Yang

X. Yang, K. Huang, R. Zhang, and A. Hussain, ¡°Learning latent features
with infinite non-negative binary matrix tri-factorization,¡± in Neural
Information Processing - 23rd International Conference, ICONIP, 2016,
pp. 587¨C596.

----------------------------------------------------------
Com-USPS and Pre-USPS Data: 

We generated two datasets from USPS: the Com-USPS and the Pre-USPS. 
The digits, used in these two datasets, are sampled randomly from the USPS. 
Moreover, our generated datasets are scaled to [0,1].
Each row of the Com-USPS dataset is built up with 32 ¡Á 32 grey images. 
Various kinds of handwriting digits 0,1,2,3 are combined into each sample.
The Pre-USPS dataset contains merely a single handwritten digit, which is also chosen randomly from 0,1,2,3. 
In the training set, each digit has 100 samples.

----------------------------------------------------------
Com-NIST and Pre-NIST Data: 

The rest two datasets were all generated from NIST handprinted forms and characters database. 
It is worth mentioning that all the images are binary in this database. 
In the way same as generating Com-USPS, we generated the Com-NIST dataset so that each sample of the Com-NIST consists of 64 ¡Á 64 binary images
combined from a,b,c,d. 
On the other hand, in the Pre-NIST dataset, each sample contains a single handwritten letter chosen randomly from a, b, c, d. 
In the training set, each digit has 200 samples. 