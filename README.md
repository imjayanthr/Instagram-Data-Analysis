# Instagram-Data-Analysis
##  Instagram Data Analysis and Visualization

##  Project Overview
This project involves analyzing **Instagram performance metrics** using Python (`Pandas` and `Plotly`) in **Google Colab**.  
The goal is to generate insights into **engagement trends**, identify the best posting times, and categorize content based on topics.  
The results are visualized using **interactive charts**.

---

##  Dataset
- **File Name:** `Instagram-Data.csv`
- **Columns Included:**
    - `Post type`: Type of content (image, video, reel)
    - `Impressions`: Number of times the post was viewed
    - `Reach`: Number of unique users who viewed the post
    - `Likes`, `Comments`, `Saves`: Engagement metrics
    - `Publish time`: Date and time the post was published
    - `Description`: Caption text of the post

---

##  Key Features

###  1. Engagement Metrics by Post Type
- Analyzes and visualizes **average likes, comments, and saves** for each post type.  
- Helps identify which content type generates the most **engagement**.  
-  **Visualization:** Grouped bar chart using `Plotly Express`.

---

###  2. Time-Based Analysis
- Extracts **day of the week** and **hour of the day** from the `Publish time` column.  
- Calculates the **average impressions and reach** by day and hour.  
-  **Visualization:**  
    - Bar chart for **daily performance**.  
    - Line chart for **hourly trends**.  

---

###  3. Topic Categorization and Engagement Analysis
- Cleans descriptions by **removing hashtags**.  
- Categorizes posts into **topics** using keyword matching (e.g., "Projects," "Career Growth").  
- Aggregates **average likes, comments, and saves** by topic.  
-  **Visualization:** Grouped bar chart showing **engagement by topic**.  

---

### 4. Weekly and Monthly Performance
- Summarizes **performance metrics** by week and month.  
- **Visualization:**  
    - **Weekly and monthly** bar charts showing **engagement trends over time**.  

---

## Technologies Used
- **Google Colab**: Environment for running Python notebooks.  
- **Python Libraries:**  
    - `Pandas`: Data processing and analysis.  
    - `Plotly`: Interactive data visualization.  
- **Google Colab File Upload:** Importing CSV data into the notebook.  
