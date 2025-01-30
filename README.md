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

Here, we calculate the final tumor volume of each mouse across four of the treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin
We also calculated the IQR and quantitatively determine if there are any potential outliers. 

![boxplot](https://github.com/user-attachments/assets/3d597f42-9087-4659-b1d0-97d3dd42f1c3)

The above boxplot help us to compare the interquartile ranges. The longer the box, the more dispersed the data. In our case, Ceftamin has the longer box. The large ranges indicate wider distribution, that is, more scattered data. The Infubinol has the outliers, that is the data point outside the boundary. 

## Line and Scatter Plots

![mouse l509](https://github.com/user-attachments/assets/dc20569f-65a5-4b9d-94fd-e4fe1d570fed)

Here, we have selected a single mouse (l509) that was treated with Capomulin and generated a line plot of tumor volume against the time point of that mouse. As we can see, the tumor volume reduces as the time point increases. So there is a significant reduction in the tumor volume by using this drug in this mouse. 


![scatter](https://github.com/user-attachments/assets/08fca75e-3bff-4497-8e63-42bd19954b42)

A scatter plot is also generated to see how each mouse weight affects the entire Capomulin regimen over average tumor volume. The higher the weight, the higher the relation with tumor volume. 

## Correlation and Regression

![lr](https://github.com/user-attachments/assets/cf4354e4-0965-47bc-b460-de1dcb2764b2)

As we saw from the previous scatter diagram, the mouse weight and average tumor volume are positively related. The correlation between mouse weight and the average tumor volume is 0.84. The Overall summary of this study shows a positive result. Especially when using the drug, Capomulin.


# Acknowledgment

I have completed the challenge with the help of my Instructor and some internet searches.


