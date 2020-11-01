# Comparison of means

Congratulations on working out that the fact we have a large amount of data allows us to use the normal distribution to perform the hypothesis case in this second exercise in place of the t-distribution that was used in the previous exercise.

We need to consider one final thing before we are done with the programming tasks this week.  Last week I introduced the following test statistic that can be used to compare the sample means for two data sets.

![](https://render.githubusercontent.com/render/math?math=T=\frac{\frac{1}{n_1}\sum_{i=1}^{n_1}X_i-\frac{1}{n_2}\sum_{j=1}^{n_2}Y_j-\theta_0}{\sqrt{\frac{\sigma_1^2}{n_1}%2B\frac{\sigma_2}{n_2}}})

In the last exercise, however, I introduced this paired comparison test.  You thus might be asking yourself when it is appropriate to use the paired comparison test and when you do should the comparison of means that we learned about last week.  The best way I can think to explain this is to give you the following example of a situation when it is appropriate to do the comparison of means test: 

_A trial is performed on a new blood pressure medication.  The patients in group A are given the medication while the patients in group B are given a placebo.  Does the data extracted suggest that the drug has an effect?_

Compare this question with the question that was asked in the task before the previous one.  In that question, the same group of patients were both given and not given the drug.  We can thus calculate the change in each patient's blood pressure from the data.  In this case, by contrast, we cannot calculate these changes as the set of patients who are given the drug is different from the set of patients who are given the placebo.  We do not even know if the same number of patients who were given the drug is the same as the number of patients who were given the placebo.

__Your task is to demonstrate that you understand when it is appropriate to use the comparison of means test and the paired test.  Consider the two tests that you are described on the left.__  Replace the ????? on the left with the phrase comparison of means test or paired comparison test.  The phrase you select should be the appropriate test for performing analysing the data that is described. 

## QUIZ QUESTIONS

# Question 1
print("To determine if men are taller than women on average you would use a ?????")
# Question 2 
print("To determine if the test scores of a particular group of children have improved with a change")
print("of teacher you would use a ????")
# Question 3
print("To determine if sales of product are different in France and Spain you would")
print("use a ????")
# Question 4
print("To determine if the students in one year of a university are more interested in statistics than")
print("another you would use a ?????")
# Question 5
print("To determine if a particular group of customers used Zoom more frequently during lockdown")
print("you would use a ?????")
# Question 6
print("To determine if a changes in the industrial strategy in a factory has affected the")
print("polution levels in the rivers local to the factory you would use a ????")
