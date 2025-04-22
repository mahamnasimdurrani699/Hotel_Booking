# 🏨 Hotel Booking Demand Analysis

> 📊 An exploratory data analysis project using the **Hotel Booking Demand Dataset** from TidyTuesday.  
> 💡 Focus: Cancellations, guest behavior, booking trends, and more.

---

## 📂 Dataset

- **Source:** [TidyTuesday Dataset (2020-02-11)](https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-02-11/hotels.csv)
- **Records:** 119,390 rows
- **Columns:** 32 features related to hotel bookings

---

## 🛠️ Tools Used

- Python 🐍
- Pandas 📊
- Google Colab ☁️
- Matplotlib (for optional visuals) 📈

---

## ✅ Tasks Performed

### 📌 Question 1
✔ Created a custom function to inspect:
- Data types  
- Missing values  
- % of missing values  
- Unique values  

### 📌 Question 2
✔ Analyzed canceled vs. non-canceled reservations  
✔ Calculated proportions

### 📌 Question 3
✔ Calculated cancellation % by hotel type  
✔ Identified which hotel has more cancellations

### 📌 Question 4
✔ Filtered data for only non-canceled reservations → `df_checkout`

### 📌 Question 5
✔ Monthly bookings by hotel  
✔ Identified busiest months (by name and number)  
✔ Compared trends between hotel types

### 📌 Question 6
✔ Created a clean `arrival_date` (datetime) column from year, month, day

### 📌 Question 7
✔ Built:
- `df_daily_reservation`: daily reservations  
- `df_avg_daily_reservation_per_week`: average reservations by weekday

### 📌 Question 8
✔ Calculated average ADR by hotel and customer type  
✔ Identified which customer type pays the most (ADR)

### 📌 Question 9
✔ Merged with `df_country`  
✔ Listed top 10 countries by reservation count

### 📌 Question 10
✔ Found average number of guests per reservation  
✔ Identified reservation with highest guest count (💥 55 guests!)

---

## 🧠 Key Insights

- **City Hotels** have a higher cancellation rate than Resort Hotels
- **August** is the busiest booking month for both hotel types
- **Transient** customers are the most profitable (highest ADR)
- Some reservations involve very large groups (e.g., 55 guests)

---

## 📈 Future Improvements

- Visualize data with Seaborn or Plotly
- Apply clustering to segment customer types
- Train ML model to predict cancellations

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🙌 Acknowledgments

- [TidyTuesday Project](https://github.com/rfordatascience/tidytuesday)
- Dataset authors and contributors
- Google Colab & Python community


