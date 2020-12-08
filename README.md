# people-s-preference-autovehicle
The results came from the dataset from MIT Age lab
glm(formula = paratransit ~ mind + health + knowav + disability + 
    able_out + avlevel + gender + travelcost + likelychange + 
    avatt + age + education + techinterest + income + trust + 
    safety, family = binomial, data = paratransit)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-1.5687  -0.6248  -0.4490  -0.2897   2.5100  

Coefficients: (1 not defined because of singularities)
              Estimate Std. Error z value Pr(>|z|)   
(Intercept)   0.762003   1.649626   0.462  0.64414   
mind         -0.096157   0.029509  -3.259  0.00112 **
health        0.355848   0.186435   1.909  0.05630 . 
knowav        0.267927   0.147340   1.818  0.06900 . 
disability    1.837700   1.013898   1.813  0.06991 . 
able_out      0.066263   0.115807   0.572  0.56720   
avlevel       0.078849   0.154764   0.509  0.61042   
gender       -0.125086   0.310681  -0.403  0.68723   
travelcost    0.003175   0.001701   1.867  0.06197 . 
likelychange -0.580993   0.183033  -3.174  0.00150 **
avatt         0.019464   0.032107   0.606  0.54437   
age           0.002042   0.010198   0.200  0.84130   
education           NA         NA      NA       NA   
techinterest -0.067758   0.056607  -1.197  0.23131   
income        0.165852   0.318738   0.520  0.60283   
trust         0.098446   0.048152   2.044  0.04091 * 
safety       -0.139258   0.087911  -1.584  0.11318   
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for binomial family taken to be 1)

    Null deviance: 354.34  on 365  degrees of freedom
Residual deviance: 301.77  on 350  degrees of freedom
AIC: 333.77

Number of Fisher Scoring iterations: 5
