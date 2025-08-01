# WATER QUALITY MONITORING AND FORECASTING SYSTEM

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&style=for-the-badge)
![Django](https://img.shields.io/badge/Django-3.2+-green?logo=django&style=for-the-badge)

---

## 1. Project Overview

This system leverages Machine Learning to monitor and forecast water quality by analyzing water data and predicting the Water Quality Index (WQI). The solution includes data collection, preprocessing, supervised model training (Random Forest and LSTM), and a Django-based web platform for data upload, visualization, and forecasting.

---

## 2. Features

- **Data Collection & Preprocessing:** Handles gathering, cleaning, and transforming raw water quality data.
- **Supervised ML Models:** Integrates both Random Forest and LSTM for robust quality prediction and classification.
- **Web Interface:** Provides an interactive Django-powered portal for data uploads and management.
- **Result Visualization:** Displays data and forecasts through clear visual charts and tables.
- **Prediction & Classification:** Offers real-time WQI predictions and water quality classification (e.g., "Good", "Poor").
- **IoT Ready (Future Scope):** Designed for integration with IoT sensors for live water data monitoring.

---

## 3. Technologies Used

- **Backend:** Python, Django
- **Machine Learning:** TensorFlow, Scikit-learn, NumPy, Pandas
- **Visualization:** Matplotlib
- **Frontend:** HTML, CSS
- **Models:** Random Forest, LSTM

---

## 4. Installation Steps

1. **Clone the Repository**
    ```bash
    git clone <repository_url>
    cd water-quality-monitoring-and-forecasting-system
    ```
2. **Set Up a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use venv\Scripts\activate
    ```
3. **Install Requirements**
    ```bash
    pip install -r requirements.txt
    ```
4. **Set Up the Database**
    - Configure your `settings.py` to connect to your preferred database (e.g., MySQL, SQLite).
    - Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. **Create a Superuser (Optional, for admin access)**
    ```bash
    python manage.py createsuperuser
    ```

---

## 5. How to Run the Project

1. Start the Django development server:
    ```bash
    python manage.py runserver
    ```

2. Open your web browser and navigate to:
    ```
    http://127.0.0.1:8000/
    ```

3. Use the interface to:
   - Register/Login
   - Upload datasets
   - View model results and water quality forecasts

---

## 6. Future Scope

- **IoT Sensor Integration:** Support for streaming real-time water data from physical sensors.
- **Automated Alerts:** Notify users of significant water quality changes.
- **Cloud Deployment:** Scale system for public or industrial use.
- **Advanced Analytics:** Add more predictive models and real-time dashboards.

---

*For questions or support, please open an [issue](https://github.com/karthikgannoju03/Water-Quality-Monitoring-and-Forecasting-System/issues) on the repository.*
