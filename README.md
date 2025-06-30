🐟 Detection of Illegal Fishing Activities Using AIS Data
📌 Project Overview
Illegal, unreported, and unregulated (IUU) fishing poses a major threat to marine biodiversity, global economies, and food security. This project presents an AI-driven solution to identify and monitor illegal fishing activities using Automatic Identification System (AIS) data. By leveraging the temporal and spatial properties of vessel movement data, we apply advanced deep learning techniques to forecast and detect suspicious fishing behavior.

🎯 Objectives
Predict the likelihood and intensity of fishing activity using vessel AIS data.

Build accurate and scalable deep learning models using LSTM and RNN architectures.

Enable automated surveillance to support maritime regulatory enforcement.

Visualize fishing activity trends both temporally and geospatially.

🛠️ Features
AIS Data Processing: Cleansing, feature engineering (e.g., distance from shore/port), timestamp extraction, and normalization.

Deep Learning Models: Implementation of LSTM and RNN networks to analyze temporal dependencies in vessel movements.

Regression-based Approach: Predicts fishing activity levels instead of binary classification, offering more nuanced insights.

High Accuracy: Achieves 96% prediction accuracy on test data.

Visualization Tools:

Hourly fishing activity trends.

Interactive geospatial maps of illegal fishing hotspots and proximity to shorelines.

📂 Dataset
The dataset consists of over 166,000 entries, including:

Maritime Mobile Service Identity (MMSI)

Timestamps

Latitude and Longitude

Vessel Speed and Course

Distance from Shore and Port

Fishing Activity Indicator (is_fishing: 1, 0, or -1)

Source: Global Fishing Watch (GFW)

🧠 Models Used
Recurrent Neural Network (RNN): Captures short-term temporal patterns.

Long Short-Term Memory (LSTM): Excels at capturing long-term dependencies, outperforming RNN in this context.

📈 Performance Metrics
Accuracy: 96%

MAE (Mean Absolute Error): 0.0397

MSE (Mean Squared Error): 0.0397

R² Score: 0.8328

🌍 Visualizations
Figure 1: Proposed model architecture.

Figure 2: Hourly trends in fishing activity.

Figure 3 & 4: Mapping illegal fishing zones with proximity indicators.

🧩 Future Scope
Real-time integration of live AIS streams for dynamic detection.

Expansion to include external factors (weather, vessel type, economic data).

Collaborations with international maritime authorities for deployment.

📜 Citation
If you use this project or dataset in your research, please cite:

Kavya M, Jokheeswar B, Yashwanth S, Mohanam K. Detection of Illegal Fishing Activities Using AIS Data, 2024.

🧪 Tools & Libraries
Python, TensorFlow/Keras

Pandas, NumPy, Scikit-learn

Matplotlib, Seaborn, Folium

🙌 Acknowledgements
Global Fishing Watch for AIS data

FAO and related studies for baseline references
