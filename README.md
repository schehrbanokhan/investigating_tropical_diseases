# How has climate change effected the spread of Malaria, Yellow Fever and Leprosy in the World

The focus of this project was to understand the correlation between climate change and spread of diseases like Malaria, Yellow Fever and leprosy. 

The proposal question was as follows:
Does the expanding temperate zone (global warming) influence the occurrence of tropical diseases?
What is the northern most and southern most latitude of the disease occurance.

### Approach:
The data was accessed the API of:
1. National Oceanic and Atmospheric Administration to extract historical temperature trend
2. World Health Organization disease to extract disease occurance, country of occurance
3. Google developers tables to get every single country and its longitude and latitude

The ETL was performed in Python Library Pandas and is part of the repo.

The database was run on MongoDB and the visualizations were made with Mapbox. This website is not being hosted online however inorder to run this do the following:

1. Clone the repo locally
2. Using terminal navigate to to this cloned repo
3. Type into terminal "python3 app.py". This will generate an http link locally, copy the link and open it in browser
4. In a new terminal window type sudo mongod. this will prompt you to type password. Type the computer password. This will run the MongoDB database

Some screenshots of the website are as follows:
![HTML](https://github.com/schehrbanokhan/investigating_tropical_diseases/blob/master/Screen%20Shot%202019-04-14%20at%202.52.10%20PM.png?raw=true)

![second](https://github.com/schehrbanokhan/investigating_tropical_diseases/blob/master/Screen%20Shot%202019-04-14%20at%202.53.01%20PM.png?raw=true)
