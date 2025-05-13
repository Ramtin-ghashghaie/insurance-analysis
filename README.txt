 پروژه پاک‌ سازی و مدلسازی داده‌ های آماری بیمه  
**Insurance Data Cleaning and Modeling Project**

این پروژه شامل دو مرحله‌ اصلی است:  
This project consists of two main stages:
1. پاک ‌سازی کامل داده‌ های آماری  
   **Complete data cleaning**
2. ساخت مدل یادگیری ماشین برای پیش‌ بینی یا دسته‌بندی  
   **Building a machine learning model for prediction or classification**

---

 ساختار پوشه‌ها  
**Folder Structure**
├── data
│ ├── raw/ ← داده‌ های خام
│ ├── cleaned/ ← داده‌ های پاک‌ سازی‌شده
├── notebooks
│ ├── insurance-cleaning.ipynb ← پاک‌سازی داده
│ └── insurance-model.ipynb ← آموزش مدل ML

---

 مرحله ۱: پاک‌ سازی داده بیمه  
**Step 1: Insurance Data Cleaning**

در نوت‌بوک `insurance-cleaning.ipynb` مراحل زیر اجرا شده:  
The following steps are performed in the `insurance-cleaning.ipynb` notebook:

- تغییر نوع ستون‌ها (مثل تبدیل ستون‌ های عددی/رشته‌ ای)  
  **Changing column types (e.g., numeric/string conversion)**
- بررسی و حذف مقادیر گمشده  
  **Handling and removing missing values**
- حذف داده ‌های پرت (Outliers)  
  **Removing outliers**
- نرمال‌ سازی یا کد گذاری مقادیر دسته‌ای (Encoding)  
  **Normalization or encoding of categorical values**
- ذخیره داده‌ی نهایی در `data/cleaned/`  
  **Saving the final cleaned data in `data/cleaned/`**

---

 مرحله ۲: مدلسازی با یادگیری ماشین  
**Step 2: Modeling with Machine Learning**

در نوت‌ بوک `insurance-model.ipynb`:  
In the `insurance-model.ipynb` notebook:

- تقسیم داده ‌ها به آموزش/تست (Train/Test Split)  
  **Splitting data into training/testing sets**
- انتخاب ویژگی‌های کلیدی (Feature Selection)  
  **Selecting important features**
- آموزش مدل ‌های مختلف برای پیش‌ بینی:  
  **Training different models for prediction:**
  - خطی (Linear Regression)  
  - Random Forest  
  - Ridge Regression  
- ارزیابی مدل‌ها با:  
  **Evaluating models using:**
  - MAE / R² Score  
  - نمودارهای بصری از عملکرد مدل  
    **Visual performance charts**

---

 هدف پروژه  
**Project Goal**

تحلیل داده‌ های بیمه با هدف ساخت مدلی برای پیش‌ بینی ویژگی‌ هایی مثل:  
**Analyzing insurance data to build a model for predicting features such as:**

- هزینه بیمه (insurance charges)  
  **Insurance charges**

---

ابزارهای استفاده ‌شده  
**Used Tools**

- Python 3  
- Pandas, NumPy  
- scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

نویسنده  
**Author**

رامتین قشقائی – [GitHub Profile](https://github.com/ramtin-ghashghaie)  



