# GoBike Dataset Exploration

#### by Abdullah Elsayed

## Dataset

> This dataset has information about trips for Ford FoBike service. All the trips have taken place in February 2019.

The dataset can be downloaded from here <a href="bikeshare.com/data/">GoBike Dataset</a>

### Dataset attibutes

<ul>
    <li>duration_sec: Trip Duration (seconds)</li>
    <li>start_time: Start Time and Date</li>
    <li>end_time: End Time and Date</li>
    <li>start_station_id: Start Station ID</li>
    <li>start_station_name: Start Station Name</li>
    <li>start_station_latitude: Start Station Latitude</li>
    <li>start_station_longitude: Start Station Longitude</li>
    <li>end_station_id: End Station ID</li>
    <li>end_station_name: End Station Name</li>
    <li>end_station_latitude: End Station Latitude</li>
    <li>end_station_longitude: End Station Longitude</li>
    <li>bike_id: Bike ID </li>
    <li>user_type: User Type (Subscriber or Customer)</li>
    <li>member_birth_year: Member Year of Birth</li>
    <li>member_gender: Member Gender</li>
    <li>bike_share_for_all_trip: Boolean</li>
</ul>

### Exploration goals

> In our exploration we are going to focus on finding the factors the affect the number and duration of the rides. In the following list we stated the features that we will be using during our investigation.

<ul>
    <li>duration_sec</li>
    <li>start_time</li>
    <li>end_time</li>
    <li>start_station_name</li>
    <li>end_station_name</li>
    <li>user_type</li>
    <li>member_birth_year</li>
    <li>member_gender</li>
</ul>

### Data cleaning

> We have done the operations listed below inorder to clean our data

<ul>
    <li>Drop unwanted columns</li>
    <li>Drop missing values</li>
    <li>Delete any duplicated rows</li>
    <li>Convert data types</li>
    <li>Inverstigate member_birht_year and drop invalid data values</li>
    <li>Change duration_sec from seconds to minutes</li>
    <li>Change member_birth_year to member_age</li>
    <li>Add new column for age groups</li>
</ul>

## Summary of Findings

### Most of the users are subscribers

> We found that almost 90 of the users are subscribers.

### Big gap in genders

> From our investigation on gender, we can clearly see that males have the biggest share of trips. This might indicate that marketing campainges do not target females. Also, it might indicate that females did not find the service good for them. We can solve this through survays to see what we can afford for them to make the service better.

### GoBike is most likely used by workers

> People tend to make trips more on working days. Also, we found that people make trips in the morning and evening. This indicate that people user the service to go to work and go back from work. Futhermore, from our investigation on age, we found that the service is populer amoung people with age from 20 to 50. This age is the age of working people. Therefore, from all these finding we can conclude that the service is very popular amoung working people and these findings might indicate that most people use it only go to work or go back from work to home. We can solve this issue by trying to target other groups in marketing campainges.

### Age and trip duration

> Our exploration on age did not indicate that there is any relarionship between age and trip duration. We found that people below 20 and people with age from 60 to 70 take longer trips than other age groups. All other groups take trips with almost the same duration.

## Key Insights for Presentation

> In the persentation we are going to create a facted graph for the percentage of ride made by the different genders and a box graph for the relationship between genders and duration of the trip. In our exploration these graphs are separated in different sections. Also, we are going to make a facted graph for the freq. by hour, freq. by day graphs, and Freq. by age group. These graphs are also separated in our exploration.
