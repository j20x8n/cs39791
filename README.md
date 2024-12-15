java c
STAT 385 
Project Policy 
Deadline 
Final projects will be due on Thursday, December 19 at 11:59 PM, Champaign time.
Submission 
Submit a single .zip file named your-app-name.zip where your-app-name is whatever you name your app. This .zip file should contain an RStudio Project in a folder named your-app-name . This folder should contain the following, which will be described in this document:
your-app-name.Rproj - a required RStudio project file.
app.R - a required file that defines the Shiny application.
about.Rmd - a required file containing information describing the application.
R/ - a required directory that contains .R files that contain additional functions.
data/ - an (optional) directory that contains .csv or other files necessary to import data.
Submit your project to the relevant assignment on Canvas.
Data
For this project, you can use (almost) any data!
The following are some potential data sources:
Tidy Tuesday - Datasets curated by the R community for weekly wrangling, visualization, and analysis practice.
wadefagenʼs Useful Datasets - A number of “useful” datasets, especially related to UIUC.
You may not use the gpa dataset as it is used in tutorials for Shiny in STAT 385.
Illinois Shield Testing Data - Data on Illinoisʼ COVID testing. Data is available through a link to Box at the bottom of the page.
This data may no longer be used as it has been used in many previous projects from past semesters.
Open-Meteo - Freely available weather data.
OPEN Powerlifting - Data on results from powerlifting meets. CSV files can be obtained on the Data page. As the data is extremely large, consider pre-processing.
nflfastR - A package to efficiently scrape NFL play-by-play data. See related packages as well.
ffverse - A collection of fantasy football R packages.
baseballr - A package for scraping various baseball data from websites such as FanGraphs.com, Baseball-Reference.com, and baseballsavant.com.
538 Data - Data used in 538 articles.
Kaggle Datasets - Data from the ML practice platform. Kaggle. Be aware of the licences of the various dataset. (And try to consider data that can most readily be legally shared.)
sportsdataverse - Collect of packages for obtaining sports data in R.
cfbfastR - An R package for working with CFB data
CDC Data - Catalog of CDC data, which currently is heavily populated with COVID data.
We recommend that you attempt to find a dataset ASAP and verify that you can load it into R and perform. basic data manipulations.
Requirements
In short, you must create a Shiny application with at minimum three inputs and two outputs. The files and how to submit them are described above. The grading details below indicate additional details about the application and the necessary files.
Shiny App Tutorial
The following documents will describe background needed to understand the video walk-through of developing an MLB Spin Rate Application. The background for this lab was given as part of a lab in the Fall 2021 semester.
Fall 2021 Lab 10 Assignment
Fall 2021 Lab 10 Solution
YouTube: Fall 2021 Lab 10 Video Walk-Through /// ClassTranscribe Mirror
Yes, this is a lot of background information, but it will be very useful for understand the video about the application development.
The following video will detail the development of an application with the data described above. It will代 写STAT 385 - Project PolicyR
代做程序编程语言 start from describing the idea for the application, and illustrate the entire development process:
YouTube: Shiny App Tutorial: Spin Rate App /// ClassTranscribe Mirror
Final Project Tutorial
The following video will demonstrate developing an application from scratch, that meets all of the specifications of the final project. The video begins by sketching an idea for an application, and ends with grading the finished project against the rubric found below.
YouTube: GPA Shiny Application /// ClassTranscribe Mirror
Grading
Your project will be graded based on the following criteria. As each criteria is very specific, partial credit will only be used in very rare situations. (Assume no partial credit is possible.) Note that we are not grading on quality or creativity of analysis, only functionality and correctness of the application. (However, you should still work towards these things!) The total points available for the project is the sum of the points listed.
[4] After unzipping submission, all required files exist.
[5] After opening app.R , the applications runs without error using the “Run App” feature inside RStudio.
[1] Data used by the application should either be loaded directly from the web, or stored in the data/ directory and loaded accordingly. (We strongly recommend the latter so that your application will not break if a link becomes broken later.)
[1] The UI is well organized. Hint: leverage sidebarLayout() , fluidRow() , or other UI layout features documented on the R Shiny cheat sheet.
[1] The UI contains a navigation bar with at least two tabs.
[3] The application contains three input elements.
[1] Of the minimum three input elements, two must be unique.
[1] Of the minimum three input elements, the choices of one of the inputs must be conditionally dependent on another input.
[2] The application contains at least two output elements, one graphical and one tabular.
[1] The graphical output element is created using ggplot2 .
[1] The graphical output element reacts to at least one of the input elements.
[1] The application uses at least one reactive element that is user defined using reactive() .
[1] The application performs some data manipulation using dplyr .
[1] The tabular output element reacts to at least one of the input elements.
[1] The R/ directory should contain at least one .R file which contains at least one function.
[1] The function described above is used in the application.
[1] One of the tabs in the navigation bar links to the rendered output from about.Rmd .
[1] The about page has four sections: Author, Purpose, Data, and References.
[1] The author section of the about page should contain the name and email of the author, as a bulleted list.
[1] The purpose section of the about page should contain a very brief (think one paragraph) description of what the application is meant to do and what it could be used for.
[1] The data section of the about page should describe the source of the data. It should also describe the data in enough detail such that a user of the application understands the data enough to use the application.
[1] The references section of the about page should contain a list of references used, which at minimum includes the source of the data.
[3] When using the application, no errors or crashes occur.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
