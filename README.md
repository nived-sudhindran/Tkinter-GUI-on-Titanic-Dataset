This program uses Tkinter GUI to explore data from Titanic Dataset. 
Here I have used my previously cleared Dataset which has already did preprocessing steps for dealing with NULL values, Duplicate values and Outliers. I have included the cleaned dataset in this repository. see the excel file.

I have created a GUI Window with resolution 1200x1000 which can fully display the complete row of data after loading the CSV file - Cleared Titanic Dataset.csv
**
Note: You can try loading any other Dataset for preview. But the rest of the buttons will work only with the Titanic Dataset, as its coding has been done only to show graphs/charts for this dataset.
**

Just after loading the dataset successfully, the Statistics - Mean Age, Median Age and Survival rate will be automatically loaded and displayed under the Dataset Preview Window.

Then once you click on the Button ** Fare vs Age **, the function ** plot_fare_vs_age() ** will be executed which generates the plot. To display this plot function ** show_plot(fig) ** is called and executed.
Similarly, once you click on the Button ** Survival Rate by Class **, the function ** plot_fare_vs_age ** will be executed which generates the plot. To display this plot function ** show_plot(fig) ** is called and executed.
