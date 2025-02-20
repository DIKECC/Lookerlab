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
📊 **Objective:** Identify states and cities with the highest number of heliports  
📌 **Dataset:** Airports  
🔹 **Key Metrics:** Airports Count, State, Facility Types  
🛠 **Process:** Used a table visualization with pivoting to display the facility type distribution, sorting by the highest number of airports in each state.  
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


### **2️⃣ Facility Type Breakdown for Top States**  
📊 **Objective:** Analyze facility type distribution in states with the most airports  
📌 **Dataset:** Airports  
🔹 **Key Metrics:** Airports Count, State, Facility Types  
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
<br />
<br />
🔹 **Final output:** Airports Count, State, Facility Types  
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
<br />
<br />


### **3️⃣ Highest Flight Cancellation Rates**  
📊 **Objective:** Determine airports and states with the highest percentage of cancellations  
📌 **Dataset:** Flights  
🔹 **Key Metrics:** Aircraft Origin City, Aircraft Origin State, Percentage of Flights Cancelled  
<img src="IMAGE_LINK_HERE" height="80%" width="80%" alt="Highest Flight Cancellation Rates"/>
<br />
<br />

### **4️⃣ Smallest Average Distance Between Airports**  
📊 **Objective:** Identify airport pairs with the shortest average flight distance  
📌 **Dataset:** Flights  
🔹 **Key Metrics:** Origin, Destination, Average Distance (Miles)  
<img src="IMAGE_LINK_HERE" height="80%" width="80%" alt="Smallest Average Distance Between Airports"/>
<br />
<br />

### **5️⃣ Busiest Major Joint-Use Airports with Control Towers**  
📊 **Objective:** Identify the busiest airports that are major, joint-use, and have control towers  
📌 **Dataset:** Flights & Airports (Merged)  
🔹 **Key Metrics:** City, State, Code, Number of Flights  
<img src="IMAGE_LINK_HERE" height="80%" width="80%" alt="Busiest Major Joint-Use Airports with Control Towers"/>
<br />
<br />

### **2️⃣ Facility Type Breakdown for Top States**  
📊 **Objective:** Analyze facility type distribution in states with the most airports  
📌 **Dataset:** Airports  
🔹 **Key Metrics:** Airports Count, State, Facility Types  
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
<br />
<br />
🔹 **Final output:** Airports Count, State, Facility Types  
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Replace"/>
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
