# Class Assignment 3

This git repository contains solutions py file with functions for each question that you will be implementing, along with a public test cases evaluation script in test.py. You will have to clone this repository to your own private repo, create a fresh branch for each question as answers/q1 answers/q2 and so on, implement the solution, commit it, and merge it back into main branch. We will be evaluating on completion of git workflow tasks as well, and no marks will be given if files are directly edited online instead of following above flow.

## Problem 1

A shared office printer serves documents fairly rather than finishing one before
starting the next. Documents wait in a single queue, numbered `0, 1, 2, …` in the
order they were submitted. Document `i` has `pages[i]` pages.

The printer repeats this until the queue is empty:

1. Take the document at the **front** of the queue.
2. Print exactly **one page** of it.
3. If that document still has pages left, send it to the **back** of the queue.
   Otherwise it is finished and leaves the queue.

### Return

The document numbers in the order they **finish printing**.

