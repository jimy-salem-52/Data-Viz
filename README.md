# Data Vizualization Project

### Team 

Duytan Lee,
Lihang Fang,
Zihang Wang,
Jimy Salem

## Introduction

The project aims to conduct a data analysis and visualization for a dataset concerned in the crimes happening in South Australia for 4 carters 
It was collected from the open data site https://data.gov.au/

## Data Cleaning

After the first look a the dataset the shape is made of 50123 rows.
Many null values were shown mainly in postcodes and suburbs 

Some null values are existant in postcodes while they weren't existent in suburbs and vice versa and while some are existant in both
Some criminal activities marks an undisclosed for both postcodes and suburbs, therefore null values for both postcodes and suburbs will be marked as undisclosed

Cases where null values in postcodes while suburbs exists are studied to create a dictionnary with the exact naming and wording 
Cases where null values in suburbs but postcodes were present shows a high case for postcodes 5000 which is aldelaide and 5540 port piri

## Feature Egineering 

Considering there were null values in postcodes while there was existant suburbs, a new dataset was introduced and for reasons of naming (such as port piri and port pirie), the datset was used to match postcodes and retreive the longitide and latitude 

The offence levels are divided into three groups level 1 to 3:

Level 1 was changed to only property or person

Level 2 didn't seem to be as relevant to Level 3

Level 3 shows more details of the crime 

# Questions & Limitations

## General Question

What is the frequency of the crimes done ? Where to increase the security measures to lower crime rate

From the data collected, a study can show answers for which suburbs are high on crime,  or if the crimes are increasing or decreasing with time whether targeting a person or a property, which suburbs with the highest crime and their types, monthes with the high crimes.

The limitations of the project can be seen in:
  1. Time of Day
  2. Changing the systems of records to include the postcodes
  3. Methods of catching the subjects (for example police passing by, surveillance cameras, alarm triggered, ...)

