# AI Study Assistant

## Project Overview

The AI Study Assistant is an educational application designed to estimate a student's mathematics grade using machine learning and provide personalized study recommendations using a language model.

The application is intended to help students understand their academic performance and identify areas where they may improve their study habits.

The predictions are estimates and should not be used to make important decisions about a student's future.

## AI Areas

### 1. Classical Machine Learning

I will build and evaluate a regression model that estimates a student's final mathematics grade using selected study-related information.

The model will use data from the UCI Student Performance dataset.

### 2. Language Models

A pretrained language model will explain the prediction in simple language and provide practical study suggestions.

### How the Two Areas Work Together

The grade prediction produced by the machine learning model will be passed to the language model. The language model will use the prediction and selected study information to generate understandable feedback.

## Dataset

Source: UCI Machine Learning Repository

Dataset: Student Performance

Link: https://archive.ics.uci.edu/dataset/320/student%2Bperformance

I plan to use the mathematics dataset to train and evaluate the regression model.

## Evaluation

I will evaluate the regression model using Mean Absolute Error (MAE).

I will compare its performance with a simple baseline that always predicts the average final grade in the training data.

## Application

I plan to build a web application using Streamlit.

Users will enter selected study-related information and receive an estimated grade and study recommendations.

## Ethics and Limitations

The dataset may not represent students in Uzbekistan or other educational settings.

Predictions may be inaccurate and should not be treated as facts about a student's ability.

I will explain these limitations clearly in the application.

## Project Status

This project is currently in the proposal stage. Model training, evaluation, and application development are planned future tasks.