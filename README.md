# SqlAlchemy-Challenge

# In this repository, you will find the following analyses:

## Step 1 - Climate Analysis and Exploration

### Using Python and SQLAlchemy I conduct a basic climate analysis and data exploration of my climate database (hawaii.sqlite) which contains temperature and precipitation data from 9 weather collection stations across the Hawaiian islands.

### Queries:

#### 1. Retrieve the last 12 months of precipitation data, plot bar graph of distribution and print summary statistics.

#### 2. Retrieve the total number of collection stations in the dataset, determine which station has been most active.

#### 3. Retrieve the last 12 months of temperature observation data (TOBS) for the most active station. Plot results on a histogram.


## Step 2 - Climate App

### Using Flask, I designed an API based on the queries that I just developed.

### Available Routes:

### /api/v1.0/precipitation

#### Queries for and displays date and precipitation values in json format

### /api/v1.0/stations

#### Queries for and displays all station names in json format

### /api/v1.0/tobs

#### Returns last year of temperature data for the most active station

### /api/v1.0/start_only/

#### Define start date which provideds TMIN, TMAX, TAVG for dates greater than or equal to provided start date

### /api/v1.0/start/end/

#### Define start/end page which provideds TMIN, TMAX, TAVG for dates between provided end and start dates
