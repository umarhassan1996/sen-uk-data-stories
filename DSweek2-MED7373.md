# Pupils with special educational needs in England most likely to receive no statement or EHC plan

## Dataset used to work on this story - Department for Education on the Explore Education Statistics Service of gov.uk (Get the data)
[Link to original dataset in csv format](https://data.explore-education-statistics.service.gov.uk/api/download/special-educational-needs-in-england/2019-20/data/sen_age_gender.csv)

## Link to more information about the dataset
The information in this document covers the 2019/2020 academic year dataset with statistics around a breakdown of SEN provision, free school meals, gender and ethnicity and more -
[Link to page here](https://explore-education-statistics.service.gov.uk/find-statistics/special-educational-needs-in-england).

## Methodology/Tutorial

For this pivot table, I saved the original csv that I downloaded from the Explore Education Statistics website of gov.uk for SEN by age and gender.

The data covered the 2019/20 academic year as an Excel Workbook before I selected insert to copy all the data into a new sheet to create the Pivot Table.

I filtered out the data to the latest time period (201920) while filtering out the Missing and Total values from the primary_need column.

Next, I dragged region_name on Rows and removed (blank) from the view and added number_of_pupils onto Values.

Once I did this, I dragged pupil_sen_status onto Columns where I deselected Totals to create the final pivot table for my story.

The aggregate totals in the pivot table include state-funded nurseries, primary and secondary schools, as well as pupil referral units and non-maintained special schools.

What I did next was sort out the data from high to low so that it allowed me to recognise which regions in England had the highest to lowest total of pupils with SEN No Statement or EHC or Statement or EHC, depending on the column being used for analysis. 

Working out the percentage of SEN No Statement or EHC and Statement or EHC, I divided the total value of each column by the combined total in which I got the final percentage for those two columns.

For example, to work out the percentage of pupils with SEN No Statement or EHC, I used the SUM function to get the percentage of that field by dividing it from the total number of pupil_sen_status.

To do this, I used this calculation to get the percentage of SEN pupils with No Statement or EHC, which was =SUM(B8:B16)/D17, which came out as 0.783844684 (with formatting changes, 78%).

I did the same thing with the Statement or EHC column where I calculated in Excel =SUM(C8:C16)/D17, which the final result was 0.216155316 (with formatting changes, 22%).

When working out the percentage of pupils with a Statement or EHC plan, I divided the selected region in England by total for all regions. For example, with London, the calculation was =C8/C17 to give me the result of 0.171688987 (or 17% with formatting changes). 

With the North East, I calculated the total of SEN pupils with a Statement or EHC plan by the North East (=C16/C17), which gave me the figure of 0.049560418 (or 5% with formatting changes).

## Short story version

Pupils with Special Educational Needs are most likely to receive no SEN statement or a education, health, and care plan in England.

Analysing the Department for Education data on pupils in education with special educational needs, covering the 2019/20 time period, 78% (1,998,840) of pupils in regions across the country had no SEN Statement or EHC plan.

In comparison, 22% (551,201) of pupils have had a statement of special educational needs or a education, health and care plan, covering the same period.

<h3><strong>What does having no SEN statement or EHC plan mean? </strong></h3>

<p>If a pupil who has special educational needs in the English education system has no SEN statement or EHC plan, then provision should be provided for the child in school through 'SEN Support'.</p>

<p>In the <a href="https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/398815/SEND_Code_of_Practice_January_2015.pdf">SEND Code of Practice 2015</a>, it explains in Chapter 6 of the Code how schools should assess a child with special educational needs by using the graduated approach of <strong>Assess, Plan, Do, </strong>and <strong>Review.</strong></p>

<p>An <a href="https://www.gov.uk/children-with-special-educational-needs/extra-SEN-help">education, health, and care plan</a> is for children and young people from up to the age of 25 who may need more support than what is required through SEN support.</p>

<p>Pupils who have no statement of special educational needs through an EHC plan are more than twice as likely to be excluded from school, compared with a pupil who has one, according to data from the <a href="https://explore-education-statistics.service.gov.uk/find-statistics/permanent-and-fixed-period-exclusions-in-england">Department of Education</a>.</p>

<p><strong>London</strong> has the highest number of pupils in education who have a SEN statement or EHC with <strong>17%</strong> (94,636). The <strong>North East</strong> has the lowest number of pupils with a SEN statement or EHC at <strong>5%</strong> (27,318).</p>

## Link to story for DS on The DDJ Nerd website
[The DDJ Nerd - Pupils with special educational needs in England most likely to receive no statement or EHC plan](https://theddjnerd.wordpress.com/2020/09/30/pupils-sen-statement-ehc-plan/) - <strong>30/09/2020</strong>
