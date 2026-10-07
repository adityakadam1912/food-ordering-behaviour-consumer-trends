# Food Ordering Behaviour and Consumer Trends
### Interactive Tableau Business Intelligence Web Application

A modern, responsive dashboard web application built with **Flask**, **HTML5/CSS3/JavaScript**, and embedded with live interactive visualizations from **Tableau Public**.

---

## 🌟 Key Highlights

- **Tableau Public Integration**: Embeds live, interactive dashboards and stories directly from the published workbook on Tableau Public (`FoodOrderingBehaviourandConsumerTrends-Aditya` by Aditya Kadam).
- **Authentic Behavioral Data**: 100% data integrity based on 50,000 real-world transaction records across 6 major metropolitan cities (Mumbai, Pune, Bangalore, Delhi, Chandigarh, and Hyderabad).
- **Responsive Modern UI**: Soft light background palette, rounded cards (`16px–24px` radius), multi-tier subtle drop shadows, smooth transitions, and glassmorphic navigation.
- **Dedicated Sections**:
  - **Hero Section**: Introduces the study with verified dataset metrics and clear CTAs (*Explore Dashboard*, *View Insights*, *Interactive Story*).
  - **Dashboard Section**: Interactive Tableau visualizer with multi-view switcher (*Main Dashboard*, *Executive View*, *Cuisine Preferences*, *Cities by Value*, *Meal Revenue*), fullscreen mode, and reload controls.
  - **Story Section**: Narrative chapter walkthrough highlighting regional cuisine demand and demographic cohorts.
  - **Key Insights Section**: 6 real data-backed findings categorized with interactive category filters (*Temporal*, *Demographics*, *Regional*, *Economics*).
  - **Academic Showcase**: Complete attribution for college project demonstration and viva evaluation.

---

## 📁 Project Structure

```text
Food_Ordering_Web/
├── app.py                      # Flask application server & routing
├── config.py                   # Central configuration (Tableau URLs, metadata)
├── requirements.txt            # Python dependencies
├── README.md                   # Documentation
├── data/
│   └── food_ordering_behavior_dataset.csv   # Project dataset (50k records)
├── static/
│   ├── css/
│   │   └── style.css           # Vanilla CSS design system & responsive styling
│   ├── js/
│   │   └── main.js             # View switching, fullscreen, scroll spy, filters
│   └── images/
│       └── logo.svg            # Custom SVG culinary analytics logo
└── templates/
    ├── base.html               # Base layout, navbar, SEO tags & Tableau API
    └── index.html              # Main dashboard presentation page
```

---

## 🚀 How to Run Locally

### 1. Requirements
Ensure Python 3.9+ is installed.

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Start the Flask Server
```bash
python app.py
```

### 4. Open in Browser
Visit **[http://127.0.0.1:5000](http://127.0.0.1:5000)** in any modern web browser.

---

## ⚙️ Customizing Tableau URLs

All Tableau Public URLs and views are configured cleanly in [`config.py`](file:///c:/Users/Aditya%20Kadam/OneDrive/Documents/Food_Ordering_Web/config.py):

```python
TABLEAU_DASHBOARD_URL = "https://public.tableau.com/views/FoodOrderingBehaviourandConsumerTrends-Aditya/Dashboard1"
TABLEAU_STORY_URL = "https://public.tableau.com/views/FoodOrderingBehaviourandConsumerTrends-Aditya/ProfessionalClear"
```

If you publish new dashboards or update the workbook on Tableau Public, simply update the URLs in `config.py` and the entire web application will automatically sync!

---

## 📊 Summary of Dataset Metrics

- **Total Orders Analyzed**: 50,000
- **Unique Consumers**: 4,000
- **Average Order Value (AOV)**: ₹547.73
- **Median Order Value**: ₹547.00
- **Average Delivery Fee**: ₹59.64
- **Average Decision Time**: 7.5 minutes
- **Customer Satisfaction**: 2.99 / 5.0
- **Target Metros**: Mumbai, Pune, Bangalore, Delhi, Chandigarh, Hyderabad

---

## 🎓 Academic Demonstration
- **Author**: Aditya Kadam
- **Domain**: Business Intelligence & Consumer Behavior Analytics
- **Tools**: Tableau Desktop / Public, Python Flask, HTML5, CSS3, JavaScript
