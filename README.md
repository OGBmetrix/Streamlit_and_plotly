Trainer / Coach Monitoring Dashboard

A Streamlit-based web app for real-time monitoring of client training data.
This dashboard loads and validates a features.parquet dataset and provides:

Client & Session Selection: Filter data by participant and individual training sessions.

Fatigue Status Tracking: Computes and displays the latest fatigue risk level (Normal or High Risk ) using label_binary.

Key Metrics: Displays average heart rate, acute load (10 min), and HR z-scores.

Interactive Visualizations: Line charts of heart-rate trends and session summaries built with Plotly Express.

Actionable Insights: Generates recommended actions based on fatigue risk to help adjust training plans.

Built with Python, Streamlit, Pandas, and Plotly to support data-driven decisions for trainers, coaches, and sports scientists.
