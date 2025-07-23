# Bangalore-Flood-Risk-Dashboard
Bengaluru Flood Risk Detection Dashboard
A real-time, AI-powered Streamlit dashboard that predicts and visualizes flood severity across different areas of Bengaluru using machine learning, elevation data, rainfall, and proximity to rivers.


📌 Project Summary
This project was developed as part of a hackathon to tackle flood-related urban challenges in Bengaluru. Using historical flood data and geospatial features, it predicts flood severity and helps visualize affected zones on an interactive map.

Built with:

🧠 Random Forest Classifier for severity prediction

🗺️ Folium & Streamlit for interactive map and UI

📊 Seaborn & Matplotlib for visual analytics

🧪 Custom simulation of flood risk based on input conditions

🚀 Features
🔍 Area-wise flood severity prediction (Low / Medium / High)

🗺️ Interactive flood risk map with marker clusters and heatmaps

📈 Rainfall and severity charts per locality

🤖 Custom flood severity predictor based on user-defined inputs

🌀 Real-time rainfall overlay using Windy

📁 Project Structure

📦 Bengaluru Flood Risk Detection
├── bengaluru_flood_dectector.py       # Main Streamlit app
├── bengaluru-182.csv                  # Dataset with location-wise flood data
├── image_file.jpg                     # Background image
├── requirements.txt                   # Python dependencies
🧠 Model Information
Algorithm Used: Random Forest Classifier

Features: rainfall, elevation, distance_to_river

Target: severity_code (mapped to Low, Medium, High)

Training Method: Trained on area-wise statistical values (CSV)

🖥️ How to Run
🔧 Prerequisites
Make sure Python is installed and run the following to install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
▶️ Start the App
bash
Copy
Edit
streamlit run bengaluru_flood_dectector.py
📸 Screenshots
Interactive Folium Map with Clusters

Custom Severity Prediction Panel

Area-wise Rainfall Charts

Live Weather Overlay from Windy

🧑‍💻 Contributors
This project was developed during a hackathon event. Special thanks to:

Manjunath VP 

Harsha S 

Darshan N V

Tarun 

📊 Data Source
Dataset used: bengaluru-182.csv

Contains: Area names, coordinates, rainfall, elevation, distance to river, severity code

📌 Future Improvements
🌐 Integrate BBMP real-time alerts via API

🛰️ Satellite data integration for more accuracy

📱 Mobile-friendly UI for emergency access

📦 Docker deployment for portability

🔗 Useful Links
BBMP Flood Forecast Portal

Windy Live Weather

📄 License
This project is open-source and free to use for educational and non-commercial purposes.
