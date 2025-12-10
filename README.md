# Harvard Art Museums Data Collection and Storage

This project uses the **Harvard Art Museums API** to collect, process, and store artwork data.  
The current implementation focuses on large-scale data extraction, transformation, and cloud database storage.  
Future work includes writing analytical SQL queries and building an interactive **Streamlit application**.

---

## 📌 Project Objective

- Collect artwork data from the Harvard Art Museums API  
- Identify divisions with more than **2,500 records**  
- Select **five divisions** for detailed analysis  
- Extract metadata, media information, and color details  
- Transform API data into structured formats  
- Store the processed data in a cloud-based SQL database  

---

## ✅ Current Status (Completed)

✔ Retrieved division-wise data using the Harvard Art Museums API  
✔ Filtered divisions with more than **2,500 records**  
✔ Selected **five divisions** for data collection  
✔ Collected:
- Artwork metadata  
- Media information  
- Color details  

✔ Converted raw API responses into **Pandas DataFrames**  
✔ Uploaded the structured data into **TiDB Cloud**  
✔ Database created: **`Harward_database`**  
✔ Database connection handled using **SQLAlchemy**

---

## 🔄 Planned Work (In Progress)

🔹 Write **SQL queries** for:
- Division-wise analysis  
- Artwork and media exploration  
- Color distribution analysis  
- Record count and metadata insights  

🔹 Develop a **Streamlit web application** to:
- Query the TiDB database interactively  
- Display summary statistics  
- Visualize artwork metadata and color patterns  
- Enable user-driven filtering and exploration  

---

## 📁 Project Structure

PROJECT_HARWARD/

├── PROJECT_HARWARD.ipynb # Data collection and database upload

├── README.md # Project documentation


