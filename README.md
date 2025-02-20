<h1>Prepare Data for Looker Dashboards and Reports</h1>

This project showcases a data visualization challenge lab completed after taking the google cloud course "Prepare Data for Looker Dashboards and Reports". The objective was to analyze FAA datasets and create interactive dashboards to help a private plane and helicopter rental company determine optimal rental hub locations.  

**The challenge required:**  
✅ Creating multiple **Looks** (custom visualizations) to answer key business questions  
✅ **Merging datasets** from Flights and Airports for enhanced insights  
✅ **Building a dashboard** to present all visualizations in an interactive format  

<h2>Languages and Utilities Used</h2>

✅ **Looker (Google Cloud)**  
✅ **SQL (Custom Measures, Table Calculations)**  
✅ **Data Visualization (Tables, Bar Charts, Pivot Tables)**

<h2>Environments Used </h2>

- <b>🖥 Google Cloud Platform (Looker Instance - Temporary Credentials)

</b> 

<h2>Tasks and Visualizations:</h2>

### **1️⃣ Most Heliports by State**  
📊 **Objective:** Identify the top 10 states and cities with the highest number of heliports  
📌 **Dataset:** Airports  
🔹 **Data used:** Airports Count, State, Facility Types  
🛠 **Process:** I filterd only for heliport and limited to 10  
🔹 **Final output:** Table visualization in descending order
<p align="center">
  <img src="https://i.imgur.com/UAmccNW.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />


### **2️⃣ Facility Type Breakdown for Top States**  
📊 **Objective:** Analyze facility type distribution in states with the most airports  
📌 **Dataset:** Airports  
🔹 **Data used:** Airports Count, State, Facility Types  
🛠 **Process:** I Pivoted the facility dimension to show the distribution   
🔹 **Final output:** Table visualization in descending order
<p align="center">
  <img src="https://i.imgur.com/xehkt7M.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />


### **3️⃣ Highest Flight Cancellation Rates**  
📊 **Objective:** Identify airports and states with the highest percentage of flight cancellations (with over 10,000 flights)  
📌 **Dataset:** Flights  
🔹 **Data used:** Aircraft Origin City, Aircraft Origin State, Percentage of Flights Cancelled  
🛠 **Process:** I filtered for flights exceeding 10,000, then created a table calculation to determine the cancellation percentage   
🔹 **Final output:** Table visualization in descending order  
<p align="center">
  <img src="https://i.imgur.com/cF4uTKv.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />


### **4️⃣ Smallest Average Distance Between Airports**  
📊 **Objective:** Determine the origin and destination airports with the smallest average flight distance  
📌 **Dataset:** Flights  
🔹 **Key Metrics:** Origin, Destination, Average Distance (Miles)  
🛠 **Process:** Created a custom measure to calculate the average flight distance, applied a filter to remove zero values, and sorted the results in ascending order.    
<p align="center">
  <img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />

🔹 **Final output:** Airports Count, State, Facility Types  
<p align="center">
  <img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />

### **5️⃣ Busiest Major Joint-Use Airports with Control Towers**  
📊 **Objective:** Identify the busiest airports that are major, joint-use, and have control towers  
📌 **Dataset:** Flights & Airports (Merged)  
🔹 **Key Metrics:** City, State, Code, Number of Flights  
🛠 **Process:**  Merged the Flights and Airports datasets, filtering for airports marked as major, joint-use, and with control towers, then visualized the busiest ones using a bar chart. 
<p align="center">
  <img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />

🔹 **Final output:** Airports Count, State, Facility Types  
<p align="center">
  <img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />

### **6️⃣ Dashboard: Consolidated Insights**  
📊 **Objective:** Combine all visualizations into a single interactive dashboard for presentation  
📌 **Dataset:** Airports, Flights  

🛠 **Process:** Added all created Looks and the merged results visualization to a new dashboard, organizing them for easy navigation and insights.  
<p align="center">
  <img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />

🔹 **Final output:** Interactive dashboard with all visualizations  
<p align="center">
  <img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />

🔹 **Skill badge:**   
<p align="center">
  <img src="https://i.imgur.com/fAtKYhg.png" height="80%" width="80%" alt="Replace"/>
</p>
<br />
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!># Lookerlab
