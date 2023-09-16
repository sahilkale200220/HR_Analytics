# HR Analytics Dashboard with Power BI
## Overview
This repository contains a Power BI project that focuses on HR Analytics. The project aims to provide insights into employee presence, sick leave, and work from home trends. The primary goal is to help HR professionals understand the possible reasons behind these trends. The dashboard has been designed to automatically update when new data for a different month is added. Additionally, an automated email notification system has been implemented to alert HR when employee presence falls below 70%.

## Table of Contents
1. Introduction
2. Features
3. Requirements
4. Usage
5. Dashboard Overview
6. Data Sources
9. Automation


## Introduction
HR Analytics plays a crucial role in understanding employee behavior and making data-driven decisions. This Power BI project provides a visually appealing and interactive dashboard to explore HR-related data. It allows HR professionals to gain insights into employee presence percentages, sick leave statistics, and work from home trends.

## Features
   1. **Dynamic Dashboard:** The dashboard is designed to automatically update when new data for a different month is added to the dataset.

   2.** Automated Email Alerts:** An automated email notification system sends alerts to HR when the employee presence percentage falls below 70%.

   3. **Data Visualization:** The project uses various data visualization techniques such as charts and graphs to present the data in a clear and concise manner.

## Requirements
To run this Power BI project, you need the following:

**Power BI Desktop**: Download and install Power BI Desktop from here.

**Data:** You should have access to HR-related data in a compatible format (e.g., CSV, Excel) to populate the dashboard.



## Usage
To use this Power BI project:

Open the saved Power BI project file in Power BI Desktop.

Refresh the data to update the dashboard with the latest HR data.

Explore the dashboard to gain insights into employee presence, sick leave, and work from home trends.

## Dashboard Overview
The dashboard provides several key visualizations, including:

1. Employee Presence Percentage Trend
2. Sick Leave Statistics
3. Work from Home Trends
4. Employee Details
These visualizations help HR professionals track and analyze employee behavior and identify potential areas of concern.

## Data Sources
The HR data used in this project can be from various sources such as HRIS systems, spreadsheets, or databases. Ensure that the data is in a structured format compatible with Power BI.

## Automation
To set up automated email notifications for employee presence below 70%:

Create a scheduled task or use Power Automate (formerly known as Flow) to periodically run a script or query that checks employee presence percentages.

Configure the script or query to send an email to HR when presence falls below 70%.

Ensure that the script or query has access to the updated HR data.

Customize the email template and recipient list as needed.
