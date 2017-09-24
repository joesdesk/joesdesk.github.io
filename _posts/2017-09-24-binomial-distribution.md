---
layout: post
title: The Binomial Distribution
---

How many flips of a coin will come out as heads if we flip 10 coins? If we roll 3 dice, how many will give odd numbers? Notice that these questions ask about an event that is reasonably repeatable: a coin flip or a dice roll. For each event, we have an outcome of interest: a coin coming up heads or rolling an odd number. The outcome can either occur or not. When it does, we call the trial a "success" and if not, a "failure." The success of any event has a constant probability of occurring–for both the coin and dice example, the probability of success is one-half.

Questions like the ones I just asked are common and interesting enough that statisticians have a tool for answering them. The formula is called the binomial distribution. Like other distributions, this one describes the way probability is spread out over a given set of outcomes like mountains and hills on land. Mountains and hills are higher on some areas of land than others, just as some outcomes are more probable than others. Distributions tell us how high the probability is for an outcome.

For a fair coin, it seems rather unlikely that 10 flips will result in no heads or all heads. These are the outcomes for which the probability is low. It seems more likely that half of the flips will be heads. The probability of this outcome is higher. If we change the number of coin flips to 20, we expect the probabilities to be different. If we change the coins to dice and the outcomes to rolls of six, the probabilities for outcomes change again.

The binomial distribution makes this intuition more mathematical by specifying the exact probability. To determine the probabilities, let $n$ be the number of trials and let $r$ be the number of successes. Keeping in mind that the probability each trial's success is constant regardless of the outcome of other trials, we let this constant probability be $p$. The binomial distribution tells us the probability $P$ of such an outcome is $$ P = \frac{n!}{r!(n-r)!} p^r (1-p)^{(n-r)} $$ where $!$ denotes the factorial. The factorial of a number is simply itself, times all of its predecessors. For example, $5!=5\times 4\times 3\times 2\times 1$. We usually use a calculator to compute these things!

Because the binomial distribution can be applied to a wide range of problems, sometimes more serious than the examples we have shown, it has become a standard tool in the statisticians' toolbox.
