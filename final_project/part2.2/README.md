# 📁 Part 2.2

โปรเจกต์นี้เกี่ยวข้องกับการทำ Machine Learning เพื่อจำแนกประเทศตาม Gender Ratio Class โดยใช้ข้อมูลจาก World Bank และกระบวนการเตรียมข้อมูลอย่างเป็นระบบ เช่น การจัดการ Missing Values, Outlier Removal, Feature Selection, และการแก้ไขปัญหา Class Imbalance ด้วย Undersampling พร้อมวิเคราะห์ Bias-Variance Tradeoff เพื่อจูนค่าพารามิเตอร์ในโมเดล Logistic Regression

---

## 📄 รายละเอียดไฟล์

| ไฟล์ | รายละเอียด |
|------|-------------|
| `after_filter_60_percent.csv` | Dataset หลังจากกรอง columns ที่ missing เกิน 60% ออก |
| `after_remove_outlier.csv` | Dataset หลังจากแทนค่า outlier ด้วย median หรือ mode |
| `after_rfe.csv` | Dataset หลังจากทำ Recursive Feature Elimination (RFE) เพื่อคัดเลือกฟีเจอร์ |
| `after_undersampling.csv` | Dataset หลังจากทำ undersampling ให้จำนวนแต่ละ class เท่ากัน |
| `before_filter.csv` | Dataset ดิบก่อนการทำ Data Cleaning |
| `metadata_final.xlsx` | Metadata อธิบายรายละเอียดของตัวแปรใน dataset เช่น ความหมายของแต่ละ column |
| `part2_2.ipynb` | ไฟล์ Notebook สำหรับทำ preprocessing, training และ evaluate โมเดล |
| `worldbank_gender_2021.csv` | ข้อมูลดิบจาก World Bank ปี 2021 ที่ใช้ในโปรเจกต์ |

---
