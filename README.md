# Smartwatch Fitness Data Analysis: Insights into Daily Activity

## Introduction

This project analyzes fitness data collected from a smartwatch, focusing on physical activity trends such as step count, distance covered, calories burned, and walking efficiency. The analysis provides insights into user activity patterns throughout the day.

## Analysis Overview

The analysis explores fitness activity trends using time-series visualizations, aggregated metrics, and efficiency calculations. It aims to help users understand their daily movement habits and optimize their fitness goals.

## Features

### 1. Data Preprocessing and Transformation
- Load and clean the dataset.
- Handle missing values and convert time-based data into a structured format.

### 2. Time-Series Analysis
- **Step Count Over Time**: Visualizes how step count changes throughout the day.
- **Distance Covered Over Time**: Shows variations in walking distance.
- **Energy Burned Over Time**: Tracks calories burned across different times of the day.
- **Walking Speed Over Time**: Displays fluctuations in walking speed.

### 3. Aggregated Activity Analysis
- **Daily Step Count Trends**: Calculates and visualizes average step count per day.
- **Walking Efficiency**: Computes efficiency as `Distance / Step Count` to understand movement effectiveness.

### 4. Time-Based Activity Segmentation
- Categorizes activity into **Morning, Afternoon, and Evening** based on recorded time.
- Analyzes variations in movement patterns across different periods of the day.

### 5. Summary Metrics and Visualization
- **Treemap Representation**: Provides an overview of daily average fitness metrics in a compact visual format.

## Dataset

The dataset used in this analysis includes the following columns:
- **Date**: The recorded date of activity.
- **Time**: The specific time of activity recording.
- **Step Count**: The number of steps taken.
- **Distance**: The distance covered (in kilometers).
- **Energy Burned**: The number of calories burned.
- **Flights Climbed**: The number of floors climbed.
- **Walking Double Support Percentage**: The percentage of time spent with both feet on the ground while walking.
- **Walking Speed**: The average walking speed (in km/h).

## Visualizations

- **Step Count, Distance, Energy Burned, and Walking Speed Over Time**: Line charts showing daily movement trends.
- **Daily Step Count Trends**: Bar chart representing step count averages per day.
- **Walking Efficiency Over Time**: Line chart analyzing movement effectiveness.
- **Activity Distribution by Time Segments**: Visualization categorizing activity into different time intervals.
- **Treemap of Daily Averages**: Compact representation of summarized fitness data.

