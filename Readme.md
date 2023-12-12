
---

# Spanish Train Ticket Data Analysis

## Overview

This repository contains the code and analysis for cleaning, exploring, and visualizing Spanish train ticket data using Python. The dataset includes information about train trips, such as departure and arrival details, ticket prices, and vehicle types.

## Project Structure

- **1. Importing and Exploring Data**
  - Imported the dataset (`train_ticket_data.csv`).
  - Examined the first few rows and data types using `head()` and `info()`.

```python
import pandas as pd

# Code for importing and exploring data
# ...
```

- **2. Data Cleaning and Transformation**
  - Checked for missing values and handled them.
  - Transformed data types for memory optimization.
  - Created additional columns for analysis.

```python
# Code for data cleaning and transformation
# ...
```

- **3. Statistical Analysis**
  - Calculated average, minimum, and maximum prices and durations.
  - Explored rows with the highest and lowest prices.
  - Compared fares for tickets departing from Madrid and Barcelona.

```python
# Code for statistical analysis
# ...
```

- **4. Ridership and Revenue Analysis**
  - Built a dual-axis line chart for daily ridership and revenue.
  - Grouped data by departure date and calculated ridership and total fare.

```python
# Code for ridership and revenue analysis
# ...
```

- **5. Ridership by Day of Week and Departure Location**
  - Created a bar chart to visualize average ridership by day of the week and departure location.

```python
# Code for ridership by day of week and departure location
# ...
```

- **6. Price and Duration Comparison by Train Type**
  - Developed bar charts to compare average price and duration by vehicle category.

```python
# Code for price and duration comparison by train type
# ...
```

- **7. Price Heatmap Analysis**
  - Constructed a heatmap to visualize average prices based on departure day and time.

```python
# Code for price heatmap analysis
# ...
```

## Results

Include any insights, trends, or interesting findings from your analysis.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spanish-train-ticket-analysis.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks or Python scripts for each analysis step.

## Resources

- [Documentation](link-to-documentation)
- [Dataset](link-to-dataset)

Feel free to explore the Jupyter notebooks (`analysis_notebooks/`) for detailed code and visualizations.

## Acknowledgments

- Thank you to [Data Source Provider] for providing the Spanish Train Ticket dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
