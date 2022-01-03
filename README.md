# The final project for the 'Fundamentals of Data Analytics' course

This is the repository for the final year projects for the course 'Fundamentals of Data Analytics' run in GMIT in Winter semester of 2021. it consists of 2 separate projects: CAO Points requirements comparison and Introduction to Pyplot.


## What to Install

Please refer to 'requirements.txt' file for detailed list of required software and Python packages.


## How to run this project
1. Download the project to your computer by pressing the green 'Code' button and then downloading the 'ZIP' file or cloning this repository using git.
2. Unzip the file (if ZIP file was downloaded), open the Cmder (or other Console of your choice) and navigate to downloaded project folder
3. When in the folder, type 'Jupyter Lab' or 'Jupyter Notebook'
    - Jupyter Lab/Notebook will open in your system default browser
4. Using Jupyter Lab/Notebook navigation Menu, open:
    - 'cao.ipynb' notebook 
    - 'pyplot.ipynb' notebook


## cao.ipynp

The aim of this notebook is to compare the CAO Points requirements for the Level 6/7 and Level 8 courses offered by all the Irish Higher Education Institutions.

The following data was downloaded from the http://www.cao.ie website:

1. 2019 points were made available through pdf file
2. 2020 points are available in the Excel format
3. 2021 points are available on the website and in the Excel format

All the data sources were downloaded, cleaned, prepared, and joined using mainly Pandas and Numpy packages. Next, Matplot and Seaborn packages were used to visualize the changes in the overall points requirements year-to-year and to look in more details and the Higher Education Institutions and course category levels.

## pyplot.ipynb

The goal of this notebook is to describe the purpose and use of the Matplotlib package: starting from its purpose, installation, and the usage. I have looked closer at 3 example plot types:
* Scatter plots
* Histograms
* Box plots
I have selected these 3 plot types based on their usefulness in the data science.