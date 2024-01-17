# Keyword-Network-Analysis-and-Word-Frequency-Analysis-2021-2022

## Introduction

This project focuses on keyword network analysis and tweet analysis using data spanning from 2017 to 2022. The primary objectives include constructing weighted networks based on keyword co-occurrence and analyzing word frequencies and patterns over the years.

## Technologies Used

- R
- Libraries: dplyr, tidytext, ggplot2, igraph, ggraph

## Keyword Network Analysis

### Data Preparation

1. Imported the dataset (`Keyword_data.csv`).
2. Extracted relevant columns for keyword analysis.
3. Constructed a weighted adjacency matrix for keyword co-occurrence.

### Network Visualization

4. Converted the adjacency matrix into a weighted network.
5. Plotted the keyword network using the igraph library.

### Degree and Strength Calculation

6. Calculated the degree and strength of each node in the network.

### Top Keywords and Pairs

7. Identified and printed the top 10 keywords by degree and strength.
8. Printed the top 10 keyword pairs by weight.

### Scatter Plot

9. Generated a scatter plot with average strength on the y-axis and degree on the x-axis.

## Tweet Analysis

### Data Import

10. Imported tweet data for the years 2017 to 2022.

### Text Processing

11. Created stopword lists and removed irrelevant terms.
12. Conducted word frequency analysis for each year.
13. Explored Zipf's law for word frequencies.

### Bigrams Analysis

14. Analyzed bigrams to identify meaningful word pairs.
15. Constructed bigram networks and visualized them using ggraph.

## Conclusion

This README provides an overview of the methods and analyses conducted in the project. For detailed code and outputs, refer to the corresponding R script or notebook.

