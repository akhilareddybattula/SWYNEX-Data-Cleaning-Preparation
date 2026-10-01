# SWYNEX – Data Cleaning & Preparation

## Project Overview

This project focuses on cleaning and preparing road accident data for further exploratory data analysis and visualization.
The dataset contains state-wise road accident, road fatality, and collision-type information for India.

## Dataset

The data covers road accident information from **2020 to 2024**, with detailed analysis focused on **2024**.
The dataset was obtained from **OpenCity**, based on data from the Ministry of Road Transport and Highways (MoRTH), Government of India.

## Tools Used

- Microsoft Excel
- Power Query
- MySQL Workbench
- GitHub

## Data Cleaning Performed

The following data preparation steps were performed:

- Removed unnecessary serial number columns.
- Removed ranking columns that were not required for analysis.
- Removed blank rows.
- Removed percentage-share rows from the collision dataset.
- Removed the total row from the collision dataset.
- Verified and corrected data types for numerical columns.
- Retained the required accident and fatality measures for analysis.
- Preserved the original year-wise accident and fatality values.
- Prepared separate cleaned datasets for accidents, fatalities, and collision types.

## Cleaned Datasets

This repository contains the following cleaned CSV files:

### 1. Cleaned Accidents
State-wise road accident data from 2020–2024.

### 2. Cleaned Fatalities
State-wise road fatality data from 2020–2024.

### 3. Cleaned Collisions
Road accidents classified by type of collision, including 2023 and 2024 accident, fatality, and injury information.

## Purpose

The cleaned datasets will be used for:

- Exploratory Data Analysis (EDA)
- SQL analysis
- Data visualization
- Interactive dashboard development
- Final data analytics project

## Project Status

**Task 1 – Data Cleaning & Preparation: Completed**
