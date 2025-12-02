# Assignment 6 Part 1 - Writeup

**Name:** Ashley Quiroz
**Date:** 11/20/25

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

R2 tells us how well my model's predictions match the data. If its is close to 1 it means that it's a good fit and strongly matches it, but if it's close to 0 it tells us that it has a poor fit and that the model doesn't really match the data.
---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

MSE tells you how far the models values are from the actual data. I think we square the errors instead of just taking the average of the errors in order to make the number a positive if it is a negative number so that there aren't any negatives.

---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

No I wouldn't trust it to accurately predict a score for a student who studied for 10 hours because the maximum number of hours in my dataset is 9.6 hours and when a prediction that is outside of the range of the training data is made the model can give incorrect predictions because it has not seen data in that region.

---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?
The relationship between hours studied and test scores is strong, it is mlinear, and is positive.

---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. Quality of studying
2. The prior knowledge each individual had before studying
3. Stress levels during the exam

---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

We split our data into training and testing sets in order to see how well it works with data it has never seen before (test accuracy). If we trained and tested on the same data then we wouldn't know well it works with new data since it would seem to be wokring with the trained data only because it has already seen it before. 

---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

The most challenging part of this assignment for me was making errors with the brackets, parantheses, and underscores used for the program. I overcame it by typing slower and looking over my code several times to see if I could spot where I was making an error. 



---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**
X - Square footage of a house
Y - The price of the house
This relationship might be linear because larger house typically cost more than smaller houses, meaning that the price of the houses would most likely increase if the square footage of the house increases as well.

---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
