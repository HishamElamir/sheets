# Introduction

A t-test is one of the most frequently used procedures in statistics in general and hypothesis in particular.

## What is t-test

The t-statistic was introduced in 1908 by _William Sealy Gosset_, a chemist working for the Guinness brewery in Dublin, Ireland. "Student" was his pen name.

> _Gosset_ had been hired owing to _Claude Guinness_'s policy of recruiting the best graduates from _Oxford_ and _Cambridge_ to apply biochemistry and statistics to _Guinness_'s industrial processes. _Gosset_ devised the **t-test** as an economical way to monitor the quality of stout(type of beers). The t-test work was submitted to and accepted in the journal Biometrika and published in 1908. Company policy at Guinness forbade its chemists from publishing their findings, so Gosset published his statistical work under the pseudonym "**Student**".

The t test (also called Student’s T Test) compares two averages (means of samples) and tells you if they are different from each other. The t test also tells you how significant the differences are; In other words it lets you know if those differences could have happened by chance.

## Two Examples

### Example 1

 > Let’s say you have a cold and you try a naturopathic remedy. Your cold lasts a couple of days. The next time you have a cold, you buy an over-the-counter pharmaceutical and the cold lasts a week. You survey your friends and they all tell you that their colds were of a shorter duration (an average of 3 days) when they took the homeopathic remedy. What you really want to know is, are these results repeatable? A t test can tell you by comparing the means of the two groups and letting you know the probability of those results happening by chance.

### Example 2

> Student’s T-tests can be used in real life to compare means. For example, a drug company may want to test a new cancer drug to find out if it improves life expectancy. In an experiment, there’s always a control group (a group who are given a placebo, or “sugar pill”). The control group may show an average life expectancy of +5 years, while the group taking the new drug might have a life expectancy of +6 years. It would seem that the drug might work. But it could be due to a fluke. To test this, researchers would use a Student’s t-test to find out if the results are repeatable for an entire population.

## T-Score

The **t-score** is a ratio between the difference between two groups and the difference within the groups.

* The _larger_ the **t-score**, the more difference there is between groups.
* The _smaller_ the **t-score**, the more similarity there is between groups.
* A **t-score** of `3` means that the groups are three times as different from each other as they are within each other.
* When you run a **t-test**, the _bigger_ the `t-value`, the more likely it is that the results are repeatable.
* A _large_ **t-score** tells you that the groups are different.
* A _small_ **t-score** tells you that the groups are similar.

## T-Value/P-Value

* Every t-value has a p-value to go with it.
    > A p-value is the probability that the results from your sample data occurred by chance.
* P-values are from 0% to 100%. They are usually written as a decimal.
    > For example, a p value of 5% is 0.05.
* Low p-values are good; They indicate your data did not occur by chance.
    > For example, a p-value of .01 means there is only a 1% probability that the results from an experiment happened by chance. In most cases, a p-value of 0.05 (5%) is accepted to mean the data is valid.

## T-Test Types

There are **three** main types of t-test:

1. An **Independent Samples** t-test compares the means for two groups.
2. A **Paired sample** t-test compares means from the same group at different times (say, one year apart).
3. A **One sample** t-test tests the mean of a single group against a known mean.

## How to perform a t-test

1. Determine a _null_ and _alternate_ hypothesis.
2. Collect sample data.
3. Determine a _confidence interval_ and _degrees of freedom_.
4. Calculate the **t-statistic**.
5. Calculate the critical **t-value** from the **t-distribution**.
6. Compare the critical **t-values** with the calculated **t-statistic**.