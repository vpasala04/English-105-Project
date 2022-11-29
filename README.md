# Vineeta Pasala: English-105-Project

This is a repository containing instructional materials and sample datasets for Prof. Gotzler's Fall 2022 sections of ENGL-105 at the University of North Carolina at Chapel Hill

This repository contains a .csv file to County Public Health Data from 2014-2015, and python notebooks covering basic topics in modifying the County Public Health .csv dataset into a simpler data analysis of a specific issue

The 4 python notebooks in this repository contains information as follows:
  - A basic introduction to using the python coding language
  - A basic introduction to using the Pandas package
  - Using the Pandas package to manipulate, modify, and prepare large chunks of data for analysis
  - A specific instance of using the python language and pandas package together to modify the County Health Public Data .csv file to only include data regarding the number of teen pregnancies and high school graduates in various counties in Alaska.

The .csv data was gathered from County Public Health Data from various States in the U.S., and obtained by Prof. Gotzler and adapted by the [UNC Research Hub](https://library.unc.edu/hub/) in the Davis Library.

## Navigation

At the top of this repository, there are multiple folders containing files.

- In "Python Notebooks," you will find all of the tutorial-based files that introduce you to python as a general programming language, and itroduce you to the pandas package as a tool to use when dealing with data. Lastly, the notebook containing the edited and indexed data from the County Health Public Data is located here.

- In "CSV_Data_Files," you will find the County Health Public Data .csv file, and the newly exported Teen County Data file (created from the python notebook)

- In "Visualizations," you will find all of the data representations and you will find the screenshot providing the prior data preparation in excel, further explained later in this repository.

## Provenance

As mentioned above, the County Public Health Data .csv was obtained through lesson plans adapted by the [UNC Research Hub](https://library.unc.edu/hub/) in the Davis Library.

The python code was from a notebook created in the Jupyter software retrieved from the Anaconda Navigator application.

The bar graph visualization analysis was created using the Tableau software through an imported excel sheet file containing the tabular version of the .csv file exported from Jupyter.

## Purpose

This data is to be used by anyone trying to study or examine trends in specific public health issues. 

In this repository, we will be focusing on comparing the number of teen pregancies and the number of people who graduated from high school in Alaskan Counties, and examining whether there is a correlation that exists between the two. Based on what trends are present in the data, actions can be taken to potentially advocate for better sex education and better access to contraceptives in Alaskan counties.

This repository can also be of use to anyone starting to explore data manipulation and simple data analysis using the python coding language and pandas package.

## Potential

This repository was created in order to explore and gain understanding for obtaining data and analyzing it through simple coding and visualization methods. Some may use the data in this repository to do more extensive data analysis amongst multiple variables of County Health Public Data for a larger project, or simply get an introduction to simple coding practices in python.

On a more specific note, the data and results presented in this repository can aid the ongoing study and research on the effects of teen pregnancies on one's future career and pursuing of higher education, by seeing whether they were able to graduate high school given the circumstance. 

## Visualization and Data Analysis

Along with preparing the data by indexing certain sections by using python and the pandas package, I also had to prepare the data by converting the values of the high school graduates from percentages to average numbers as shown with the teen pregnancy column. In order to do this, I went to Microsoft Excel and implemented an algorithm that would calculate the number of high school graduates by multiplying the decimal percentage by the population of each Alaskan county. The following process is shown in the excel sheet below:

<img width="667" alt="Screen Shot 2022-11-28 at 6 06 52 PM" src="https://user-images.githubusercontent.com/118345487/204399612-05f87528-8195-43d7-b096-b7c65ff66571.png">

A bar graph is used in the representation of this data because the goal is to compare the numbers between teen pregnancies and high school graduates. We are trying to see if the increase in teen pregnancies is followed by an increase or decrease in high school graduates across multiple counties in Alaska specifically. A bar graph can also adequately compare the teen pregnancies and high school graduates between counties and see where areas need more education regarding family planning and higher education. The following visual representation is shown below:

<img width="859" alt="Screen Shot 2022-11-28 at 6 32 53 PM" src="https://user-images.githubusercontent.com/118345487/204407141-a5670510-49aa-4558-8c1e-66e47b66e8a6.png">

Another visual representation that can be used for this data is a scatterplot because this can determine whether a trend exists for these two sets of data; in this case, we can determine whether a trend (correlation) exists between teen pregnancies and high school graduates. The scatterplot is shown below:

<img width="827" alt="Screen Shot 2022-11-28 at 7 24 29 PM" src="https://user-images.githubusercontent.com/118345487/204408491-3198c7c5-c92f-4828-8b31-b328d496ba10.png">

However, it is important to note that the numbers of those who graduated high school in the counties in Alaska include both young women and men, whereas the teen pregnancy numbers obviously only consist of women. Therefore, there is an underlying assumption in the data, in that the young men are equally likely to attend/not attend high school as a result of a teen pregnancy.
