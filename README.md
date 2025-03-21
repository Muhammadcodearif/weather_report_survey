# weather_report_survey
This is the Global Weather Repository Dataset — your comprehensive source for daily weather data from countries and capital cities worldwide.

This dataset captures a wide range of features that represent current weather conditions in various locations.

Features of the Dataset: The dataset includes key variables such as temperature, humidity, precipitation, wind speed, and atmospheric pressure. These features provide a detailed understanding of the weather patterns affecting each region.

Global Coverage of the Dataset: With data from countries and capital cities around the world, the dataset offers a global perspective on weather trends and allows for comparisons between climates across different regions.

Practical Uses of the Dataset: This dataset is an invaluable resource for gaining deep insights into climate conditions, useful for developers, researchers, and data scientists studying weather patterns and climate change.
# Complete Overview of Dataset
This Dataset consists of 25,612 rows and 41 columns.

There are a total of 30 numeric columns present in the Dataset.

There are a total of 11 categorical columns present in the Dataset.

No missing values are present in the Dataset.

No duplicates are present in the Dataset.

There are 205 unique values in the Country column.

There are 248 unique values in the location_name column of this Dataset.

In the Country column, some unique values are not standardized (e.g., Colombia, Turkey, Poland, Guatemala).
# Import Libraries
About Libraries Used:
1. Pandas: It is a powerful library used for data manipulation and analysis
It is particularly useful for working with structured data like tables or spreadsheets ##### 2. Numpy: It is a Fundamental package for numerical computations in Python.
It Supports multi-dimensional arrays and matrices and Provides high-performance tools for working with these arrays ##### 3. Seaborn: It is a statistical data visualization library
It Simplifies the process of creating informative and attractive visualizations It also includes built-in themes and color palettes for creating Visually appealing plots ##### 4. Matplotlib: It is the foundational library which is used for creating static, animated, and interactive visualizations in Python.
It also allows to create wide variety of 2D graphs, including line. It also offers full control over the style and customization of the plots.
# Observations 1 :
There are 206 unique values present in the country column of this dataset.
The 'country' which occurs minimum in this dataset is: Afghanistan.
And The 'country' which occurs maximum in this dataset is: Zimbabwe.
There are 248 unique values in the location_name column of this Dataset.
Hence, in this Dataset there are Total 205 unique countries along with their location names present.
There are Total 205 unique countries along with their location names present in the dataset
Comprehensive Coverage: The dataset includes 206 unique countries and 248 unique location names, providing extensive global weather data.

Data Distribution Insight: The least represented country is Afghanistan, whereas Zimbabwe has the most entries, pointing out the need for balanced data collection.

Future Directions:

Enhance Data Collection: Aim to increase data representation for countries like Afghanistan.
Advanced Analytics: Further explore the climate trends of countries with extensive data using advanced analytical techniques.
Predictive Modeling: Utilize the dataset for predictive modeling and real-time analysis to support decision-making in various sectors.
# Observations 2:
According to this Dataset Highest Temperature in Celsius is present in Kuwait
The Highest Temperature in Celsius in Kuwait is 49.2 in Kuwait
And The Highest Temperature in Fahrenheit is also in Kuwait
The Highest Temperature in Fahrenheit in Kuwait is: 120.6 in Kuwait
According to this Dataset the lowest Temperature in Celsius is present in Australia in its federal capital which is Canberra.
The Minimum Temperature in Celsius is -3.7 in Australia in its federal capital which is Canberra
The Minimum Temperature in Fahrenheit is 25.3 in Australia in its federal capital which is Canberra
And The lowest Temperature in Fahrenheit is also present in Australia in its federal capital which is Canberra.
There are total 5 months when the average temperature is lowest

Ultimate Global Weather Hub

Author Introduction

Arshman Khalid
Data Scientist | Software Engineer | ex Consultant PwC | ex Senior Data Analyst Fortune 500

With over 5 years of expertise in data science and software engineering, I am dedicated to transforming complex data into actionable insights. My focus lies in predictive analytics, data strategy, and the implementation of robust machine learning models that drive measurable business outcomes. I have a track record of optimizing operations, reducing costs, and improving decision-making processes across industries. Proficient in Python, Alteryx, Power BI, and cloud platforms.

When I am not wrangling datasets, you will find me attempting to code my way to the perfect cup of coffee!

LinkedIn X GitHub Kaggle
Dataset: Context and Description

This is the Global Weather Repository Dataset — your comprehensive source for daily weather data from countries and capital cities worldwide.

This dataset captures a wide range of features that represent current weather conditions in various locations.

Features of the Dataset: The dataset includes key variables such as temperature, humidity, precipitation, wind speed, and atmospheric pressure. These features provide a detailed understanding of the weather patterns affecting each region.

Global Coverage of the Dataset: With data from countries and capital cities around the world, the dataset offers a global perspective on weather trends and allows for comparisons between climates across different regions.

Practical Uses of the Dataset: This dataset is an invaluable resource for gaining deep insights into climate conditions, useful for developers, researchers, and data scientists studying weather patterns and climate change.

Complete Overview of Dataset

This Dataset consists of 25,612 rows and 41 columns.

There are a total of 30 numeric columns present in the Dataset.

There are a total of 11 categorical columns present in the Dataset.

No missing values are present in the Dataset.

No duplicates are present in the Dataset.

There are 205 unique values in the Country column.

There are 248 unique values in the location_name column of this Dataset.

In the Country column, some unique values are not standardized (e.g., Colombia, Turkey, Poland, Guatemala).

Goals and Objectives

My goal in working with this dataset is to explore it thoroughly and gain deep insights.

The first step in this process is data cleaning and exploration to check for missing values, duplicates, and to standardize unique values.

After cleaning the data, I created various visualization plots to provide detailed insights into the dataset.

The visualizations include Count Plot, Pie Chart, Choropleth Map, 3D Animated Scatter Plot, Violin Plot, Strip Plot, Tree Map, and histograms for numeric columns, along with boxplots and count plots for categorical variables.

I used Boxplots to detect outliers.

I applied the IQR (Interquartile Range) Method to remove outliers from the dataset.

After removing the outliers, I re-visualized the Boxplots to confirm that the outliers were effectively removed.

Finally, I developed various questions and further analysis based on the insights gained from the dataset.

Kernel Version Used

Python Version Used: 3.10.14
Columns of the Dataset with Description

Column Name	Description
country	The country where the location is situated
location_name	The name of the specific location
latitude	The geographical latitude of the location
longitude	The geographical longitude of the location
timezone	The timezone of the location
last_updated_epoch	Epoch time of the last update
last_updated	The last updated timestamp
temperature_celsius	Temperature in degrees Celsius
temperature_fahrenheit	Temperature in degrees Fahrenheit
condition_text	Text description of the weather condition
wind_mph	Wind speed in miles per hour
wind_kph	Wind speed in kilometers per hour
wind_degree	Wind direction in degrees
wind_direction	Text description of wind direction
pressure_mb	Atmospheric pressure in millibars
pressure_in	Atmospheric pressure in inches
precip_mm	Precipitation in millimeters
precip_in	Precipitation in inches
humidity	Humidity percentage
cloud	Cloud cover percentage
feels_like_celsius	Apparent temperature in degrees Celsius
feels_like_fahrenheit	Apparent temperature in degrees Fahrenheit
visibility_km	Visibility in kilometers
visibility_miles	Visibility in miles
uv_index	UV index value
gust_mph	Wind gust speed in miles per hour
gust_kph	Wind gust speed in kilometers per hour
air_quality_Carbon_Monoxide	Carbon monoxide level in air quality
air_quality_Ozone	Ozone level in air quality
air_quality_Nitrogen_dioxide	Nitrogen dioxide level in air quality
air_quality_Sulphur_dioxide	Sulphur dioxide level in air quality
air_quality_PM2.5	PM2.5 level in air quality
air_quality_PM10	PM10 level in air quality
air_quality_us-epa-index	US EPA air quality index
air_quality_gb-defra-index	UK DEFRA air quality index
sunrise	Time of sunrise
sunset	Time of sunset
moonrise	Time of moonrise
moonset	Time of moonset
moon_phase	Current phase of the moon
moon_illumination	Illumination percentage of the moon
Import Libraries

About Libraries Used:
1. Pandas: It is a powerful library used for data manipulation and analysis
It is particularly useful for working with structured data like tables or spreadsheets ##### 2. Numpy: It is a Fundamental package for numerical computations in Python.
It Supports multi-dimensional arrays and matrices and Provides high-performance tools for working with these arrays ##### 3. Seaborn: It is a statistical data visualization library
It Simplifies the process of creating informative and attractive visualizations It also includes built-in themes and color palettes for creating Visually appealing plots ##### 4. Matplotlib: It is the foundational library which is used for creating static, animated, and interactive visualizations in Python.
It also allows to create wide variety of 2D graphs, including line. It also offers full control over the style and customization of the plots.
# import libraries
import pandas as pd 
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px
# Set color palette 
sns.set_palette("Set2")  
# ignore warnings
import warnings
warnings.filterwarnings("ignore")
# Set the option to display the maximum number of rows and column
pd.set_option('display.max_columns', None)
pd.set_option('display.max_rows', None)
Display the Top 5 Rows of Dataset

# Lets have a look at the First five rows of the dataset
df=pd.read_csv('/kaggle/input/global-weather-repository/GlobalWeatherRepository.csv')  
df.head()
country	location_name	latitude	longitude	timezone	last_updated_epoch	last_updated	temperature_celsius	temperature_fahrenheit	condition_text	wind_mph	wind_kph	wind_degree	wind_direction	pressure_mb	pressure_in	precip_mm	precip_in	humidity	cloud	feels_like_celsius	feels_like_fahrenheit	visibility_km	visibility_miles	uv_index	gust_mph	gust_kph	air_quality_Carbon_Monoxide	air_quality_Ozone	air_quality_Nitrogen_dioxide	air_quality_Sulphur_dioxide	air_quality_PM2.5	air_quality_PM10	air_quality_us-epa-index	air_quality_gb-defra-index	sunrise	sunset	moonrise	moonset	moon_phase	moon_illumination
0	Afghanistan	Kabul	34.52	69.18	Asia/Kabul	1715849100	2024-05-16 13:15	26.6	79.8	Partly Cloudy	8.3	13.3	338	NNW	1012.0	29.89	0.0	0.00	24	30	25.3	77.5	10.0	6.0	7.0	9.5	15.3	277.0	103.0	1.1	0.2	8.4	26.6	1	1	04:50 AM	06:50 PM	12:12 PM	01:11 AM	Waxing Gibbous	55
1	Albania	Tirana	41.33	19.82	Europe/Tirane	1715849100	2024-05-16 10:45	19.0	66.2	Partly cloudy	6.9	11.2	320	NW	1012.0	29.88	0.1	0.00	94	75	19.0	66.2	10.0	6.0	5.0	11.4	18.4	193.6	97.3	0.9	0.1	1.1	2.0	1	1	05:21 AM	07:54 PM	12:58 PM	02:14 AM	Waxing Gibbous	55
2	Algeria	Algiers	36.76	3.05	Africa/Algiers	1715849100	2024-05-16 09:45	23.0	73.4	Sunny	9.4	15.1	280	W	1011.0	29.85	0.0	0.00	29	0	24.6	76.4	10.0	6.0	5.0	13.9	22.3	540.7	12.2	65.1	13.4	10.4	18.4	1	1	05:40 AM	07:50 PM	01:15 PM	02:14 AM	Waxing Gibbous	55
3	Andorra	Andorra La Vella	42.50	1.52	Europe/Andorra	1715849100	2024-05-16 10:45	6.3	43.3	Light drizzle	7.4	11.9	215	SW	1007.0	29.75	0.3	0.01	61	100	3.8	38.9	2.0	1.0	2.0	8.5	13.7	170.2	64.4	1.6	0.2	0.7	0.9	1	1	06:31 AM	09:11 PM	02:12 PM	03:31 AM	Waxing Gibbous	55
4	Angola	Luanda	-8.84	13.23	Africa/Luanda	1715849100	2024-05-16 09:45	26.0	78.8	Partly cloudy	8.1	13.0	150	SSE	1011.0	29.85	0.0	0.00	89	50	28.7	83.6	10.0	6.0	8.0	12.5	20.2	2964.0	19.0	72.7	31.5	183.4	262.3	5	10	06:12 AM	05:55 PM	01:17 PM	12:38 AM	Waxing Gibbous	55
Display Discriptive Summary

# Summary Statistics
df.describe()
latitude	longitude	last_updated_epoch	temperature_celsius	temperature_fahrenheit	wind_mph	wind_kph	wind_degree	pressure_mb	pressure_in	precip_mm	precip_in	humidity	cloud	feels_like_celsius	feels_like_fahrenheit	visibility_km	visibility_miles	uv_index	gust_mph	gust_kph	air_quality_Carbon_Monoxide	air_quality_Ozone	air_quality_Nitrogen_dioxide	air_quality_Sulphur_dioxide	air_quality_PM2.5	air_quality_PM10	air_quality_us-epa-index	air_quality_gb-defra-index	moon_illumination
count	42519.000000	42519.000000	4.251900e+04	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000	42519.000000
mean	19.136300	22.138145	1.725319e+09	23.900059	75.021569	8.344324	13.432795	172.008984	1013.371105	29.924244	0.148489	0.005655	62.752393	39.762647	25.133347	77.233554	9.684924	5.741457	4.515149	12.104250	19.482102	498.306241	62.691670	12.903922	9.499331	21.602927	41.871092	1.584186	2.333145	49.742492
std	24.483356	65.806321	5.521035e+06	8.524570	15.344277	10.362704	16.676343	102.450733	6.829782	0.201538	0.640776	0.025315	24.792144	33.448259	10.149064	18.266717	2.430976	1.505551	3.304853	11.352699	18.270976	1007.029530	38.863318	24.672996	53.511570	45.705960	117.104817	0.914142	2.306881	35.054372
min	-41.300000	-175.200000	1.715849e+09	-22.900000	-9.200000	2.200000	3.600000	1.000000	971.000000	28.670000	0.000000	0.000000	2.000000	0.000000	-27.900000	-18.200000	0.000000	0.000000	0.000000	2.200000	3.600000	-9999.000000	0.000000	0.000000	-9999.000000	0.185000	0.185000	1.000000	1.000000	0.000000
25%	3.750000	-6.836100	1.720444e+09	19.500000	67.000000	4.300000	6.800000	86.000000	1010.000000	29.820000	0.000000	0.000000	44.000000	4.000000	19.500000	67.000000	10.000000	6.000000	1.000000	6.700000	10.800000	213.600000	36.000000	0.740000	0.600000	4.100000	6.900000	1.000000	1.000000	15.000000
50%	17.250000	23.320000	1.725366e+09	26.000000	78.800000	7.200000	11.500000	166.000000	1013.000000	29.910000	0.000000	0.000000	68.000000	29.000000	27.000000	80.600000	10.000000	6.000000	5.000000	10.800000	17.400000	299.700000	58.000000	2.700000	1.900000	10.730000	17.300000	1.000000	1.000000	51.000000
75%	40.400000	50.580000	1.730107e+09	29.100000	84.400000	11.600000	18.700000	259.000000	1017.000000	30.030000	0.030000	0.000000	83.000000	75.000000	31.800000	89.300000	10.000000	6.000000	7.000000	16.200000	26.100000	451.400000	84.000000	12.300000	7.030000	23.865000	39.300000	2.000000	2.000000	83.000000
max	64.150000	179.220000	1.734780e+09	49.200000	120.600000	1841.200000	2963.200000	360.000000	1080.000000	31.890000	42.240000	1.660000	100.000000	100.000000	51.200000	124.200000	32.000000	19.000000	15.400000	1845.700000	2970.400000	38879.398000	480.700000	427.700000	425.130000	1614.100000	5858.020000	6.000000	10.000000	100.000000
Dataset Info

# Dataset structure
print(f'Dataset info: {df.info()}')
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 42519 entries, 0 to 42518
Data columns (total 41 columns):
 #   Column                        Non-Null Count  Dtype  
---  ------                        --------------  -----  
 0   country                       42519 non-null  object 
 1   location_name                 42519 non-null  object 
 2   latitude                      42519 non-null  float64
 3   longitude                     42519 non-null  float64
 4   timezone                      42519 non-null  object 
 5   last_updated_epoch            42519 non-null  int64  
 6   last_updated                  42519 non-null  object 
 7   temperature_celsius           42519 non-null  float64
 8   temperature_fahrenheit        42519 non-null  float64
 9   condition_text                42519 non-null  object 
 10  wind_mph                      42519 non-null  float64
 11  wind_kph                      42519 non-null  float64
 12  wind_degree                   42519 non-null  int64  
 13  wind_direction                42519 non-null  object 
 14  pressure_mb                   42519 non-null  float64
 15  pressure_in                   42519 non-null  float64
 16  precip_mm                     42519 non-null  float64
 17  precip_in                     42519 non-null  float64
 18  humidity                      42519 non-null  int64  
 19  cloud                         42519 non-null  int64  
 20  feels_like_celsius            42519 non-null  float64
 21  feels_like_fahrenheit         42519 non-null  float64
 22  visibility_km                 42519 non-null  float64
 23  visibility_miles              42519 non-null  float64
 24  uv_index                      42519 non-null  float64
 25  gust_mph                      42519 non-null  float64
 26  gust_kph                      42519 non-null  float64
 27  air_quality_Carbon_Monoxide   42519 non-null  float64
 28  air_quality_Ozone             42519 non-null  float64
 29  air_quality_Nitrogen_dioxide  42519 non-null  float64
 30  air_quality_Sulphur_dioxide   42519 non-null  float64
 31  air_quality_PM2.5             42519 non-null  float64
 32  air_quality_PM10              42519 non-null  float64
 33  air_quality_us-epa-index      42519 non-null  int64  
 34  air_quality_gb-defra-index    42519 non-null  int64  
 35  sunrise                       42519 non-null  object 
 36  sunset                        42519 non-null  object 
 37  moonrise                      42519 non-null  object 
 38  moonset                       42519 non-null  object 
 39  moon_phase                    42519 non-null  object 
 40  moon_illumination             42519 non-null  int64  
dtypes: float64(23), int64(7), object(11)
memory usage: 13.3+ MB
Dataset info: None
Number of Numeric and Categorical columns Count

# Count numeric columns
numeric_columns_count = df.select_dtypes(include='number').shape[1]

# Count categorical columns
categorical_columns_count = df.select_dtypes(include='object').shape[1]

# Display the counts
print(f'Number of numeric columns: {numeric_columns_count}')
print(f'Number of categorical columns: {categorical_columns_count}')

# Check the shape of the dataset
print(f'Shape of the Dataset is: {df.shape}')
Number of numeric columns: 30
Number of categorical columns: 11
Shape of the Dataset is: (42519, 41)
Data Cleaning or Preprocessing

Missing Values

missing_values=df.isnull().sum()
print("Missing values:\n", missing_values)
missing_values = df.isnull().sum().sum()
# Check if there are any missing values and print the result using an f-string
if missing_values > 0:
    print(f"Missing values are present. Total missing values: {missing_values}")
else:
    print(f"No missing values are present in the Dataset.")
Missing values:
 country                         0
location_name                   0
latitude                        0
longitude                       0
timezone                        0
last_updated_epoch              0
last_updated                    0
temperature_celsius             0
temperature_fahrenheit          0
condition_text                  0
wind_mph                        0
wind_kph                        0
wind_degree                     0
wind_direction                  0
pressure_mb                     0
pressure_in                     0
precip_mm                       0
precip_in                       0
humidity                        0
cloud                           0
feels_like_celsius              0
feels_like_fahrenheit           0
visibility_km                   0
visibility_miles                0
uv_index                        0
gust_mph                        0
gust_kph                        0
air_quality_Carbon_Monoxide     0
air_quality_Ozone               0
air_quality_Nitrogen_dioxide    0
air_quality_Sulphur_dioxide     0
air_quality_PM2.5               0
air_quality_PM10                0
air_quality_us-epa-index        0
air_quality_gb-defra-index      0
sunrise                         0
sunset                          0
moonrise                        0
moonset                         0
moon_phase                      0
moon_illumination               0
dtype: int64
No missing values are present in the Dataset.
Check the Duplicates

# Count the number of duplicate rows
duplicates_count = df.duplicated().sum()

# Check if there are any duplicate rows and print the result using f-strings
if df.duplicated().any():
    print(f"Duplicates are present. Total duplicate rows: {duplicates_count}")
else:
    print(f"No duplicates are present in the Dataset.")
No duplicates are present in the Dataset.
Standardize Country Names and Displaying Unique Values

df['country'] = df['country'].apply(lambda x: 'Colombia' if x == 'كولومبيا' else x)
df['country'] = df['country'].apply(lambda x: 'Turkey' if x == '火鸡' else x)
df['country'] = df['country'].apply(lambda x: 'Poland' if x == 'Польша' else x)
df['country'] = df['country'].apply(lambda x: 'Turkey' if x == 'Турция' else x)
df['country'] = df['country'].apply(lambda x: 'Guatemala' if x == 'Гватемала' else x)

# Show the last 50 unique values
unique_countries=df['country'].nunique()
num_unique_countries=df['country'].unique()[-50:]
print(f'Num Unique countries are: {unique_countries}')
print(f'There are {num_unique_countries} unique values in the country column.')
Num Unique countries are: 205
There are ['South Africa' 'South Korea' 'Sudan' 'Spain' 'Sri Lanka' 'Suriname'
 'Sweden' 'Switzerland' 'Syria' 'Tajikistan' 'Tanzania' 'Timor-Leste'
 'Tonga' 'Trinidad and Tobago' 'Tunisia' 'Turkmenistan' 'Tuvalu' 'Uganda'
 'Ukraine' 'United Arab Emirates' 'United Kingdom'
 'United States of America' 'Uruguay' 'Uzbekistan' 'Vanuatu' 'Venezuela'
 'Vietnam' 'Yemen' 'Zambia' 'Zimbabwe' 'Colombia'
 'USA United States of America' "Lao People's Democratic Republic" 'Libya'
 'Kosovo' 'Togo' 'Malásia' 'Komoren' 'Estonie' 'Inde' 'Letonia' 'Mexique'
 'Polônia' 'Marrocos' 'Saint-Vincent-et-les-Grenadines' 'Saudi Arabien'
 'Südkorea' 'Bélgica' 'Turkménistan' 'Jemen'] unique values in the country column.
Insights about each Column

Taking Insights about the country and location name column

# Check and print the minimum and maximum values of the country column
min_country, max_country = df['country'].min(), df['country'].max()
print(f"The 'country' which occurs minimum in this dataset is: {min_country}")
print(f"The 'country' which occurs maximum in this dataset is: {max_country}")
The 'country' which occurs minimum in this dataset is: Afghanistan
The 'country' which occurs maximum in this dataset is: Zimbabwe
# Show the last 50 unique values
num_unique_location_name = df['location_name'].nunique()
print(f'There are {num_unique_location_name} unique values in the location_name column.')
# Lets check the minimum and maximum values of the id column and explore this it
min_location_name, max_location_name = df['location_name'].min(), df['location_name'].max()
print(f"The 'Location_name' which occurs minimum in this dataset is: {min_location_name}")
print(f"The 'Location_name' which occurs maximum in this dataset is: {max_location_name}")
There are 248 unique values in the location_name column.
The 'Location_name' which occurs minimum in this dataset is: 'S Gravenjansdijk
The 'Location_name' which occurs maximum in this dataset is: Zagreb
# Count unique combinations of country and location_name
country_location_count = df.groupby(['country', 'location_name']).size().reset_index(name='count')

# Lets Get the number of unique countries along with their location names
unique_countries = country_location_count['country'].nunique()

print(f"Total number of unique countries along with their location names present in the dataset are: {unique_countries}")
Total number of unique countries along with their location names present in the dataset are: 205
Observations:
There are 206 unique values present in the country column of this dataset.
The 'country' which occurs minimum in this dataset is: Afghanistan.
And The 'country' which occurs maximum in this dataset is: Zimbabwe.
There are 248 unique values in the location_name column of this Dataset.
Hence, in this Dataset there are Total 205 unique countries along with their location names present.
There are Total 205 unique countries along with their location names present in the dataset
Comprehensive Coverage: The dataset includes 206 unique countries and 248 unique location names, providing extensive global weather data.

Data Distribution Insight: The least represented country is Afghanistan, whereas Zimbabwe has the most entries, pointing out the need for balanced data collection.

Future Directions:

Enhance Data Collection: Aim to increase data representation for countries like Afghanistan.
Advanced Analytics: Further explore the climate trends of countries with extensive data using advanced analytical techniques.
Predictive Modeling: Utilize the dataset for predictive modeling and real-time analysis to support decision-making in various sectors.
Taking Insights from Temperature Celsius and Temperature Fahrenheit column

# Lets Get the country and location with the highest temperature in Celsius
highest_temp_celsius = df.loc[df['temperature_celsius'].idxmax(), ['country', 'location_name', 'temperature_celsius']]
print("Country and Location with the Highest Temperature in Celsius:")
print(highest_temp_celsius)

# Lets Get the country and location with the highest temperature in Fahrenheit
highest_temp_fahrenheit = df.loc[df['temperature_fahrenheit'].idxmax(), ['country', 'location_name', 'temperature_fahrenheit']]
print("\nCountry and Location with the Highest Temperature in Fahrenheit:")
print(highest_temp_fahrenheit)

# Lets print the overall max temperatures countries and location names
print(f"\nMaximum Temperature in Celsius: {highest_temp_celsius['temperature_celsius']}")
print(f"Maximum Temperature in Fahrenheit: {highest_temp_fahrenheit['temperature_fahrenheit']}")
Country and Location with the Highest Temperature in Celsius:
country                     Kuwait
location_name          Kuwait City
temperature_celsius           49.2
Name: 6896, dtype: object

Country and Location with the Highest Temperature in Fahrenheit:
country                        Kuwait
location_name             Kuwait City
temperature_fahrenheit          120.6
Name: 6896, dtype: object

Maximum Temperature in Celsius: 49.2
Maximum Temperature in Fahrenheit: 120.6
# Get the country and location with the lowest temperature in Celsius
lowest_temp_celsius = df.loc[df['temperature_celsius'].idxmin(), ['country', 'location_name', 'temperature_celsius']]
print("\nCountry and Location with the Lowest Temperature in Celsius:")
print(lowest_temp_celsius)

# Get the country and location with the lowest temperature in Fahrenheit
lowest_temp_fahrenheit = df.loc[df['temperature_fahrenheit'].idxmin(), ['country', 'location_name', 'temperature_fahrenheit']]
# Correct print statement to show the lowest temperature
print("\nCountry and Location with the Lowest Temperature in Fahrenheit:")
print(lowest_temp_fahrenheit)

# Lets print the overall min temperatures countries and location names
print(f"\nMinimum Temperature in Celsius: {lowest_temp_celsius['temperature_celsius']}")
print(f"Minimum Temperature in Fahrenheit: {lowest_temp_fahrenheit['temperature_fahrenheit']}")
Country and Location with the Lowest Temperature in Celsius:
country                   Mongolia
location_name          Ulaanbaatar
temperature_celsius          -22.9
Name: 40683, dtype: object

Country and Location with the Lowest Temperature in Fahrenheit:
country                      Mongolia
location_name             Ulaanbaatar
temperature_fahrenheit           -9.2
Name: 40683, dtype: object

Minimum Temperature in Celsius: -22.9
Minimum Temperature in Fahrenheit: -9.2
Observations:
According to this Dataset Highest Temperature in Celsius is present in Kuwait
The Highest Temperature in Celsius in Kuwait is 49.2 in Kuwait
And The Highest Temperature in Fahrenheit is also in Kuwait
The Highest Temperature in Fahrenheit in Kuwait is: 120.6 in Kuwait
According to this Dataset the lowest Temperature in Celsius is present in Australia in its federal capital which is Canberra.
The Minimum Temperature in Celsius is -3.7 in Australia in its federal capital which is Canberra
The Minimum Temperature in Fahrenheit is 25.3 in Australia in its federal capital which is Canberra
And The lowest Temperature in Fahrenheit is also present in Australia in its federal capital which is Canberra.
There are total 5 months when the average temperature is lowest
Taking Insights from Latitude and Longitude Column

# Lets Find the country and location with the highest latitude
highest_latitude = df.loc[df['latitude'].idxmax(), ['country', 'location_name', 'latitude']]
print("Country and Location with the Highest Latitude:")
print(highest_latitude)

# Lets Find the country and location with the highest longitude
highest_longitude = df.loc[df['longitude'].idxmax(), ['country', 'location_name', 'longitude']]
print("\nCountry and Location with the Highest Longitude:")
print(highest_longitude)
Country and Location with the Highest Latitude:
country            Iceland
location_name    Reykjavik
latitude             64.15
Name: 8032, dtype: object

Country and Location with the Highest Longitude:
country            Tuvalu
location_name    Funafuti
longitude          179.22
Name: 181, dtype: object
# Find the country and location with the lowest latitude
lowest_latitude = df.loc[df['latitude'].idxmin(), ['country', 'location_name', 'latitude']]
print("\nCountry and Location with the Lowest Latitude:")
print(lowest_latitude)
# Find the country and location with the lowest longitude
lowest_longitude = df.loc[df['longitude'].idxmin(), ['country', 'location_name', 'longitude']]
print("\nCountry and Location with the Lowest Longitude:")
print(lowest_longitude)
Country and Location with the Lowest Latitude:
country          New Zealand
location_name     Wellington
latitude               -41.3
Name: 123, dtype: object

Country and Location with the Lowest Longitude:
country               Tonga
location_name    Nuku`Aloia
longitude            -175.2
Name: 176, dtype: object
# Observations 3:
According to this Dataset the Highest Latitude is of Iceland Country
The Reykjavik which is the capital of Iceland has Highest Latitude
The Highest latitude 64.15 is of Reykjavik which is the capital of Iceland
According to this Dataset the Highest Longitude is of Tuvalu Country
The Funafuti which is the capital of Tuvalu has Highest Longitude
The Highest longitude of Funafuti which is the capital of Tuvalu is 179.22
According to this Dataset the Lowest Latitude is of New Zealand Country
The Wellington which is the capital of New Zealand has lowest Latitude
The lowest latitude -41.3 is of Wellington which is the capital of New Zealand
According to this Dataset the lowest Longitude is of Tuvalu Country
The Nuku'alofa is the capital and the chief port of the island country of Tonga has lowest Longitude
The lowest longitude Nuku'alofa is -175.2 in the capital and the chief port of the island country of Tonga
# Observations 4:
Range of last updated dates according to this Dataset are : 2024-05-16 01:45:00 to 2024-09-24 22:45:00
The Earliest Updated time according to this Dataset is: 2024-05-16 01:45:00
The Latest Updated time according to this Dataset is: 2024-09-24 22:45:00
According to this Dataset there are total 9 Month with highest humidity
In Bujumbura there is highest wind speed which is 1841.20 mph according to this Dataset
There are total Locations 967 with Full Moon
There are total 25417 Records last updated in 2024
There are total 5 Number of Month when average temperature is lowest
# Count Plot of Weather Records by Countries
About the Code of Countplot:
This plot is used for the visual representation of the top 10 countries in the dataset based on the number of weather records.
This code highlights the frequency of occurrences and make easier to compare countries directly by count of records which is shown at the top of each bar.
By creating this plot we can easily took insights about the value counts of the country column
.nlargest(10) is used to extracts the top 10 most frequent countries on which the plot is being created.
The command filtered_df = df[df['country'].isin(top_countries)] is used to filter the dataframe to include only those records where the country is in the top 10.
sns.countplot(data=filtered_df, x='country', order=top_countries) is used to create a bar plot that counts the occurrences of each country present in the Dataset.
The order=top_countries is used to ensure that the bars are displayed in the same order as the top 10 countries.
Then the loop is created which causes looping through each bar of the plot
Then add the label and the count of each Country on the Top of each Bar
These value counts is used to provide the deep insights about the value counts of country column of this Dataset
Then set the title, x-axis and y-axis label and adjust the layout
Finally Displays the plot
# Observations 5:
The Highest Number of count is of Bulgaria Country
The Bulgaria Country have 294 counts
The Lowest Number of count is of Vietnam Country
The Vietnam Country have 212 counts
The Iran, Sudan and Madagascar have the same number of counts which is 260
Similarly, Bolivia, Belgium, Thiland have same number of counts which is 259
After the Bulgaria there are Highest number of counts of Indonesia which is 263 and then Turkey which is 261
# Exploring Categorical Data with Pie Chart Subplots
About the Code of Pie chart Subplots:
The code is used to create the pie charts of four categorical columns such as moon_phase, condition_text, wind_direction, and country from the dataset.
For each column, only the top 6 categories with their percentages are shown which helps us to focus on the most important data and avoid cluttering (which causes difficulty in taking insights about the Dataset).
Pie charts provide us the way to understand easily that how thecategories are distributed.
The set the "Set2" palette which ensures that the charts are visually appealing and the different categories are easy to distinguish.
By applying this code we can generate pie charts of four categorical columns in a dataset.
The categorical columns list is then created which then used to visualize the plot
After that Subplot figures are created
axes = axes.flatten() is used to onverts the 2x2 array of subplots into a 1D list, Hence it makes easier to iterate over the subplots in the loop
Setting the Set2 color pelette is used to display the visually appealing plot
Then plot the pie chart, set the x-axis and y-axis labels and Finally Displays the plot
# Observations 6:
In the moon_phase column the highest percentage is of Waxing Gibbous Column which is 26.8%
Then after the Waxing Gibbous Column the Highest percentage is of Waxing Cresent column which is 23.6%
The Full moon has the lowest percentage which is 4.0% of the moon_phase column.
The highest percentage of wind_direction is 19.8% in E
Then The highest percentage of wind_direction is in the N which is 19.8%
The lowest percentage of wind_direction is 15.0% in Sw
After analyzing the condition_text column by creating the pie chart it is determined that highest percentage which is 39.8% is partly cloudy wheather condition and 37.8% is sunny
The Lowest percentage which is 3.7% is over cast
The Higher percentage of wheather condition is Bulgaria and lowest in Turkey, Iran, Sudan, Madagascar which is same in four of them and is 16.3%
# Taking Geospatial Temperature Insights via Choropleth Map
About the Code of Choropleth Map:
This code is used to grouped the sampling technique to ensure that each country of this Dataset represented equally on the map.
By creating the choropleth map we can easily understand that how the locations are distributed geographically.
The colors represents the temperature data across different countries.
This is especially useful when we want to analyze the regional patterns in temperature or want to visualize the spread of locations on a global level.
The hover feature provides specific details about the location names in Choropleth Map.
Firstly this code took 20 random samples of locations from each country of the dataset and then creates a choropleth map inorder to visualize the geographical distribution of these locations
After applying the sampling reset_index(drop=True) is used to reset the index of the resulting Dataframe
The choropleth map basically uses the colors to represent different regions on a map
Various parameter like hover_name, location_mode, color, title name is usedto create the plot which provide deep insights about the Dataset.
Finally by this code updates the layout and displays the plot
# Observations 7:
By Analyzing the Geo Map it is determined that the Highest Temperature in Celsius is present in Kuwait
The Highest Temperature in Celsius in Kuwait is 49.2 in Kuwait
And By Analyzing the Geo Map it is determined that the lowest Temperature in Celsius is present in Australia in its federal capital which is Canberra.
The Minimum Temperature in Celsius is -3.7 in Australia in its federal capital which is Canberra
# Tree map Visualization of Humidity and Air Quality by Country
About the Code of Tree Map:
The treemap is basically used to visualize the hierarchy present in the Data.
By applying this code I observe that each country is represented by a rectangle Hence the size of the country is average humidity.
I provide the color of each rectangle on the basis of average ozone level in the country so that we can quickly visualize the comparison of both humidity and air quality across different countries present in the Dataset.
df.groupby('country') command is used to group the dataset by the country column and after that i aggregate the data and calculate the mean for the columns which is being specified.Here, each row represents a country and the columns contain the average values for humidity and air quality pollutants
After that set various parameters for better visully appealing visulization to be shown. Finally Displays the plot
# Visualizing Numeric Columns Distributions
About the Code of Histogram:
The Histogram are commonly used to show the frequency distribution of continuous variables,to determine the distribution of columns such as temperature, humidity, pressure etc.
Adding the KDE (Kernel Density Ewstimation Line) line helps to provide a smooth curve that represent the underlying probability distribution of the data.
It also helps in understanding the shape of the distribution of the columns.
Hence, By creating the subplots, this code effectively compares multiple weather columns side by side. This is particularly useful for gaining deep insights into how different columns such as temperature, humidity, pressure are distributed across the dataset.
This code displays the multiple subplots where each subplot corresponds to a specific weather conditions present in the Dataset.
the list of column which is created in this code is basically taken to add the columns which represents the geographical data from this Dataset
After that set the rows, columns and flattens the axes and displays the plot.
