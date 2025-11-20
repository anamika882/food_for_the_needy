# food_for_the_needy

A new Flutter project.

## Getting Started

while running this project remove ngo folder and run that ngo folder seperately


# 🍽️ Food for the Needy – ML-Based Food Stall Optimization App

**Food for the Needy** is an Android + Machine Learning application designed to help NGOs determine the *most optimal food stall locations* based on real-time user demand.  
The system collects geolocation requests from users who need food and uses clustering algorithms to recommend the best areas for setting up food distribution stalls.

---

## 🚀 Features

### 📍 User Location Collection
The Android app allows users to:
- Request food assistance
- Send their GPS coordinates to the server
- View available distribution locations

### 🤖 Machine Learning (Python Backend)
The ML module analyses all user location data and identifies:
- High-demand zones  
- Optimal food stall placement  
- Data patterns, clusters, and geographic density  

### 🗺️ Algorithm-Generated Heatmaps
The system creates visual plots to show:
- User distribution  
- Cluster centers  
- High-demand hotspot regions  

### 🧭 Updated Stall Recommendations
The ML model computes and updates:
- Optimal number of stalls  
- Exact geographic coordinates for each stall  
- Location changes based on real-time requests  

---

## 🛠️ Tech Stack

### **Mobile App**
- Android (Java / XML)
- Firebase / API integration
- Google Maps API

### **Machine Learning / Backend**
- Python  
- NumPy, Pandas  
- Matplotlib  
- Scikit-learn  
- Geopy (distance calculation)

---

## 📊 Machine Learning Algorithms Used

This project uses four clustering algorithms to analyse user-location data:

### 🔹 **1. K-Means Clustering**
- Creates initial clusters of users  
- Helps identify high-demand areas  

### 🔹 **2. Elbow Method**
- Determines the optimal number of food stalls  

### 🔹 **3. Mean-Shift Clustering**
- Density-based refinement  
- Generates more accurate optimal centers  
- Used for final stall location output  

### 🔹 **4. DBSCAN**
- Detects noise/outliers  
- Helps understand irregular request patterns  

### 🔹 **5. Gaussian Mixture Model (GMM)**
- Models distributions of request locations  
- Useful for detecting elliptical clusters  

> **Note:** The provided project demonstrates visual validation of clusters but does not include numerical accuracy metrics.

---

## 📁 Project Structure




