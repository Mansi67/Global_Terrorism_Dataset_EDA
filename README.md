# **Global Terrorism Database EDA**
The Global Terrorism Database (GTD) has loads of information about terrorist activities across many years worldwide. But, there's a need to dive deeper into this data. We want to do a detailed study, find out trends, and see patterns in how terrorism happens. Our aim is to understand when and where attacks occur most, the ways they happen, who they target, and how different terrorist groups operate. By using data analysis techniques, we hope to get useful insights. These insights will help make better security plans, create effective policies, and find ways to deal with the changing challenges of global terrorism.
Our main goal from studying the Global Terrorism Database (GTD) is to make the world safer and better prepared to handle terrorism. By understanding the data, we want to improve security plans and make smarter decisions for dealing with terrorism. The aim is to create strong strategies and work together globally to keep communities and countries safe from the threats posed by terrorism.

# Data Description
The Global Terrorism Database (GTD) is a comprehensive dataset that collects information on terrorist incidents worldwide. It is maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism (START) at the University of Maryland.
The GTD defines a terrorist attack as the threatened or actual use of illegal force and violence by a nonstate actor to attain a political, economic, religious, or social goal through fear, coercion, or
intimidation.
## Dataset Overview:
**Source:** The GTD collects data from open-source information, including media reports, government documents, and other reliable sources.
**Format:** The dataset is typically available in a structured format, such as CSV, containing various fields capturing details about each terrorist incident.
**Scope:** It covers terrorist incidents globally, spanning multiple years and providing information on the nature of attacks, perpetrators, targets, locations, and casualties.

**Dataset contains info about over 180000 terror attacks throughout the world occurring between 1970 - 2017. The dataset contains 135 columns out of which 20 have been used in this EDA project.**

# Analysis Approach
Exploratory Data Analysis (EDA)
**Data Exploration:** Begin by exploring the dataset's structure, examining data types, distributions, and summary statistics of key variables.
**Visualizations:** Create visualizations (such as histograms, bar plots, and maps) to understand the distribution of terrorist incidents across time, regions, and attack types.

# Libraries and Tools Used
Python serves as the primary programming language for data manipulation, analysis, and visualization due to its extensive libraries. Pandas is used for loading, cleaning, and exploring the dataset, performing operations on structured data. Matplotlib and Seaborn are used for data visualization. Geopandas is used for geospatial data visualization and analysis.

# Key Findings 
1. Middle East & North Africa and South Asia are most attacked regions by terrorists. Iraq in Middle East and Afghanistan in South Asia are most hit countries. 
2. Iraq is the country with maximum number of terrorist attacks in 47 years followed by Pakistan and Afghanistan.
3. The number of attacks were max in 2014 with 16,903 attacks all over the world.
4. Explosion is the main type of attack in the terrorist attacks. After Explosives, Armed Assaults are the next most used attack type.
5. The primary targets of terrorists are Private Citizens & Property, Military, Police, Government and Businesses.
6. Taliban has made most number of attacks among all the terrorist organisations, more than 7000 attacks. ISIL comes on second position with approx 6000 attacks.
7. Speaking of casualities ISIL has caused most number of casualities followed by Taliban. Terrorist group Boko Haram has also caused major casualities.
8. Top 10  terror groups all over the world in recent years are:
   Taliban, Al-Shabaab, New Peoples Army, CPI- Maoists, Tehrik-i-Taliban, ISIL, Boko Haram, Houthi Extremists(Ansar Allah) and Kurdistan Workers' Party. Taliban and Al-Shabaab are on a rise.
9. Most number of suicide attacks are executed in Iraq and Afghanistan.
10. Australasia & Oceania has seen least number of attacks as recorded in database.






