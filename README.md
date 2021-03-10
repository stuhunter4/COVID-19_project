# Los Angeles vs. San Francisco (Counties)
<p>Two urban centers in the state of California have shown drastically different COVID-19 trajectories; in particular regarding testing, cases, deaths, and hospitalizations.</p>
<p>For this project we did an exploratory analysis into some of these and other differences between the two counties, and attempted to draw some conclusions from the data we found.</p>
<p>For my part, I have included the Jupyter notebooks used to: extract data using Python API requests, processed different types of data files into clean dataframes with Pandas, then generated some of the visualizations we used in our presentation, via Matplotlib.</p>
<p>Post-project, I have kept up with COVID-19 cases and deaths in California counties on my website, https://stuhunter4.github.io/hunterStuff/county_data/county_data.html</p>
<h3>Individual Notebooks Explained:</h3>
<p><strong>Census_data.ipynb: </strong>Using a .csv created in County_size.ipynb, and python api requests from census.gov, created a .csv file of select census data on Los Angeles and San Francisco counties.  This .csv census file was created for use in later notebooks devoted to analysis and visualizations.</p>
<hr>
<img src="https://github.com/stuhunter4/COVID-19_Project/blob/main/resized/AverageCases_PerCapita.jpg" alt="avgCases">
<img src="https://github.com/stuhunter4/COVID-19_Project/blob/main/resized/AverageDeaths_PerCapita.jpg" alt="avgDeaths">
<p><strong>COVID_Summ_Data.ipynb: </strong>This notebook contains the calculations and visualizations related to COVID-19 cases and deaths for our two California counties.  Data was read from our Census_data.ipynb-created .csv file and another .csv from California Open Data Portal for COVID-19 cases and deaths.  There are charts for daily COVID-19 cases and deaths, and per capita cases/deaths over two-week periods, in this notebook.</p>
<hr>
<p><strong>COVID_Cases_Outliers.ipynb: </strong>Box plots were created to explore outliers in our data.  This information was ultimately supplemental and unused in our final presentation.</p>
<p><strong>County_size.ipynb: </strong>A .txt file with geographic data from census.gov had its data on California counties processed for use in other notebooks, namely to complete the census .csv file created in Census_data.ipynb.</p>
<hr>
<img src="https://github.com/stuhunter4/COVID-19_Project/blob/main/resized/Census_BarGraphs.jpg" alt="censusGraphs">
<p><strong>CensusData_BarGraphs.ipynb: </strong>Utilizes our newly organized census information into four bar graphs comparing the populations of Los Angeles and San Francisco counties.</p>
<hr>
<p><strong>Covid19_StateCounty_Policy.ipynb: </strong>Early in the project we wanted to examine COVID-19 policy differences between California counties, and executed python api requests from healthdata.gov for our data.  This information was ultimately unused in our final presentation, due to lack of enough data on the subject.</p>
<p><strong>Testing_Data.ipynb: </strong>The two counties being compared both offered COVID-19 testing data on their respective official websites.  Two charts were created to visualize daily COVID-19 tests, and daily COVID-19 tests per capita, over time.</p>
<p><strong>Hospital_Data.ipynb: </strong>California Open Data Portal has detailed data on COVID-19 patients in California hospitals, which we processed to create charts that display, over time, positive and suspected COVID-19 patients along total available hospital beds.  This information was ultimately supplemental and unused in our final presentation.</p>
<hr>
<img src="https://github.com/stuhunter4/COVID-19_Project/blob/main/resized/LASF_top10LA_employees.jpg" alt="topEmployees">
<p><strong>Employment_Data.ipynb: </strong>Details about each respective county's employment profile was queried from census.gov through python api requests.  This information was organized into several bar graphs that examine the relative proportion of employees working in front line occupations during the pandemic.</p>
<hr>
<img src="https://github.com/stuhunter4/COVID-19_Project/blob/main/resized/Households_BarGraphs.jpg" alt="houseGraphs">
<p><strong>Household_Census_Data.ipynb: </strong>In search of additional census.gov information that may help our analysis, a number of details relating to households was queried and displayed as bar graphs.  This information was ultimately supplemental and unused in our final presentation.</p>
<hr>
<h3>The 'NEW' notebooks were created after the project presentation, to expand the analysis to the differences between the metropolitan statistical areas of Los Angeles-LongBeach-Anaheim and San Francisco-Oakland-Berkeley.</h3>
<img src="https://github.com/stuhunter4/COVID-19_Project/blob/main/resized/NEW_DailyCases.jpg" alt="newCases">
<img src="https://github.com/stuhunter4/COVID-19_Project/blob/main/resized/NEW_Census_BarGraphs.jpg" alt="newCensus">
<p><strong>NEW_Census_data.ipynb: </strong></p>
<p><strong>NEW_COVID_Summ_Data.ipynb: </strong></p>
<p><strong>NEW_County_Size.ipynb: </strong></p>
<p><strong>NEW_CensusData_BarGraphs.ipynb: </strong></p>
<p><strong>NEW_PPE_data_draft.ipynb: </strong></p>
<p><strong>NEW_PPE_data.ipynb: </strong></p>
