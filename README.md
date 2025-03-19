# **Growth Analyst Challenge: Mercado Libre**

You’re a **growth analyst** at *Mercado Libre*. With over **200 million users**, Mercado Libre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in **clever ways** to help it grow.  

### **Objective**  
You want to determine whether predicting **search traffic trends** can translate into **successful stock trading**.

---

## **Challenge Instructions**
This challenge consists of **four steps**:

### **Step 1: Find Unusual Patterns in Hourly Google Search Traffic**
- **Read** the search data into a DataFrame. *(5 points)*
- **Slice** the data to include only **May 2020**. *(5 points)*
- **Calculate** the total search traffic for the month. *(5 points)*
- **Compare** the value to the monthly median across all months. *(5 points)*
- **Analyze** whether Google search traffic increased during Mercado Libre’s financial results release. *(5 points)*  

### **Step 2: Mine the Search Traffic Data for Seasonality**
- **Group** the hourly search data to plot the **average traffic by hour of the day**. *(5 points)*
- **Group** the hourly search data to plot the **average traffic by day of the week**. *(5 points)*
- **Group** the hourly search data to plot the **average traffic by week of the year**. *(5 points)*
- **Identify** time-based trends in the data and document findings. *(5 points)*  

### **Step 3: Relate Search Traffic to Stock Price Patterns**
- **Read and plot** the stock price data. *(5 points)*
- **Concatenate** the stock price data with search data into a single DataFrame. *(5 points)*
- **Slice** the data to the **first half of 2020** (January–June) and plot it. *(5 points)*
- **Create a "Lagged Search Trends" column** that shifts search traffic by one hour. *(5 points)*
- **Create two additional columns**:
  - `"Stock Volatility"` – A **4-hour exponentially weighted rolling average** of stock volatility. *(5 points)*
  - `"Hourly Stock Return"` – The **percent change** of the company's stock price on an hourly basis. *(5 points)*
- **Analyze** the relationship between **lagged search traffic and stock volatility or stock price returns**. *(5 points)*  

### **Step 4: Create a Time Series Model with Prophet**
- **Prepare** the Google search data for a Prophet forecasting model. *(5 points)*
- **Estimate the model** and plot the forecast. *(5 points)*
- **Plot the individual time series components** (trend, seasonality, etc.). *(5 points)*
- **Answer the following questions**:  
  - **What time of day exhibits the greatest popularity?** *(2 points)*
  - **Which day of the week gets the most search traffic?** *(2 points)*
  - **What's the lowest point for search traffic in the calendar year?** *(1 point)*  

---

## **Scoring Breakdown**
- **Step 1:** *25 points*
- **Step 2:** *20 points*
- **Step 3:** *35 points*
- **Step 4:** *20 points*
- **Total:** **100 points**