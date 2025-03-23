# -Processing-Map-Data-with-Metadata
A Java-based solution to process and analyze location data using Streams, SQL, and Spring Boot.

📂 Project Overview
This project processes location-based data by merging JSON files, analyzing metadata, and extracting insights. It is implemented using four different approaches:

1️⃣ SQL-Based Approach → Uses SQL queries for data processing.
2️⃣ Spring Boot Backend → A REST API for managing location data.
3️⃣ Java Streams Approach → Uses Java Streams & HashMap for functional programming.
4️⃣ HashMap-Based Approach → Uses HashMap for efficient lookups and data aggregation.

🛠 Features Implemented
✅ Merge Location & Metadata → Combines data from two JSON files.
✅ Count Valid Locations → Groups locations by type.
✅ Identify Invalid Locations → Filters incomplete or missing data.
✅ Calculate Average Rating → Computes the average rating per type.
✅ Find Highest & Lowest Reviewed Locations → Finds locations with max/min reviews.
✅ Top 3 Most Reviewed Locations → Sorts and retrieves top-reviewed locations.
✅ Filter Below Average Locations → Identifies locations with below-average ratings.
✅ Find Locations with >500 Reviews → Filters based on review count.
✅ Count Locations by Review Category → Groups locations based on review range.

🛠 Tech Stack
Java 17

Spring Boot (For Backend Implementation)

SQL & MySQL (For SQL-Based Approach)

Java Streams & HashMap (For Functional Approach)


📦 Location-Data-Processor
 ┣ 📂 SQLApproach/
 ┃ ┣ 📜 Location.sql
 ┃ ┣ 📜 Metadata.sql
 ┃ ┣ 📜 Queries.sql
 ┣ 📂 SpringBootBackend/
 ┃ ┣ 📜 LocationController.java
 ┃ ┣ 📜 LocationService.java
 ┃ ┣ 📜 MetadataRepository.java
 ┣ 📂 StreamsApproach/
 ┃ ┣ 📜 Location.java
 ┃ ┣ 📜 Metadata.java
 ┃ ┣ 📜 MapDataProcessor.java
 ┣ 📂 HashMapApproach/
 ┃ ┣ 📜 Location.java
 ┃ ┣ 📜 Metadata.java
 ┃ ┣ 📜 HashMapProcessor.java
 ┣ 📜 README.md



🚀 How to Run?



1️⃣ Using Java Streams Approach
javac StreamsApproach/MapDataProcessor.java
java StreamsApproach.MapDataProcessor



2️⃣ Running Spring Boot Backend
cd SpringBootBackend
mvn spring-boot:run



3️⃣ SQL Approach
Run SQL scripts inside the SQLApproach folder.



4️⃣ HashMap-Based Approach
javac HashMapApproach/HashMapProcessor.java
java HashMapApproach.HashMapProcessor
