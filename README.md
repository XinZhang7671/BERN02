# Bird Count Analysis Project
This project analyzes bird count data and generates hypothetical observations.
## introduction
This project analyzes bird count data using maximum likelihood estimation and fits the data with a simple linear regression model.
The data file bird_count.csv contains bird counts from one site from the years 1999 to 2012. Formulate a model for Poisson regression with year as predictor and we are not allowed to use ready available functions.
git clone https://github.com/XinZhang7671/BERN02.gi
## Result
Based on the Poisson regression model's results, the intercept is 1.948875, and the coefficient for yr (year) is 8.323285e-05. The model can be expressed as:
log(λ)=1.948875+8.323285×10^−5×yr
Here, λ represents the expected value of the bird count in the logarithmic scale. Converting it to the original count scale, the expected bird count is given by:
λ=exp(1.948875+8.323285×10^−5×yr)
This means that as the year increases, the expected bird count increases at a very small rate.
