# Server Traffic & Anomaly Analysis Pipeline 🚀

This repository demonstrates a complete, end-to-end data engineering and analytics pipeline built with Python. It showcases object-oriented programming (OOP), data simulation, database integration, and static visualization.

## 📌 Project Overview
Instead of relying on pre-existing datasets, this project generates a large-scale synthetic dataset of server logs (50,000 records). The pipeline processes this data, handles missing values, ingests it into a relational database, and visualizes the results.

### Key Features:
- **Data Simulation:** Uses `NumPy` to generate realistic server traffic data with normal distributions and random noise.
- **Data Preprocessing:** Uses `pandas` to clean data and handle missing values (`NaN`).
- **Database Integration:** Connects to a `PostgreSQL` database using `SQLAlchemy` to securely store and retrieve processed logs.
- **Data Visualization:** Generates an analytical dashboard using `Matplotlib` to explore the relationship between server traffic and CPU load.
- **Architecture:** The code is structured using Object-Oriented principles (Classes) and includes professional logging for production-readiness.

## 🛠️ Technologies Used
- **Python 3**
- **pandas** (Data manipulation)
- **NumPy** (Numerical operations)
- **Matplotlib** (Data visualization)
- **PostgreSQL** (Database)
- **SQLAlchemy & psycopg2** (Database connection & ORM)

## 🚀 How to Run

1. Clone this repository.
2. Install the required dependencies: 
   ```bash
   pip install pandas numpy matplotlib sqlalchemy psycopg2-binary
3. Ensure you have a local instance of PostgreSQL running with a database named server_db.
4. Update the database connection string in the code with your own credentials (do not share your real password).
5. Run the Jupyter Notebook to execute the pipeline.
