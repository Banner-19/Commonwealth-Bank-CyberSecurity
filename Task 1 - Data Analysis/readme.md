# What you'll learn
* Gain hands-on experience in data analysis, especially in the context of cyber data.
* Understand the importance of data visualization in uncovering trends and patterns.
* Learn to use Splunk, a data analysis tool, for creating dashboards and visual representations of data.
* Develop skills in interpreting data fields and identifying key insights.
# What you'll do
* Install and set up Splunk Enterprise, import the provided dataset and explore it using Splunk.
* Create a comprehensive dashboard with charts and tables to visualize fraud-related data for submission.

__NOTE:__ I used `Power Bi` for this task instead of `Splunk`. If you want to do it in `Splunk` please refer to the "Task Guide" pdf.

# Here is the background information on your task
* As a cyber security generalist at Commonwealth Bank, it is important to be aware of the increasing rate and complexity of financial fraud and the need for effective defence solutions. Financial fraud poses a significant challenge for financial institutions, and it is important for Commonwealth Bank to stay up to date with the latest fraud detection technologies and strategies to minimise risk. Protecting against and responding to fraud is a major responsibility for you and your team. By detecting and stopping fraud, the bank can protect its customers, employees and reputation while also enhancing the resilience of its financial system.

* To help with this task, you will be using a tool called Splunk to visually represent the given data. Representing data in a visual format, also known as data visualisation, makes it easier for the data analytics team to understand and gain insights. Visual data is a universal, fast and effective way to communicate information.

* You will be building a dashboard to make it easier to identify patterns and trends in the given dataset. The dashboard will provide crucial reporting and metrics information that can aid in identifying and detecting fraud. By using this dashboard, the team will be able to quickly identify any suspicious activity and take the necessary steps to prevent fraud from occurring. Overall, the goal of this task is to use data visualisation and a dashboard to make it easier to detect fraud and protect Commonwealth Bank and its customers from financial loss.

## About the dataset
* Data was collected and structured by the Fraud team. This dataset consists of payments from various customers made in different periods and amounts. The feature columns include:

* __Step:__ This feature represents the month from the start of the simulation. The steps represent four months that the simulation ran virtually.
  * 0: May
  * 1: June
  * 2: July
  * 3: August
* __Customer:__ Customer ID
* __Age:__ Categorised age
  * 0.0: <= 18
  * 1.0: 19 - 25
  * 2.0: 26 - 35
  * 3.0: 36 - 45
  * 4.0: 46 - 55
  * 5.0: 56 - 65
* __Gender:__ Gender of the customer
  * F: Female
  * M: Male
* __PostcodeOrigin:__ The postcode of origin/source.
* __Merchant:__ The merchant's ID. 
* __Category:__ Category of the purchase. 
* __Amount:__ Amount of the purchase.
* __Fraud:__ Target variable that shows if the transaction is fraudulent - 1 or non-fraudulent - 0.

__Note:__ Dataset was randomly generated and created for your virtual experience.
