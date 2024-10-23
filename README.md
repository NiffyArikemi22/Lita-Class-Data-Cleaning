# Lita-Class-Data-Cleaning
## Cleaning Dirty Data with Power BI
A step-by-step guide on cleaning and Preprocessing dirty data using Power BI.

### Introduction

Dirty data can significantly impact business decisions. This repository demonstrates how to identify and clean common data issues using Power BI.

### Dirty Data file
data (folder containing sample dirty data)
[Excel Functions 2 - Text.xlsx](https://github.com/user-attachments/files/17488830/Excel.Functions.2.-.Text.xlsx)

### issues
1. unnecessary space
2. Name not properly entered
3. Null columns and rows
4. Proper, Upper and Lower case issues

### Transformation stage: Cleaning Data with Power BI
1. Take the dirty Data to Transform Data on PowerBI
2. Remove null rows: using powerBI Romove rows function
3. Promote header: using first row as header
4. Remove null columns: using powerBI remove column functions
5. Eliminate unnecessary space: firstly split column by delimiter, do necessary adjustment, then merge the split columns
6. Use of proper case, Upper and lower case powerBI functions
   
### Visualisation
This depicts the final transformation of Cleaned Data after passing through the Transformation stage

#### * Extracting First and Surname from Email
Check applied steps on the image

![Text Cleaning 4](https://github.com/user-attachments/assets/44f73cea-7195-400d-8b0e-b87aa54a6cab)

#### * Merge First Name and Surname to form full name
  Check applied steps on the image
  
 ![Text Cleaning 3](https://github.com/user-attachments/assets/056cd020-d523-48d7-a7ba-ec77f8385173)

#### * Extract first name, surname and email from the full name
Check applied steps on the image

  ![Text Cleaning 2](https://github.com/user-attachments/assets/a5d49290-efdb-4338-b672-eeb7c5f8e319)

### Conclusion

Cleaning dirty data is essential for accurate business insights. This repository demonstrates how to use Power BI to identify and clean common data issues.
