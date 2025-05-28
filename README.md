# Movie Recommender System 🎬🍿

Welcome to my university data analytics project, graded 5.0 (top grade), showcasing a **Movie Recommender System** built on the popular MovieLens dataset! This repository demonstrates both **User-Based Collaborative Filtering** and **Content-Based Filtering** approaches, complete with exploratory data analysis, modeling pipeline, and evaluation.

---

## 📖 Table of Contents
1. [Motivation & Goals](#-motivation--goals)  
2. [Dataset](#-dataset)  
3. [Features](#-features)  
4. [Tech Stack](#-tech-stack)  
5. [Author](#-author)  

---

## 🎯 Motivation & Goals
In a world flooded with thousands of movies, how can viewers effortlessly discover films they love? Traditional search often leads to choice paralysis. This project aims to:

- **Learn** individual tastes from past ratings and tags.  
- **Balance** popular blockbusters & hidden gems.  
- **Build** transparent, interpretable recommendation pipelines.  
- **Compare** two classic approaches: user-based CF vs. content-based filtering.

Whether you’re a streaming service or a movie buff, personalized recommendations can transform your viewing experience—and that’s what this project delivers!

## 📊 Dataset
I leverage the **MovieLens ml-latest-small** dataset by GroupLens Research, featuring:

- **~100,000** ratings on a 0.5–5.0 scale  
- **610** active users (each rated ≥20 movies)  
- **9,742** movies across **18** genres  
- **3,683** free-text tags  

This moderate-sized dataset is perfect for rapid prototyping and clear insights into recommender performance.

## ✨ Features
- **User-Based Collaborative Filtering**: Computes cosine similarity among users and aggregates neighbor ratings to predict interests.  
- **Content-Based Filtering**: Profiles movies by genres & tags, then ranks unseen titles by similarity to user preferences.  
- **Exploratory Data Analysis**: Interactive charts on rating distributions, genre popularity vs. rating quality, and tagging behavior.  
- **Evaluation**: Top-10 recommendation precision; CF also reports RMSE.

## 🛠️ Tech Stack
- **RapidMiner**: Data preprocessing & modeling workflows  
- **Tableau**: Charts & plots

## 👤 Author

Tim Benjamin Hoffmann
Electrical Engineering Student, Budapest University of Technology and Economics (BME)
📧 tim.b.hoffmann@gmail.com
