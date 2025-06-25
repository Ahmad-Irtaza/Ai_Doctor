# AI Doctor: A Desktop-Based Health Assistant

## Introduction

Healthcare is one of the most critical areas where Artificial Intelligence (AI) can be applied to improve decision-making, reduce diagnosis time, and assist medical professionals in delivering timely care. Inspired by the global need for accessible and reliable primary health support systems, we propose the development of a desktop-based **AI Doctor** application.

The purpose of this project is to predict possible diseases based on selected symptoms using basic machine learning logic. This tool aims to assist users in understanding potential health conditions and offer preliminary medical advice through suggestions for medicine and precautions.

The core motivation for building this project stems from the increasing burden on healthcare professionals and the need for early detection mechanisms that are simple, intuitive, and readily accessible. In regions with limited medical infrastructure, such AI-based tools can provide essential support, serving as a first layer of screening before formal consultation with a healthcare provider.

Our application intends to simulate such a tool in a lightweight, beginner-friendly manner using core AI principles.

## Proposed Solution

We aim to develop a desktop application that interacts with the user through a graphical interface built using Python’s Tkinter library. The user will be prompted to select relevant symptoms through checkboxes. Upon submission, the application will process the selected symptoms and predict the most likely disease using a custom implementation of the **Naive Bayes algorithm**.

Unlike traditional approaches that utilize machine learning libraries such as scikit-learn, we will **manually calculate disease probabilities** using frequency-based logic derived from a dataset stored in CSV format. This aligns with our current academic exposure and helps reinforce the fundamentals of probabilistic learning.

The dataset will contain various records mapping binary symptom presence (1 or 0) to disease names.

Based on the predicted disease, the application will retrieve and display **recommended medicine and precautionary steps** from a predefined dictionary. This will offer the user instant feedback that is both informative and actionable.

## Key Features

- GUI-based symptom input using Tkinter  
- Manual Naive Bayes classifier (no external ML libraries)  
- Disease prediction based on custom CSV dataset  
- Instant feedback with suggested medicine and precautions  

## Technologies Used

- Python 3  
- Tkinter for GUI  
- CSV for dataset management  

## Concepts Covered

- Uninformed Search *(Optional for logical tree)*  
- Manual Naive Bayes *(Probabilistic Reasoning)*  
- Data Handling *(CSV)*  
- Simple GUI Design *(Human-Centered)*  

## Conclusion

This project will serve as an excellent beginner-level AI application. It demonstrates how foundational concepts like Naive Bayes can be applied manually to solve real-world problems. With a focus on simplicity, accessibility, and educational value, the **AI Doctor** application has the potential to serve as a learning tool as well as a basic medical support system.

We believe this project aligns well with the learning objectives of the *Applied Artificial Intelligence* course and look forward to developing and presenting it.
