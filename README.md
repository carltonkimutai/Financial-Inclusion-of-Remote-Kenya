# 🌍 Financial Deserts: Strategic Expansion in Kenya

### 📑 Project Roadmap

Structure of the ReadMe file:

1. **The Problem & Strategic Solution:** An overview of the economic friction caused by "Financial Deserts" and the market-capture solution.
2. **Deep Analysis & Methodology:** A technical summary of the data engineering and machine learning logic used.
3. **Interactive Visualizations:** Access to the hosted web application/dashboard.
4. **Running the Project:** Technical requirements and installation steps to replicate the analysis.
5. **Video Demonstration:** A video walkthrough located at the very bottom of this file.

---

✨ **Technologies**

* **Python:** GeoPandas, Pandas, NumPy, Scikit-Learn
* **Spatial Analysis:** Shapely, EPSG:21037 Projections
* **Front-End:** React / Framer Motion / Power BI

🚀 **The Problem & Strategic Solution**

* **The Problem: The "Financial Desert" Crisis.** While cities are crowded with bank agents, millions of people in rural Kenya live in "Financial Deserts". These are areas where the nearest financial hub is so far away that it traps entire settlements in isolation. Because roads are often poor or non-existent, a simple trip to withdraw money can require an exhausting journey on foot.
* **The Insight: The Opportunity Cost of Time.** In these areas, the true barrier is the **Opportunity Cost of Time**. When a community must spend several hours just to reach an agent, they lose valuable time that could be spent on farming, labor, or education. Every hour spent walking is an hour of lost economic productivity for the whole region.
* **The Solution: Market-Capture through Expansion.** This project treats agent expansion as a **market-capture strategy**, not just a social initiative. By reducing the travel burden, we "unlock" the dormant economic potential of these settlements.
* **The Analytical Approach: Engineering an "Impact Score."** I analyzed 9,900+ towns against 1,737 financial service points. By projecting the map into meters (EPSG:21037), I calculated the exact walking hours for every settlement. I then created a custom **Impact Score** (Population Weight × Walking Hours) to find the "Financial Deserts" where the travel burden is crushing the largest populations.
* **The Optimization: Finding the Mathematical "Sweet Spot."** Using the **Elbow Method**, I tested expansion plans from 10 to 300 hubs. By measuring the drop in travel burden, the model identified the exact mathematical optimum: a rollout of **50 strategic hubs** that provides the highest national impact.
* **The Actionable Output: K-Means Deployment.** I used **K-Means Clustering** (weighted by population) to map these 50 hubs to real-world Kenyan towns. This created a ranked National Hub Leaderboard and a Hub-and-Spoke network linking 1,500+ high-impact towns to their nearest base camp.

📍 **Deep Analysis & Methodology**
For a comprehensive, in-depth analysis of each stage of this project, please open the primary analysis file:
👉 **[`/notebooks/Financial_Deserts_Spatial_MVP.ipynb`](https://www.google.com/search?q=./notebooks/Financial_Deserts_Spatial_MVP.ipynb)**

The notebook is designed to walk you through the project in a **Phase-to-Phase** manner. Each code block is accompanied by a detailed explanation of the phase, the mathematical reasoning used, and the business logic behind the data transformations.

**Visualizations:** [View the Interactive Dashboard Here]

🚦 **Running the Project**

1. Clone the repository: `git clone https://github.com/carltonkimutai/financial-deserts-kenya.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Launch the environment: `jupyter notebook`
4. Open `notebooks/Financial_Deserts_Spatial_MVP.ipynb`

---

🎞️ **Video Walkthrough**
*Below is a video demonstration showing the final visualization tool in action, including the interactive Hub-and-Spoke mapping and the National Leaderboard:*

**(Attached Video: `visualization_demo.mp4`)**

---

