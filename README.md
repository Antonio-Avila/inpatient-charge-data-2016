# inpatient-charge-data-2016

Analysis of how Medicare benefitiaries are charged for hospital services and procedures when admitted into a hospital for the year 2016. 

Data comes from the Centers for Medicare & Medicaid Services. Can be found via the following link: 
*https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Inpatient2016.html*

In addition to the analysis, I built an interactive web app using R's Shiny package. The web app creates a heat map of the US
based on selected values the user can choose from, such as the average cost per procedure. Moreover, the user can specify
a state via its abbreviation (for example, Texas is TX) to receive its exact value from the plot. Alternatively, the user may 
choose the "Table" tab located above the plot to display a chart containing all the states' values.
The web app can be accesed via the following [link](https://antonioavila.shinyapps.io/med_shiny/)
![alt text](https://github.com/Antonio-Avila/inpatient-charge-data-2016/blob/master/shinyimage.png)(https://antonioavila.shinyapps.io/med_shiny/)


My thoughts as I am analyzing the data are found in the **_medicare_proj.pdf_** file. 
I am not familiar with how Medicare pays for hospital services or typical hospital charging structures so I am going 
through everything that crosses my mind to get a better idea of what goes on and possible reasons why. 

A smaller file will be uploaded when I am finished going through everything that comes to mind summarizing the most important
 things I found and things I found noteworthy. 


Finally, also uploading my rmarkdown script which prints out the pdf in the **_medicare_proj.rmd file_**. 
It contains all the R code outputting the analysis, visualizations, etc.


I plan on combining it with another file containing state location, ie South, West, etc and state political affiliation 
in case there is a patter. Also plan on eventually including past dataset dating back to 2011 to see the progression of 
charges and payments and how they were affected by the adoption of lack of adoption of ACA era policies such as Medicare 
expansion. 

