**This project is a data cleaning and visualization notebook that explores global GDP trends from 1980 to 2023, focusing on distribution patterns, trillion-dollar economies, and recession analysis for the USA and China. It uses Python libraries like Pandas, Seaborn, and Matplotlib to process and visualize the dataset.**

---

## 🔑 Project Overview
- **Dataset**: World GDP data from 1980–2023, measured in billions of U.S. dollars.
- **Tools Used**:  
  - **Pandas** for data handling  
  - **NumPy** for numerical operations  
  - **Seaborn & Matplotlib** for visualization  
  - **SciPy** for statistical analysis
- **Main Goals**:
  1. Load and clean GDP data.
  2. Visualize GDP distribution across countries and years.
  3. Identify trillion-dollar economies in 2022.
  4. Analyze recession trends in the USA and China.

---

## 📊 Key Steps in the Notebook

### 1. **Data Loading & Cleaning**
- Reads `world_gdp_dataset.csv` into a Pandas DataFrame.
- Renames the GDP column for clarity.
- Defines a `check_data()` function to confirm successful loading.

### 2. **GDP Distribution (2000–2022)**
- Extracts GDP values from 2000–2022.
- Creates a **histogram** showing the frequency distribution of GDP values.
- Highlights the **mode GDP** (most frequent value) with a red line.

### 3. **Trillion-Dollar Economies (2022)**
- Filters countries with GDP > **1 trillion USD** in 2022.
- Plots a **bar chart** of these economies.
- Shows the dominance of the **USA and China**, along with other major economies.

### 4. **Recession Analysis (USA & China)**
- Defines recession as **three consecutive years of GDP decline**.
- Plots GDP trends for both countries from 1980–2023.
- Highlights potential recession years with vertical lines.
- **Finding**: Neither the USA nor China experienced a recession under this definition.

---

## 📌 Insights Derived
1. **Recession Analysis**:  
   - Neither the USA nor China had three consecutive years of GDP decline.  
   - Both economies show consistent long-term growth.

2. **Highest GDP**:  
   - The **USA** consistently holds the top spot globally.  
   - It dominates the trillion-dollar economy list.

3. **China’s Growth**:  
   - China is the **second-largest economy**.  
   - Its GDP growth trajectory is steep, reflecting rapid industrialization and global influence.

---

## 🧾 Purpose of the Project
- **Practice in data cleaning and visualization** using real-world economic data.
- **Exploratory analysis** of global GDP trends.
- **Educational value**: Helps learners understand how to use Python for economic data analysis.

---

## ⚠️ Limitations
- GDP data is in **current prices**, not adjusted for inflation (real GDP).  
- Recession definition is simplified (only GDP decline, not broader economic indicators).  
- Dataset may not include the latest IMF or World Bank revisions.


