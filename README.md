# Module 5 Challenge

This assignment provides us with two CSV files, Mouse_metadata and Study_results. Mouse_metadata contains all the information of mice used in this treatment regimen such as their weight, gender, drug regimen used, etc. Study_results contains the study statistics such as timepoint, tumor volume, etc. Both files are combined using the Mouse ID. we are also provided with a starter Jupyter Notebook, which includes the instructions and the results we need to achieve by writing the code. My results are inside the pymaceuticals.ipynb file.
To run this code just copy the Pymaceuticals folder in your desktop and open the Jupyter notebook and run it. Make sure that the 'data' folder which contains the CSV files we used in this project and the Jupyter notebook (pymaceuticals.ipynb) are in the same location.

In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

## Summary Statistics

In this analysis we calculated the mean,median, variance, standard deviation and standard error of the data. We assemble the resulting series into a summary dataframe. From this results we can see that the drugs, Capomulin and Ramicane are the most successful in reducing the tumor volume. 

## Bar and Pie Charts

![bar diagram](https://github.com/user-attachments/assets/98cd9b91-13c9-48ed-a0ec-d3deb9ee2b77)

The above bar diagram shows the total number of Mice used for each drug regimen. As mentioned above, Capomulin and Ramicane are the most used and Propriva is the least used.

![gender](https://github.com/user-attachments/assets/97a1d90d-25b3-4db5-850e-e72c86646f74)

This Pie chart shows diffrent gender ratio used in the study. As we can see, almost equal number of male and female mice are used. We have not seen any significant difference in the effectiveness of drug based on particular gender.

## Quartiles, Outliers and Boxplots

Here we calculate the final tumor volume of each mouse across four of the treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin
