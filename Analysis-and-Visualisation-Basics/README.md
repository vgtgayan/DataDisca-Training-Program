[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

<img src="https://raw.githubusercontent.com/DataDisca/django_api1/master/DataDisca-Logo.svg_d400.png" width="75" height="25" />

# Analysis and Visualisation Basics 
Data extraction, transformation and loading are crucial skills for any Data Scientist. 
There are numerous examples where the problems are solved with the right statistics and visualisations before applying any specialised machine learning algorithm. 

## Branch
 Make sure you know your branch of this module.  
 We continue to improve the modules based on your feedbacks and submitted outputs. 
 Therefore, we create a branch for you when we assign the module.  
 Go through the `README.md` of your branch.
 
 ARE YOU READING THE RIGHT BRANCH?
 
 If there is any doubt contact DataDisca.

This code is hosted in a private repository to regulate access.
After completing the module, you can host your work in an open repository under MIT license. 

Please help us by reporting all type of errors. 

## Study

1. Study basic Python unless you are already familiar with the same
2. Study `numpy` using a tutorial found on the internet.    
3. Study `pandas` using a tutorial found on the internet.
4. Study  `pandas_profiling` [https://pypi.org/project/pandas-profiling/](https://pypi.org/project/pandas-profiling/)
5. Study `dtale` [https://pypi.org/project/dtale/](https://pypi.org/project/dtale/)
6. Study `Plotly` (Python) using a tutorial found on the internet
7. Study `folium` (Python) using a tutorial found on the internet
8. Study [GeoPandas](https://geopandas.org/en/stable/)

## Application
Steps:  

1. Download 
`Quarterly median rents by local government area - June quarter 2021` dataset from [https://www.dhhs.vic.gov.au/publications/rental-report](https://www.dhhs.vic.gov.au/sites/default/files/documents/202108/Quarterly%20median%20rents%20by%20local%20government%20area%20-%20June%20quarter%202021.xlsx)
3. Perform necessary handling to import the dataset into a pandas dataframe.
4. Save the extracted dataset in .csv and .json formats
5. How many columns the dataset has? 178
6. How many rows the dataset has? 92
7. Complete the following table about the dataset columns

| Field Name | Description | Pandas Data Type | Data Scale | Min Value | Max Value | No of Unique Values | Missing Value Count |    
| Region | Region | object | ---- | NA | NA | 10 | 801 |  
| LGA | Local government area | object | ---- | NA | NA | 83 | 0 |
| Quater | Year and starting month of the quater | object | ---- | NA | NA | 89 | 0 |  
| Count | No: of rentals | object | ---- | 3 | 65229 | 2508 | 0 |
| Median | Median of the rentals | object | ---- | 70 | 595 | 259 | 0 |

7. Use the following plotly chart types at least once to discuss the data characteristics.   
    1. Scatter [https://plotly.com/python/line-and-scatter/](https://plotly.com/python/line-and-scatter/)
    1. Pie [https://plotly.com/python/pie-charts/](https://plotly.com/python/pie-charts/)
    1. Bubble [https://plotly.com/python/bubble-charts/](https://plotly.com/python/bubble-charts/)
    1. Bar [https://plotly.com/python/bar-charts/](https://plotly.com/python/bar-charts/)
    1. Histogram  [https://plotly.com/python/histograms/](https://plotly.com/python/histograms/)
    1. Maps [https://plotly.com/python/maps/](https://plotly.com/python/maps/)
8. Calculate Pearson and Spearman correlation matrices between numerical columns/series as applicable. 
And show the results on annotated heatmaps [https://plotly.com/python/annotated-heatmap/](https://plotly.com/python/annotated-heatmap/)   
9. Use folium maps to display and annotate geographic data. [http://python-visualization.github.io/folium/](http://python-visualization.github.io/folium/).
Note: You need to learn both Plotly and Folium.
10. Study and use [GeoPandas](https://geopandas.org/en/stable/) to draw the map above.
10. Use pandas_profiling https://pypi.org/project/pandas-profiling/ to visualise your dataset (or a part of it as memory and processing permit). 
11. Use dtale https://pypi.org/project/dtale/ to visualise your dataset (or a part of it as memory and processing permit). 
12. Upload neatly arranged code/Jupyter notebook, Readme.md for Git and your work to your Git Repository.

## Quality Standard of Your Work
1. Code should follow PEP8 Standard
1. Host your code on your GitHub in a public or private repository as you prefer. 
- If it is a public repository, send the link for us to evaluate.
- If it is a private repository, share (view only) with our GitHub usernames. Please contact us for them.

    Send us a notification to start the evaluation.
    We evaluate your code for your technical progress.

## Sponsor
DataDisca Pty Ltd, Melbourne, Australia

[https://www.datadisca.com](https://www.datadisca.com)

 

