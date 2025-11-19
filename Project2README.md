Earthquake Web Scraping & Data Analysis Project

This project scrapes earthquake data from five different CSV endpoints of the USGS FDSN Event Web Service and analyzes global M4.5+ earthquakes from 2020, 2021, and 2022.
The project includes:
	•	Scraping data from 5 different USGS CSV query URLs
	•	Cleaning and combining the data using pandas
	•	Creating new columns (year and depth category)
	•	Answering four research questions
	•	Producing Seaborn plots with labels and styling

Data Source

https://earthquake.usgs.gov/fdsnws/event/1/

File in this repository:
Project#2Part2.ipynb
README.md

Research Questions Answered
	1.	Number of M4.5+ earthquakes per year
	2.	Comparison of magnitude distributions (2020–2022)
	3.	Relationship between depth and magnitude
	4.	Shallow vs deep earthquakes (counts + average magnitude)

Summary of My Results
	•	2021 had the highest number of earthquakes (8,922).
	•	Magnitude ranges across all years looked very similar.
	•	Depth vs magnitude did not show a strong pattern.
	•	Shallow earthquakes (<70 km) were far more common (18,686) than deep ones (4,463).
	•	Average magnitudes were almost identical between shallow and deep events (4.8).

Sources (where I learned the code techniques)
	•	https://earthquake.usgs.gov/fdsnws/event/1/#methods
	•	https://requests.readthedocs.io/en/latest/user/quickstart/#errors-and-exceptions
	•	https://pandas.pydata.org/docs/user_guide/io.html#reading-from-a-buffer
	•	https://pandas.pydata.org/docs/reference/api/pandas.concat.html
	•	https://pandas.pydata.org/docs/user_guide/groupby.html#aggregation
	•	https://seaborn.pydata.org/generated/seaborn.barplot.html
	•	https://seaborn.pydata.org/generated/seaborn.histplot.html
	•	https://seaborn.pydata.org/generated/seaborn.scatterplot.html
	•	https://matplotlib.org/stable/gallery/lines_bars_and_markers/bar_label_demo.html
	•	https://stackoverflow.com/

  Author

Alexandra Lawler
