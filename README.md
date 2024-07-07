# Iris Dataset Visualization

This Dash app visualizes the Iris dataset using a scatter plot, allowing users to select different varieties of Iris flowers.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Overview

This web application displays a scatter plot that shows the relationship between Sepal Width and Sepal Length of Iris flowers. Users can choose different varieties (Setosa, Versicolor, Virginica) from a dropdown menu to dynamically update the plot.

## Setup

To run this application locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Install dependencies:**

   Make sure you have Python installed. Then, install the required libraries using pip:

   ```bash
   pip install dash pandas plotly
   ```

3. **Run the app:**

   Execute the Python script to run the Dash app:

   ```bash
   python app.py
   ```

   The app will be running locally at `http://127.0.0.1:8050/`.

## Usage

- Select a variety from the dropdown menu to update the scatter plot accordingly.
- Explore the relationship between Sepal Width and Sepal Length for different Iris varieties.

## Dependencies

- [Dash](https://dash.plotly.com/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly](https://plotly.com/python/)




