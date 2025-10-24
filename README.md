# YDP2025
## Bank Customer Churn Prediction

โปรเจกต์นี้ใช้ **Machine Learning** ในการทำนายว่าลูกค้าจะเลิกใช้บริการธนาคารหรือไม่ โดยใช้ข้อมูลจาก Kaggle เกี่ยวกับลูกค้าธนาคาร 10,000 ราย ข้อมูลประกอบด้วยพฤติกรรมทางการเงินและข้อมูลส่วนตัว เช่น อายุ, คะแนนเครดิต, ยอดคงเหลือ, รายได้, เพศ, ประเทศ ฯลฯ

## Purpose
1. พัฒนาโมเดลสำหรับการทำนายการปิดบัญชีธนาคารของลูกค้า
2. หา insight สำหรับการวางแผนธุรกิจ

## Features
- โมเดล: **Random Forest, XGBoost, LightGBM**
- วิเคราะห์ **Customer Churn Rate** และแสดงผล **Confusion Matrix, ROC Curve**

## Getting Started
### 1. Clone Repo
```bash
git clone https://github.com/anfar09/YDP2025
cd YDP2025
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run Notebook
เปิดไฟล์ Bank_Prediction.ipynb ใน Google Colab หรือ Jupyter Notebook

## Environment
- Python 3.11+
- Libraries: ดูใน `requirements.txt`

**ก่อนรัน notebook ต้องติดตั้ง dependencies ทั้งหมดด้วย `pip install -r requirements.txt`**
