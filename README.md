# udacity-descriptive-statistics-project

*"An experiment dealing with drawing from a deck of playing cards."*

(Text contained in this document available freely online, presumed © 2011-2015 Udacity, Inc.)

## Overview

Welcome to the Descriptive Statistics Final Project! In this project, you will demonstrate what you
have learned in this course by conducting an experiment dealing with drawing from a deck of playing
cards and creating a writeup containing your findings.  Be sure to check through the project rubric
to self-assess and share with others who will give you feedback.

In the final project, you will demonstrate what you have learned in this course by conducting an
experiment dealing with drawing from a deck of playing cards and creating a writeup containing your
findings. If you are a student viewing the free courseware, you are welcome to complete this project
but you will not submit your project for evaluation.

## Questions for Investigation

This experiment will require the use of a standard deck of playing cards. This is a deck of
fifty-two cards divided into four suits (spades (♠), hearts (♥), diamonds (♦), and clubs (♣)), each
suit containing thirteen cards (Ace, numbers 2-10, and face cards Jack, Queen, and King).

You can use either a physical deck of cards for this experiment or you may use a virtual deck of
cards such as that found on random.org (http://www.random.org/playing-cards/).

For the purposes of this task, assign each card a value: The Ace takes a value of 1, numbered cards
take the value printed on the card, and the Jack, Queen, and King each take a value of 10.

1. First, create a histogram depicting the relative frequencies of the card values.
2. Now, we will get samples for a new distribution. To obtain a single sample, shuffle your deck of
   cards and draw three cards from it. (You will be sampling from the deck without replacement.)
   Record the cards that you have drawn and the sum of the three cards’ values. Repeat this sampling
   procedure a total of at least thirty times.
3. Let’s take a look at the distribution of the card sums. Report descriptive statistics for the
   samples you have drawn. Include at least two measures of central tendency and two measures of
   variability.
4. Create a histogram of the sampled card sums you have recorded. Compare its shape to that of the
   original distribution. How are they different, and can you explain why this is the case?
5. Make some estimates about values you will get on future draws. Within what range will you expect
   approximately 90% of your draw values to fall? What is the approximate probability that you will
   get a draw value of at least 20? Make sure you justify how you obtained your values.

## The Rubric

| Criteria                                                             | Does Not Meet Specifications                                                                                                                                                           | Meets Specifications                                                                                                                                                               |
| -----------------------------------------------------------------    | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Question 1: Plotting a histogram of card values**                  | The histogram does not accurately reflect the card values’ relative frequency distribution or no histogram is provided.                                                                | A histogram is provided that accurately reflects the card values’ relative frequency distribution.                                                                                 |
| **Question 2: Obtain samples from a deck of cards**                  | Sampled data is not provided, insufficient, or does not reflect the experiment being performed for the project.                                                                        | At least thirty samples have been performed and the summed values from each sample have been reported in a submitted spreadsheet.                                                  |
| **Question 3: Report descriptive statistics regarding sample taken** | Two measures of central tendency and variability are not reported to describe the sample or are not computed correctly.                                                                | At least two measures of central tendency and two measures of variability are accurately reported to summarize and describe the samples taken for Question 2.                      |
| **Question 4: Plotting a histogram of sampled values**               | The histogram does not accurately reflect sampled values or no histogram is provided. No discussion of the shape of the distribution is provided or comparison is not well-justified.  | A histogram accurately reflecting the sampled data is provided. Discussion of the shape is provided, including a comparison to that of the histogram of the original card values.  |
| **Question 5: Making estimates based on the sampled distribution**   | Estimates made for the prompted questions do not reflect the values obtained from the sample.                                                                                          | Estimates are made for the prompted questions that reflect the samples taken and their distribution.                                                                               |

## INSTALL

```
conda create -n newenv --file exported_packages.txt
source activate newenv
```
