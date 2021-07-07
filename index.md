## Welcome to Data Science!

This is the course website for Professor Hartigan's sections of LLO 8200 Introduction to Data Science. Make sure you bookmark and check this page frequently for the most up-to-date files to use for both async and assignments. Over the course of the term code may be optimized or corrected, so please alert me if you’re going to be working ahead. (_If you do work ahead, you will be responsible for updating your work if the assignments are updated._) You should have R, RStudio, and Tidyverse installed prior to the first day of class. Instructions for installing R and Rstudio can be found [here](./Installing R and RStudio.pdf). Instructions for updating R and Rstudio can be found [here](./Updating R and RStudio.pdf).

While there are files on the "Files" section of the LMS, you should use the files from THIS page to ensure you have the most up to date information. Additionally, please reference this syllabus for information. You are responsible for reviewing and ensuring you are following the schedule included in this syllabus, found here: [Hartigan's Summer 2021 LLO8200 Syllabus](./Hartigan_LLO8200_syllabus_summer2021.pdf). 

If you want to set up email alerts for updates/additions to this site, you can use the free version of a third-party program: [Distill](https://distill.io/). The free version will check for updates every 6 hours and send you alerts. Note: this is a platform that is not owned by Vanderbilt or me and you should review their data privacy and security to ensure you are comfortable with their practices.

### Async/Sync RStudio (.Rmd) Files
These are the RStudio files and datasets that you will use in tandem with the async videos each week, listed by class week and LMS Module number. The first file below (Week 0) is a general setup file that provides a good structure for setting up your .Rmd files.
0. LMS Mod 0 - [.Rmd File Setup](./00_setup.Rmd)
1. LMS Mod 1 - [Introduction Rmd File](./01_Intro.Rmd) 
2. LMS Mod 2 - [Conditional Means Rmd File](./02_Conditional Means.Rmd) 
  * Async Video Locations (listed by section #):
    * Lecture 2.1 - view on LMS
    * [Lectures 2.2 through 2.5 video](https://www.youtube.com/watch?v=NQtvxw9CNCU)
    * Lectures 2.7 and 2.8 - view on LMS
    * [Lectures 2.6 and 2.9 video](https://www.youtube.com/watch?v=K3f-5fb-lL0)
3. LMS Mod 3 - [Descriptive Plots](./03_DescriptivePlots.Rmd) 
4. LMS Mod 4 - [Flat data](./04_flatdata.Rmd)
5. LMS Mod 5 (part 1) - [Regression, part 1 - updated](./05_regression_updated.Rmd)
  * Async Video Locations (listed by section #):
    * Lecture 5.1 - view on LMS
    * [Lecture 5.2 video](https://youtu.be/8P5CLj5Vy70)
    * [Lectures 5.3 & 5.4 video](https://youtu.be/6s5__DICHDg)
6. LMS Mod 5 (part 2) - [Regression, part 2 - updated](./05_regression_part2.Rmd), [html lecture notes](https://raw.githack.com/wdoyle42/ll0_8200_summer_21/main/05-regression-2.html)
  * Async Video Locations (listed by section #):
    * [Lecture 5.4a video](https://www.youtube.com/watch?v=llfHYO_MujY)
    * [Lecture 5.4b video](https://www.youtube.com/watch?v=hm33VbjQZMY)
    * Lecture 5.5 - view on LMS
7. LMS Mod 6 - [Scatterplots](./06_scatterplots.Rmd)
8. LMS Mod 7 - [Getting Data: Web Sources](./07_webscraping_updated.Rmd)
  * Async Video Locations (listed by section #):
    * Lectures 7.1-7.3 - view on LMS
    * [Lecture 7.4 video](https://www.youtube.com/watch?v=NHbs55PTb-g)
    * Lecture 7.5 - view on LMS
9. LMS Mod 8 (part 1) - [Analyzing Data: Classification](./08_classification.Rmd) -- Note, we are stretching this out over two weeks! 
  * Async Video Locations (listed by section #):
    * Lecture 8.1 - view on LMS
    * [Lecture 8.2 video](https://www.youtube.com/watch?v=IIEvyvsVO7Q)
    * Lecture 8.4 - view on LMS
    * [Lecture 8.5 video](https://www.youtube.com/watch?v=KbmEJkslBeE)
10. LMS Mod 8 (part 2) - [Analyzing Data: Classification](./08_classification.Rmd)
    * Video forthcoming

### Datasets (for async & sync sessions - we may not use all of these)
* [Area dataset - ACS 2019](./area_data.Rds)
* [Attrition dataset](./attrition.Rdata)
* [College "sc" dataset](./college.Rdata)
* [College debt dataset](./sc_debt.Rdata)
* [Education variables (if needed)](./educ_vars.Rdata)
* [ELS full dataset](./els.Rdata)
* [ELS testing dataset](./els_test.Rdata)
* [ELS training dataset](./els_train.Rdata)
* [Free excel dataset](./free.xls)
* [FRL dataset](./frl.Rdata)
* [HSB csv dataset](./hsbdata.csv)
* [Income variables (if needed)](./income_vars.Rdata)
* [PD dataset](./pd.Rdata)
* [SF cluster dataset](./sf_cluster.RData)
* [SF complete dataset](./sf_complete.RData)
* [SFO dataset](./sfo.RData)
* [Za full dataset](./za.RData)
* [Za testing dataset](./za_test.RData)
* [Za training dataset](./za_train.RData)

### Synchronous (.Rmd) Files
These files will only be uploaded when there are substantive code changes/additions to the async .Rmd files.
* Week 2 - [Conditional Means in-class .Rmd File - added Ntiles code](./02_Conditional Means_inclass.Rmd)
* Week 3 - [Descriptive Plots in-class .Rmd File](./03_DescriptivePlots_inclass.Rmd)
* Week 6 - [Regression part 1 in-class .Rmd File](./05_regression_updated_inclass.Rmd)
* Week 7 - [Regression - Specifying/Changing the Reference Group for Dummy Variables .Rmd File](./05_regression_part2_referencegroup.Rmd)
* Week 8 - [Twitter API .Rmd File](./07_twitterAPI.Rmd); [Webscraping in-class .Rmd File](./07_webscraping_inclass.Rmd)

### Assignments
Each assignment (problem set) should be uploaded to the LMS _before_ we meet for live session on the given due date. All assignment submissions must include two files to receive credit:
1. .Rmd code file.
2. "Knit" assignment file. The knit file can be in pdf or html (pdf is preferred). 

Note that you must upload BOTH files BEFORE you hit "submit" in the LMS; if you try to submit them one at a time, it will only allow you to upload one. Also, you are responsible for reviewing the files before uploading (check formatting, output, etc.). I will not accept submissions via email (unless there are extenuating circumstances). **There will be a penalty for submissions not meeting these requirements.**

All assignments are graded on a 100-point scale. Corrections can be submitted for any assignment and you can earn up to half of the deducted points back. You have one week from the time you receive feedback on the assignment to submit corrections.

| File(s)      | Due Date          |
|:-------------|:------------------|
| [Assignment 1 PDF](./01_Assignment_starter.pdf), [starter .Rmd](./01_Assignment_starter.Rmd) | 5/25/21 |
| [Assignment 2 PDF](./02_Assignment_starter.pdf), [starter .Rmd](./02_Assignment_starter.Rmd) | 6/8/21 |
| [Assignment 3 PDF](./03_Assignment.pdf) | 6/22/21 |
| [Assignment 4 PDF](./Assignment-4---Regression.pdf) | 7/6/21 |

### Final Project Materials
* [Final Project Expectations and Rubrics](./Final Project - Expectations and Rubrics.pdf)
* [Progress Report 1 Instructions](./Progress Report 1 - Instructions.pdf) - due 6/1/21
* [Progress Report 2 Instructions](./Progress Report 2 - Instructions.pdf) - due 6/22/21
* [Progress Report 3 Instructions](./Progress Report 3 - Instructions.pdf) - due 7/20/21

#### Final Project Examples
Note: these are strong examples; but that doesn't mean they are perfect. Be sure that you use the supplied rubrics to ensure you're meeting all expectations. 
* [Presentation - Bike Share in the Bay Area](./Booker_Kumbhari_Rasnick_Stonesifer_LLO 8200 Data Science_ BikeShare.pdf)
* [Presentation - Modeling Parent Participation in School Events](https://docs.google.com/presentation/d/1sgmQ52i69Vwmb1mfGb9L7vwsygUfuCwn6k0ZyeJiRcA/edit#slide=id.g8f4bd20341_0_1)
* [Presentation - A Tale of Two Cities: Examining Crime and Arrest Rates in the Community Areas of Chicago](./LLO8200_Final Presentation_Bhowmick, Edonick, Emuron, Kabbaz.pptx)
* [Knit report - What Predicts Family Spending on Groceries?](https://raw.githack.com/wdoyle42/ll0_8200_summer_21/main/example_report.html)
* [Knit report - How Might Race Influence Employee Experience?](./Wilen_FinalProject_Final.pdf)

### Additional Resources
Because our syllabus differs slightly from what's in the LMS, the gradebook calculations won't be entirely accurate. If you'd like to keep track of your current average, here is a tool to help you do so. This properly weights the various course elements (note that you'll need to put in some "estimated" data for the final products to populate an average). 
* [Data Science Average Calculator](./Student Average Calculator.xlsx)

There are a multitude of resources re. RStudio and RMarkdown on the web. Here is where I'll save some of my favorites. 
* [R Markdown Reference Guide](./rmarkdown-reference.pdf)
* [R Markdown Cheat Sheet](./rmarkdown-cheatsheet.pdf)
* [R Color Palette Cheat Sheet](./colorPaletteCheatsheet.pdf)
* [GGplot Cheat Sheet](./ggplot2-cheatsheet.pdf)

Additional Practice
* [Census data with R (advanced course)](https://www.census.gov/data/academy/courses/ranking-project.html)
* [Mapping census data with R using choroplethr (intermediate course)](https://www.census.gov/data/academy/courses/choroplethr.html)
* [Squirrel census - mapping exercise](https://annielyu.com/2019/10/29/fun-leaflet-in-r-with-nyc-squirrel-census-data/)
* [ggplot2](https://rpubs.com/williamsurles/295930)
* [ggplot2](http://euclid.psych.yorku.ca/www/psy6135/tutorials/gapminder.html)
* [Linear regression](https://www.machinelearningplus.com/machine-learning/complete-introduction-linear-regression-r/)
* [Logistic regression/classification](https://towardsdatascience.com/modelling-binary-logistic-regression-using-tidymodels-library-in-r-part-1-c1bdce0ac055)
* [Logistic regression/classification](https://ntaback.github.io/UofT_STA130/week8/Week8PracticeProblems-solutions1.html)
* [Logistic regression/classification](https://rpubs.com/AIventurer/datacamp_R_ML_TB_Ch2)
* [K-fold cross validation](https://drsimonj.svbtle.com/k-fold-cross-validation-with-modelr-and-broom)
* [Random partititioning/Monte Carlo approach to cross validation](https://ijlyttle.github.io/model_cv_selection.html)
* ["For" loops](https://www.datamentor.io/r-programming/for-loop/)

#### Known Corrections to Async Questions
* Week 1 - UNC Chapel Hill admit rate = 0.34
