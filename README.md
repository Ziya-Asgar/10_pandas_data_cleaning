# Notes

## Intro

This repository contains a data cleaning project using Python's `pandas` library. The project is developed alongside this resource:

[Data Cleaning in Pandas](https://www.youtube.com/watch?v=bDhvCp3_lYw)

Parts of my code don't align with the video, because I've decided to do things in a different way.

## Project Details

In this project, we simulate working with customer data to prepare a clean dataset for contacting customers. The project includes

- Importing `pandas` library
- Loading data from an excel file, and creating a DataFrame
- Removing duplicate rows
- Dropping unnecessary columns
- Removing and replacing various unwanted characters
- Standardizing all phone numbers to a specific format
- Handling missing values by removing null entries
- Splitting the full address column into three separate columns: "Street Address", "State", and "Zip Code"
- Standardizing boolean columns to ensure consistent formatting
- Filtering out customers who opted out of being contacted
- Removing records for customers without phone numbers
