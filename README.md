![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Reading About Statistic Concepts

## Introduction

In the future, you will need to understand deep statistical concepts by reading technical articles. As a training for that, it is interesting to start from here. Also, as we have limited time, this is a way to have some self guided learning to understand everything better and have a wider knowledge.

This week you will find some questions here that you will need to answer by documentating yourself. So you will do a different PR for each question (you are meant to answer the questions in different days). Don't hesitate to write as many text as you need and push images if you need them.

Remember for this lab: there is a right answer. But there is no perfect way to explain it (except for in a mathematical way, but this is another story).

## Challenges

### Challenge 1: What is the difference between expected value and mean?
You know both concepts but, is there a difference? Are they synonims? Start investigating. 

As a good reference (once you have looked for some information) you have   [this](http://expected.news/value2) article.

ANSWER:

Expected value, refers to a single event that will happen in the future; ie: in future I expect my bus 
to be 50% likely to be earlier or later than now. 
Average value is a statistical generalization of multiple occurances of an event: ie based on the past 
ten times I waited for a bus, the bus arrived at X time.

The expectation is the average value or mean of a random variable not a probability distribution. 
As such it is for discrete random variables the weighted average of the values the random variable takes on where the weighting is according to the relative frequency of occurrence of those individual values. 
For an absolutely continuous random variable it is the integral of values x multiplied by the probability density. 
Observed data can be viewed as the values of a collection of independent identically distributed random variables. 
The sample mean (or sample expectation) is defined as the expectation of the data with respect to the empirical distribution for the observed data. This makes it simply the arithmetic average of the data.


### Challenge 2: What is the "problem" in science with p-values?
We have told you that a lot of scientifical investigations are based on p-values. The last week, Nature magazine published [an article](http://nature.social/statistical4) regarding the problem. Start digging on it!

Don't hesitate to use more articles if you want to :)

Overreliance on P-values as a metric of significance negates the importance of actually analysing the data itself on it's strength.
A p value denotes the probability of your experiment happening the way it did the way it did. 
A p value of 0.05 means there is a 5% chance that the results you got support your conclusion not because there is a bias for some reason towards such results (say a coin is heaver on one side than another) 
but because of just dumb luck.



### Challenge 3: Applying testing to a specific case: A/B testing.
A/B testing is a widely used tool to understand differences between two samples. It is a way to measure the impact of something we did: 
* A marketing campaign.
* A new feature in our application. 
* A new design in our application.
* A different flow in the User Experience flow.

To do this, is very important first to design our experiment. 
* We need to know how we are measuring the impact. If people has the behaviour we want with this new implementation.
* We choose a control group (people who doesn't have/see the new change) and the group which will see the new change. 
* We think about how much data do we need.
* We measure the difference between them.

One example:
Our application has a lot of mini-games. We want people to reach the games that we think are the best but the behaviour is not the expected, they don't reach them.

So we call a designer and after a lot of work he shows us a new design for our application: we will add a botton specific for that kinf of games inviting the users to click on it:

*Click here to discover cool games!*

We think it will work but can we be sure? So instead of implementing this new botton for all users, we implement it for 10% and we compare the results with the users that didn't have it. Is there a significant difference? Is our botton working?

Read more about A/B testing with a couple of examples:

[Another example about Netflix here](http://select.video/artwork4)

[What happened to Basecamp](http://millions.social/tested7)

[An example with Python](http://math.social/tested3)

[A cool general explanation](http://arts.show/tested7)

So, take one single example in the articles you just read, which specific test/s would you apply? (We want you just to do a draft and think a little bit how to apply the tests you already know in this case)

Carrying out an A/B Test:

	1. Design the study to investigate your aim, without being biased towards one result or another, whilst collecting sufficient information.
	2. Establish the null hypothesis and alternative hypothesis. 
	3. Identify your users.
	4. Detemrine the key metrics eg: hits per hour / day / month.
	5. Run the test, record the success rate, allow it to run for a sufficient amount of time.
	6. Plot the distribution of the difference between the samples.
	7. Calculate the statistical power.
	8. Evaluate how the sample size affects testing. 
	9. Take action based on the outputted metrics and plan the next A/B test based on the significance or lack thereof of
	previous test. 








## Deliverables
You need to submit a markdown file with the answers to the questions above. You can create a new `.md` file or directly edit the `README.md`.

## Submission
Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.
