# Business_Stat_Assignment_1

**The Scenario**

In this assignment you will be analysing data on children living in low income households in London. For this data, London is split into boroughs (large areas of London which usually have their own local
council or local government) and then further sub-divided into wards. This data is provided across 8 years. It shows the counts for the number of children living in low income housing within each ward
in London.

You are being asked to prepare a simple report answering specific questions.

**The Structure **

The assignment should be completed in RMarkdown and knitted into a html file. Your submission should be a zip file containing the RMarkdown file and the html output it creates. When the
RMarkdown file is re-run, it must produce the same html output that you submit. This should have two parts. The first part should include the code that you produce to perform all
stages of the data analysis. It should read in the datafile provided, check the integrity of data, calculate all of the statistics requested, and produce all of the figures/visualisations requested. 

The purpose of this first part is that it could be shared with someone else who is not familiar with the data or project, but is expert in R and statistics. They should be able to see how you achieved your
results, and if necessary, easily modify the code to work with new or updated data. Therefore, the appropriateness of your comments and data documentation will also be assessed.

The second part should be a short, polished and professional report presenting and interpreting the findings for an audience of managers or policy makers. You should assume that the managers/policy makers have a basic knowledge of the data and where it comes from, but are not experts in statistics or R. Therefore, in addition to reporting the results of statistical tests using standard reporting
conventions, you should also state the results in plain English and say what they mean or what they tell us about the real scenario – in this case what they tell us about rates of children living in low income households. The visualisations and figures in this section should be as clear as possible and of publication standard.

The official word count for this assignment is 1500 words, but the written report should be much shorter than this. Since this is a code and analysis based assignment, the word count is not directly applicable in the way that it is for an essay. The word count is provided as a guide: that this assignment is assumed to be approximately the same amount of work as a 1500 word essay. The
report should be short, succinct and clear in communicating the main results only of the elements requested in the assignment question. Including additional irrelevant information in the second
section will have a negative impact on your mark.

**The Request**

The company have requested the following:
Children in low income homes by borough Provide a table that shows for each borough: the average number of children in low income homes per ward across all years in the dataset, the standard deviation of children in low income homes per
ward across all years in the dataset, the lowest number of children in low income homes recorded for a ward in any year, and the highest number of children in low income homes recorded for a ward in
any year.

To clarify, there should be one row per borough in the table: “across all years” means that you should use all of the data from all of the years and all of the wards to calculate e.g. one mean.
For this table you should include all boroughs in the dataset.

**Exclude unusual boroughs**

A small number of boroughs are unusual. They should be included for the table above, but should be excluded from all of the elements from this point onwards. The boroughs to be excluded are: City of
London; Kensington and Chelsea; Kingston upon Thames; Richmond upon Thames; Westminster.

**Visualise data for different years**

Create a visualisation that shows the distribution of children in low income households in wards for each year. This should be a plot such as a violin or jitter plot that shows the distribution of values for
each year so that the reader can clearly see how this has changed. The plot should also clearly show a visual representation of the mean value and standard deviation for each year.

**A t-test comparing earliest and latest year**

Use a t-test to compare the children in low income households in wards in the earliest year in the dataset (2014) and the latest year in the dataset (2021).

You should report the results using Null Hypothesis Significance Testing, and the estimation approach.

