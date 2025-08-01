# Electric Vehicle Spec Dashboard

1. Project Objective

   To visualize and analyze key specifications of electric vehicles — including battery capacity, range, acceleration, top speed, and efficiency — and gain insights that can assist in comparing models,     understanding market trends, and supporting data-driven decisions for manufacturers and customers.

2. Key Insights
- The average EV range across all models is 393 Km, with an average battery capacity of 79 kWh.
- The fastest accelerating vehicle goes from 0–100 Km/h in just 4 seconds.
- Most vehicles fall under the Luxury and Executive segments.
- AWD (All-Wheel Drive) slightly dominates over RWD in drivetrain preference.
- Fastest charging capacity is seen in brands like Zeekr and Volvo.
- Efficiency (Wh/km) varies significantly across models and segments, providing insights into energy consumption.

3. Tech Stack

📊 Microsoft Power BI Desktop - Main data visualization platform used for report creation.

📂 Power Query - Data transformation and cleaning layer for reshaping and preparing the data.

🧠 DAX (Data Analysis Expressions) - Used for calculated measures or KPIs (AVERAGE, MIN, MAX, DISTINCTCOUNT), dynamic visuals, and conditional logic.

📝 Data Modeling - Relationships established among various specifications in table format (such as Range (Km), Battery Capacity (kWh), Fast Charging (kW), Top Speed (Km/h), Segment, Efficiency (Wh/km).

📁 File Format - .pbix for development and .png for dashboard previews.

📗 Microsoft Excel - used for initial data formatting/cleaning.

5. Dashboard Purpose & Features
   
🎯 Business Problem:
- With the growing demand for electric vehicles (EVs) worldwide, car manufacturers and buyers need an easy way to compare EV specifications across brands and segments. However, these details are often scattered or too technical to interpret quickly.
- There is a need for a consolidated, visual tool that helps answer questions like:
  
a) Which EVs offer the best range for the battery size?

b) How do different body types or segments compare in efficiency?

c) Which brands lead in performance or fast charging capabilities?

🧭 Goal of the Dashboard:

- The goal of this Power BI dashboard is to:

a) Provide a side-by-side comparison of EV models across key technical specs.

b) Offer insights on top-performing brands, segments, and body types.

c) Help manufacturers and buyers identify trends, performance benchmarks, and potential improvements.

- This dashboard simplifies complex EV data into visual summaries, KPIs, and comparisons to enable quicker, data-driven decisions.  
   
KPIs for:
- Average Range (Km)
- Average Battery Capacity (kWh)
- Min Acceleration Time (0–100 Km/h in Sec)
- Max Top Speed (Km/h)
- Total Number of Models
  
Interactive Filters:
- Brand
- Car Body Type
- Segment
-Drivetrain

Visualizations:

📋 Table: Detailed EV specifications (Range, Battery, Charging, Speed, Segment, Efficiency)

🎯 Scatter Plot: Range vs Top Speed vs Acceleration by Brand

🍩 Donut Chart: Top 5 Vehicle Segments by Model Count

📊 Bar Charts: Avg. Battery Capacity by Brand & Segment

📈 Line Chart: Max Fast Charging Power by Brand

🧭 Efficiency (Wh/km) included for technical evaluation
  
5. Dataset
- This dataset provides a comprehensive collection of specifications and performance metrics for modern electric vehicles (EVs).
- Included specs of 470+ electric cars: battery, range, fast charging, size & performance.
- The dataset includes over 60 EV models from popular brands such as Audi, Porsche, Volvo, XPENG, Voyah, Zeekr, and more.
- Fields include: Brand, Model, Range, Battery Capacity, Fast Charging Power, Top Speed, Segment, Efficiency (Wh/km), Acceleration, Drivetrain, and Car Body Type.
  
💡 Source: https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025/data

6. Screenshots / Demos
   
Here's a preview of the dashboard:
![Dashboard Snapshot](https://github.com/DivyaBasantray/Electric-Vehicle-Spec-Dashboard-/raw/main/Snapshot%20of%20the%20Dashboard.png)




   
  
  
