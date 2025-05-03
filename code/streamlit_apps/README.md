# Streamlit Apps

This folder contains Streamlit applications designed to provide interactive web-based interfaces for data visualization, analysis, and interaction. These apps complement the KNIME workflows and Python scripts by offering an accessible way to explore and present data.

## Overview

The Streamlit apps in this folder aim to:
- Provide user-friendly interfaces for data exploration.
- Visualize data and analytics results interactively.
- Extend the functionality of KNIME workflows and Python scripts.

## Structure

The folder is organized as follows:
- **`apps/`**: Contains individual Streamlit app scripts.
- **`data/`**: Sample datasets used by the apps.
- **`config/`**: Configuration files for app customization.
- **`README.md`**: Documentation for the Streamlit apps folder.

## Prerequisites

To run the Streamlit apps, ensure you have:
1. Python 3.8 or later installed.
2. Required dependencies installed (see `requirements.txt`).

## Setup

1. Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Navigate to the folder containing the app script.
2. Run the app using Streamlit:
   ```bash
   streamlit run app_name.py
   ```
3. Open the provided URL in your web browser to interact with the app.

## Contribution

Feel free to contribute by:
- Adding new Streamlit apps.
- Improving existing apps.
- Updating documentation.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).