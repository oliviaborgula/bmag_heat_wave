# bmag_heat_wave
Data Analysis for Baltimore magazine article on increased heatwaves in June

Data analysis for this <a href="https://www.baltimoremagazine.com/section/health/baltimore-heat-wave-safety-cooling-hydration-tips/"> article</a> was done in June 2024 for Baltimore magazine. 

I uploaded two datasets showing maximum and average temperatures in Baltimore in the last 50 years. I cleaned it using the clean_names() function in the janitor library, removing rows containing only NA values and added a column for date. I then filtered datasets to only show data from the month of June before using group_by and count to determine the number of 90+ degree days in the last 50 Junes, a threshold I determined after speaking with a climate expert, who told me that was the official designation of a heat wave during the month of June. 

I wrote my final dataset into a CSV before uploading and visualizing it in Flourish. 

To visualize the Urban Heat Island effect, I downloaded an Excel file for Baltimore UHI data from <a href="https://www.climatecentral.org/climate-matters/urban-heat-islands-2023"> Climate Central</a> and uploaded it directly into Flourish. I uploaded a <a href= "https://data.baltimorecity.gov/"> GeoJSON file</a> showing Baltimore City and parts of the surrounding county for the custom Flourish map. 
