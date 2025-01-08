# Water Quality and Infrastructure Analysis

This project focuses on analyzing water quality data, infrastructure improvements, and employee perfomance for water sources in various locations. The project uses SQL to join and filter data accross multiple tables, identifyig problematic sources, and track project progress.

![Project Overview](/Maji_Ndogo.png)

## Project Overview

The analysis is centered on?

- Evaluating water sources based on pollution results.
- Identifying infrastructure needs for various water sources types
- Tracking employee data to assess improvement efforts
- Generating recommendations for improvement (e.g. installing filters, diagonising infrastructure issues, etc)

## Database Structure
The project uses the following tables:


-**`visits`**: Contains information on visits to each other water source, including queue times and assigned employees.
-**`well-pollution`**: Tracks pollution results for well water sources.
-**`water_source`**: Stores metadata on each water source including type and population served.
-**`location`**: Stores location-specific information including town, province and address.
-**`Project-progress`**: Tracks improvement for each source including status an comments.

## Key Features

1. **Project Tracking**: Automatically updates improvement recommendations based on water quality results and queue times.
2. **Employee Performance**: Monitors employee perfomance by tracking discrepancies between auditor and surveyor assessments.
3. **Infrastructure Recommendations**: Generates specific infrastructure improvements actions based on data (e.g, installing additional taps for long queues).

## How to Run the Project

1. Import the SQL file provided in the '\sql' directory.
2. Populate the database with sample data, following the instructions in 'data.loading.sql'.
3. Excecute the query files to generate views, track progress and analyze data.

## Access the Full Documentation

Dataset was provided by ALX [Project Documentaion](https://alxafrica.com)
