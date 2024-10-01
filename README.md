# belly-button-challenge
# Belly Button Biodiversity Dashboard
Welcome to the Belly Button Biodiversity Dashboard! 🦠

This project explores the microbial diversity found in human navels. The dataset reveals that while most microbial species are rare, a few are found in 
over 70% of people. This dashboard allows you to interactively dive into the data and explore what’s living in our belly buttons!

# Table of Contents

   1. Project Overview
   2. Features
   3. How to Get Started
   4. How It Works
   5. Bar Chart
   6. Bubble Chart
   7. Metadata Panel
   8. Tech Stack
   9. Acknowledgments

# Project Overview

This dashboard provides visualizations and metadata for each sample in the Belly Button Biodiversity dataset.

# Features
# What Does This Dashboard Do?

 1. Top 10 OTUs Bar Chart: Visualizes the top 10 bacterial species (Operational Taxonomic Units or OTUs) found in each sample.
 2. Bubble Chart: Displays all the OTUs for the selected sample in a bubble chart.
 3. Demographic Info: Shows demographic information for each selected sample.
 4. Dynamic Dropdown: Allows users to select a sample ID, updating the bar chart, bubble chart, and demographic panel accordingly.

# How to Get Started
   1. Clone the Repo
   2. Open the Dashboard: Open the index.html file in your browser to view the dashboard locally.
   3. View the Live Version: The dashboard is live! Access it here: Live Dashboard.

# How It Works

The dashboard pulls its data from the Belly Button Biodiversity dataset using D3.js and visualizes the data using Plotly.js.

# Bar Chart

  . Displays the top 10 OTUs found in the selected sample.
  . The x-axis shows the sample values, and the y-axis shows the OTU IDs.
  . Hover over the bars to see additional info about each OTU.

# Bubble Chart

  . Shows all the OTUs in the selected sample.
  . The x-axis shows the OTU IDs, and the y-axis shows the sample values.
  . The size of each bubble represents how abundant that OTU is, and the colors differentiate between OTUs.
# Metadata Panel

  . Displays demographic information of the selected sample, including:
    . ID
    . Ethnicity
    . Gender
    . Age
    . Location

# Tech Stack
 This project uses:

  . D3.js: To load and manipulate the dataset.
  . Plotly.js: For interactive visualizations.
  . HTML/CSS/JavaScript: For building and styling the webpage.
  . GitHub Pages: For hosting the live version of the dashboard.

# Acknowledgments
This project is part of Module 14 of the Data Analysis and Visualization Bootcamp. Special thanks to the contributors of the Belly Button Biodiversity
dataset. Additionally, I would like to acknowledge the use of AI assistance for debugging and resolving issues throughout the Challenge.
