# ElevateLabsInternship_Task1
I used the Customer Personality Analysis (Akash Patel) dataset from Kaggle.

The data was not arranged in the form of columns. So I first arranged the dataset in columns using the "Text-to-Column" function. I then changed the "Date" column from "General" to "Short Date".

I first analyzed the dataset and found out that the "Income" column has 24 missing values. So I took the average of the income values of the available data which came out to be 52247. Then I replaced the missing values with 52247.

In the "Marital Status" column, there were some dubious values like "Absurd" and "YOLO". I removed the rows with such values.

Then I removed the duplicate values. Although some customers have different ID numbers, all of the remaining data is same. Such customers are duplicates. I removed all the duplicate customers using the "Remove Duplicates" function.

In this way, I preprocessed the data file.
