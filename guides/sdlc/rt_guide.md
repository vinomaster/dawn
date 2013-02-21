Regression Test  / Process Monitor Title
=========================================================
[ *The intent of this system analysis workflow guide is to provide a reusable utility for monitoring and regression testing a specific system process.
The objective is to produce reproducible process monitoring code and documentation of the regression analysis.* ]

Process Details
----------------------
[ *Describe the system process to be monitored. What are the key characteristics about this process that need to be monitored? What are the major regression concerns?* ]

Experiment Goal
----------------------
[ *Describe the objective of this test (experiment) against the system? What is the expected or desired result for the system process once this experiment is executed?* ]

Experiment Environment 
----------------
[ *Your analysis may include several external source code libraries, data sets and it may produce several file artifacts. Organizing your workarea is imperative to achieve optimal reproducible results. Use this section to outline the preparation of your analysis environment.* ]

### Setup
[ *Outline your project workarea folder structure and provide a description of the purpose of all sub-folders. Provide the inline code necessary for setting up your working environment (i.e: working directory, system options, handling of warning messages, etc).* ]

### Obtain the data
[ *Provide the inline code necessary for accessing your experimental data.* ]

### External Experiment Dependencies
[ *Provide the inline code necessary for loading any required libraries and other source files to be included. These are dependencies for your reproducible research code. As such, you should call out these dependencies textually as well as within the inline code.* ]

Statistical Model 
----------------
[ *Are there any standard statistical modeling processes that you would like to explore in this experiment? What is the statistical basis for the experiment? What standards will you use to interpret your results? You will need to capture references for how and when such models should be applied as well as any assumptions you are making.* ]

[ *Provide the inline code necessary for implementing the statistical model that you will use.* ]

Statistical Results 
----------------

### Assumptions
[ *Are there any assumptions that need to be called out relative to this experiment and the analysis being performed?* ]

### Code
[ *Provide the inline code necessary for applying the statistical model against the specifics of this experiment.* ]

### Observations
[ *Describe the statistical results.* ]

Interpret Results 
----------------
[ *Are the statistical results inline with our desired result? If not how do they vary and why? Do we consider these results negative and as such a regression in the system process? What adjustments need to be made to they system as a result of this analysis?* ]

System Feedback Process
----------------------------
[ *Describe how these results and any suggested adjustments will be injected back into the system for re-assessment.* ]

