# Data-Analysis-of-bug-review-report-to-minimize-missing-bugs-during-code-review
Course Project for Mining Software Repositories

Language: R

Tool: RStudio

Date: 01-12-17

Dataset: Find the file named dataset.csv

We take the following predictive variables into consideration: 1) lines 2) chunks 3) file_count 4) r_queue 5) r_exp 6) r_exp_product 7) s_exp 8) s_exp_product

We predict the following variables: 1) review_time_minutes (how much time does reviewer take to review the code) 2) is_bad (whether his review is good or bad)

We analyze the effect of all the predictor variables on each of the two predicted variables separately. Purpose is to identify the most important predictor Variables for each of the predicted variables.

Concludion: Technical (patch size, number of chunks, and module) as well as personal factors (reviewer’s
experience and review queue) strongly contribute to the review quality. We	identified the following most important predictor variables that contribute to bad code review: 1) lines of code, and 2) number of pending code reviews for the reviewer

