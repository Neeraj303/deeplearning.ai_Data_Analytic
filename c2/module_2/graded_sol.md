### Graded Quiz

**Q1**: What is a random variable?  
- [ ] A variable that can only take on one value.  
- [x] A variable that represents all the possible outcomes of a random phenomenon.  
- [ ] A variable that represents numerical outcomes.  
- [ ] A variable that represents the probabilities of various events.  

**Q2**: Which three of the following options are sources of real-world randomness? (Select all that apply)  
- [x] Hidden features that influence the outcome.  
- [x] Complex interactions between features.  
- [ ] Perfect predictability of all events.  
- [x] Measurement limitations.  

**Q3**: Your company is evaluating whether customers who receive a free trial are more likely to sign up for your music subscription service. Historical data suggests that users who receive a free trial sign up for your service at a rate of 60%. How can you use random sampling with the standard uniform distribution to simulate a user who signs up for the service?  
- [ ] Generate a random sample between 0 and 1; if the number is less than or equal to 0.4, simulate a user who signed up for the service.  
- [x] Generate a random sample between 0 and 1; if the number is less than or equal to 0.6, simulate a user who signed up for the service.  
- [ ] Generate a random sample between 0 and 1; if the number is greater than 0.6, simulate a user who signed up for the service.  
- [ ] Generate a random sample between 0 and 1; if the number is greater than 0.8, simulate a user who signed up for the service.  

**Q4**: Your company is helping a car dealership analyze their sales process. The dealership has found that 30% of customers who test drive a car end up purchasing it. What is the probability of a customer not purchasing the car after a test?  
- [ ] 25%  
- [ ] 30%  
- [ ] 50%  
- [x] 70%  

**Q5**: What does a distribution tell you about your sample data or population of interest?  
- [ ] The exact values of all data points.  
- [x] How often different values occur.  
- [ ] The causes of the variations in your data.  
- [ ] The median value of the dataset.  

**Q6**: Your company is running an email marketing campaign and sends a promotional offer to 100 customers. Each customer either makes a purchase or doesn’t. You want to model the total number of purchases that will result from this campaign. Assuming that each customer has a fixed probability of buying, which probability distribution best models this scenario?  
- [ ] Normal distribution  
- [ ] Bernoulli distribution  
- [ ] Power law distribution  
- [x] Binomial distribution  

**Q7**: Which three of the following options are key characteristics of the normal distribution? (Select all that apply)  
- [x] It is symmetrical around the mean.  
- [x] The mean, median, and mode are all equal.  
- [ ] It has a skewed distribution.  
- [ ] It has multiple peaks.  
- [x] The tails extend to positive and negative infinity.  

**Q8**: What is the multiplication rule for independent events?  
- [ ] P(A and B) = P(A) + P(B)  
- [ ] P(B) = 1 - P(A)  
- [x] P(A and B) = P(A) * P(B)  
- [ ] P(A and B) = P(A|B) * P(B|A)  

**Q9**: Which of the following options correctly describes the meaning of a z-score?  
- [x] A z-score describes the number of standard deviations a particular value is from the mean in the standard normal distribution.  
- [ ] A z-score describes the number of different possible normal distributions that can be defined using a particular outcome.  
- [ ] A z-score describes the mean value of the standard normal distribution.  
- [ ] A z-score is equivalent to the percentile of a particular value.  

**Q10**: Based on the set of sigma rules associated with the normal distribution, 99.7% of the data falls within how many standard deviations of the mean?  
- [x] 3  
- [ ] 1  
- [ ] 2  
- [ ] 4  

**Q11**: Below is a graph of the cumulative distribution function (CDF) for a binomial distribution with n = 10 and p = 0.7. How should you interpret the bar for 6 successes?  
- [x] The probability of obtaining 6 successes or fewer is around 35%.  
- [ ] The probability of obtaining more than 6 successes is around 35%.  
- [ ] The probability of obtaining exactly 6 successes is around 35%.  
- [ ] The probability of obtaining 5, 6, or 7 successes is around 35%.  

**Q12**: What is the process for estimating a particular value of a population using a sample?  
- [x] You collect a sample, then use the sample statistic (such as x̄) to estimate the population parameter (such as μ).  
- [ ] You collect data from the entire population, then use the population parameter (such as μ) to estimate a sample statistic (such as x̄).  
- [ ] You collect a sample, then use the sample statistic (such as x̄) to estimate another sample statistic (such as x̄).  
- [ ] You collect data from the entire population, then use the population parameter (such as μ) to estimate another population parameter (such as μ).


### Graded Lab

**Q1**: What is the frequency of fires with area < 0.5 and on X = 2?  
- **Answer**: 0.0618  

**Q2**: Are the events “The fire has small area” and “The fire happened on X coordinate 2” independent?  
- [ ] Yes  
- [x] No  

**Q3**: According to your dataset, which event is most frequent (most likely to occur)?  
- [x] Having a small fire occur on any coordinate  
- [ ] Having a fire of any size occur on X coordinate 2.  
- [ ] Having a small fire occur on X coordinate 2.  
- [ ] Having a small fire given that the X coordinate is 2.  

**Q4**: Based on the distribution charts you created in Exercise 2, which of the following features appear as though they might follow a normal distribution?  
- [x] temp  
- [ ] DC  
- [ ] is_small  

**Q5**: Why might you conclude that the DC feature does not follow a normal distribution?  
- [x] It does not appear to be symmetric about the mean.  
- [ ] It does not appear to have a fixed number of trials.  
- [ ] It does not appear to have only two outcomes: success and failure.  
- [ ] It does not have a mean of 1.  

**Q6**: What can you say about the ISI feature?  
- [ ] It appears to be uniformly distributed  
- [x] It appears to have an outlier at 56.1  
- [x] The data only has positive values  
- [ ] It is a discrete variable  

**Q7**: What is the mean temperature (temp) in the data?  
- **Answer**: 18.89  

**Q8**: Do the observed frequencies of temp falling within 1, 2, and 3 standard deviations ($s$) from the mean closely match (within a margin of 0.05) the theoretical predictions provided by the set of sigma rules for the normal distribution?  
- [x] Yes  
- [ ] No  

**Q9**: Which two of the following are correct statements about using a normal distribution to simulate the temperature based on this dataset (select all that apply)?  
- [x] Because the distribution of the temp feature resembles a normal distribution, it is reasonable to use the normal distribution for simulation.  
- [x] When simulating the temperature, you can use the sample mean and standard deviation as estimates for the true population parameters.  
- [ ] You will only be able to perform a simulation once using this data.  
- [ ] Your simulation will always generate the same values as you have observed in the data.  

**Q10**: The parks department chief has asked you to simulate the number of small fires in a group of 10 fires. Recall that the proportion of fires that are small is 0.4971. Which distribution would best model this scenario?  
- [ ] A normal distribution with μ=10 and σ=0.4971  
- [ ] A uniform distribution with range -10 to 10  
- [x] A Binomial distribution with n=10 and p=0.4971  
- [ ] A Bernoulli distribution with p=0.4971  
