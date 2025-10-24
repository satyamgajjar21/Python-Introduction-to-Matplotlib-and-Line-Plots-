<p align="center">
  <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="200" alt="Skills Network Logo">
  </a>
</p>

# Introduction to Matplotlib and Line Plots 🎨📈

> **Estimated time:** 20 minutes  
> **Author:** [Alex Aklson, Ph.D.](https://www.linkedin.com/in/aklson/)  
> **Contributors:** [Jay Rajasekharan](https://www.linkedin.com/in/jayrajasekharan), [Ehsan M. Kermani](https://www.linkedin.com/in/ehsanmkermani), [Slobodan Markovic](https://www.linkedin.com/in/slobodan-markovic), [Weiqing Wang](https://www.linkedin.com/in/weiqing-wang-641640133/), [Dr. Pooja](https://www.linkedin.com/in/p-b28802262/)

---

## 🎯 Objectives

After completing this lab, you will be able to:

- Create data visualizations with Python  
- Use **Matplotlib** and **Pandas** to create and customize line plots  

---

## 🧠 Introduction

This lab introduces **Matplotlib**, the standard plotting library in Python, and demonstrates how to create **line plots** using real-world data.  
Make sure you have completed the *Pandas* refresher labs before starting this one.

---

## 🗂 Table of Contents

1. [Pandas Refresher](#pandas-refresher)  
2. [Dataset: Immigration to Canada (1980–2013)](#dataset)  
3. [Visualizing Data using Matplotlib](#visualizing-data)  
4. [Matplotlib and Pyplot](#matplotlib-and-pyplot)  
5. [Line Plots](#line-plots)

---

## 🐼 Pandas Refresher <a id="pandas-refresher"></a>

If you need to revisit data exploration and preprocessing, check the [Data Pre-processing with Pandas Lab](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/labs/v4/DV0101EN-Exercise-Dataset-Preprocessing-Exploring-with-Pandas.ipynb).

---

## 📊 Dataset <a id="dataset"></a>

**Dataset:** [International Migration Flows to and from Selected Countries — 2015 Revision](https://www.un.org/development/desa/pd/data/international-migration-flows)  
We focus on immigration to **Canada** between **1980–2013**.

📥 Download dataset:  
[Canada.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Canada.csv)

---

## ⚙️ Setup

Install dependencies:
```bash
pip install pandas numpy matplotlib
