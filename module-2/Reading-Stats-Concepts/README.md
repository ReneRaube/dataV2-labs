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

### Answer:
If an experiment were to be repeated infinitely often, the average value of a discrete random variable would be the mean value of the results of the experiment. This mean value can be interpreted as an expected value, i.e. we would expect this value if we were to perform the experiment infinitely.
Expected value and arithmetic mean are identical if the probability for each attempt is the same. This is the case in a binomially distributed experiment, for example. If the probability is different for each experiment the expected value is a weighted arithmetic mean.

The expected value can be used to determine whether a game is "fair". In a fair game, the expected value would be zero - you would lose as often as you would win. In the long run, profit and loss would balance each other out.


### Challenge 2: What is the "problem" in science with p-values?
We have told you that a lot of scientifical investigations are based on p-values. The last week, Nature magazine published [an article](http://nature.social/statistical4) regarding the problem. Start digging on it!

Don't hesitate to use more articles if you want to :)

### Answer:
According to the article, one should not conclude that there is "no difference" or "no association" just because a P-value has reached a certain magnitude or because a confidence interval includes zero. Nor should one come to the conclusion that two studies contradict each other because one had a statistically significant result but the other did not. 

Furthermore, the authors of this article state that surveys in numerous papers have shown that statistically non-significant results are interpreted as "no difference" or "no effect" in about half of the cases. The authors of this article call for the entire concept of statistical significance to be abandoned.
They further argue that one has to learn to accept uncertainty. A practical way to do this, would be to rename confidence intervals to "compatibility intervals" in order to avoid excessive confidence. 
In particular, the authors also recommend describing the practical effects of all values within the interval, especially the observed effect (or point estimate) and the limits. It should be noted that all values between the bounds of the interval are reasonably compatible with the data given the statistical assumptions used to calculate the interval. Therefore, the authors do not consider it useful to mark a particular value (such as the zero value) in the interval as "shown".

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

## Deliverables
You need to submit a markdown file with the answers to the questions above. You can create a new `.md` file or directly edit the `README.md`.

## Submission
Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.
