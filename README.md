# Olympics Paris 2024-Power BI Dashboard



## Problem Statement

The Olympics Paris 2024 Dashboard provides a comprehensive and user-friendly interface that aggregates data from the games, offering real-time updates, statistics, and visual insights. Users can easily explore medal counts, athlete performance metrics, and other essential details. This dashboard simplifies the experience of following the Paris 2024 Olympics, whether you're a fan, journalist, or data analyst.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, from kaggle using Python script.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in some csv files there were columns with null values and hence were fixed.
- Step 5 : Create a Measure Table for storing all the measures to be created.
- Step 6 : Measures like Total Medals, Total Atheletes, Total Gold Medals, Country Playing etc were created.
- Step 7 : For Overview Page of the dashboard cards were used to display Total Gold, Silver, Bronze Medals, Country Playing, Playig Teams and Total Athletes. 
- Step 8 : Shape Map to display the world map color saturation according to the medals won by the country.
- Step 9 : Slicer to select the country, can be changed to single select or multi select along with search bar to search the country.
- Step 10 : Two Stacked bar charts were also added to display Medals by Sports and Medals by Country and Medal Type. 
- Step 11 : Slicer was added for different sports (hidden).

  - Bookmark was created "Open" with Slicer not hidden.
  - Another Bookmark was created "Close" with Slicer hidden.
  - A button was added with action to open the Bookmark "Open".
  - Another button was added grouped to the slicer with action to open the Bookmark "Close"
  - This was the way to create a toggle button to on and off the Sports Slicer.

- Step 12 : Navigation was added to go to different pages of the dashboard.
- Step 13 : Backgrounds and Images were created in Adobe Illustrator and was added.

Snap of Overview Page ,

![Screenshot (4637)](https://github.com/user-attachments/assets/4c81812c-4b8f-440d-8a39-8e6f24d4c2f2)

Snap of Overview Page with India Selected ,

![Screenshot (4638)](https://github.com/user-attachments/assets/28ab9165-d6bd-4f2a-a90a-4eb4fa9534d3)

- Step 14 : For Athletes Page cards were used to display Total Athletes, Total Male Athletes, Total Female Athletes, Total Golds, Silver and Bronze Medals.
- Step 15 : Two Stacked Bar charts were used to display Athletes by Country and Gender and Athletes by Country and Medal Type.
- Step 16 : Clustered Colum Chart was used to display Athletes by Age Category with Male and Female as legends.

    - Age was a new column created using DATEDIFF() DAX statement.
    - Age Category was also a new column created using SWITCH() DAX statement.

Snap of Athletes Page ,

![Screenshot (4639)](https://github.com/user-attachments/assets/9fe1aa1c-2028-43ef-aa7d-d34f91bd8570)

Snap of Athletes Page with United States Selected ,

![Screenshot (4640)](https://github.com/user-attachments/assets/aeb017df-976b-4743-8bd6-7d60721019bd)


- Step 17 : A Shape Map was used to display world map with Color saturation of countries with medals.
- Step 18 : For Country Page cards were used to display Total Golds, Total Silver and Total Bronze Medals.
- Step 19 : A Stacked Bar chart was used to display Medals by Country and Medal Type with a Top 3 Filter applied.
- Step 20 : A slicer was added for selecting countries with search bar. 

Snap of Country Page ,

![Screenshot (4643)](https://github.com/user-attachments/assets/0d132621-5552-4abe-b8fa-0013376e45ec)

Snap of Athletes Page with China Selected ,

![Screenshot (4644)](https://github.com/user-attachments/assets/b0648ef2-3898-4637-ac1f-925d08c78326)

- Step 21 : At last Home Page was created. 

![image](https://github.com/user-attachments/assets/2af5d8b9-bf15-44a1-9850-50e192e31f6b) 
 


# Insights

Following inferences can be drawn from the dashboard;

### [1] Total Number of Athletes = 11113

   Number Male Athletes = 5658

   Number Male Athletes = 5455

### [2] Total Number of Medals = 1052
    
   Number of Gold Medals = 329

   Number of Silver Medals = 333    

   Number of Bronze Medals = 390

### [3] Top 3 Best Performer Countries 
   - United States of America
   - China
   - France

