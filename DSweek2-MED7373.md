# Pupils with special educational needs in England most likely to receive no statement or EHC plan

## Dataset used to work on this story - Department for Education on the Explore Education Statistics website for the gov.uk
[Link to original dataset](https://data.explore-education-statistics.service.gov.uk/api/download/special-educational-needs-in-england/2019-20/data/sen_age_gender.csv)

## Link to more information about the dataset
The information in this document covers the 2019/2020 academic year dataset with statistics around a breakdown of SEN provision, free school meals, gender and ethnicity and more -
[link to page here](https://explore-education-statistics.service.gov.uk/find-statistics/special-educational-needs-in-england).

## Methodology
For this pivot table, I saved the original csv for SEN by age and gender from the Explore Education Statistics website as an Excel Workbook before I selected insert to copy all the data into a new sheet to create the Pivot Table.

I then created a pivot table that filtered the data to the latest time period (201920) while filtering out the Missing and Total values from the primary_need column.

Next, I dragged region_name on Rows and removed (blank) from the view and added number_of_pupils onto Values.

Once I did this, I dragged pupil_sen_status onto Columns where I deselected Totals to create the final pivot table for my story.

The aggregate totals in the pivot table include state-funded nurseries, primary and secondary schools, as well as pupil referral units and non-maintained special schools.

Working out the percentage of SEN No Statement or EHC and Statement or EHC, I divided each of the total value by the combined total in which I got the final percentage for those two categories.

For example, to work out the percentage of pupils with SEN No Statement or EHC, I used the SUM function to get the percentage of that field by dividing it from the total number of pupil_sen_status.

To do this, I used =SUM(B8:B16)/D17, which came out as 0.783844684 (with formatting changes, 78%).

I did the same thing with Statement or EHC where I calculated =SUM(C8:C16)/D17, which the final result was 0.216155316 (with formatting changes, 22%).

## Short story version

Pupils with Special Educational Needs are most likely to receive no SEN statement or a education, health, and care plan in England.

Analysing the Department for Education data on pupils in education with special educational needs, covering the 2019/20 time period, 78% (1,998,840) of pupils in regions across the country had no SEN Statement or EHC plan.

In comparison, 22% (551,201) of pupils have had a statement of special educational needs or a education, health and care plan, covering the same period.

London has the highest number of pupils in education who have a SEN statement or EHC with 17% (94,636). The North East has the lowest number of pupils with a SEN statement or EHC at 5% (27,318).

## Updated version of story for DS on The DDJ Nerd website
[The DDJ Nerd - Pupils with special educational needs in England most likely to receive no statement or EHC plan](https://theddjnerd.wordpress.com/2020/09/30/pupils-sen-statement-ehc-plan/)


#
