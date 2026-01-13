Trash Haulers: Missed Pickup Analysis (Team Incedibles)
Project Overview

This Week 10 group project at Nashville Software School analyzes missed trash pickup service requests from hubNashville, Metro Nashville Government’s customer service platform.
Working as part of a 4-member team (The Incedibles), we evaluated contractor performance, calculated liquidated damages, and explored operational and geographic patterns using real municipal data.
The project simulates a real-world government analytics problem, requiring data cleaning, business-rule interpretation, collaboration, and clear communication of findings.

Business Problem
Under Metro Nashville’s contract with Red River Waste Solutions, repeated service failures result in financial penalties:
The first missed pickup at an address → no fine
Repeated missed pickups → financial penalties
Chronic issues can trigger significant damages

Our task was to:
Identify valid missed trash pickups
Calculate total damages owed
Evaluate alternative fine calculation methods
Provide insights for oversight and future policy decisions

Fine Calculation Method Used
We evaluated multiple fine structures and implemented Method 1, as proposed by the city:
Method 1 (Used in this Analysis):
If 3 or more missed pickups occur within 180 days at the same address
A $1,500 fine is applied
A new fine is triggered for every additional set of three missed pickups within the same six-month window

Key Analysis Questions
What is the total amount of damages owed due to missed pickups?
What other complaint types exist in the data?
How does contractor performance compare to Metro crews?
How much does each trash hauler owe?
Which routes and addresses experience the most missed pickups?
What geospatial patterns emerge across Nashville?

Geospatial Analysis
Using location-based data, we explored:
Hotspots of repeated missed pickups
Geographic clustering by route and hauler
Visual insights to support oversight and accountability

Key Skills & Concepts Applied
Data cleaning and validation
Group collaboration and task planning
Exploratory and geospatial analysis
Communicating insights from messy, real-world data

Tools & Technologies
Python
Pandas
Jupyter Notebook
Geospatial visualization
Data cleaning & transformation
