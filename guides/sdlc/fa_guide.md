Functional Analysis Title
=========================================================
[ *The intent of this system analysis workflow guide is to help streamline the activities associated with the evaluation of a functional aspect of a software system. The objective is to produce an assessment report based on an investigation into a specific functional aspect of a software system. The approach of the analysis is to model a problem and iterate through possible solution alternatives that will help achieve the functional goals of the system for the subject problem.* ]

Hypothesis
-----------------------
[ *Your software system is expected to produce results for a category of problems with some degree of accuracy. Describe the attributes of the current state of the system and how accurate it is with sample data. Describe your  prediction for what it will take to alter the system to gain some incremental percentage of improvement.* ]
   
Environment Setup
----------------
[ *Your analysis may include several external source code libraries, data sets and it may produce several file artifacts. Organizing your workarea is imperative to achieve optimal reproducible results. Use this section to outline the preparation of your analysis environment.* ]

### Project Setup
[ *Outline your project workarea folder structure and provide a description of the purpose of all sub-folders. Provide the inline code necessary for setting up your working environment (i.e: working directory, system options, handling of warning messages, etc).* ]

### Obtain the data
[ *Provide the inline code necessary for accessing your sample data.* ]

### Handle required files and libraries
[ *Provide the inline code necessary for loading any required libraries and other source files to be included. These are dependencies for your reproducible research code. As such, you should call out these dependencies textually as well as within the inline code.* ]
   
Analysis Process
-------------------------
[ *In order to test your hypothesis you may iterate through the analysis feedback loop process several times. This iterative process may include new information from external influencers (stakeholders) for this analysis. Use this section to describe who will be aiding in the effort, their role and how their input will be communicated and ingested into the analysis (new data sets, emails, other).* ]

### Stakeholders
[ *Who will be reviewing, observations and helping to make adjustments?* ]

### Communications
[ *How will adjustments be communicated?* ]

Current Baseline
-----------------------
[ *Provide the inline code necessary to model the current state of the system against the sample data.* ]

Feedback Loop
-----------------------
[ *This section is the heart of the  functional analysis. You will iterate through as many functional model necessary to validate your hypothesis. Each iteration should be documented as detailed as possible as an independent subsection.* ]

### Functional Assessment #1
[ *Describe the specifics about this functional modle of the system and how it differs from the baseline. Include the reasoning behing any adjustments being made to the system.* ]

#### Run Assessment
[ *Provide the inline code necessary to model this functional testcase of the system against the sample data.* ]

#### Assessment Observations
[ *Describe what you have observed. Make note of deltas in results as compared to baseline and other assessments that have been documented herein.* ]

#### Decision Point
[ *Are the results observed adequate to validate the hypothesis? If so, stop feedback loop. If not, describe the adjustments that need to be made for the next assessment and any details from conversations with stakeholders, then iterate through the loop again.* ]

Conclusion
-----------------------
[ *Summarize your results.* ]

### Hypothesis Assessment
[ *Revisit your hypothesis and describe the why/why-not your prediction was possible.* ]

### Accuracy of Prediction
[ *How confident  are you in the results of this functional analysis? Why are you confident?* ]

### System Benefits
[ *Describe the overall system improvements achieved by this analysis.* ]





