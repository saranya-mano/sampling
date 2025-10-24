# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type: 
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used

# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#1`

Describe the purpose of your survey:
```
The purpose of the survey is to understand why there is high turnover rate, especially amongst entry- and lower-level employees, at a large tech company. The survey will explore different factors impacting employee satisfaction.  
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population is all employees at the company. The sampling frame is the list of employees with a valid email address in the different departments. This can be accessed through the HRIS. The sampling units are the different departments (strata). The observation units are employees within the different departments.  
```

Your 5-10 question survey:
```
1. Which of these factors are most important in you wanting to leave this company? (Select all that apply)
    a) Pay
    b) Benefits
    c) People Manager
    d) Hybrid working environment
    e) Culture
    f) Senior management
    g) Workload
    h) Work-life balance
    i) Promotion and development opportunities
2. Which of these factors are most important in keeping you at this company? (Select all that apply)
     a) Pay
    b) Benefits
    c) People Manager
    d) Hybrid working environment
    e) Culture
    f) Senior management
    g) Workload
    h) Work-life balance
    i) Promotion and development opportunities
3. How included do you feel?
    a) Fully
    b) 
    c) 
    d)
    e) Not at all
4. How much influence does your role exert?
    a) Very
    b)
    c)
    d)
    e) Not at all
5. How supported do you feel in accomplishing your tasks? 
    a) Very
    b)
    c)
    d)
    e) Not at all

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
Sample type: Multi-stage sampling. Stratified sampling was used in the first stage, where the strata are geographic areas within each of the 10 provinces. In the second stage, the sampling units of groups of telephone numbers representing each household were randomly selected without replacement in each stratum. 
2. Sample size: 16, 149 individuals 
3. Target population: Individuals 15 years and older in Canada from 10 provinces (excluding full-time residents of institutions)
4. Sampling frame: Individuals 15 years and over in Canada's 10 provinces identified through the redesigned GSS frame. This frame integrates data from sources of telephone numbers available to Statistics Canada and the Address Register that lists all dwellings in the 10 provinces. 
5. Survey mode(s): Households were randomly selected to receive a letter or a phone call, and then one member from the household would be invited to complete the online questionnaire or a telephone interview respectively.   
6. Timeline: September to December 2018
7. Response rate: 41.9% 
8. Weights: 
    1) Since some households are associated with multiple telephone numbers (sampling units) and the grouping of telephone numbers into a household could involve errors, some households had a higher probablity of being selected and this was accounted for with a household weight.
    2) The weights for responding households were adjusted to represent non-responding telephone numbers before being dropped.  
    3) Person weight was calculated by multiplying houhsehold weight by the number of household members 15 years or older. 
    4) Person weights were adjusted for rejective sampling (rejecting non-volunteers).
    5) Person weights were also adjusted for stratum (geographic areas), age-sex groups by province, and income distribution using raking ratio procedure. 
9. Data processing: All of the data was entered into a program that had valid codes, built-in edits and automatic questionnaire flow. For write-in responses, the responses were coded into existing categories, new categories or "other-specify". Some variables were created by collapsing categories or combining other variables. 
10. Cleaning, imputation, etc: In the first step, duplicate, non-response and out-of-scope records were removed. A few of the missing or incorrect information was imputed deterministically (for eg. mean) or with other information in the questionnaire. 
11. Sources of error: 
    1) Non-sampling error: Stemming from item or partial non-responses
    2) Non-sampling error: Stemming from interviewer errors
    3) Sampling error: Stemming from differences between the sample and the population
12. Limitations, known biases, etc:
    1) Since the 2018 survey uses the new GSS frame, it is not comparable to results from the previous surveys on the same topic. 
    2) There can be errors in combining telephone numbers with households. 
    3) Households with no telephone numbers are excluded from this survey.
    4) This survey does not include the territories. 
    5) Households that received the letter but lack access to internet or a computer maybe unable to complete the survey. 
13. Link to documentation and any additional sources used: https://www150.statcan.gc.ca/n1/pub/45-25-0001/cat5/c33_2018.zip 

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 19/10/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
