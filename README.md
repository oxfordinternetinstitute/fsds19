# Fundamentals of Social Data Science - 
## MSc in Social Data Science - Unviersity of Oxford, Michaelmas 2019 

This is the course repository for the introductory python course in Oxford's [Social Data Science program](https://www.oii.ox.ac.uk/study/msc-in-social-data-science/). 

This teaches some of the skills needed to begin working in soical data science. This focuses first on programming skills in python. It includes some key basic programming skills, such as lists and functions, as well as more abstract and complex topics like API access, file types, text processing and dataFrames. 

Data science is an emerging discipline concerned with the processing and management of data. Because data is now so prevalent, complex and volumous there is a niche for those with specific skills in data processing. Data science has four pillars: theory, data access, data wrangling and data analysis. 

This course only goes into very rudimentary detail on theory and analysis. Theory in our degree program is taught through the course "Foundations of Social Data Science". Analysis is partially taught with a focus on descriptives. Undoubtedly, a degree in data science is steeped in statistics. However, in this course statistics are used sparingly. Instead, they are taught in depth in two separate courses: _Statistics for Social Data Science_ and _Intro to Machine Learning_. 

### The repository 
This is the repository for 2018-2019 course, which consists of four main folders: 
- course work, 
- assignments,
- supplementary data (public),
- supplementeary data (withheld). 

The latter one is really just more data that should be in the supplementary data folder but for licensing reasons we will not be sharing that data in a public GitHub repository. In the case of the database of tweets, this is unavoidable as per the licensing agreement for use of the Twitter API is not to share tweets collected. 

## About this course. 
Some of the information about programming in the course is partial. It's not meant to be incorrect, but we are definitely omitting or papering over certain topics for brevity's sake. The goal here is to get people the skills and wisdom to put a study together for analysis and publication. In that sense, this course is a little more directed but also more concise than a repository such as Jake Vanderplas' [Python for Data Science](https://github.com/jakevdp/PythonDataScienceHandbook). Jake's repository, by contrast appears to be much closer to emphasizing completeness. For what it is worth, both this course and Jake's book benefit from prior knowledge of Python as found in the Whirlwind tour of Python, which can be found as a series of Python notebooks [over at GitHub](https://github.com/jakevdp/WhirlwindTourOfPython/). 

You will also notice various Muppet-themed examples throughout the course. This is because as a television show, Muppets offer an extensive amount of accessible data, from episode guides to wikipedia profiles on characters. This can help give is a flavor for high dimensional data while steer a little clear of some complex theoretical issues that are sure to arise in a more focused and sustained project.

### How to run these files 
The course is written almost entirely in Jupyter notebooks. We recommend downloading the [Anaconda package for scientific python](https://www.anaconda.com/download/), installing it and then launching the Anaconda Navigator. This navigator provides access to a host of scientific programming tools and particularly to JupyterLab. Run Jupyter lab and then navigate to a folder that includes the .ipynb files.  

### Running this course in a browser
Python notebooks can be run directly in the browser using Google Collab. To do this, simply get a url from a notebook page, such as github.com/oxfordinternetinstitute/sds-python/blob/master/Course_Material/Week_0/PySDS_week0_lecture1.ipynb Then, where it says github.com replace this with: https://colab.research.google.com/github so you would navigate to: https://colab.research.google.com/github/oxfordinternetinstitute/sds-python/blob/master/Course_Material/Week_0/PySDS_week0_lecture1.ipynb in order to run that page in the browser. That being said, we think simply cloning or downloading the notebooks and then running Jupyter Lab (from the Anaconda Navigator) is the most straightforward and reliable way to run the code. 

# Readings
## Core Texts
Russel, M & Klassen, M. 2019. Mining the Social Web, Third Edition. Sebastopol, CA: O’Reilly Press. [MtSW]

McKinney, W. 2017. Python for Data Analysis, Second Edition. Sebastopol, CA: O’Reilly Press. [PfDA] 

Matthes, E. 2016. Python Crash Course. San Francisco: No Starch Press. [PCC]

Note that the O'Reilly books can be read freely online at http://learning.oreilly.com/. You will need to go register with your Oxford email address. 

## Optional Reading
Bird, S., Klein, E., & Loper, E. Natural Language Processing with Python. Sebastopol, CA: O’Reilly Press. Python 3 version available online: https://www.nltk.org/book/ 

Knuth, D. 1997. The Art of Computer Programming, Third Edition. Vol. 1: Fundamental Algorithms. New York: Addison Wesley. See: https://www-cs-faculty.stanford.edu/~knuth/taocp.html 

Manning, C., Raghavan, P., and Schütze, H. 2009. An Introduction to Information Retrieval. Cambridge University Press. Avilable online: https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf 

Van Der Plas. 2016. Python Data Science Handbook. Sebastopol, CA: O’Reilly Press. 

## Useful code repositories and URLs

Data Science Handbook: https://jakevdp.github.io/PythonDataScienceHandbook/ 

Seaborn: https://seaborn.pydata.org 

Bokeh: https://github.com/bokeh/bokeh-notebooks 

Geopandas: http://geopandas.org 

BeautifulSoup: https://www.crummy.com/software/BeautifulSoup/bs4/doc/ 

NetworkX: https://networkx.github.io  

Markdown: https://daringfireball.net/projects/markdown/syntax  

# Course Outline 

## Week 0. Preliminary work 
Prior to the start of class we will be holding a refresher on the topics featured in the pre-course notebook, found in this repository. This is about very basic use of Python.

## Week 1. Introducing Python and Data Science
The first week ties some of the basic skills of Python programming to ways of thinking about the organization of data and the means to make claims from this data. We do not simply treat this as basic Python syntax but as ways of thinking how to categorize, order, and abstract from the world around us.

## Week 2. The DataFrame as Key Research Tool
The DataFrame is an indispensable part of data science research in Python. This week I introduce the Series and the DataFrame. I first show how to create, query, and modify these data structures. I then show how to get data into a DataFrame via various files formats. The third lecture is on how to merge and aggregate DataFrames. 

## Week 3. Data Cleaning and Exploration
This week we learn about ways in which to clean, reshape, and explore data. We will parse files, explore visualisation, and take data that is skewed and rescale it so that we can make more sense of it. 

## Week 4. Collecting Data from the Web 
Sometimes the web is a source of data for your research design. Sometimes it is simply the place where data is stored that you want to download. Approaches to collecting this data represent different relationships between the researcher and the data controller. Some approaches suggest a dialogue with the data controller, while others suggest a more observational approach. This week merely scratches the surface of what’s possible in either circumstance. 
