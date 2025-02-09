# 🎯 InvenHub - Smart Inventory Management System  

**InvenHub** is an advanced inventory management system that simplifies stock tracking, billing, and sales analytics. It features **barcode scanning, automated stock updates, secure authentication, and AI-driven sales forecasts**, making it the perfect tool for store management.  

- **Frontend:** Developed by **Biswajit Chatterjee**  
- **Backend, Machine Learning, and Database:** Developed by **Debjyoti Ghosh**  

---

## 🚀 Key Features  

### 🏪 Inventory & Stock Management  
✅ Add, update, and remove products with **pricing, quantity, and barcode**  
✅ **Barcode scanning** for instant product retrieval  
✅ Automatic stock updates after every sale  

### 🛒 Sales & Billing System  
✅ Employees can **add products** to generate a bill  
✅ **Real-time stock update** after each sale  
✅ **ESP API integration** for barcode/bill printing  

### 🔒 Secure Authentication  
✅ **User Registration & Login** with password hashing  
✅ **OTP verification** for enhanced security  
✅ **Session timeouts** for added protection  

### 📊 Sales Analytics & AI Prediction  
📈 **1-year sales database** for historical insights  
📊 **Next 12-month sales predictions** powered by machine learning  
📉 **Pie charts, profit graphs, and trend analysis**  
🔗 **/predict_sales API endpoint** for forecasts  

---

## 🛠 Tech Stack  

**Frontend:** HTML, CSS, JavaScript, Flask (Templating)  
**Backend:** Flask, Python, SQLite/MySQL, REST APIs  
**Machine Learning:** Pandas, NumPy, Matplotlib, Scikit-learn  

---

## 🏁 Setup & Installation  

### 📥 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/InvenHub.git  
cd InvenHub  
```

### 🔧 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt  
```

### 📂 3️⃣ Configure the Database  
- Update `config.py` with your database credentials.  
- Run database migrations (if needed).  

### ▶ 4️⃣ Start the Application  
```bash
python app.py  
```
- Open [`http://localhost:5000`](http://localhost:5000) in your browser.  

---

## 🔐 Default Login (Test Access)  
Use the following credentials to test the system:  
📧 **Email:** `debjyoti2ghosh@gmail.com`  
🔑 **Password:** `321`  

*This account is for testing purposes only.*  

---

## 📡 API Endpoints  

| Endpoint | Method | Description |  
|----------|--------|-------------|  
| `/add_product` | `POST` | Add a new product with details |  
| `/update_stock` | `PUT` | Update stock quantity |  
| `/generate_bill` | `POST` | Generate a bill and update stock |  
| `/reports` | `GET` | Get the next 12-month sales predictions |  
| `/reports` | `GET` | Fetch analytics, charts, and insights |  

---

## 🚀 Upcoming Features  
📊 **AI-powered demand forecasting** for smarter inventory planning  
📱 **Mobile app integration** for on-the-go inventory tracking  
🛡 **Role-based access control** (Admin, Employee)  

---

## 🤝 Contributing  
Want to improve **InvenHub**? Fork the repo, create a feature branch, and submit a pull request.  

---

## 📜 License  
This project is licensed under the **MIT License**.  

---
```
