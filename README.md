
# Phase 1 Report: Data-Driven Insights for Urban Traffic Management - Intel Unnati Grand Challenge

## Overview

This repository contains the code and data analysis for our project on urban traffic management and safety, as part of Phase 1 of the Intel Unnati Grand Challenge. The initiative leverages data analytics to address transportation challenges in urban environments. Our goal is to improve traffic flow and enhance safety using advanced analytics and machine learning techniques.

## Table of Contents

- [Introduction](#introduction)
- [Data Analysis](#data-analysis)
  - [Frequency of Different Types of Alerts](#frequency-of-different-types-of-alerts)
  - [Frequency of Alerts by Vehicle](#frequency-of-alerts-by-vehicle)
  - [Distribution of Speed During Events](#distribution-of-speed-during-events)
  - [Frequency of Alerts by Day of the Week](#frequency-of-alerts-by-day-of-the-week)
  - [Temporal Analysis](#temporal-analysis)
  - [Vehicle-Based Analysis](#vehicle-based-analysis)
  - [Speed Analysis](#speed-analysis)
- [Geospatial Analysis using QGIS](#geospatial-analysis-using-qgis)
- [Future Work](#future-work)
- [Conclusion](#conclusion)
- [Citations](#citations)

## Introduction

The world's cities are experiencing unprecedented urbanization, leading to various transportation-related challenges such as traffic congestion and safety hazards. Our project focuses on using data analytics to tackle these issues, in collaboration with Intel, to revolutionize urban traffic management.

## Data Analysis

### Frequency of Different Types of Alerts

We analyzed different types of alerts, including Headway Monitoring and Warning (cas_hmw), Lane Departure Warning (cas_ldw), Pedestrian Collision Warning (cas_pcw), and Forward Collision Warning (cas_fcw).

### Frequency of Alerts by Vehicle

The analysis revealed that certain vehicles, identified by their IDs, are more prone to generating specific types of alerts.

### Distribution of Speed During Events

Event speeds generally show a normal distribution, with most events occurring at speeds of 40-60 km/h.

### Frequency of Alerts by Day of the Week

Alert frequency is consistent throughout the week, with a slight increase on Thursdays and Fridays.

### Temporal Analysis

This section explores how alert frequency changes over different hours of the day and over a two-month period.

### Vehicle-Based Analysis

We investigated whether specific vehicles are more likely to generate particular types of alerts.

### Speed Analysis

We examined the connection between speed and the types of alerts generated.

## Geospatial Analysis using QGIS

Using QGIS, we identified specific areas ("hotspots") prone to incidents and analyzed the geographical distribution of different alert types.

## Future Work

- **Spatial Analysis**: Identify specific areas needing safety improvements.
- **Predictive Analytics**: Predict when and where alerts are likely to occur.
- **Vehicle Analysis**: Understand how different vehicle types impact safety.
- **Driver Behavior**: Explore the effects of driver actions on alert generation.
- **Traffic Control Integration**: Combine alert data with traffic control systems for real-time adjustments.

## Conclusion

Our collaboration with Intel has provided valuable insights into urban traffic management. By using data and technology, we aim to enhance traffic management, encourage safer driving, and reduce accidents, highlighting the importance of data in solving modern transportation challenges.

## Citations

For further details and interactive visualizations, visit our GitHub repository: [The Elites IGC](https://github.com/ebin-alex/The-Elites-IGC.git)
