Title
=========================================================
[ *The intent of this data analysis workflow guide is to help streamline the activities associated with a situational investigation project. It attempts to  consolidate details from process steps such as data extraction, transformation, analysis and the generation of interactive visualizations. The ultimate objective is the creation of a business proposal based on actionable insights.* ]

Business Environment
-------------------------------

### Business Situational
[ *Describe the attributes of the current state of the business. Keep the business state relative to the scope of the problem (departmental, organizational, customer, etc)* ]

### Problem Statement
[ *Provide some background information about the situational problem to be  investigated. Try to consolidate problem(s) down to a few (no more than 3) crisp problem statements.* ]

### Solution Sponsor
[ *Someone needs to be the catcher of the proposal and responsible for executing on the business decision. Without such a stakeholder, the investigation results are meaningless as they will die on the investigators desk. Identify the person responsible for taking action and document whether they have committed to support the effort. You must establish buy-in!* ]

### Objective
[ *What is the purpose of this situational information problem?*  ]

### Risk Assessment 
[ *What is at risk if this problem is not addressed in a timely manner? What are the business impacts?* ]

### Assumptions
[ *What assumptions needs to be identified about the business environment, the problem domain and/or proposed solutions?* ]

### Solution Constraints
[ *What constraints does the business impose on any proposed solution? Is there a time constraint for a solution? If so, how does that constraint impact solution value?* ]

### Other Decision Influencers
[ *Business decisions must take into account more than raw data. We must recognize that data sometimes obscures business values. Data is rarely in a raw form, it is always structured according to somebody’s predispositions and values. Choices are made along the way that influence the data from construction to interpretation. Yet there are always things to consider as influencers that are not derived from the data, such as business values. Use this section to account for any external influencers that may trump or alter insights found in the data and may thereby impact a proposed decision.* ]

### Estimates or Predictions
[ *If there are any predetermined conclusions that may drive the nature of this investigation, please identify them upfront.* ]

Situational Information
-------------------------------
[ *Describe the situational attributes of the data corpus. Howe large is t? How broad in scope (internal, external, unstructured, structured)? Is it a mix of static and real-time information where the spectrum of real-time frequency varies (infrequent to mili-sec)?* ]

### Data
[ *Use this section to capture specifics about the sample data being used for this investigation.* ]

#### Define the ideal data set
[ *Describe the ideal data corpus. Provide pertinent comments and references associated with the idea data set and what may be preventing access to it. How will a lack of access to the idea information impact a solution proposal?* ]

#### Determine what data you can access
[ *Provide specific references to the sample data being used for this investigation. Be specific so that attempts to reproduce your work can be achieved. If appropriate and applicable, include references to documentation and/or code books for understanding the schema and variables in your data sets.* ]

Getting Started
----------------

### Project Setup
[ *Your situational investigation will be comprised of several file artifacts. Organizing your workarea is imperative for reproducible research.* ]

[ *Outline your project workarea folder structure and provide a description of the purpose of all sub-folders.* ]

### Environment Setup
[ *Provide the inline code necessary for setting up your working environment (i.e: working directory, system options, handling of warning messages, etc).* ]

### Obtain the data
[ *Provide the inline code necessary for accessing your sample data.* ]

### Handle required files and libraries
[ *Provide the inline code necessary for loading any required libraries and other source files to be included. These are dependencies for your reproducible research code. As such, you should call out these dependencies textually as well as within the inline code.* ]

### Reproducibility
[ *Describe how this investigation effort will be packaged for reproducibility. For business audit reasons and historical understanding, any decisions based on the analysis herein should be reproducible.* ]

Tidy Data Check
----------------
[ *Provide commentary on the compliance of your sample data with respect to Tidy Data requirements: Variables in columns, Observations in rows, Tables holding elements of only one kind, Column names are easy to use and informative, Row names are easy to use and informative, Variable values are internally consistent, Handling of mistakes in the data need, Addition of transformed variables.* ]

### Remove noise
[ *Provide the inline code necessary for removing missing or dirty data.* ]

**Observation**: 
[ *Provide the reasoning behind the existence of the dirty data and any impact it may have to the research. Be sure to include specific details as to the size of the resulting corpus post cleansing as well as the indices of the removed observations.* ]

Extract, Transform and Load (ETL)
-----------------------------------
[ *Provide step-by-step details for any and all data munging tasks necessary for your research. You may return to this section several times during your iterative exploration. Typically, this phase of your investigation will address the transformation of qualitative data into quantitative format for downstream exploration in the analysis pipeline.*]

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

[ *Remember, situational problems typically share the characteristic that stakeholders "do not know what they do not know!" In other words, the questions that need to be asked may not be known upfront. The iterative exploration process may yield a list of more questions before it yields any insightful golden nuggets.  As such, followup questions should be captured as they are part of the iterative process.* ]

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

Statistical prediction/modeling
---------------------------------
[ *Are there any standard statistical modeling processes that you would like to explore? If so, you will need to capture references for how and when such models should be applied as well as any assumptions you are making.* ]

[ *Provide the inline code necessary for process modeling that you undertake.* ]

**Observation**: 
[ *Describe any findings and insights drawn from your statistical modeling.* ]

**Action**: 
[ *Based on current observations, what do you want to do next and why? Are there follow-on questions that you want to capture and address later?* ]

Interpret results
------------------
[ *What conclusions can you make? Are they based on inference or estimates or predictions? You should use this area to synthesize your research effort into very crisp bullets and/or short paragraphs that tell a story as well as provide concreate data points (insights) based on your research. Can we make any inference as to the cause of the problem? How confident are we about such an inference and what statistical information do we have to justify that confidence?* ]

Challenge results
--------------------
[ *What are the limitations of your findings? What assumptions did you make? How could your findings be improved? Are there follow-up research opportunities that derive from your work?* ]

References
-------------
[ *Use this section to capture and itemize a list of references obtained during your research effort. This should include internal as well as external resources that contribute to the research.* ]

Solution Options
------------------
[ *Use this section to enumerate as many solution options as necessary.* ]

### Alternative 1

#### Name: 
[ *Give this solution alternative an name so that it can be properly during decision process.* ]

#### Description
[ *Provide a concise description of this solution option.* ]

#### Correlation of Results
[ *Link this solution option top the findings of the investigation.* ]

#### Benefits
[ *What are the business benefits associated with this solution option (such as ROI).* ]

#### Actions
[ *What are the required actions that need to be taken along with time constraints for each in order to execute on this solution option.* ]

#### Issues/Concerns
[ *Are there any issues or concerns that need to be raised about this solution option.* ]

#### Dependencies
[ *Are there any dependencies associated with this solution option.* ]

Proposed Decision
------------------
#### Problem
[ *What is the problem this proposal is addressing?* ]

#### Solution Description
[ *Provide a concise description of the proposed solution.* ]

#### Business Justification
[ *Provide the reasoning behind why this solution option was chosen.* ]

#### Benefits
[ *What are the business benefits associated with the proposal (such as ROI).* ]

#### Actions
[ *What are the required actions that need to be taken along with time constraints for each in order to execute on the proposal.* ]

#### Issues/Concerns
[ *Are there any issues or concerns that need to be raised about the proposal.* ]

#### Dependencies
[ *Are there any dependencies associated with the proposal.* ]









