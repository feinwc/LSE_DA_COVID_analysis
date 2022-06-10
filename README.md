# LSE_DA_COVID_analysis

8. Summarise (>200 words) any insights you've discovered as well as anything you would like to explore further.
- Did you notice anything interesting about the data?
- Does the DataFrame have a default index? 
- What are some of the initial insights you've discovered?
- How has the number of vaccinated individuals changed over time? What might these changes indicate? Include reasons to support your rationale.
- On which date(s) are there values missing, and from which columns and rows are these values missing? Which states or provinces do the missing values belong to?
- Is there anything unusual about the filtered Gilbraltar DataFrame? Include reasons to support your rationale.

The dataset provides detailed information during the pandemic. Interestingly, there are some missing values and unusual patterns in the values of deaths, recovered and hospitalised columns, which might be caused by human errors or miscalculation during the time as the pandemic was unexpected.
There is a default index in DataFrame starting with number 0. I chose not to create a new set of indexing as I used other functions to filter the relevant data. The initial insights I have discovered is the missing values and the max/min values in the file. By filtering and sorting the shape, type, and max/min of each column, I have developed a deep insight into the story during the time. Firstly, the number of the vaccinated individuals has changed a lot over time. The vaccinated rate reached to the highest in April and May 2021 (the highest point is recorded 69,619) and slightly goes down afterwards. From 2020-01-22, there was zero vaccinated individual until January 2021, showing that the vaccination scheme might start to roll over from the month. Moreover, there are some missing values in columns Deaths, Cases, Recovered and Hospitalised on the date 2020-09-21 and 2020-09-22 in cases. The missing values all belong to "Bermuda". Fortunately, there is no missing value in "Vaccinated" file.
Some unusual findings are discovered in Gilbraltar DataFrame. During the time appearing the highest death and case rate, the hospitalised values are showing as zero on both 2021-10-14 and 2021-10-13, which can be human errors or miscalculation. Also, some recovered rate seems missing as well as the values are zero. The data reflects that there is certain relevance among death, cases, recovered and hospitalised growth rate. When the rate of death and case increase, the recovered rate tend to decrease and the hospitalised value grows in the meanwhile.
