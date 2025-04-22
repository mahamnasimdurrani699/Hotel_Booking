Dataset
Source: TidyTuesday - Hotels CSV

Rows: 119,390

Columns: 32

🔧 Technologies Used
Python

Pandas

NumPy

Matplotlib (optional for visualization)

Google Colab

✅ Tasks Completed
Question 1
✔ Created a function check_data(df) to return:

Data types

Null counts

Null percentages

Unique values per column

Question 2
✔ Counted and compared:

Total canceled vs. non-canceled reservations

Percentage share of each

Question 3
✔ Calculated:

Cancellation percentages for City Hotel and Resort Hotel

Identified the hotel type with more cancellations

Question 4
✔ Filtered and saved non-canceled reservations into df_checkout

Question 5
✔ Monthly reservation trends:

Grouped by arrival_date_month and hotel

Identified the peak month (by name and number)

Question 6
✔ Created and converted a new arrival_date column to datetime

Question 7
✔ Created:

df_daily_reservation: Reservations per day

df_avg_daily_reservation_per_week: Average by weekday

Question 8
✔ Calculated:

Average ADR by hotel and customer_type

Identified the customer type with the highest ADR per hotel

Question 9
✔ Merged with df_country to:

Show the top 10 countries by reservation count

Question 10
✔ Calculated:

Average number of guests per reservation

Found the reservation with the highest guest count (55 guests!)

📌 Insights
City Hotels have a higher cancellation rate.

Most bookings happen in August for both hotel types.

Transient customers generate the highest ADR.

A single reservation included 55 guests, which is an outlier.

📂 How to Use
Clone this repository

Open the notebook in Google Colab or Jupyter Notebook

Install necessary packages (pandas, matplotlib if needed)

Run the cells step-by-step

📮 Acknowledgments
TidyTuesday

Dataset Authors

Google Colab and the open-source Python community
