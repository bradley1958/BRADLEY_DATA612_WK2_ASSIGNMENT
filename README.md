# BRADLEY_DATA612_WK2_ASSIGNMENT
GITHUB README FILE INPUT
DATA612/PROFESSOR ISLAMAJ
WK2 ASSIGNMENT
PANDAS CODING 
ACTION ITEMS
1.	Find the “max” date of the Dataset.
2.	Subtract all the dates on the column from the maximum date.
3.	Covert the number of days into the number of months.
4.	Save the result of the conversion into a new column in the data frame.
5.	Save the dataset as a “CSV” file.
6.	Upload the completed work to GitHub.

I initially loaded the State_Drug_Utilization_Data_2010 CSV file and looked at the first five rows of data. I followed this up by printing out all the column names.
Next, I used the syntax “df.info( )” to look at the dataset, the Data Types, and for null values. 
Action Item 1 – Find the “max” date of the 2010 State Drug Utilization dataset. This dataset is not the best selection for doing this. The set has a “Year” (int64), “Quarter” (int64), plus two other dates “Quarter Begin” (object), and “Quarter Begin Date” (object). Since there are no other columns containing dates in this set of data, I had to create (insert) two new columns to create a subtraction problem for the weekly assignment. 
I inserted a “Start_Date” Column and an “End_Date” Column based on the “min” and “max” dates associated with the 2010 State Drug Utilization dataset. The Minimum date was listed as 2010-01-01 and the Maximum date was listed as 2010-10-01. These two new columns were used to complete Action Items 2 and 3. 
Action Item 4 – Create a new Column with the result of the subtraction problem in Items 2 and 3. I created a “Diff_Months” Column to hold the calculated difference from the subtraction problem. The result of the subtraction was 8.969383 (Approx. 9 Months).
Action Item 5 – Save the dataset as a “CSV” file. This was done with the following syntax:  “df.to_csv(‘df_clean.csv’, index=False”
Action Item 6 – Upload the Colab File to GitHub.

Orren Bradley
Data 612/Summer 2020

