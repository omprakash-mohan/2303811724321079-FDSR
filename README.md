

 Comparing Average Rainfall of Two Cities - R Shiny App

This R Shiny application allows users to compare the monthly average rainfall of two cities using statistical summaries and visualizations. It supports manual input as well as CSV/Excel file uploads, offering an interactive dashboard to analyze, compare, and potentially forecast rainfall trends.

 📌 Features

* 📥 Upload rainfall data via CSV or Excel files
* 📝 Manually input monthly rainfall values
* 📊 Interactive bar and line plots
* 📈 Statistical summary of average rainfall
* 🧠 (Optional) Forecasting of future rainfall using time series models
* 🚨 (Optional) Alerts for abnormal or extreme rainfall values


 🛠️ Technologies Used

R
Shiny
ggplot2
readr, readxl
dplyr
janitor
forecast(for future forecasting module)



 📂 How to Run the App

1. Clone the repository:

 bash
   git clone https://github.com/yourusername/rainfall-comparison-app.git
   cd rainfall-comparison-app


2. Open R or RStudio.

3. Install required packages if not already installed:

 r
   install.packages(c("shiny", "ggplot2", "readr", "readxl", "dplyr", "janitor"))
  

4. Run the app:

r
   shiny::runApp()
   ```



 📁 File Structure


rainfall-comparison-app/
├── app.R                 # Main Shiny app code
├── sample_data.csv       # Example rainfall data
├── README.md             # Project documentation




 📊 Sample Input Format

Manual Input:
Comma-separated values for each city representing 12 months of rainfall (e.g., `80,70,90,60,...`)

CSV/Excel Format:

| Month | City1 | City2 |
| ----- | ----- | ----- |
| Jan   | 80    | 60    |
| Feb   | 70    | 55    |
| ...   | ...   | ...   |



 🚀 Future Scope

* Add machine learning models for rainfall forecasting
* Enable email notifications and real-time alerts
* Extend comparison to more than two cities
* Add map-based rainfall visualization

