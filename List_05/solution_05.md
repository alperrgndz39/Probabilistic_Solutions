# Binomial Distribution
## Probability and Statistics Presentation

---

# Slide 1 — Introduction

Hello everyone.

Today I will talk about the **Binomial Distribution**.

In this presentation, I will explain:

- the random experiment,
- the sample space,
- the random variable,
- the support of the random variable,
- the PMF and CDF,
- parameter effects,
- graphs,
- and real-life applications.

The goal is to understand the formal structure of the distribution and how we use it in probability theory.

---

# Slide 2 — Random Experiment

First, we define the random experiment.

The experiment is:

- flipping a coin 5 times.

Each trial has only two possible outcomes:

- Heads
- Tails

The trials are independent.

This means:

- one flip does not affect another flip.

This experiment satisfies the conditions for a binomial distribution.

---

# Slide 3 — Sample Space Ω

Now we define the sample space Ω.

The sample space contains all elementary outcomes of the experiment.

An elementary outcome is one complete sequence of results.

Examples:

- HHHHH
- HHTTT
- HTHTH
- TTTTT

The sample space contains every possible sequence of heads and tails for 5 flips.

---

# Slide 4 — Random Variable X

Next, we define the random variable X.

The random variable counts the number of successes.

We define:

- success = getting Heads.

Example:

For the outcome:

`HHTHT`

the random variable is:

\[
X(HHTHT)=3
\]

because there are 3 heads.

---

# Slide 5 — Support of X

Now we identify the support of X.

The support is the set of all possible values taken by the random variable.

For 5 coin flips:

\[
X \in \{0,1,2,3,4,5\}
\]

Important difference:

- The sample space contains outcomes.
- The support contains numerical values of X.

These two concepts are different.

---

# Slide 6 — Definition of Binomial Distribution

The binomial distribution is a discrete probability distribution.

It describes the probability of obtaining a fixed number of successes in repeated independent trials.

Conditions:

- fixed number of trials,
- two possible outcomes,
- independent trials,
- constant probability of success.

The distribution is defined by two parameters:

- `n` = number of trials,
- `p` = probability of success.

---

# Slide 7 — Parameters of the Distribution

For our example:

\[
n=5
\]

and

\[
p=0.5
\]

This means:

- we perform 5 trials,
- and the probability of heads is 0.5.

The parameters change the shape of the distribution.

We will see this later in the graphs.

---

# Slide 8 — Probability Mass Function (PMF)

The PMF gives the probability of exactly k successes.

The formula is:

\[
P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}
\]

Where:

- `n` = number of trials,
- `k` = number of successes,
- `p` = probability of success.

The PMF gives probability at one exact value.

---

# Slide 9 — PMF Example

Now let us calculate a probability.

We want to find:

\[
P(X=3)
\]

This means:

- the probability of getting exactly 3 heads in 5 coin flips.

We use:

\[
n=5,\quad k=3,\quad p=0.5
\]

The result is:

\[
P(X=3)=0.3125
\]

So, the probability of exactly 3 heads is 31.25%.

---

# Slide 10 — PMF Graph

The PMF graph shows probabilities for each possible value of X.

The graph changes when parameters change.

If `p` is small:

- the graph moves to the left.

If `p` is large:

- the graph moves to the right.

If `n` increases:

- the graph becomes wider.

Graphs help us understand the behavior of the distribution visually.

---

# Slide 11 — Cumulative Distribution Function (CDF)

Now we move to the cumulative distribution function, or CDF.

The formula is:

\[
F(x)=P(X\le x)
\]

The CDF adds probabilities from left to right.

Example:

\[
P(X\le3)
\]

This means:

- probability of getting at most 3 successes.

The CDF always increases from 0 to 1.

---

# Slide 12 — PMF and CDF Comparison

The PMF and CDF describe probabilities in different ways.

PMF:

\[
P(X=3)
\]

- probability at one exact value.

CDF:

\[
P(X\le3)
\]

- cumulative probability up to a value.

Both functions are important for understanding probability distributions.

---

# Slide 13 — Graphical Understanding

Graphical analysis is very important in probability theory.

We can compare graphs for different values of:

- `n`
- `p`

We observe changes in:

- center,
- spread,
- symmetry,
- and concentration of probability.

Some properties remain invariant:

- probabilities are always between 0 and 1,
- total probability is always equal to 1.

---

# Slide 14 — Real-Life Applications

The binomial distribution has many practical applications.

Examples include:

- exams,
- surveys,
- quality control,
- medical testing,
- and reliability analysis.

It is useful whenever there are only two possible outcomes:

- success or failure.

---

# Slide 15 — Computational Tools

Computational tools help us visualize and compare distributions.

Examples:

- Python,
- HTML and JavaScript,
- statistical software.

A small application can allow users to:

- choose a distribution,
- change parameters,
- display PMF and CDF graphs,
- compare probabilities.

This improves graphical understanding and technical skills.

---

# Slide 16 — Conclusion

In conclusion:

- the binomial distribution models repeated independent experiments,
- the PMF gives exact probabilities,
- the CDF gives cumulative probabilities,
- parameters change the shape of the distribution,
- and graphs help us understand probability visually.

The binomial distribution is one of the most important distributions in probability and statistics.

Thank you for listening.