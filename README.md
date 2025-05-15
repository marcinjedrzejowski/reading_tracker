
# 📚 Reading Tracker Dashboard

Insert Image Here

## Introduction

This **Reading Tracker Dashboard** was created to help myself to visualize and analyze my reading habits over time. It provides insights into genres, formats, reading durations, and author demographics. The data is compiled from personal reading logs and showcases how Excel can be used to build a dynamic and interactive dashboard.

### 📁 Dashboard File

The final dashboard is available in [Reading_Tracker.xlsx](Reading_Tracker.xlsx)

The following Excel features were utilized to build the dashboard:

- **📈 Pivot Charts**
- **🧮 Formulas and Functions**
- **✅ Data Validation**
- **📅 Slicers and Pivot Tables**

## 📚 Dataset Overview

The dataset includes detailed information on:

- **Book Titles and Series**
- **Author Names, Countries, and Genders**
- **Reading Start and End Dates**
- **Categories and Formats**
- **Reading Time and Page Counts**
- **Status (Read, Reading, Queue)**

## 📈 Dashboard Highlights

### 📘 Books Read by Format

Visual breakdown of books read across different formats:
- **Ebook**
- **Paperback**
- **Audiobook**
- **Hardcover**

### 🌍 Books by Author Nationality

A map/chart showing the distribution of books read by the author's country of origin.

### 📅 Pages Read per Year

A time-series chart showing how many pages were read each year, helping track reading consistency.

### 🏆 Top 5 Genres

A bar chart highlighting the most frequently read genres, with **Fantasy** leading the list.

### ⏳ Average Reading Time

Insights into how many days it typically takes to finish a book.

## 🧠 Formulas and Functions

Examples of Excel logic used:

```excel
=IF([@status]="Read";[@[finished_reading]]-[@[started_reading]];"")
```


#### 🎯 Purpose

Calculates reading time for ebooks that have been read.


## ✅ Data Validation

Slicer was used to:

- Filter by **year**
- Ensure consistent data entry
- Enhance dashboard interactivity

## 📌 Conclusion

This Reading Tracker is a simple tool to reflect on their reading journey. It not only tracks what you’ve read but also reveals patterns and preferences that can guide future reading choices.
