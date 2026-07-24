# 📊 Website Traffic Analysis using Python

Website Traffic Analysis is a data analytics project developed to understand user behavior, session patterns, and page interactions using website log data. The project performs data preprocessing, session creation, behavioral analysis, and visualization to generate actionable business insights.

---
## Project Overview

This project analyzes website traffic data by:

- Cleaning and preprocessing raw traffic data.
- Creating user sessions using time-based logic.
- Identifying landing and exit pages.
- Analyzing user navigation behavior.
- Visualizing traffic patterns and user flow.
- Providing business recommendations to improve conversions.

---

## Dataset

**Dataset:** `traffic.csv`

The dataset contains website traffic information such as:

- User ID  
- Timestamp  
- Page / Track  
- Referrer (traffic source)  

> **Note:** Dataset is uploaded manually in Google Colab.

---

## Technologies Used

- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  

---

## Project Workflow

### 1. Data Preprocessing

- Load dataset  
- Handle missing values  
- Remove duplicate records  
- Standardize column names  
- Convert timestamp to datetime  

---

### 2. Session Creation

- Calculate time difference between user actions  
- Create new session if inactivity > 30 minutes  
- Assign session IDs to users  

---

### 3. Traffic Analysis

- Landing Page Analysis  
- Exit Page Analysis  
- Referral Source Analysis  
- User Navigation Flow Analysis  

---

### 4. Data Visualization

The project generates visual insights such as:

- Top Landing Pages  
- Top Exit Pages  
- Referral Source Distribution  
- User Flow between pages  

---

## Output

The analysis produces:

- Cleaned dataset
- Session-based user insights
<img width="419" height="241" alt="Top 10 Landing pages" src="https://github.com/user-attachments/assets/6ca0af48-5b9f-4b87-9689-e2ff3fd56670" />
<img width="414" height="270" alt="Top 10 Exit pages" src="https://github.com/user-attachments/assets/2dbccbf8-95f4-4612-9cb5-4239e751e313" />
<img width="262" height="237" alt="Top 10 Referral Sources" src="https://github.com/user-attachments/assets/b0235f9c-7e06-4593-9856-62916d02be20" />

- Traffic behavior patterns  
- Visualizations of user activity
-  <img width="608" height="527" alt="Top Referral Sources" src="https://github.com/user-attachments/assets/b01983b1-a42b-4731-952b-8db7e4e6493e" />
<img width="1394" height="1079" alt="Top 10 Landing and Exit Tracks" src="https://github.com/user-attachments/assets/fd726b0c-30d0-43a2-aa67-8f06a0b8cf3f" />


---

## How to Run

### Open the Notebook

Run the notebook using:
- Google Colab  
- Jupyter Notebook  

## Project Structure
Website-Traffic-Analysis/
│
├── Untitled0.ipynb
├── README.md
└── traffic.csv

---

## Business Insights

The analysis helps to:

- Identify high-traffic landing pages  
- Detect pages with high exit rates  
- Understand user navigation behavior  
- Improve website engagement  
- Optimize marketing strategies  

---

## Future Improvements

- Add bounce rate calculation  
- Add session duration analysis  
- Advanced visualizations (Sankey Diagram, Funnel Analysis)  
- Build real-time dashboard using Streamlit  
- Apply machine learning for user segmentation  

---

## Author

**Akash Yenni**

GitHub: https://github.com/yenniakash

---

## License

This project is licensed under the MIT License.

