
  # 📣 Datactives, Data Science Rakamin Academy MSIB 2023 Final Project
   E-Commerce Shipping Data Product Shipment Delivered on time or not? To Meet E-Commerce Customer Demand
   
### 🎏 Team Name : Datactives
### 💪 Team Members 
- Yudha Adi Putra
- Dendi Pratama Putra Pamungkas
- Muhammad Syahril
- Glody Syah Rabbynawa
- Susi Amelia
- Sindi Mustika Putri
- Sailina Karimah Syarifudin
- Ummul Khaeria Rasyid
  
  Theme : E-Commerce Shipping Data

### 💻 Tech stack
  |Step|Library|
  |---|---|
  |Exploratory Data Analysis|![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) |
  |Modeling|![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)|
 
### 📂 Dataset
|![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)|[Dataset](https://www.kaggle.com/datasets/prachi13/customer-analytics/data)|
|---|---|

### 💁‍♀️ How to use

- Install Python requirements `pip install -r requirements.txt`
- Start the server for development `python3 main.py`

### Sumary
# Data Cleansing
- Handle Mising Values tidak perlu dilakukan karena data tidak memiliki missing value.
- Handle Duplicated data tidak dilakukan karena tidak ada data yang duplikat,
- Handle Outliers menggunakan metode Z Score terjadi penurunan Outliers sebanyak 3%.
- Feature Transformation 
- Feature Encoding
- Handle Class Imbalance Data kolom target terlihat cukup seimbang , sehingga tidak perlu dilakukan Handle class imbalance.

# Feature Engineering
Berdasarkan heatmap yg akan dipilih kolom dengan the threshold (0,05) dengan kolom target Reached.on.Time_YN: Customer_care_calls, Cost_of_the_Products, Prior_Purchases, Discount_offered, dan Weight_in_grms.
