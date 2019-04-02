## Lesson 2: Form-based onboarding and operations
##### [Back to Home](../index.md)

It can be tricky to maintain the source-of-truth for participants of a project larger than a dozen people. Well-considered forms can help achieve this; however, it can be useful to know what kind of form you need.

 - DRY principle: Don't Repeat Yourself
 versus
 - WET principle: Write Everything Twice
 
 Aim for as dry as possible

### Overview

- We will introduce REDCap but the hands-on training will be for Google forms (REDCap authorization varies by institution and REDCap-specific training is typically offered for free once authorized). Some of the basic information management techniques you will learn using Google forms / spreadsheets are transferrable to REDCap / excel.

#### Intro to Google forms
- Option to require sign in and allow only 1 response per person (that can be updated)
- Responses can be validated (eg. a URL, or a value between X and Y)
- Responses can be dumped dynamically to gSheet
- Easy-to-use design interface
- Concept-to-impelementation in minutes
- Negatives
  - Not all institutions allow use of Google forms
  - Compared to RedCap, offers much less rigorous versioning options, both of the form and its responses

#### See one
 - Watch this demonstrated action populate multiple different custom views:
     - [External views using Google's importrange function](https://docs.google.com/spreadsheets/d/1x6HaFDqDpE8CMTrEIehEsEGcme9OviMwXWzRWtFaMPI/edit#gid=0)
     - [Pivot tables](https://docs.google.com/spreadsheets/d/1x6HaFDqDpE8CMTrEIehEsEGcme9OviMwXWzRWtFaMPI/edit#gid=1163446730)
     - [Sparklines](https://docs.google.com/spreadsheets/d/1x6HaFDqDpE8CMTrEIehEsEGcme9OviMwXWzRWtFaMPI/edit#gid=1163446730)
  
#### Do one
- Create a simple google form
 - Configure to collect email addreses from respondents, dump responses to an existing spreadsheet of your choice
- Get your neighbor to fill out the survey (while you fill out theirs)
- Edit your form's questions
- Get your neighbor to update their response
- Creat a live feed of the responses to an external spreadsheet using the importrange function
- Try out pivot table functions

#### from [the redcap site](https://rc.partners.org/research-apps-and-services/collect-data)

ADVANTAGES OF REDCAP OVER MS EXCEL, ACCESS AND SOME OTHER ONLINE SURVEY TOOLS:
- Secure and web-based - Input data from anywhere in the world with secure web authentication, data logging, and Secure Sockets Layer (SSL) encryption.
- Hosted at Partners DIPR Datacenter - No need to worry about security issues regarding third party websites hosting your private data.
- Fast and flexible - Conception to production-level database timeline determined by study team.
- Multi-site access - Projects can be used by researchers from multiple sites and institutions.
- Fully customizable - You are in total control of shaping your database or survey.
- Advanced question features - Auto-validation, branching logic, piping, and stop actions.
- Mid-study modifications - You may modify the database or survey at any time during the course of your study.
- Data import functions - Data may be imported from external data sources to begin a study or to provide mid-study data uploads.
- Data comparison functions - Double data entry / Blinded data entry.
- Export results to common data analysis packages: Microsoft Excel, SAS, Stata, R, or SPSS for analysis.
- Save your survey or forms as PDFs - Generate a PDF version for printing in order to collect responses offline.

- Demonstration of onboarding using RedCap in action [here](https://redcap-dev.cgrb.oregonstate.edu/surveys/?s=9DAAEDK8M7)
- Try it at home; upload the sample data dictionary from [here](https://github.com/data2health/mtip-tutorial/blob/master/docs/data/ProjectOnboarding_DataDictionary_2018-09-15.csv) into your own instance.
  
### RedCap Training at OHSU
More information [here](https://www.ohsu.edu/xd/research/centers-institutes/octri/resources/octri-research-services/redcap-tutorials.cfm)

##### [Click here for Lesson 3](https://data2health.github.io/mtip-tutorial/lessons/Lesson3.html)
### [Back to Home](../index)
