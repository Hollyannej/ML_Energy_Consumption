
Quick Start Guide for Energy Consumption ML Project
Holly Johnson

Navigate to this website: https://colab.research.google.com/drive/1JoMOwrkOdK6lQ1ge-dyMKkLghv8JECYe?usp=sharing.

Click on the folder icon on the left side of the screen.

Select the “Sample Data” folder.

Press the ‘Upload Session Storage Button” on the top left side of the screen. 


Select the data files named “DUQ_hourly_RAW_DATA.csv” and “temperature_RAW_DATA.csv” and upload them into the “Sample Data” folder. Be sure they are in the “Sample Data” folder, or the program will not run. You may manually drag and drop them into the “Sample Data” folder.

Scroll to the top of the page and run the first cell. Press the  ‘Play’ button in the top left-hand corner to run a cell. Be sure the little green checkmark appears next to the cell after you run it. If not, press it again. The checkmark indicates it ran successfully.


Input a username and password into the display at the bottom of the cell. Username is: my_username. Password is: my_password. Press “Login.”


Run the following cell by pressing the  ‘Play’ button in the left-hand corner. This cell removes rows from the raw energy data and puts them into filtered CSV files for easy integration.

Run the following cell by pressing the  ‘Play’ button in the left-hand corner. This cell removes excess columns from the raw temperature data and puts them into a filtered CSV file for easy integration.

Run the following cell by pressing the  ‘Play’ button in the left-hand corner. This cell parses the data and creates a new CSV file with featured engineering columns. 

Run the following cell by pressing the  ‘Play’ button in the left-hand corner. This cell scales the data for the following graphs. 

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner for the “Energy Consumption and Temperature Over Time” graph.

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner for the “Average Energy Consumption and Temperature by Month” graph.

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner for the “Energy Consumption Distribution by Hour of Day” graph.

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner to unscale the data. This step is crucial for the program to run correctly!

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner to create the SQLite database. 

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner to create the SQLite database. 

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner to verify the SQLite database.

Run the following cell by pressing the  ‘Play’ button in the top left-hand corner to run the Energy Consumption ML program and scroll down. The program may take several minutes to go through the entire learning process. 

Use the inner scroll bar to see the program results. There are two different graphs on the “Effect of Temperature on Energy Consumption” and “Actual vs. Predicted Energy Consumption in Megawatts vs. Temperature.” There is also a table with “Sample Predictions vs. Actual Energy Consumption.” 

Scroll to the bottom of the output to access the input widget. 

Adjust the slider bars based on Temperature, Month (1-12), and Hour (0-23) and get the Predicted Energy Consumption at the bottom in megawatts. This is the (New data → ML model → prediction) Energy Consumption ML produces. Input various temperatures, months, and hours to see the results.
