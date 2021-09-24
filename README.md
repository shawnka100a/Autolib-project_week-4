# Autolib-project_week-4
Business Understanding
	Business Overview
Paris, together with the Île-de-France region, has an overall population of more than ten million inhabitants. It is estimated that there are around 330 cars per 1,000 inhabitants, while the average daily use of each car is up to 4 kilometres . In order to fulfil France's commitment to reduce greenhouse gas emissions by 20% by 2020,there was a need to reduce traffic congestion along with the number of privately-owned cars (which are parked the vast majority of the time) and to search for more affordable and sustainable mobility alternatives.
After the great success of the “Velib” bike-sharing program, the former Socialist mayor, Bertrand Delaone, proposed the implementation of another 'individual transport' option for people who don't find themselves in need of a vehicle regularly, but may want to use a vehicle once in a while. His aspiration was to introduce a mobility solution that covers a coherent territory in terms of density and variety of land use and travel needs. The municipalities of the region were consulted and joined into the public institution 'Joint Association Autolib' to launch consultations with private companies about a public electric car-sharing program. During the initial development of studies and research, there was a lot of scepticism about this project. Still, in 2010, a competition on solutions for the realization of such a project was published and the company Bolloré, which offered the best service package with lower rates and a more humane approach (based on the presence of more than 800 agents and ambassadors serving the project), won over two other bids.
Business Objective
The main objective of this report is Identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018.

Business Success Criteria
the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris so as to optimise the working and operations of the electric vehicle company.
Assessing the Situation
Resource Inventory
Datasets:
Autolib dataset [Link]
Software( Github, Google Collaboratory, Python, IRA Kanban board )
Assumptions
The data provided is correct and up to date
Constraints
 Some columns within the dataset were not useful for the analysis.

Data Mining Goals
Our data mining goals for this project are as follows:
Finding What is the most popular hour for returning cars?
Investigating which postal code is the most popular for picking up Blue cars.
Finding which station is the most popular?



Data Mining Success Criteria
Our success criteria will be measured by the following criteria;
We target  addresses with the highest amount of data used within the period when data was collected.
	
	
Data Understanding
Data Understanding Overview
For this project, we are using the availed dataset by the company. These datasets are
Autolib dataset - This dataset gives the description of our main dataset, it has all columns to be used for our analyses 

Data Description
We have one dataset available for this project. A detailed description of the dataset is provided as follows:
Autolib dataset - This dataset contains the addresses within the Ile-de-France region. It consists of 25 columns;  These columns outline the details of different car charging stations such as the rental status of a car, the time it's being operated in a day, the most popular hour for car sharing within a given day e.t.c. For this dataset, we got 5000 entries.



Verifying Data Quality
The dataset had no missing values. There were also no known data errors in the datasets however we had some ambiguous columns with no meaning to our analysis hence we omitted them within the data cleaning phase.

Data Preparation 
These are the steps followed in preparing the data 
Loading Data 
Loaded the datasets from the CSV and then created a google collaboratory database from them.

Cleaning of the Datasets
After loading the data, we  cleaned it by removing irrelevant columns. 
Analysis
During our analysis, we were able to determine that 4pm and 7pm were the hours with the most demand for car sharing services.8 Avenue de la Porte de Montrouge was also found to be the most popular station for the electric cars.Lastly, the 15th arrondissement of Paris was the postal code with most inclination towards picking Blue cars.

The above analysis was done using python(my ipython notebook link …….). The full analysis can be found on my github.[https://github.com/shawnka100a/MTN-infrastructure-upgrade.]

Recommendations
From our analysis, we would recommend that autolib should engage in providing more car sharing services within the hours with more passenger traffic(16H00 and 19H00). This will enable better customer experience as well as increasing revenue for the company.
