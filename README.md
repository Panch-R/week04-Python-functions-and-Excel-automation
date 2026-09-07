# Week 4 - Python function and Excel automation
## Goal

Understand how to organize Excel data processing using Python functions and process multiple Excel files efficiently.

## What I learned
- How to define functions using def
- How to pass multiple arguments to a function
- How to use return to return processing results
- How to use for loops to process multiple Excel files
- How to separate file selection from data processing
- How to organize an Excel processing workflow into a reusable function
- How to process data using the following workflow:
  Read Excel
  Filter Japan data
  Add/calculate new columns
  Export the processed DataFrame to Excel

## Key takeaway

Functions help separate individual tasks from the main workflow.

For example, the for loop is responsible for iterating through the Excel files one by one, while process_excel() is responsible for processing each file. This makes the code easier to read, reuse, and maintain.

## What I can explain now

I can explain how a Python program can automatically process multiple Excel files using a for loop and a processing function.

I can also explain how an Excel file is read into a DataFrame, filtered, processed, and exported as a new Excel file.
