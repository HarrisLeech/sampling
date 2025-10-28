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

1. Sample type
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

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
write your answer here...

This survey aims to find out the drivers for high turnover, focusing on entry- and lower-level roles by measuring employee satisfaction, the intention to stay or leave the company, and existing gaps in pay, workload, management, growth, and culture. Findings will inform corporate HR and management of actions to improve retention and work experience in the company in general

```

Describe your target population, sampling frame, sampling units, and observational units:
```
write your answer here...
> Target Population: All entry- and lower-level roles at the company and recent leavers of the company
> Sampling Frame: Current entry and lower-level employees registered under HRIS e.g. Workday and voluntary leavers who leave the company in the last 6   
 months
> Sampling Units: Individual employees and recent leavers
> Sampling strategy: Stratified sampling by department, role level as in entry or lower level, work mode (onsite/hybrid/remote), and employment status (current vs. recent leaver).

```

Your 5-10 question survey:
```
1. write your question here...
> On a scale from 1 to 10, how satisfied you are with the company?
2. write your question here...
> How likely you would stay in the company in the upcoming year? (from 1 to 10)
3. write your question here...
> On a scale from 1 to 10, how manageable your workload and stress at work is?
4. write your question here...
> On a scale from 1 to 10, how much do you agree that “I can see a realistic path for advancement or skill growth at the company"
5. write your question here...
> On a scale from 1 to 10, how much do you agree that “My total compensation is competitive for my role and market”.
6. write your question here... (optional)
7. write your question here... (optional)
8. write your question here... (optional)
9. write your question here... (optional)
10. write your question here... (optional)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
write your answer here

1. Sample type: > Cross-sectional, probability sample; stratified by province/CMA, with a two-stage design and rejective sub-sampling for non-volunteers (long/short forms)
2. Sample size: > around 50,000 units, about 40,000 invitation letters to the electronic questionnaire were sent to selected households across Canada. A completion of 24,000 questionnaires was expected.
3. Target population: > All persons 15 years of age and older living in the ten provinces of Canada. It excludes full-time (residing for more than six months) residents of institutions.
4. Sampling frame: > Combined frame linking landline + cellular numbers (from Census/admin sources) to Statistics Canada’s dwelling frame (telephone numbers grouped by address)
5. Survey mode(s) : > Electronic questionnaire (web) and CATI (telephone); English/French; average interview ~44 minutes
6. Timeline: Collection: > September 4–December 28, 2018. Data release for PUMF: January 26, 2021
7. Response rate: > Overall 41.9%
8. Weights: > Person weight WGHT_PER for estimation; bootstrap weights for variance. Weights include adjustments for rejective sub-sampling and calibration
9. Data processing: > Generalized processing (SSPE); automated + manual flow/consistency/family edits; CATI range/flow checks; head-office review.
10. Cleaning, imputation, etc: 
> Primarily donor imputation (score-based nearest donor), with mean imputation as fallback; nine imputation steps (income first, then formal/informal  volunteering, then donations/solicitations). Income obtained via tax linkage when permitted (personal income from 2017 T1FF for ~82% of respondents; remaining imputed)

11. Sources of error: Sampling error (addressed with bootstrap weights).
> Coverage error (households without telephone service excluded; under/over-coverage possible).
 Nonresponse error (household and person-level; mitigated via weighting adjustments and use of admin characteristics to model nonresponse).
 Response/processing errors (mitigated via questionnaire testing, CATI edits, SSPE)

12. Limitations, known biases, etc
>Territorial residents and institutional populations are out of scope.
 Telephone-based frame may under-cover phoneless households (bias reduced but not eliminated).
 Rejective sub-sampling and long/short forms require correct weighting for unbiased estimates.
 Content and methodological changes vs. prior cycles affect strict comparability of trend estimates.

13. Link to documentation and any additional sources used
>The General Social Survey: An Overview
 Last review : January 7, 2021
 Format: The General Social Survey: An Overview - https://www150.statcan.gc.ca/n1/en/catalogue/89F0115X
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
