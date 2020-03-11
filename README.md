# Climate Change Detection Using Map Reduce
Submitted as a part of DATA SCIENCE AND BIG DATA ANALYTICS Course Requirement (15IT423E)

# ABSTRACT
Big Data is a term that refers to a collection of large amounts of data which requires new technologies to get value, reveal patterns, trends, and associations from it by analysis. In every aspect of human life, weather has a lot of importance. It has a direct impact on each part of human society or human beings. Accurate analytics of weather collecting, storing and processing a large amount of weather data is necessary. So, a scalable data storage platform and efficient or effective change detection algorithms are required to monitor the changes in the environment. Traditional data storage techniques and algorithms are not applicable to process the large amount of weather data. In the proposed system, a scalable data processing framework that is Map-Reduce is used with a climate change detection algorithm which is Spatial Cumulative Sum algorithm and Bootstrap Analysis algorithm. The large volume of weather data is stored on Hadoop Distributed File System (HDFS) and Map-Reduce algorithm is applied to calculate the minimum and maximum of climate parameters.Thus the aim of this project is to perform Spatial Autocorrelation based climate change detection algorithm to monitor the changes in the climate of a particular city of India. 

# METHODOLOGY 
Map-Reduce is a process which will be work in three steps, namely map, shuffle, and reduce. The mapper's job is to process the input data in map stage. In Hadoop file system, the input data is in sort of file and is collected from various weather sites. And the reducer will take the output from the Map as an input and combined that data into a set of tuples.  
# IMPLEMENTATION
A big climatic data is reduced with Hadoop MapReduce framework. Proposed Spatial Cumulative Sum algorithm is used to monitor the day wise changes in the climate from many years. MapReduce algorithm is used to create a table also.
# CONCLUSION
The traditional or existing systems which processes millions of records is a time consuming process. So here Hadoop with Map-reduce, weather data can be analyzed effectively. Map reduce is a framework which is parallel and distributed systems across large dataset. Using Map-Reduce with Hadoop helps in removing scalability issues. This technology which is used to find huge datasets has the potential for significant enhancement to analyze weather. The major advantage of Map-Reduce with Hadoop framework speeds up the processing of data, where the volume of data is increasing every day
# REFERENCES
This assignment is an implementation of the paper https://www.sciencedirect.com/science/article/pii/S004579061730811X
1. Priyanka More,Sunita Nandgave,Ms. Megha Kadam," Climate Change Detection using Hadoop with MapReduce" International Journal of Innovative Research in Computer and Communication Engineering Vol. 7, Issue 3, March 2019
2. Gunasekaran Manogaran, Daphne Lopez, “Spatial cumulative sum algorithm with big data analytics for climate change detection”, Computer and
Electrical Engineering, 2017 Elsevier ltd
3. Priyanka Chouksey, Abhishek Singh Chauhan, “A Review of Weather Data Analytics using Big Data” International Journal of Advanced
Research in Computer and Communication Engineering ISO 3297:2007 Certified Vol. 6, Issue 1,PP 130-152,January 2017
4. Mr. Sunil Navadia, “Weather Prediction: A novel approach for measuring and analyzing weather data”, IEEE International conference on ISMAC-2017 
5. Ye Ding, Yanhua Li, “Detecting and Analyzing Urban Regions with High Impact of Weather Change on Transport”, IEEE Transactions on Big
Data -2016 
