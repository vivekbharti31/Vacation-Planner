# Vacation-Planner
Vacation Planner is a system which leverages Big Data technologies and Machine Learning techniques to generate data-driven recommendations of hotels/resorts and places for users based on other users with similar tastes.  

The system uses Spark for data handling and transformations. Since the system uses big data technologies, it can handle large volumes of data. To make the system scalable and robust, we have used NYU’s HPC, a distributed environment to handle data. The system uses `User-based Collaborative Filtering` to get recommendations. The system shows it’s top 10 recommendations to the users and also queries Airfare Reports to provide the average airfare for all the predicted destinations to help the user make their final decision. We also use R and Tableau to generate impactful visualizations.

#### Instructions:
* To view the results and outputs, the .json file can be imported into Apache Zeppelin.
* The file `Spark Code - Vacation Planner` contains a text version of the above zeppelin notebook.
