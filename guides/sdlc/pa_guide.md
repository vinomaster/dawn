Process Assessment Title
=========================================================
[ *The intent of this system analysis workflow guide is to help streamline the activities associated with tuning (improving) a specific software system process. The objective is to produce an assessment report based on an investigation into a specific performance of a process along with reproducible code for future analysis. The approach of the analysis is to identify characteristics of a process bottleneck and to measure possible adjustments to the process that will remove the bottleneck.* ]

Problem Statement
-----------------------
[ *Provide an overview of the system and the problem.*]

Process Overview
-----------------------
[ *Describe the system process to be analyzed.*]

### Desired Process Behavior
[ *Describe the desired or expected characteristics of a successful execution of the process.* ]

### Acceptable Process Metrics
[ *Describe the numeric values (metrics) associated with the desired process results.* ]

Assessment Environment 
----------------
[ *Your analysis may include several external source code libraries, data sets and it may produce several file artifacts. Organizing your workarea is imperative to achieve optimal reproducible results. Use this section to outline the preparation of your analysis environment.* ]

### Environment Setup
[ *Outline your project workarea folder structure and provide a description of the purpose of all sub-folders. Provide the inline code necessary for setting up your working environment (i.e: working directory, system options, handling of warning messages, etc).* ]

### Assessment Data
[ *Provide the inline code necessary for accessing data that will be used to tune your process.* ]

### External Experiment Dependencies
[ *Provide the inline code necessary for loading any required libraries and other source files to be included. These are dependencies for your reproducible research code. As such, you should call out these dependencies textually as well as within the inline code.* ]

Current Process Baseline
-----------------------

### Assumptions
[ *Describe any assumptions associated with the current state of the system and the process being analyzed.* ]

### Code
[ *Provide the inline code necessary to model and measure the current state of the system process.* ]

### Observations
[ *Describe the characteristics of the results of these measurements. This is your baseline for comparison with potential proces improvements.* ]

Bottleneck Identification
--------------------------------
[ *A process improvement exercise requires the identification and isolation of a specific aspect of the process, the focus area for process improvement. This is known as the process bottleneck. Describe the bottleneck and why it is being considered the focus of this process with respect to the problem being addressed.* ]

Experiments
--------------------------------
[ *Enumerate several experiments that can be run to alter the performance of the bottleneck and compare each result to the baseline and our Acceptable Process Metrics.* ]

### Process Assessment #1
[ *Describe the specifics about this experiment. What process attributes have been tweaked (altered) and how? What is the expected result of these modifications?* ]

#### Run Assessment
[ *Provide the inline code necessary to model and measure the modifications captured by this process experiment.* ]

#### Assessment Observations
[ *Describe what you have observed. Make note of deltas in results as compared to baseline, the desired results and other assessments that have been documented herein.* ]

Assessment Results
--------------------------------

### Findings
[ *Summarize your results.* ]

### Outcomes
[ *What are the pros/cons associated with the improvements you have identified.* ]

### Actionable Insights
[ *Identify system recommendations specific to the resolution of this process problem.* ]
    
### Lessons Learned
[ *Identify general system observations that may have been raised by this assessment.* ]    







