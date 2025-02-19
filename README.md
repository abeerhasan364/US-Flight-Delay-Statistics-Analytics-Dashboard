# **Flight Delay Time Statistics Dashboard**  

This project has a **Dash-based web application** that visualizes flight delay time statistics using **Plotly** and **Pandas**. Users can input a specific year to analyze average delay times caused by various factors (carrier, weather, NAS, security, and late aircraft).  It also includes **Exploratory Data Analysis** and plotting insights with interactive **plotly** graphs showing Flight Carrier, Airline Name, Destination State etc.

## **Dataset**  
The application uses the **[Airline Delay Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/airline_data.csv)**, which includes **110 variables** and **27,000 samples**:  
- **Year**: The year of flight operation  
- **Month**: The month of operation  
- **Reporting_Airline**: The airline operating the flight
- **DestState**: The airline's destination state
- **CarrierDelay**: Delay caused by the airline  
- **WeatherDelay**: Delay caused by weather conditions  
- **NASDelay**: Delay caused by National Aviation System  
- **SecurityDelay**: Delay caused by security-related issues  
- **LateAircraftDelay**: Delay due to previous flight issues  

## **Features**  
✔️ Interactive **line plots** showing average delay times for different airlines  
✔️ Input field to select **year** dynamically  
✔️ Responsive **Dash layout** for visualization  
✔️ Uses **Plotly Express** for interactive figures  

## **Installation**  
To run this project locally, follow these steps:  

### **1. Clone the Repository**  
```bash
git clone https://github.com/yourusername/flight-delay-dashboard.git
cd flight-delay-dashboard
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the Application**  
```bash
python app.py
```
Then, open **http://127.0.0.1:8050/** in your browser.  

## **Dependencies**  
Ensure you have the following libraries installed:  
```bash
pip install pandas plotly dash
```

## **Project Structure**  
```
📂 flight-delay-dashboard  
 ┣ 📜 app.py         # Main Dash application script  
 ┣ 📜 README.md      # Project documentation  
 ┣ 📜 requirements.txt  # List of dependencies  
```

## **Future Improvements**  
🔹 Add **real-time data updates**  
🔹 Implement **filtering by airport or airline**  
🔹 Deploy on **Heroku or AWS**  
