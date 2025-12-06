# 🍯 Honey Production Statistics Project  

## 📖 Overview  
This project analyzes honey production data across U.S. states from **1995 to 2021** using Python. After cleaning the dataset, multiple statistical questions were explored through visualizations to uncover trends in production, pricing, and colony distribution.

---

## 📂 Dataset  
- **Source**: U.S. Honey Production Dataset  
- **Years Covered**: 1995–2021  
- **Columns**:  
  - `state`: U.S. state  
  - `colonies_number`: Number of bee colonies  
  - `yield_per_colony`: Honey yield per colony  
  - `production`: Total honey produced  
  - `stocks`: Honey stock available  
  - `average_price`: Price per pound  
  - `value_of_production`: Total production value  
  - `year`: Year of record  

---

## 🧹 Data Cleaning  
- Removed missing and inconsistent entries  
- Standardized state names  
- Converted year and price columns to numeric format  
- Verified column types and handled outliers  

---

## 📊 Questions Explored & Visualizations  

### 1️⃣ Top Honey Producing States  
<Figure size 720x720 with 1 Axes><img width="615" height="660" alt="image" src="https://github.com/user-attachments/assets/0c5287a0-55ef-41b1-b4cf-afb406be09fd" />

  
  Bar chart visualizes honey production values across U.S. states from 1995 to 2021. Highlights top contributors like North Dakota, California, South Dakota, Florida, and Montana. Gradient coloring emphasizes production scale, helping identify both leading and low-output states.
 
From the graph, the **top 5 honey-producing states** are:  
- North Dakota  
- California  
- South Dakota  
- Florida  
- Montana  

---

### 2️⃣ Change in Mean Average Price (1995–2021)  

<Figure size 1080x360 with 1 Axes><img width="891" height="317" alt="image" src="https://github.com/user-attachments/assets/66309e8d-d374-4699-9214-039891df8591" />

  
Bar chart compares honey production values across states with clear ranking. Top states like North Dakota, California, South Dakota, Florida, and Montana dominate output. Lower values highlight minimal production, showing regional disparities in U.S. honey industry.

**Which was the year when total mean value of production of Honey was the highest ?**

<Figure size 432x288 with 1 Axes><img width="362" height="259" alt="image" src="https://github.com/user-attachments/assets/29dc8edf-9dc2-4f27-9987-dcde74f76f1b" />

  
from the above graphs we can infer that the production of Honey was maximum in the year 2000 and leat in year 2021


### 3️⃣ Year of Highest Honey Production  
<Figure size 1080x360 with 1 Axes><img width="878" height="328" alt="image" src="https://github.com/user-attachments/assets/69042a23-4895-4bc3-b08a-fbc4d9c03bef" />


<Figure size 720x720 with 1 Axes><img width="557" height="558" alt="image" src="https://github.com/user-attachments/assets/cec1833d-2ff2-4668-a473-f26e3ca1639d" />

  
from the above graphs we can infer that the mean value of production of honey was maximum in year 2014

## 🛠️ Technologies Used  
- **Python** – core programming language  
- **Pandas, NumPy** – data cleaning & manipulation  
- **Matplotlib, Seaborn** – statistical visualizations  
- **Jupyter Notebook** – interactive analysis  

---

## 🎯 Key Insights  
- **North Dakota** leads in both honey production and colony count  
- Honey prices have steadily increased from 1995 to 2021  
- Production and value trends vary year to year, influenced by climate, colony health, and market demand  

---

## 🚀 How to Run  
1. Clone the repository  
2. Install required libraries:  
   ```bash  
   pip install pandas numpy matplotlib seaborn  
   ```  
3. Run the Jupyter Notebook  
4. Visualizations will be generated for each question  

---

Would you like me to also generate a **3-line GitHub description** or help you name the repository for maximum discoverability?
