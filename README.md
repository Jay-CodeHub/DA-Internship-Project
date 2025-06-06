# 🧠 Customer Segmentation – Data Analytics Internship Project

This project was developed as part of a **Data Analytics Internship** to segment customers based on behavior using clustering algorithms and generate insights that support personalized marketing strategies.

📊 **Project Notebook**:  
[🔗 View Full Notebook](https://github.com/Jay-CodeHub/DA-Internship-Project/blob/main/Customer-Segmentation.ipynb)

---

## 🎯 Objectives

- Clean and preprocess customer data.
- Apply **K-Means Clustering** to group customers by behavioral patterns.
- Visualize key patterns and segmentation insights.
- Design a **Power BI dashboard** and prepare deliverables (PPT, abstract).

---

## 🛠️ Tech Stack

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Power BI (Dashboarding)
- Jupyter Notebook
- MS Excel and PowerPoint (Supporting files)

---

## 📂 Project Structure

```
.
├── data/
│   ├── data.csv                  # Cleaned input data (CSV format)
│   └── data.xlsx                 # Excel version of the dataset
│
├── Abstract.docx                 # Summary abstract for internship report
├── Customer-Segmentation.ipynb  # Main notebook for EDA + clustering
├── Customer-Segmentation-Dashboard.pbix  # Power BI Dashboard file
├── Customer-Segmentation-PPT.pptx       # Presentation file
└── README.md                    # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Jay-CodeHub/DA-Internship-Project.git
cd DA-Internship-Project
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Run the Notebook

```bash
jupyter notebook Customer-Segmentation.ipynb
```

---

## 🔍 Project Workflow

### 🧹 Data Preprocessing
- Handled missing values
- Removed duplicates
- Scaled features where needed (e.g., using StandardScaler)

### 📊 EDA
- Frequency of purchases, recency, and monetary value
- Distributions and boxplots for customer attributes

### 🧠 Clustering
- **K-Means** algorithm applied
- **Elbow method** and **silhouette score** used to find optimal clusters
- Cluster interpretation for segmentation (e.g., High value, At-risk)

### 📈 Power BI Dashboard
- Built using `.pbix` file
- Interactive visuals for business stakeholders

---

## 💡 Insights

- Identified **3 key customer segments** for marketing focus.
- High-value customers can be targeted for loyalty programs.
- Potential churners are suggested for re-engagement campaigns.

---

## 📁 Deliverables

- ✅ Jupyter Notebook for development
- ✅ Excel and CSV data files
- ✅ Abstract and documentation (DOCX)
- ✅ Power BI Dashboard
- ✅ PowerPoint Presentation (for stakeholders)

---

## 🧾 License

This project is open-source under the MIT License. See `LICENSE` file if available.
