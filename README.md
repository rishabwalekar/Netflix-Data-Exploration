🎬 Netflix Content Analysis (Python EDA Project)

This project performs exploratory data analysis on the Netflix dataset to understand platform content distribution, audience targeting, release patterns, and global production trends.

The analysis covers 8,807 Netflix titles including Movies and TV Shows using Python data analysis and visualization libraries.

📂 Dataset Overview

Total records: 8,807 titles

Columns include:

Title, Type (Movie / TV Show)

Director, Cast

Country

Release Year

Date Added to Netflix

Rating

Duration

Genres (listed_in)

Description 

Netflix_Case_Study

🧹 Data Cleaning & Pre-Processing

Performed multiple real-world cleaning steps:

Replaced missing values:

Director → "Unknown director"

Cast → "Unavailable"

Country → "Unknown country"

Converted date_added to datetime

Fixed incorrect duration values for specific records

Handled missing dates using latest available date

Split multi-value columns (cast, director, country, genre) into normalized tables

Merged transformed datasets for advanced analysis 

Netflix_Case_Study

📊 Exploratory Data Analysis
🎥 Movies vs TV Shows

Movies: 6,131

TV Shows: 2,676

➡️ Netflix contains significantly more Movies than Shows 

Netflix_Case_Study

🔞 Content Rating Distribution

Most common ratings:

TV-MA — 3,207

TV-14 — 2,160

TV-PG — 863

R — 799

PG-13 — 490

➡️ Platform is mainly targeted toward mature audiences 

Netflix_Case_Study

🌍 Top Content Producing Countries

Top 10 countries by content:

United States — 2,818

India — 972

United Kingdom — 419

Japan — 245

South Korea — 199

Canada — 181

Spain — 145

France — 124

Mexico — 110 

Netflix_Case_Study

🎭 Most Popular Genres

Top genres on Netflix:

Dramas & International Movies

Documentaries

Stand-Up Comedy

Comedies & Dramas

Kids TV & Family Content 

Netflix_Case_Study

📅 Release Trend Analysis
Best Month to Release Content

Highest movie releases: July (565 titles) 

Netflix_Case_Study

Best Week to Release Content

Peak movie release week: Week 1 (316 titles) 

Netflix_Case_Study

⏳ Time Gap Between Release & Netflix Upload

Calculated number of days taken for a movie to appear on Netflix after release.

Most common delay: ~ 334 days (~11 months) 

Netflix_Case_Study

➡️ Netflix typically adds movies about a year after theatrical release.

📈 Key Insights

Netflix focuses heavily on Movies rather than TV Shows

Majority content targets mature audiences

US and India dominate content production

July is the most common release month

Netflix usually acquires movies after ~1 year of release

International & Drama content drives the catalog

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

🎯 Project Outcome

This project helps understand Netflix content strategy including:

Audience targeting

Global expansion

Content acquisition timing

Genre distribution trends
