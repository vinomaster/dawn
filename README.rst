=======================
Data Analysis Workflow Navigation
=======================

:Author: Dan Gisolfi
:Description: A collection of of research templates for navigating the workflow activities for various types of data analysis projects. 
:Repo Name: *dawn*
:License: New BSD, See License file.

Motivation
============
The `analysis of data <http://en.wikipedia.org/wiki/Data_analysis>`_ is a process of inspecting, cleaning, transforming, and modeling data where the objective may be to discover useful information, suggest conclusions, and/or support decision making. Data analysis has multiple facts and approaches, encompassing diverse techniques under a variety of names, in different business, science, statistical and social science domains. 

Researchers in these domains tend to organize their work differently and produce dissimilar artifacts. Yet each domain researcher is challenged with a very basic and important metric, **time-to-value**:

* How much time is required to go from problem definition to action insights?
* How much time is required to develop and package reproducible research?
* How much time is required to synthesize research into a written artifact (report, proposal, etc)? 

Purpose
=========
Provide a collection of general purpose or domain specific workflow templates that will help navigate a data analysis project. These templates are meant to serve as guides for the project. The guides are provided based on experience to help others organize data analysis projects and the artifacts (insights, plots, code, etc) of the endeavor. 

The benefits of the guides are: 

* Analytical consistency 
* Research organization and navigation
* Reduced time-to-value

The guides included in *dawn* are language and platform neutral. The intent here is to focus on the workflow tasks and observations for a data analysis project. While a guide may be derived from an R markdown file, for example, the content of the guide should be reusable in a variety of interactive analytical tools such as `iClojure <http://www.iclojure.com>`_, `iPython <http://ipython.org>`_, and `iScala <https://github.com/KenCoder/scala-notebook>`_, and `RStudio <http://www.rstudio.com>`_. 

Guides
=========
The following workflow navigation templates are included:

* Reproducible Analysis Navigation Template (rant)
* Rapid Business Insights (rbi)

Each guide package contains:

* README.rst - A Restructured Text fiel describing purpose of the guide 
* <name>_guide.<ext> - The guide template file, where <name> is the name of the guide package and <ext> is the type of file (.txt, .md, etc) 

Additionally, guide packages may also incude:

* Sample use cases

License
==============
The use and distribution terms for this software are covered by the "New BSD" license which can be found in the file LICENSE at the root of this distribution. By using this software in any fashion, you are agreeing to be bound by the terms of this license. You must not remove this notice, or any other, from this software.

Getting Started
=============

Data Analyst
----------------
1. Clone the latest master branch from GitHub 
2. Open your favorite interactive analysis tool
3. Open the <guide_name>_guide.md file
4. Begin your data analysis activity

Guide Developer
---------------------
Contributors, if in agreeement with the License terms, are encouraged to fork the code and send GitHub pull requests.

Epilogue
=============
As a designated trail in the woods, these guides mark a path once taken. There is no harm in deviating from an existing guide or in the establishment of a new one. If a guide is only needed to get you started, then the guide has served it's purpose.

*"An investigator starts research in a new field with faith, a foggy idea, and a few wild experiments. Eventually the interplay of negative and positive results guides the work. By the time the research is completed, he or she knows how it should have been started and conducted."*  - `Donald Cram, American Chemist and 1987 Nobel Prize Winner <http://www.brainyquote.com/citation/quotes/quotes/d/donaldcram193831.html?ct=Donald+Cram>`_.


