---
keywords: Investing,Fundamental Analysis,Tools for Fundamental Analysis,Tools
title: Wilcoxon Test
description: The Wilcoxon test, which alludes to either the rank sum test or the marked rank test, is a nonparametric test that compares two paired gatherings.
---

# Wilcoxon Test
## What Is the Wilcoxon Test?

The Wilcoxon test, which can allude to either the rank sum test or the marked rank test form, is a nonparametric statistical test that compares two paired gatherings. The tests essentially calculate the difference between sets of pairs and break down these differences to establish on the off chance that they are [statistically significantly](/statistical-importance) different from each other.

## Understanding the Wilcoxon Test

The rank sum and marked rank tests were both proposed by American statistician Frank Wilcoxon in a historic research paper distributed in 1945. The tests established the groundwork for [hypothesis testing](/hypothesistesting) of [nonparametric statistics](/nonparametric-statistics), which are utilized for population data that can be ranked but don't have mathematical values, for example, customer satisfaction or music audits. Nonparametric distributions don't have parameters and cannot be defined by an equation as parametric distributions can.

The types of questions that the Wilcoxon test can assist reply with including things like:

- Are test scores different from 5th grade to 6th grade for similar students?
- Does a particular medication meaningfully affect health when tested on similar people?

These models assume that the data comes from two matched, or dependent, populations, following a similar person or stock through time or place. The data is likewise assumed to be continuous rather than discrete. Since it is a nonparametric test, it doesn't need a particular probability distribution of the dependent variable in the analysis.

## Types of the Wilcoxon Test
- The Wilcoxon rank sum test can be utilized to test the [null hypothesis](/null_hypothesis) that two populations have a similar continuous distribution. A null hypothesis is a statistical test that says there's no significant difference between two populations or variables. The base assumptions important to utilize the rank sum test is that the data are from a similar population and are paired, the data can be estimated on at least an interval scale, and the data were picked haphazardly and independently.
- The Wilcoxon marked rank test assumes that there is information in the magnitudes and indications of the differences between paired observations. As the nonparametric equivalent of the paired student's t-test, the marked rank can be utilized as an alternative to the [t-test](/t-test) when the population data doesn't follow a [normal distribution](/normaldistribution).

## Calculating a Wilcoxon Test Statistic

The steps for showing up at a Wilcoxon marked rank test statistic, **W,** are as follows:

1. For every item in a sample of **n** items, obtain a difference score, D~i~, between two measurements (i.e., subtract one from the other).
1. Neglect then positive or negative signs and obtain a set of **n** absolute differences |D~i~|.
1. Omit difference scores of zero, providing you with a set of **n** non-zero absolute difference scores, where **n' ≤ n**. Thus, **n'** turns into the actual sample size.
1. Then, assign ranks R~i~ from 1 to **n** to every one of the |D~i~| to such an extent that the smallest absolute difference score gets rank 1 and the largest gets rank **n**. Assuming that at least two |D~i~| are equivalent, they are each assigned the average rank of the ranks they would have been assigned separately had ties in the data not happened.
1. Presently reassign the symbol "+" or "- " to each of the **n** ranks R~i~, contingent upon whether D~i~ was initially positive or negative.
1. The Wilcoxon test statistic **W** is subsequently obtained as the sum of the positive ranks.

In practice, this test is performed utilizing statistical analysis software or a spreadsheet.

## Highlights
- Both variants of the model assume that the pairs in the data come from dependent populations, i.e., following a similar person or share price through time or place.
- The goal of the test is to determine on the off chance that at least two sets of pairs are different from each other in a statistically significant way.
- The Wilcoxon test compares two paired gatherings and comes in two forms, the rank sum test, and marked rank test.
