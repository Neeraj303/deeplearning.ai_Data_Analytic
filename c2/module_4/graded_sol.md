### Quiz 1 Solution

**Q1**: What is the purpose of hypothesis testing in the context of the Rubik's cube challenge, where two people compete to solve the Rubik’s cube faster?  
- [x] To determine if the observed outcome is due to random chance or a true pattern.  
- [ ] To measure the total time taken to solve the cubes.  
- [ ] To scramble the Rubik's cubes more thoroughly.  
- [ ] To count the number of cubes solved.  

**Q2**: Why is it important to define your hypotheses before performing a hypothesis test?  
- [x] To make sure you construct and interpret your test correctly.  
- [ ] To increase the sample size.  
- [ ] To ensure data is collected randomly.  
- [ ] To calculate the p-value directly.  

**Q3**: Which two of the following phrases should be avoided when explaining the results of a hypothesis test to stakeholders? (Select all that apply)  
- [x] “Prove the alternative hypothesis”  
- [x] “Accept the null hypothesis”  
- [ ] “Reject the null hypothesis”  
- [ ] “Fail to reject the null hypothesis”  

**Q4**: What kind of hypothesis test would you use if you want to determine whether movie lengths in 2013 are greater than 120 minutes?  
- [ ] Two-tailed test  
- [x] Right-tailed test  
- [ ] Left-tailed test  
- [ ] One-winged test  

**Q5**: In a two-tailed test with alpha = 0.05, what is the size of each rejection region?  
- [ ] 5% in one tail  
- [x] 2.5% in each of two tails  
- [ ] 10% in each of two tails  
- [ ] 1% in each of two tails  

**Q6**: Which two of the following options are ways to manage error rates in hypothesis testing? (Select all that apply)  
- [x] Adjusting the significance level alpha  
- [x] Increasing the sample size  
- [ ] Ignoring the null hypothesis  
- [ ] Choosing any random value for alpha  


### Graded Quiz

**Q1**: In which three scenarios would a two-sample hypothesis test be most appropriate? (Select all that apply)  
- [x] A/B testing in product development  
- [x] Clinical research with experimental and control groups  
- [ ] Testing whether average hours of sleep per night is greater than 8  
- [x] Comparing rural and urban opinions on AI  
- [ ] Testing whether the average pH of a sample of beverages is less than 7  

**Q2**: What does the "rejection region" represent in a hypothesis test?  
- [x] The range of values that lead you to reject the null hypothesis  
- [ ] The range of values that support the null hypothesis  
- [ ] The average values expected under the null hypothesis  
- [ ] The middle 95% of the distribution  

**Q3**: Which two of the following are required conditions for hypothesis tests to work effectively? (Select all that apply)  
- [x] The data must be a representative sample, ideally a random sample.  
- [ ] The data must have low variance.  
- [ ] The sample mean must be equal to the population mean.  
- [x] The data must be normally distributed or have a large sample size.  

**Q4**: What does it mean if you "reject the null hypothesis"?  
- [x] The data suggest that the null hypothesis is likely not true.  
- [ ] The null hypothesis is absolutely false.  
- [ ] The alternative hypothesis is proven.  

**Q5**: In which two of the following scenarios might you choose to use the t distribution instead of the normal distribution in hypothesis testing? (Select all that apply)  
- [x] When the population standard deviation (σ) is unknown.  
- [x] When the sample size is small (typically n < 30)  
- [ ] When you want to use the simplest calculation  
- [ ] When the sample size is large (n > 1000)  

**Q6**: What does it mean if a hypothesis test concludes that the difference between two means is statistically significant?  
- [x] The difference likely reflects a genuine difference between the population means.  
- [ ] The two population means are likely equal to each other.  
- [ ] The observed difference between the two sample means is likely due to random chance.  
- [ ] The two means are both different from the hypothesized value.  

**Q7**: Your client, a pharmaceutical company, needs to determine if their new drug significantly decreases pain levels among patients with a particular disease. The current average pain level for patients with the disease is 5.47. What set of hypotheses would be most appropriate for this test?  
- [x] H₀ (null): μ = 5.47 H₁ (alternative): μ < 5.47  
- [ ] H₀ (null): μ < 5.47 H₁ (alternative): μ = 5.47  
- [ ] H₀ (null): μ = 5.47 H₁ (alternative): μ ≠ 5.47  
- [ ] H₀ (null): μ = 5.47 H₁ (alternative): μ > 5.47  

**Q8**: You are working with a defense contractor on a safety-critical application, so you've chosen to use a 99% confidence level for your relevant hypothesis tests. What tradeoff are you making by choosing such a high level of confidence?  
- [x] You require stronger evidence to detect an effect, so you may not detect a true effect.  
- [ ] You require less evidence to detect an effect, so false positives are more likely.  
- [ ] Your chosen confidence level of 99% is more difficult to explain to stakeholders than a typical 95% confidence level.  
- [ ] Your sample size will decrease, so you may have fewer observations to work with.  

**Q9**: In which scenario would a one sample test for proportions be more appropriate than a one sample test for means?  
- [x] A company wants to test whether the percent of defective products in a batch is greater than 5%.  
- [ ] A researcher wants to determine if the average height of a population differs from a known value.  
- [ ] A scientist is testing whether the mean weight of a certain species of fish has changed over time.  
- [ ] A teacher wants to compare the average test scores of students in two different classrooms.  

**Q10**: Which test is most suitable for analyzing categorical data to determine if there is a relationship between variables?  
- [x] Chi-squared test  
- [ ] ANOVA  
- [ ] Paired t test  
- [ ] Goodness of fit test  


### Graded Lab

**Question 1**: What test type is most appropriate to calculate the mean price of all diamonds in Exercise 1?  
- [ ] two-tailed  
- [ ] left-tailed  
- [x] right-tailed  
- [ ] zero-tailed  

**Question 2**: What is the p-value associated with this test?  
- [x] 0.0228  
- [ ] 0.1110  
- [ ] -0.0057  
- [ ] 0.0489  

**Question 3**: In Exercise 2, you tested whether the mean price of 'Premium' cut diamonds is higher than that of 'Fair' cut diamonds. Which set of hypotheses correctly tests this question?  
- [x] H₀ (null): μ_premium = μ_fair, H₁ (alternative): μ_premium > μ_fair  
- [ ] H₀ (null): μ_premium = μ_fair, H₁ (alternative): μ_premium ≠ μ_fair  
- [ ] H₀ (null): μ_premium = μ_fair, H₁ (alternative): μ_premium < μ_fair  
- [ ] H₀ (null): μ_premium ≠ μ_fair, H₁ (alternative): μ_premium = μ_fair  

**Question 4**: Referring to Exercise 2, what is the p-value for the test that compares the mean price of ‘Premium’ and ‘Fair’ diamonds?  
- [x] 0.2602  
- [ ] 0.0001  
- [ ] 0.3108  
- [ ] 1.559  

**Question 5**: Referring to Exercise 2, what can you conclude from your calculated p-value?  
- [x] There is not enough evidence to reject the null hypothesis that the means are the same.  
- [ ] You have proven the null hypothesis.  
- [ ] The means of the two cuts are the same.  
- [ ] You reject the null hypothesis that the means are the same.  
- [ ] You have proven the alternative hypothesis.  

**Question 6**: Referring to Exercise 3, calculate the difference between the average price_per_carat for Fair and Premium diamonds. Subtract x̄ (Fair) from x̄ (Premium) of the price_per_carat feature.  
- [x] $891.91  
- [ ] $75.89  
- [ ] $1,044.09  
- [ ] $643.30  

**Question 7**: Referring to Exercise 3, calculate the difference between the average carat for Fair and Premium diamonds. Subtract x̄ (Fair) from x̄ (Premium) of the carat feature.  
- [x] -0.172  
- [ ] 0.414  
- [ ] -3.188  
- [ ] -1.454  

**Question 8**: Based on the hypothesis test you conducted in Exercise 3, where you compared the mean carat of ‘Premium’ and ‘Fair’ diamonds, which two statements below are true?  
- [x] You can reject the null hypothesis.  
- [ ] You don’t have enough evidence to reject the null hypothesis.  
- [x] You performed a one-tailed test.  
- [ ] You performed a two-tailed test.  

**Question 9**: In Exercise 4, can you reject the null hypothesis that the proportion of ‘Ideal’ or ‘Premium’ cut diamonds makes up 67% of the shipment?  
- [ ] Yes  
- [x] No  

**Question 10**: Based on the hypothesis test results for cut proportions, which of the following statements best communicates an appropriate recommended action to your stakeholders?  
- [x] The proportion of the two cuts is as expected, so no changes to inventory management are necessary.  
- [ ] Adjust inventory strategies to focus more on premium or ideal cut diamonds.  
- [ ] Remove all fair cut diamonds from the batch to focus only on premium or ideal cuts.  
- [ ] Increase the proportion of premium or ideal cut diamonds in the new batch to improve inventory composition.


### Capstone Project

**Q1**: What distribution does the feature maxheartrate most closely resemble?  
- [ ] Bernoulli  
- [ ] Binomial  
- [ ] Uniform  
- [x] Normal  

**Q2**: Which two of the following features appear to have a negative skew?  
- [x] age  
- [x] maxheartrate  
- [ ] oldpeak  
- [ ] fbs  

**Q3**: In what range (approximately) would you expect 68% of the maxheartrate values to be? Assume that the distribution is normal.  
- [x] 126-172 BPM  
- [ ] 129-175 BPM  
- [ ] 150-155 BPM  
- [ ] 149-152 BPM  

**Q4**: Which diagnosis group (sick or healthy) has a higher proportion of patients with fasting blood sugar (fbs) = 1?  
- [x] Healthy (diagnosis = 0y)  
- [ ] Sick (diagnosis = 1)  
- [ ] Both groups have the same average fasting blood sugar  
- [ ] You cannot calculate proportion of patients with fbs = 1  

**Q5**: What is the difference between the average maxheartrate of sick patients and the average maxheartrate of healthy patients?  
- [x] The sample mean of maxheartrate is about 19.5 beats per minute higher for sick patients.  
- [ ] The sample mean of maxheartrate is about 19.5 beats per minute lower for sick patients.  
- [ ] The sample mean of maxheartrate is about 11.5 beats per minute higher for sick patients.  
- [ ] The sample mean of maxheartrate is about 11.5 beats per minute lower for sick patients.  

**Q6**: Generally speaking, would you expect the margin of error for your 95% confidence interval to increase or decrease if you get your hands on a lot more data, and why?  
- [x] Decrease, because the margin of error is divided by the square root of the sample size.  
- [ ] Increase, because the variability increases the more samples you have.  
- [ ] Increase, because you will halve your sample size.  
- [ ] Decrease, because the margin of error is divided by the sample mean.  

**Q7**: You are working on delivering your results to the group of physicians. As part of your report, you will carefully explain the meaning of your 95% confidence interval, to avoid potential misinterpretation. What do the upper and lower limits of confidence intervals correspond to in your statistical analysis?  
- [ ] They represent the exact values of the population parameter.  
- [ ] They indicate the range of values within which future observations will fall.  
- [x] They define the range in which the true population parameter is expected to lie with a certain level of confidence.  
- [ ] They show the probability of 5% of events occurring within the interval.  

**Q8**: One of the physicians has approached you to ask about the possibility of simulating data for additional patients. Which of the following describes the main benefit of simulation in this case?  
- [x] You can quickly and easily generate many possible scenarios, without having to identify more sick and healthy patients.  
- [ ] You can be 100% confident in your conclusions based on the simulated data.  
- [ ] You will be able to destroy the data you have collected, since you no longer need any real data.  
- [ ] You can be certain that your data will always follow a normal distribution when simulating it.  

**Q9**: The test for comparing the means of maxheartrate that you performed in exercise 3 is a **one-sided test**, and has a p-value of **1.71E-45**. This means that you **can** reject the null hypothesis with any reasonable significance level.  

**Q10**: The physicians have asked you to conduct further analysis on the cholesterol feature. Which set of hypotheses would be appropriate if you wanted to conduct a two-sided test comparing the means of cholesterol between sick and healthy patients?  
- [ ] Null hypothesis: mu_sick = mu_healthy; Alternative hypothesis: mu_sick > mu_healthy  
- [ ] Null hypothesis: mu_sick = mu_healthy; Alternative hypothesis: mu_sick < mu_healthy  
- [x] Null hypothesis: mu_sick = mu_healthy; Alternative hypothesis: mu_sick ≠ mu_healthy  
- [ ] Null hypothesis: mu_sick ≠ mu_healthy; Alternative hypothesis: mu_sick > mu_healthy  
