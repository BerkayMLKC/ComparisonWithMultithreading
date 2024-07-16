# Multithreading Comparison Project

Welcome to the **Multithreading Comparison Project**! This repository contains a Python-based project designed to compare data rows using multithreading, optimizing processing speed and efficiency. The project includes a graphical user interface for easy interaction.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Project Report](#project-report)

## Project Overview

The **Multithreading Comparison Project** was developed as part of a university programming lab course. The goal is to preprocess a given dataset, clean it, and compare rows using multiple threads to enhance performance. The project also allows for customized comparison criteria through a user-friendly GUI.

### Objectives

- Preprocess and clean a dataset by removing unnecessary columns, null values, and stop words.
- Compare dataset rows based on user-defined criteria using multithreading.
- Display results and performance metrics on a graphical interface.
- Using page system for showing results to prevent lagging on GUI. 

## Features

- **Data Preprocessing:** Automated cleaning of datasets to prepare for comparison.
- **Multithreaded Comparison:** Use of Python’s threading capabilities to compare data rows efficiently.
- **Customizable Parameters:** Users can define similarity thresholds and the number of threads to be used.
- **Graphical User Interface:** Easy-to-use interface created with Tkinter.
- **Detailed Performance Metrics:** Displays the time taken for operations and the efficiency of different thread counts.

## Usage

1. Run the main Python script:
    ```bash
    python main.py
    ```

2. A GUI will appear, prompting you to input the necessary parameters:
   - **Column Name:** The column to be used for comparison.
   - **Minimum Similarity Threshold:** The minimum similarity required for comparison.
   - **Maximum Similarity Threshold:** The maximum similarity allowed for comparison.
   - **Number of Threads:** The number of threads to be used for processing.

3. Click "Start Comparison" to begin the data processing and comparison.

4. Results will be displayed in the GUI, showing matched rows and performance metrics.

## Methodology

### Data Preprocessing

1. **Load Data:** Import the dataset in CSV format.
2. **Clean Data:** Remove null values, unnecessary columns, and stop words.
3. **Save Clean Data:** Save the cleaned data to a new CSV file for faster access in future runs.

### Multithreaded Processing

1. **User Input:** Collect comparison criteria and thread count from the GUI.
2. **Thread Management:** Create and manage threads to handle data comparison tasks concurrently.
3. **Data Comparison:** Compare rows within the dataset based on the similarity thresholds provided.
4. **Display Results:** Show the comparison results and performance metrics on the GUI.

### Performance Metrics

- Time taken for each thread to process data.
- Overall time taken for the comparison process.
- Efficiency improvements with different thread counts.

## Results

The project successfully demonstrates how multithreading can be used to optimize data comparison tasks. Users can customize the comparison parameters and observe the impact of multithreading on processing time and efficiency.

## Project Report

You can review the project report [here](MultithreadingRep.pdf).
