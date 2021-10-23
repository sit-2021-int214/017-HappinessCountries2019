# 017-StudentPerf_inExam

ที่มาชุดข้อมูล: [Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams)

## 📝 Overview

ชุดข้อมูลชุดนี้เป็นชุดข้อมูลเกี่ยวกับประสิทธิภาพของนักเรียนหรือนักศึกษาในการสอบ 3 หมวด อาทิ คณิตศาสตร์ (Mathematics) การอ่าน (Reading) และการเขียน (Writing) ซึ่งในชุดข้อมูลนี้มีการเก็บข้อมูล เพศ กลุ่มที่อยู่ ระดับการศึกษาของผู้ปกครองของนักเรียน ค่าใช้จ่ายอาหารกลางวัน การเตรียมตัวก่อนสอบ และคะแนนการสอบทั้ง 3 หมวดของนักเรียนหรือนักศึกษาแต่ละคน กลุ่ม **สหายSTAT** (กลุ่มที่ 17) ได้ทำการเลือกชุดข้อมูลนี้นำมาวิเคราะห์ข้อมูลเพื่อค้นหาปัจจัยที่ทำให้นักเรียนหรือนักศึกษาแต่ละคนทำคะแนนการสอบในแต่ละหมวดได้คะแนนแตกต่างกัน อะไรที่ส่งผลต่อความสามารถในการสอบของนักเรียนหรือนักศึกษา เช่น ภูมิหลังครอบครัว ระดับการศึกษาของผู้ปกครองที่อาจเสริมความสามารถของนักเรียนหรือนักศึกษา การฝึกทำข้อสอบก่อนไปสอบสนามจริง ฯลฯ เป็นต้น

## ✏ Purpose

ทำความเข้าใจปัจจัยภูมิหลังครอบครัว การเตรียมตัวสอบก่อนไปสอบสนามจริง ค่าใช้จ่ายอาหารกลางวัน และอื่น ๆ ที่ส่งผลต่อประสิทธิภาพในการสอบของนักเรียนหรือนักศึกษาในหมวดต่าง ๆ

## 🎯 Objective

### Steps

1. ตั้งคำถามที่จะวิเคราะห์ข้อมูล
2. ค้นหาชุดข้อมูลจกาเว็บไซต์ Kaggle
3. ดาวน์โหลด Library กับ Dataset ที่จะใช้วิเคราะห์ข้อมูล
4. สำรวจชุดข้อมูลจากชุดข้อมูลเดิมที่ยังไม่ผ่านการ Cleaning
5. Cleaning ชุดข้อมูลเพื่อทำการวิเคราะห์
6. ตรวจสอบชุดข้อมูลเพื่อทำความเข้าใจชุดข้อมูลแล้วนำไปทดสอบสมมติฐานและตรวจสอบสมมติฐาน

### Define Questions

1. นักศึกษาเพศใดจบปริญญาตรีมากกว่ากัน
2. คนที่ทำคะแนนการสอบทั้งคณิตศาสตร์ การอ่าน และการเขียนได้ 90 คะแนนขึ้นไปมีกี่คน
3. เพศไหนทำคะแนนเฉลี่ยคณิตศาสตร์ได้มากกว่ากัน
4. คะแนนเฉลี่ยในแต่ละวิชาของชายหรือหญิงมีค่ามากน้อยต่างกันเพียงใด
5. ค่าเฉลี่ยการทั้งสอบทั้งคณิตศาสตร์ การอ่าน และการเขียนมีค่าเท่าไร แล้วให้เปลี่ยนชื่อคอลัมน์ให้สื่อความหมาย เช่น `Subject_Score` เป็น `Subject_AVG` ที่จะใช้ summarise
6. ให้หาคนที่ทำคะแนนได้สูงสุด (ได้เต็ม 100 คะแนน) โดยแสดงข้อมูลคอลัมน์ของ เพศ กลุ่ม ระดับการศึกษาของผู้ปกครอง และคะแนนที่ทำได้ทั้งคณิตศาสตร์ การอ่าน และการเขียน

### Tools

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

### References

- [safesit23/INT214-Statistics](https://github.com/safesit23/INT214-Statistics)
- [R Studio Cheatsheets](https://www.rstudio.com/resources/cheatsheets)
- [R Markdown](https://rmarkdown.rstudio.com)
- [R Markdown CheatSheets](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)
- [Markdown Guide](https://www.markdownguide.org)
- [R Documentation](https://www.rdocumentation.org)

## 👨‍🎓 About Us

งานนี้เป็นส่วนของวิชา INT214 Statistics for Information Technology\
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
