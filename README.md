# Help_with_Fee_Remission_Model_RAP

## Acknowledgement

The concept of a Reproducible Analytical Pipeline (RAP) was 
created by Matthew Upson and Matthew Gregory at the Government Digital Service. 

https://dataingovernment.blog.gov.uk/2017/03/27/reproducible-analytical-pipeline/

https://ukgovdatascience.github.io/rap_companion/

https://ukgovdatascience.github.io/rap_companion/why.html#why-learning-to-rap-might-be-hard

https://www.isdscotland.org/About-ISD/Methodologies/_docs/Reproducible_Analytical_Pipelines_paper_v1.4.pdf

https://ukgovdatascience.github.io/rap_companion/exemplar.html#tidy-data

https://software-carpentry.org/lessons/



## Determine whether work is reproducible, some key questions1 to ask are:
· Is it clear where to begin?
· Can you determine which inputs produced which outputs?
· Which is the most recent copy of the code?
· What files can I safely delete, and should I delete files at all?
· Are scripts and reports version controlled?
· Are there lots of manual steps in the process?
· Are proprietary software used in the process?

## A Reproducible Analytical Pipeline should be:

# 1. Reproducible
This is achieved through the use of open source software, R Projects, package 
management and ideally computing environment management.
# 2. High quality
This is achieved by removing manual steps in the production process which increase the 
risk of errors and incorporating data QA and unit testing of R functions into the pipeline.
# 3. Auditable
This is achieved through the use of version control and documentation of R functions and 
code.
# 4. Sustainable
This is achieved through training and up skilling of staff – “sustainability is social, not 
technical” (Matthew Upson, 2018) and requires everyone in a team to know how to use and 
update the pipeline.




## ######################################################### ##
## Identifying RAP battles in the organisation:

# Does your team spend too much time moving data between various softwares?

# Could you reproduce your most recent publication’s stats? How about from five years ago?

# What would your team do with their time if it was freed up from copying and pasting?

# Do you know of any periodic reports like this in your organisation?
 
# Now rank them from simple to complex.


# Are there any quick wins here? (revisit this list at the end of the course)

# How consistent is the input data format? (does it change often?)

# How consistent is the output report format? (does it change often?)

# Can you code in the open? Are the analytical methods used in the report sensitive?

# What proportion of spreadsheets contain errors?


## ######################################### ##

## Bussiness Benefits:

# How many statistical reports are you involved in the production of each year (or quarter; whatever time period makes most sense to you and your organisation)?

# What proportion of your time do you spend working on these productions?
Multiply the proportion of your time spent on producing these reports by your salary. Is your organisation getting good value for money? What about if you consider all the other staff working on this report?

## ######################################### ##

## Finding a buddy to collaborate with

# Buddy up and work on a project together, facilitating peer review and sharing the workload to build a working package more quickly together.

# Who in your organisation would be interested with collaborating with you on your RAP battle. Who has the time and enthusiasm? Is there anyone who already knows how to RAP who could peer review your code and pull requests?


## ######################################### ##

## Pick the RAP battle wisely

## DIY principle:
# Do not repeat yourself
instead of copy-pasting piece of code, RAPing the R package 

Periodic, customer need is likely to stay constant, business critical, time consuming but straight forward, consistent output format, we can publish it all except our internal data which we can hold locally, customers might like to check our analysis thus improving our transparency objectives

# Drawing data from many disparete sources

As it is NOT a one off report you might not benefit from the time investment of upskilling. 
You are NOT likely time pressured so we do NOT suggest carrying on with this using your traditional methods.

## Establishing the minimal tidy dataset

Read this paper by Hadley Wickham on tidy data.

A Garrett Gromulund tutorial provides characteristics of countries through time data.

Work through the Digital, Culture, Media and Sport (DCMS) example in the RAP companion.

We include an extension case study example here. The walkthrough to the thought processes for this case study on a report on the special educational needs of students in England is also included as a downloadable resource.


@Article{tidy-data,
  author = {Hadley Wickham},
  issue = {10},
  journal = {The Journal of Statistical Software},
  selected = {TRUE},
  title = {Tidy data},
  url = {http://www.jstatsoft.org/v59/i10/},
  volume = {59},
  year = {2014},
  bdsk-url-1 = {http://www.jstatsoft.org/v59/i10/},
}

## ######################################### ##
