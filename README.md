# Fitting_and_Simulating_Archimedean_Copulas
Fitting and Simulating Archimedean Gumbel, Clayton and Frank Copulas

In this notebook, we implement algos to fit and simulate bivariate Archimedean copulas.

To fit Archimedean copulas we will use the Kendall distribution function.

To simulate Archimedean copulas we will invert the Kendall distribution function using numerical root finding.

There is plenty of materials from where you can enjoy the mathematics of the Copula functions. Our intention is not to add more maths to such long and reach lists of books and research papers. Rather, we just want to implement in Python some of the many copula objects we personally found useful when fitting and simulating data to the Gumbel, Clayton and Frank copulas.

The various copula objects we are using were collected from the following materials:

Genest C, Rivest LP, 1993. Statistical inference procedures for bivariate archimedean copulas. Journal of the American Statistical Association, 88: 1034-1043.

Genest C, MacKay J, 1986. The Joy of copulas: bivariate disributions with uniform marginals. Journal of the American Statistical Association, 88: 280-283.

Frees EW, Valdez EA, 1998. Understanding relationships using copulas. North American Actuarial Journal, 2: 1-25.

Cherubini U, Luciano E, 2001. Value-at-risk trade-off and capital allocation with copulas. Economic Notes, 30: 235–256.

Cherubini U, Luciano E, Vecchiato W, 2004. Copula Methods in Finance, Wiley.
