
# Bayes' Theorem - Lab

## Introduction

In this lab, we shall try to put some of the formulas to practice that we came across with in the previous lesson. 

## Objectives
* Understand and describe the Bayesian theorem from conditional probabilities
* Describe the roles of Prior, Likehood and Posterior components of Bayes Theorem 
* Understand and perform simple applications of Bayes Theorem for sensitivity and specificity

## Exercise 1
### If a single card is drawn from a standard deck of playing cards, What is the probability of seeing a king ?


```python
# Your solution
```

### If evidence is provided (for instance, someone looks at the card) that the single card is a **face card**, what would be the posterior probability according to Bayes theorem?


```python
# Your Solution
```

## Exercise 2
#### 1. A couple has two children, the older of which is a boy. What is the probability that they have two boys?
#### 2. A couple has two children, one of which is a boy. What is the probability that they have two boys?


```python
# Explain events as:
# A = both children are boys
# B = older child is a boy 
# C = One of the children is a boy 
```


```python
# Part 1
# Your solution
# P(C|A)

```


```python
# Part 2 
# Your solution
# P(A|C)
```

## Exercise 3 - Bayesian Disease Diagnosis

[Visit this link for an insight into Bayesian Disease Daignosis](http://doingbayesiandataanalysis.blogspot.com/2013/01/bayesian-disease-diagnosis-with.html)



A disease test is advertised as being 99% accurate 

* If a patient has the disease,they  will test positive 99% of the time.

* If you don't have the disease, they will test negative 99% of the time. 

* 1% of all people have this disease 

#### Now a patient tests positive, what is the probability that you actually have the disease?


```python
# By Bayes' Theorem, the probability you have the disease is

#P(D|Pos) = P(Pos|D)* P(D) / P(Pos) 

# P(Pos) is calculated as :
# You either have the disease and tested incorrectly (0.1*0.99), 
# or you have the disease and tested correctly (0.99 *0.1). 

```

## Summary 

In this lab, we saw a few simple examples of Bayesian logic and how we can add prior information to our calculation, in order to update our beliefs about the certain events. Bayesian logic works in numerous ways and it is not within the scope of this section to give you a deep dive in complex Bayesian problems. You are advised to re-visit the provided links when you have a better understanding of Bayesian inference. 

# Problem 1
You go to see the doctor about an ingrowing toenail. The doctor selects you at random to have
a blood test for swine flu, which for the purposes of this exercise we will say is currently suspected
to affect 1 in 10,000 people in Australia. The test is 99% accurate, in the sense that the probability
of a false positive is 1%. The probability of a false negative is zero. You test positive. What is the
new probability that you have swine flu?

# Problem 2
Now imagine that you went to a friend’s wedding in Canada recently, and (for the purposes of this
exercise) it is know that 1 in 200 people who visited Canada recently come back with swine flu.
Given the same test result as above, what should your revised estimate be for the probability you
have the disease?

# Problem 3
Imagine that, while in Canada, you also took a side trip to Las Vegas, to pay homage to the
TV show CSI. Late one night in a bar you meet a guy who claims to know that in the casino at
the Tropicana there are two sorts of slot machines: one that pays out 10% of the time, and one
that pays out 20% of the time [note these numbers may not be very realistic]. The two types
of machines are coloured red and blue. The only problem is, the guy is so drunk he can’t quite
remember which colour corresponds to which kind of machine. Unfortunately, that night the guy
becomes the vic in the next CSI episode, so you are unable to ask him again when he’s sober.

# Problem 4
Next day you go to the Tropicana to find out more. You find a red and a blue machine side by side.
You toss a coin to decide which machine to try first; based on this you then put the coin into the
red machine. It doesn’t pay out. How should you update your estimate of the probability that this
is the machine you’re interested in? What if it had paid out - what would be your new estimate
then

# Problem 5
In a particular pain clinic, 10% of patients are prescribed narcotic pain killers. Overall, five percent of the clinic’s patients are addicted to narcotics (including pain killers and illegal substances). Out of all the people prescribed pain pills, 8% are addicts. If a patient is an addict, what is the probability that they will be prescribed pain pills?

# Problem 6
Given the following statistics, what is the probability that a woman has cancer if she has a positive mammogram result?

1. One percent of women over 50 have breast cancer.
2. Ninety percent of women who have breast cancer test positive on mammograms.
3. Eight percent of women will have false positives.
