# **Conditional Formatting**
 Faith Meyer

## **What am I talking about?**
In this tutorial I will be talking about the Excel tool called Conditional Formatting. This is one of the tools to help you organize your data. It will also help you visualize the range of your data in a different way than just creating a graph or sorting your data. Conditional Formatting is a tool that can look at the full range of your data and color code it in whatever color scheme you would like. There are plenty of other ways it can be used such as for creating macros and formatting your data in different ways. 

## **Why would I use Conditional Formatting?**
Conditional Formatting is a very useful tool for many different things. Like I said earlier, conditional formatting is a tool that can be used to visualize the full range of your data. It will color code your data however you want it. The example I created has to do with temperatures. We will look at the example closer later on in this tutorial. The great thing about this tool is there are many different ways you can organize your data. You could order the cells by value, based on what they contain, the top and bottom values to just name a few. You can also decide how you want the data to be represented. You can choose to have a two or three color scheme, change the way the bars appear in a bar, or change the icons that are being shown to represent the data. 

## **How Do I use Conditional Formatting?**
Here is a step by step guide of how to use this tool. Before we begin, make sure you have a dataset downloaded and saved as a CSV or it is just downloaded right into Excel. If that happens you will be able to skip some steps.

1. Open up the Excel application on your computer. If you do not have the application downloaded, go to the Microsoft Office website, create an account, and download the application.
![Excel_Icon](/excelicon.png)

2. Click on the blank workbook option so then you can import whatever data you want or create your own data set.
![Workbook_Selection](/workbookselection.png)

3. Now that we have our blank workbook, we need to import our data. Look at the very top of the screen. You will see a line with a bunch of different tabs, you want to click on the tab that says data. Down below all of those tabs is what is called the tool bar. This is a bar with many different actions that is used a lot when working with Excel. On the toolbar, click on the option that says from csv. After the button is clicked, navigate to where you saved your data set and it will be imported into your workbook.
![Import](/import.png)

4. Once you have the data set you are going to work with is imported, you can manipulate it in order to get as much or as little data that you want. Once you are happy with the data you have, you need to go back to the home tab. One major thing to know about conditional formatting is that it will only work if the data is just raw numbers. If they have any sort of unit of measurement or string attached to it, this tool will not work. To clean up the data and get rid of the unit of measurement we need to use a formula. The formula is =NUMBERVALUE((TEXTJOIN("",TRUE,IFERROR(MID(B3,SEQUENCE(20),1)+0,"")))).
![Imported_Data](/importeddata.png)

5. On the home tab, the tool bar is divided into eight different categories. If you look at the fifth category, the style category, on the left most side you will see an option with the name Conditional Formatting. This is the tool we will be using to visualize the range of our data. This is what I was describing in some of my earlier sections.
![Conditional_Formatting_Location](/conditionalformattinglocation.png)

6. Once you click on that button, there will be a dropdown menu that appears with many different options on it about how you want to visualize and manipulate your data. 
![Dropdown](/conditionalformattingdropdown.png)

7. The section I am going to focus on is the 24hr New Snowfall category fot the 2017 season. I will be comparing it based on the date listed. You can go over each of the options which presents a new dropdown. Since the option that I wanted to work with was not listed, I clicked on the button that said More Rules.  
![Dropdown_Options](/dropdownoptions.png)

8. After clicking on the More Rules option, another box opens up with more ways you can play with your data. I want to format the cells based on their data so that I can see the full range of how different the amount of snow that appeared was between a certain amount of time.
![More_Rules](/morerules.png)


9.  If I keep the data the way it is, you will just see a your data with different colors scattered throughout the set in no particular order. That is okay for this data set since it is a small amount of data with not a very large range, but if you have a much larger range and data set, it may help to use the sort tool, which you will learn about in a different tutorial.
![RangeDataSet](/rangecoloreddataset.png)

## Another Use of Conditional Formatting
Another use of Conditional Formatting is to see which of your data points is above or below the average of your data set. For this example I made up my own data set. I created a new Excel workbook full of the number of hours different employees worked over a period of time. We will use this to see which employees work above average and which ones work below average.

1. Since you have made it this far in the tutorial, you should already have Excel open. To make a new workbook after having one open you would go to File->New and click on Blank workbook.

2. Now that you have the blank workbook open, we can create our data set. You can either import a data set like we did for the first part, or create your own. I created my own, so I used row number 1 as my header and Column A as my Employee Names. Row 1 should have the headers Employee Name in Column A and Hours Worked in Column B.
![NewData](/newdataset.png)

3. For this data set, I want to see which Employees work above the average number of hours, and which ones work below the average. The first step is optional, but you could figure out the average number of hours worked for all of the employees. You would use the formula =Average(B2:B27). Inside the parenthasis you would change it to (Start cell: End cell).

4. Now we need to highlight out data again and click on Conditional Formatting like last time. You will see that the same dropdown will appear, but this time we will click on the option called Top and Bottom Rules.
![HoursWorkedDropdown](/conditionalformattingdropdownhoursworked.png)

5. Once you click on that option, you want to click on the button that says Above Average. Then you can select a color scheme that you want to pick for the datapoints that are above the average number of hours worked.
![AboveAverage](/aboveaverage.png)

6. To get the data points that are below average, you would do the same thing, only click on the button that says Below Average.
![BelowAverage](/belowaverage.png)

7. Now you are able to see who worked above or below average work hours.


## Now It's Your Turn
Try playing around with conditional formatting using this temperature data set!
![TemperatureSet](./ClassTries.xlsx)

### Sources Used
1. Data Set 1: https://www.kaggle.com/mrmarjo/resort-daily-snowfall-20092017/version/1?select=Snowbird+-+Utah.csv
2. My friend Veronique who told me about the formula to get rid of the units of measurements
3. Created my own data set for hours worked
4. Class Tries: https://weatherspark.com/y/21872/Average-Weather-in-Maryland-City-Maryland-United-States-Year-Round
