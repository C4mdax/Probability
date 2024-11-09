# Probability-Poisson
Within the probabilistic concept of discrete random variables, we can find a parametric family of distributions called Poisson Distribution. This distribution is very useful for modeling the probability of occurrence of rare events. For example, if we know that the average magnitude on the Richter scale of all earthquakes that occurred during the last 5 years was 4.4, what is the probability that an earthquake of magnitude 7.9 will occur? This is a simple and colloquial example, but it helps to understand the concept behind this random variable. Despite being a relatively less complex distribution to understand and abstract than other distributions, it is one of the most used and best suited to computational and probabilistic models, even entering machine learning models.

Let's delve deeper into it:

Let $\lambda$ be the average frequency rate of ocurrence of events in a given time, and let %x% be the number of events that happen/will happen.
With $X$ the Random Variable, we define:  
#### $$\Huge{f_X (x) = \frac{e^{-\lambda}\lambda x}{x!}}$$  
as the probability density function evaluated for the case of x successes. Simply put, $$f_X (x) = \mathbb{P}[X = x]$$

In this code, a calculation of the probability of occurrence of $x$ cases given $$\lambda$$ frequency rate is provided, in addition to a graphical visualization of the behavior of the Poisson distributed probability.
