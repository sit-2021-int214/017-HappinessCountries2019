# 017-StudentPerf_inExam

ที่มาชุดข้อมูล: [Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams)

## 📝 Overview

ชุดข้อมูลชุดนี้เป็นชุดข้อมูลเกี่ยวกับประสิทธิภาพของนักเรียนหรือนักศึกษาในการสอบ 3 หมวด อาทิ คณิตศาสตร์ (Mathematics) การอ่าน (Reading) และการเขียน (Writing) ซึ่งในชุดข้อมูลนี้มีการเก็บข้อมูล เพศ กลุ่มที่อยู่ ระดับการศึกษาของผู้ปกครองของนักเรียน ค่าใช้จ่ายอาหารกลางวัน การเตรียมตัวก่อนสอบ และคะแนนการสอบทั้ง 3 หมวดของนักเรียนหรือนักศึกษาแต่ละคน กลุ่ม**สหายSTAT** (กลุ่มที่ 17) ได้ทำการเลือกชุดข้อมูลนี้เพื่อนำมาวิเคาระห์ข้อมูลเพื่อค้นหาปัจจัยที่ทำให้นักเรียนหรือนักศึกษาแต่ละคนทำคะแนนการสอบในแต่ละหมวดได้คะแนนแตกต่างกัน อะไรที่ส่งผลต่อความสามารถในการสอบของนักเรียนหรือนักศึกษา เช่น ภูมิหลังครอบครัว ระดับการศึกษาของผู้ปกครองที่อาจเสริมความสามารถของนักเรียนหรือนักศึกษา การฝึกทำข้อสอบก่อนไปสอบสนามจริง ฯลฯ เป็นต้น

## ✏ Purpose

ทำความเข้าใจปัจจัยที่ภูมิหลังครอบครัว การเตรียมตัวสอบก่อนไปสอบสนามจริง ค่าใช้จ่ายอาหารกลางวัน และอื่น ๆ ที่ส่งผลต่อประสิทธิภาพในการสอบของนักเรียนในหมวดต่าง ๆ

## 🎯 Objective

### Steps

1. Define questions
2. Search datasets from Kaggle
3. Download Library and dataset
4. Explore the dataset from the original dataset
5. Cleaning Dataset
6. Exploratory Data Analysis

### Define Questions

1. นักศึกษาเพศใดจบปริญญาตรีมากกว่ากัน
2. คนที่ทำคะแนนการสอบทั้งคณิตศาสตร์ การอ่าน และการเขียนได้ 90 คะแนนขึ้นไปมีกี่คน
3. เพศไหนทำคะแนนได้มากกว่ากัน
4. คะแนนเฉลี่ยในแต่ละวิชาของชายหรือหญิงมีค่ามากน้อยต่างกันเพียงใด
5. ค่าเฉลี่ยการทั้งสอบทั้งคณิตศาสตร์ การอ่าน และการเขียนมีค่าเท่าไร แล้วให้เปลี่ยนชื่อคอลัมน์ให้สื่อความหมาย เช่น `Subject_Score` เป็น `Subject_AVG` ที่จะใช้ summarise
6. ให้หาคนที่ทำคะแนนได้สูงสุด (ได้เต็ม 100 คะแนน) โดยแสดงข้อมูลคอลัมน์ของ เพศ กลุ่ม และคะแนนที่ทำได้ทั้งคณิตศาสตร์ การอ่าน และการเขียน

### 🛠 Tools

- R Language
- R Studio Desktop

## 📁 Table of Contents

1. [Exploratory Data Analysis](https://github.com/sit-2021-int214/017-StudentPerf_inExam/blob/main/01_explore.md)
2. [Data Visualization](https://github.com/sit-2021-int214/017-StudentPerf_inExam/blob/main/StudentPerf.R)

## 📌 Resources

### Important Files in Repository

- [StudentPerf.R](https://github.com/sit-2021-int214/017-StudentPerf_inExam/blob/main/StudentPerf.R): Exploratory Data Analysis
- [StudentsPerformance_Original.csv](https://github.com/sit-2021-int214/017-StudentPerf_inExam/blob/main/StudentsPerformance_Original.csv): Original Dataset
- [StudentsPerformance_Clean.csv](https://github.com/sit-2021-int214/017-StudentPerf_inExam/blob/main/StudentsPerformance_Clean.csv): Cleaned Dataset

## 👨‍🎓 About Us

งานนี้เป็นส่วนของวิชา INT214 Statistics for Information technology\
ภาคเรียนที่ 1\
ปีการศึกษา 2564\
คณะเทคโนโลยีสารสนเทศ\
มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี

### Team: สหายSTAT

| No. | Firstname/Lastname | Student ID  |
| :-: | ------------------ | :---------: |
| 1   | นายชาญ ทองเจิม      | 63130500019 |
| 2   | นายธนาคาร จันทร์หอม  | 63130500052 |
| 3   | นายปาณัสม์ อ่อนมั่นคง  | 63130500080 |

### Instructor

- ATCHARA TRAN-U-RAIKUL
- JATAWAT XIE (Git: [safesit23](https://github.com/safesit23))
