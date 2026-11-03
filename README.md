# Customer Ticket Resolution Analysis & Insights Dashboard
## Project Overview 
This project analyzes customer support ticket data to understand ticket resolution patterns, identify trends, and generate insights that can help improve customer support operations.

## Tools & Technologies 
- **Google Colab** – Notebook environment for writing and executing Python code.
- **Python** – Programming language used for data analysis.
- **Pandas** – Data manipulation and analysis.
- **Matplotlib** – Data visualization and charts.

## Dataset description
The dataset contains customer support ticket records with 17 columns covering customer demographics, product purchases, ticket details, resolution metrics, and customer satisfaction.

**Key data attributes include:**

- **Customer Information:** Customer name, email, age, and gender.
- **Product Information:** Product purchased and purchase date.
- **Ticket Details:** Ticket type, subject, description, status, priority, and channel.
- **Resolution Metrics:** Resolution details, first response time, and time to resolution.
- **Customer Feedback:** Customer satisfaction rating.

## Key Analysis & Insights
The project explores customer support ticket patterns, resolution performance, customer satisfaction, and ticket trends through data analysis and visualizations.

**Analysis Performed:**
- Ticket distribution by category and priority.
- Ticket volume across different support channels.
- Average resolution time by ticket priority and channel.
- Monthly and day-wise ticket trends.
- Relationship between resolution time and customer satisfaction.
- Comparison of high-priority ticket resolution time against the overall average.

**Key Findings:**
- Technical issues represented the highest ticket category, with 907 tickets.
- Chat was the most frequently used support channel, accounting for 2,085 tickets.
- October 2020 recorded the highest monthly ticket volume, with 197 tickets.
- Tuesday recorded the highest number of tickets, with 624 tickets.
- Phone support had the shortest average time between first response and resolution (2.23 hours).
- High-priority tickets averaged 2.71 hours between first response and resolution, compared with 2.52 hours overall.
- The analysis showed a positive correlation (0.645) between resolution time and customer satisfaction ratings.

## Visualizations
The project uses Matplotlib to visualize customer support ticket data and highlight patterns across different dimensions.

**The visual analysis includes:**

- Ticket distribution by category and priority.
- Ticket volume across support channels.
- Monthly and weekly ticket trends.
- Average resolution time comparisons.
- Customer satisfaction and resolution time relationship.

## How to Run the Project

1. Clone this repository. 
2. Open the project in Jupyter Notebook or Google Colab.
3. Load the customer_support_tickets.csv dataset.
4. Run the notebook cells sequentially to reproduce the analysis and visualizations.