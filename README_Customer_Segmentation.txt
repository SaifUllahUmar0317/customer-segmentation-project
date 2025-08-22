# 🛠️ Customer Segmentation using K-Means Clustering

This project applies **K-Means clustering** to segment customers based on their **Annual Income** and **Spending Score**.  
It helps businesses (like a car repair company) understand different types of customers and design better marketing strategies.

---

## 📌 Project Overview
- Dataset: Mall Customers Dataset  
- Features used: Annual Income (k$), Spending Score (1-100)  
- Algorithm: K-Means Clustering  
- Output: 5 customer segments with business insights

---

## 📊 Customer Segments & Business Decisions

### 1. VIP Customers (most valuable 💎)
- Give them premium services (priority support, loyalty programs).
- Offer exclusive discounts (because they can afford & are loyal).
- Keep them happy → they bring major revenue.

### 2. Inactive Customers (low spenders 🚫)
- Don’t spend too much marketing budget here.
- Maybe target them with low-cost offers (oil change discount, free car wash).
- If they don’t respond → better to ignore (avoid wasting money).

### 3. Balanced Customers
- Good steady customers.
- Offer cross-selling (add-on services like battery check, air filter).
- Keep them in the system as long-term base revenue.

### 4. Saver Customers (want to save 💰)
- Attract them with discounts / coupons.
- Upsell affordable packages (basic maintenance bundle).
- Don’t pitch luxury services → they won’t buy.

### 5. Spender Customers (spend a lot, but not always rich)
- Offer personalized deals (e.g., tire + brake combo).
- They’re impulse buyers → promote limited-time offers.
- They can be converted into VIPs if nurtured.

---

## 🚀 Tech Stack
- Python 🐍
- Pandas, NumPy
- Scikit-learn (KMeans)
- Matplotlib for visualization

---

## 📂 How to Run
1. Clone this repo  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script  
   ```bash
   python customer_segmentation.py
   ```

---

## 📈 Results
- Identified **5 meaningful customer groups**
- Provided **business strategies** for each group
- Helps in **better marketing & customer retention**

---

## 💡 Future Improvements
- Add more features (Age, Gender, Service History)
- Try other clustering methods (DBSCAN, Hierarchical)
- Build a simple UI for businesses to upload customer data and get segmentation results

