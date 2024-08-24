# Optimizing Hospital Resource Allocation During a Pandemic: A COVID-19 Simulation Study
## Simulating Hospitals’ Intake of COVID-19 Patients with Arena

## Team #13
- **Arkaprabha Bhattacharyya**
- **Chidubem Nuela Enebechi**
- **Jamie MacLaren**
- **Omar Zu'bi**

## Course
IE 580: Team #13

---

## Table of Contents
1. [Introduction](#1-introduction)
2. [Problem Description](#2-problem-description)
3. [Solution Approaches](#3-solution-approaches)
4. [Simulation Modeling](#4-simulation-modeling)
5. [Design of Experiments](#5-design-of-experiments)
6. [Results](#6-results)
7. [Conclusions and Discussion](#7-conclusions-and-discussion)
8. [References](#8-references)

---

## 1. Introduction
COVID-19 severely impacted the U.S. economy and strained the healthcare system. Hospitals faced a $202.8 billion loss over four months due to increased costs, canceled procedures, and the need for protective equipment and staff support. This project explores how hospitals can balance patient care during a pandemic while maintaining financial viability.

## 2. Problem Description
The project simulates a hospital's response to a health crisis like COVID-19. It focuses on managing resources in a two-story hospital, where each floor has three units: general care, moderate care, and intensive care (ICU). The goal is to find optimal strategies for treating COVID-19 patients while minimizing revenue loss from canceled procedures.

## 3. Solution Approaches
The simulation allocates doctors, nurses, and beds across units and floors. Patients are categorized based on their condition and follow specific treatment flows. The model aims to optimize resource allocation to maximize hospital revenue while effectively treating patients.

## 4. Simulation Modeling
A simulation model was created to adjust resources and find the optimal balance between COVID-19 patients and planned procedures. The model includes six patient types and simulates various scenarios to determine the most effective allocation of resources.

## 5. Design of Experiments
The project team conducted experiments using OptQuest for Arena Simulation to find the optimal resource allocation. The goal was to maximize revenue by adjusting the number of beds and nurses on each floor. The experiments replicated early pandemic conditions and explored various scenarios to improve financial outcomes.

## 6. Results
The baseline simulation model generated a revenue of $2,770,115, which was optimized to $3,654,654 by adjusting resource allocations. The optimized model suggested allocating 80% of ICU and general care beds, and 50% of moderate care beds to COVID-19 patients, with corresponding adjustments to nurse and doctor allocations.

## 7. Conclusions and Discussion
The simulation demonstrated that increasing elective procedures during a pandemic can significantly boost hospital revenue. The model's limitations include not accounting for patient retention and using a simplified version of Arena. Future work could address these constraints and improve the model's accuracy.

## 8. References
- [1] American Hospital Association. (2020). Financial Impact of COVID-19 on Hospitals and Health Systems.
- [2] Source for Cardiac Surgery Revenue Data.
- [3] Source for Orthopedic Surgery Revenue Data.
- [4] Source for Cesarean Surgery Revenue Data.
- [5] Levitt, et al. (2020). Projections of COVID-19 Impact on Healthcare Systems.
