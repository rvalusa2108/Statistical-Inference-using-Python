# Statistical Inference using Python
 Coursera Statistical Inference using Python - Exercises and Assignments
 
 #### Inferential Statistic:  
 Inferential Statistics enables you to make an educated guess about a population parameter based on a statistic computed from a sample randomly drawn from that population.  
 
 Parameter - is about Population  
 Statistic - is about Sample  
 
## Confidence Intervals

 - ### One Proportion: 
 Only one proportion of the population is considered.
 
 #### Estimating a Population Proportion with Confidence:
 
<a href="https://www.codecogs.com/eqnedit.php?latex=\fn_cm&space;Confidence&space;Interval&space;=&space;Best&space;Estimate&space;\pm&space;Margin&space;of&space;Error" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\fn_cm&space;Confidence&space;Interval&space;=&space;Best&space;Estimate&space;\pm&space;Margin&space;of&space;Error" title="Confidence Interval = Best Estimate \pm Margin of Error" /></a>
 
Best Estimate = Unbiased Point Estimate = Sample Proportion(<a href="https://www.codecogs.com/eqnedit.php?latex=\fn_cm&space;\hat{p}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\fn_cm&space;\hat{p}" title="\hat{p}" /></a>)
 
 Margin of Error = "a few" Estimated Standard Error  
 "a few" is a multiplier from appropriate distribution based on desired confidence level.eg: <a href="https://www.codecogs.com/eqnedit.php?latex=\fn_cm&space;z^{\star}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\fn_cm&space;z^{\star}" title="z^{\star}" /></a>, <a href="https://www.codecogs.com/eqnedit.php?latex=\fn_cm&space;t^{\star}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\fn_cm&space;t^{\star}" title="t^{\star}" /></a> (Student's t-test)
 
 #### 95% Confidence Interval Calculation for one Population Proportion:  
 
 <a href="https://www.codecogs.com/eqnedit.php?latex=\fn_cm&space;\hat{p}&space;\pm&space;1.96\times&space;\sqrt{\frac{\hat{p}(1-\hat{p})}{n}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\fn_cm&space;\hat{p}&space;\pm&space;1.96\times&space;\sqrt{\frac{\hat{p}(1-\hat{p})}{n}}" title="\hat{p} \pm 1.96\times \sqrt{\frac{\hat{p}(1-\hat{p})}{n}}" /></a>
 
 **With Confidence Intervals, we can conclude that, in the multiple sample iterations caclulating the confidence interval for each sample, about 95% of such confidence intervals will contain the true population proportion**
 
 - Different z^{\star} multiplers for different confidence intervals  
  90% CI - 1.645  
  95% CI - 1.96  
  98% CI - 2.326  
  99% CI - 2.576  
  
  Therefore, More Confident ==> Larger Multipler ==> Wider Interval
