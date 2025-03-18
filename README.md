# Solar Flare Data Processing and Database Integration
Solar Flare Data Pipeline - This project is designed to collect, process, and analyze solar flare event data using Python, PostgreSQL, and Pandas. Additionally, it implements regression models to predict missing or future values based on historical trends. The goal is to showcase data engineering and data science skills, including API data ingestion, ETL processing, predictive modeling, and database management.

## Key Features
* Data Ingestion: Fetches real-time and historical solar flare data from external APIs.
* Data Cleaning & Transformation: Uses Pandas to preprocess and normalize data.
* Database Storage: Stores structured data in PostgreSQL with optimized schema design.
* Bulk Data Loading: Efficiently inserts large datasets using PostgreSQL’s COPY command.
* Error Handling & Logging: Ensures robustness with built-in exception handling.
* Predictive Modeling: Implements regression models (e.g., Linear Regression) to estimate missing values and forecast solar activity.

## Tech Stack
* Python (Pandas, Psycopg2, SQLAlchemy, Scikit-learn)
* PostgreSQL (Relational Database)
* Machine Learning (Regression models for prediction)

## API Keys
This project requires API keys from NASA Open API. 
To obtain your API key:
1. Sign up at https://api.nasa.gov/
2. Navigate to the API section in your account
3. Generate a new API key
4. Add this key to your `.env` file

### Future Improvements
* Automate data pipeline with Apache Airflow.
* Enhance regression models with time-series forecasting (ARIMA, LSTM).
