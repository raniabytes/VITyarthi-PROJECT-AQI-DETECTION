## AQI Detection System

## ⭐Introduction

Air pollution is a growing environmental issue affecting human health and climate systems. The Air Quality Index (AQI) provides a standardized method for interpreting pollutant levels and communicating the associated health risks to the public.
This project implements a Python-based AQI detection system that calculates AQI values for PM2.5 and PM10 using official US EPA standards. The system is simple, accurate, and suitable for learning, analysis, and environmental awareness.

## ⭐ Problem Statement:

Raw pollutant concentration data (e.g., PM2.5, PM10) do not directly indicate how harmful the air is.
Calculating AQI manually is challenging because it requires:
Identifying pollutant breakpoints
Applying EPA linear interpolation

Mapping AQI to air quality categories
The absence of an easy-to-use digital tool makes AQI interpretation difficult for students and beginners.
This project solves the problem by providing a user-friendly Python program that automates AQI calculation and classification.


## ⭐Scope of project:
The scope of the AQI Detection System includes the development of a Python-based application capable of calculating and interpreting air quality levels based on user-provided pollutant concentrations. This project focuses on two major particulate matter pollutants:

PM2.5 (fine particles)

PM10 (coarse particles)

## ⭐ Target users:

1. Students

Learning environmental science, Python programming, or AQI concepts
Useful for academic projects, assignments, and practical demonstrations


2. Educators & Trainers

Teaching air quality, pollution monitoring, or coding fundamentals
Can use the tool to demonstrate AQI calculation logic


3. Developers / Beginners

Individuals practicing Python
Users who want to understand modular programming and data processing


4. Environmental Enthusiasts

People who want to check air quality levels based on raw PM2.5/PM10 values


5. Researchers (Basic Level)

Those needing a simple AQI calculator for small experiments or indoor pollution studies

## ⭐ High-Level Features

Below are the major high-level functionalities provided by the system:

1. Pollutant Input Handling

Accepts PM2.5 and PM10 concentrations directly from the user

Validates numerical input


2. AQI Calculation Engine

Implements the official US EPA AQI calculation method

Uses defined breakpoint tables for PM2.5 and PM10

Applies linear interpolation for accurate results


3. AQI Classification Module

Converts AQI score into a meaningful category such as:

Good

Moderate

Unhealthy

Very Unhealthy

Hazardous




