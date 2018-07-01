[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

>> 
"python"

    import scipy.stats
    mu = 178
    sigma = 7.7
    dist = scipy.stats.norm(loc=mu, scale=sigma)
  
    low = dist.cdf(177.8)    
    high = dist.cdf(185.4)   
    high-low 

By subtracting the lower bound from the upper bound, we get the percentage of males that would meet the height requirement for Blue Moon group, which is about 34% of U.S. men. 
