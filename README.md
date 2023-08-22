# Drillhole_Geospatial_Attribute_Missing_Values_Inputation

### Challenge : Filling nulls Values

**Missing data is a common issue and we often get nulls in operational data from mining sites.**

**The goal of this task is to fill nulls in length and reading columns of the given geospatial drillhole data.**

There are three CSV files usually provided to us:

The index.csv file contains unique sensor ID and the geo indexes associated with the subject sensor ID. 
area_index_1 covers an area of 0.74 square km, area_index_2 covers an area of 5.16 square km and area_index_3 covers an area of 36.13 square km. 

Those unique indexes are determined by the location coordinates of the sensor (https://h3geo.org/).
If two IDs share the same index, it means their coordinates are inside the same area covered by that particular index.


The distance.csv file contains the sensor ID, the neighbor sensor ID and the distance between two sensors. 


The attributes.csv file contains the sensor ID, length and reading information of the subject sensor.


The reading is proportional to the length and nearby sensors share similar design in terms of length. 


Please come up with algorithm to fills nulls in the dataset by leveraging those given data and information.
