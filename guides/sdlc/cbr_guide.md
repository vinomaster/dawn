Case-based Reasoning Analysis Title
=========================================================
[ *The intent of this system analysis workflow guide is to help streamline the activities associated with the evaluation of a functional aspect of a software system using a case-based reasoning process. The objective is to produce an assessment report based on an investigation into a specific functional aspect of a software system. The approach the analysis is to model performance on new problems using results from past experiences with similar problems.* ]

Problem Statement
-----------------------
[ *Provide an overview of the system and the problem.*]

### Target Problem
[ *Describe the problem that the system needs to solve and the expected result.* ]

### Problem Category
[ *Identify the category the system would associate with this type of problem.*]

### Unique Attributes
[ *What makes this problem unique from others like it in the problem category? Given the current state of the system,  what attributes of the problem are preventing an expecting result? events the system from solving the problem in its current the system would associate with this type of problem.*]
   
Environment Setup
----------------
[ *Your analysis may include several external source code libraries, data sets and it may produce several file artifacts. Organizing your workarea is imperative to achieve optimal reproducible results. Use this section to outline the preparation of your analysis environment.* ]

### Project Setup
[ *Outline your project workarea folder structure and provide a description of the purpose of all sub-folders. Provide the inline code necessary for setting up your working environment (i.e: working directory, system options, handling of warning messages, etc).* ]

### Obtain the data
[ *Provide the inline code necessary for accessing data that will provide prior case details associated with problems of this category.* ]

### Handle required files and libraries
[ *Provide the inline code necessary for loading any required libraries and other source files to be included. These are dependencies for your reproducible research code. As such, you should call out these dependencies textually as well as within the inline code.* ]
   
Reasoning Process
-------------------------

### Retrieve
[ *Provide the inline code necessary for accessing your cases relavent to the target problem. For each case, load the necessary details associated with a problem statement, the solution, and related comments/annotations.* ]

### Comments and Observations
[ *Provide commentary about decisions made for the retrieval process of historic cases.* ]

### Reuse
[ *Provide the inline code necessary for identifying and adapting prior case solutions that may be applicable to the target problem.* ]

### Comments and Observations
[ *Provide commentary about the solution mapping process and clearly describe the characteristics about related cases you have identified as applicable for testing. The artifact of this analysis phase should be a list of solution alternatives.* ]

### Revise
[ *Provide the inline code necessary for testing each solution alternative to the target problem.* ]

### Comments and Observations
[ *Describe the observations associated with each test result for all solution alternatives. Identify the solution attributes necessary to revise the system to solve the target problem.* ]

### Retain
[ *Provide the inline code necessary for updating your knowledge base of relavent cases with the necessary details for resolving this target problem, namely, problem statement, the solution, and related comments/annotations. Identify and execute any necessary system adjustments.* ]

Conclusion
-----------------------
[ *Summarize your results.* ]

### Problem Assessment
[ *Describe why this problem was so unique for the system and what the key solution attributes were that lead to the desired results.* ]

### System Benefits
[ *Describe the overall system improvements achieved by this analysis.* ]





