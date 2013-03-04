Title
=========================================================

Define the question
--------------------
[ *Provide some background information about the research problem under investigation* ]

### Objective
[ *What is the purpose of this research endeavor? What are some of the topics to be considered?* ]

### Data
[ *Use this section to capture specifics about the sample data being used for this research effort.* ]

#### Define the ideal data set
[ *Describe the ideal data corpus. Provide pertinent comments and references associated with the idea data set and what may be preventing access to it.* ]

#### Determine what data you can access
[ *Provide specific references to the sample data being used for this research effort. Be specific so that attempts to reproduce your work can be achieved. If appropriate and applicable, include references to documentation and/or code books for understanding the schema and variables in your data set.* ]

Getting Started
----------------

### Project Setup
[ *Your research will be comprised of several file artifacts. Organizing your workarea is imperative to reproducible research.* ]

[ *Outline your project workarea folder structure and provide a description of the purpose of all sub-folders.* ]

### Environment Setup
[ *Provide the inline code necessary for setting up your working environment (i.e: working directory, system options, handling of warning messages, etc).* ]

### Obtain the data
[ *Provide the inline code necessary for accessing your sample data.* ]

### Handle required files and libraries
[ *Provide the inline code necessary for loading any required libraries and other source files to be included. These are dependencies for your reproducible research code. As such, you should call out these dependencies textually as well as within the inline code.* ]

Tidy Data Check
----------------
[ *Provide commentary on the compliance of your sample data with respect to Tidy Data requirements: Variables in columns, Observations in rows, Tables holding elements of only one kind, Column names are easy to use and informative, Row names are easy to use and informative, Variable values are internally consistent, Handling of mistakes in the data need, Addition of transformed variables.* ]

### Remove noise
[ *Provide the inline code necessary for removing missing or dirty data.* ]

**Observation**: 
[ *Provide the reasoning behind the existence of the dirty data and any impact it may have to the research. Be sure to include specific details as to the size of the resulting corpus post cleansing as well as the indices of the removed observations.* ]

Extract, Transform and Load (ETL)
-----------------------------------
[ *Provide step-by-step details for any and all data munging tasks necessary for your research. You may return to this section several times during your iterative exploration. Typically, this phase of your research endeavor addresses the transformation of qualitative data into quantitative format for downstream exploration in the analysis pipeline.*]

### Transform 1: field1(string) to filed2(numeric)
[ *Provide the inline code necessary for this ETL task.* ]

**Action**: 
[ *Provide a description of the transformation and why it was necessary.* ]

### Transform 2: field3(string) to filed4(numeric)
[ *Provide the inline code necessary for this ETL task.* ]

**Action**: 
[ *Provide a description of the transformation and why it was necessary.* ]

Exploratory Data Analysis
----------------------------
[ *Use this section to document your iterative exploration tasks. You should include inline code , observations and follow-on actions for each exploratory question. You may also want to capture follow-on questions that may arise from your observations. Keeping track of follow-on questions, will help your research endeavor to be as exhaustive as possible.* ]

[ *Find relationships you didn't know about. Exploratory models are good for discovering new connections. They are also useful for defining future studies. Exploratory analyses are usually not the final say. Exploratory analyses alone should not be used for generalizing/predicting.* ]

### Question 1
[ *Question text* ]

[ *Provide the inline code necessary for this question. This code should include analytic task as well as code necessary for plot generation.* ]

**Observation**: 
[ *Describe any findings and insights drawn from any plots.* ]

**Action**: 
[ *Based on current observations, what do you want to do next and why? Are there follow-on questions that you want to capture and address later?* ]

### Question 2
[ *Question text* ]

[ *Provide the inline code necessary for this question. This code should include analytic task as well as code necessary for plot generation.* ]

**Observation**: 
[ *Describe any findings and insights drawn from any plots.* ]

**Action**: 
[ *Based on current observations, what do you want to do next and why? Are there follow-on questions that you want to capture and address later?* ]

Inferential Analysis
----------------------------
[ *Use a relatively small sample of data to say something about a bigger population. Inference is commonly the goal of statistical models. Inference involves estimating both the quantity you care about and your uncertainty about your estimate. Inference depends heavily on both the population and the sampling scheme.* ]

[ *Provide the inline code necessary for implementing the statistical models that you will use for your interential analysis.* ]

**Observation**: 
[ *Describe any findings and insights drawn from your statistical modeling.* ]

**Action**: 
[ *Based on current observations, what do you want to do next and why? Are there follow-on questions that you want to capture and address later?* ]

Predictive Analysis
---------------------------------
[ *Can your data be used on some objects to predict values for another object?
Be careful, prediction if A can predict B, that does not mean A causes B. An accurate prediction depends heavily on measuring the right variables. Although there are better and worse prediction models, more data and a simple model works
really well.* ]

[ *Are there any standard statistical modeling processes that you would like to explore? If so, you will need to capture references for how and when such models should be applied as well as any assumptions you are making.* ]

### Find the right data

### Define your error rate

### Prepare your prediction environment
[ *Split data into: Training, Test (optional), Validation* ]

### Using Training Set
[ *Provide the inline code necessary for implementing the statistical prediction model.* ]

**Observation**: 
[ *Describe any findings and insights drawn from your statistical modeling.* ]

**Action**: 
[ *Based on current observations, what do you want to do next and why? Are there follow-on questions that you want to capture and address later?* ]

### Using Test Set (optional)
[ *Provide the inline code necessary for iteratively implementing and refining prediction model used on training set against the test set. The benefit here is that we can estimate the validation set accuracy with the test set. The approach is to Use the training set, split it into training/test sets, build a model on the training set, evaluate on the test set, repeat and average the estimated errors.* ]

**Observation**: 
[ *Describe any findings and insights drawn from your statistical modeling.* ]

**Action**: 
[ *Based on current observations, what do you want to do next and why? Are there follow-on questions that you want to capture and address later?* ]

### Using Validation Set
[ *Provide the inline code necessary for implementing the statistical model used on training set against, apply it just once to the validation set.* ]

**Observation**: 
[ *Describe any findings and insights drawn from your statistical modeling.* ]

**Action**: 
[ *Based on current observations, what do you want to do next and why? Are there follow-on questions that you want to capture and address later?* ]

Interpret results
------------------
[ *What conclusions can you make? Are they based on inference or estimates or predictions? You should use this area to synthesize your research effort into very crisp bullets and/or short paragraphs that tell a story as well as provide concreate data points (insights) based on your research.* ]

Challenge results
--------------------
[ *What are the limitations of your findings? What assumptions did you make? How could your findings be improved? Are there follow-up research opportunities that derive from your work?* ]

References
-------------
[ *Use this section to capture and itemize a list of references obtained during your research effort.* ]

Finalize Report
-----------------
[ *Your reproducible research effort will most likely be accompanied by a written report. Use this section to organize your thoughts based on your work so far and establish an outline for your write-up. General topics that should be considered are: Research Methods (Data Collection, Exploratory Analysis, Statistical Modeling, Reproducibility), Results, Conclusions, References.*]


