# AXA MANSARD INVESTMENT ANALYSIS

# TABLE OF CONTENT
- [AXA MANSARD INVESTMENT OVERVIEW](#axa-mansard-inestment-overview)
- [DATA SOURCE](#data-source)
- [TOOLS](#tools)
- [DATA PROCESSING](#data-processing)
- [SKILLS DEMONSTRATED](#skills-demonstrated)
- [OBJECTIVES/ PROBLEM STATEMENT](#objectives-/-problem-statement)
- [DATA ANALYSIS AND VISUALIZATION](#data-analaysis-and-visualization)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

# AXA MANSARD INVESTMENT OVERVIEW
This report presents a comprehensive analysis of my husband's money market investment with AXA Mansard from 2019 to 2024, based on the provided dataset. The primary objective of this analysis is to track deposits, liquidations, and profits generated from the money market investment. By examining these financial activities, this report aims to provide clearer insights into investment performance and offer strategic recommendations on optimizing returns by minimizing withdrawals or liquidations.

# DATA SOURCE
The dataset was obtained from AXA Mansard in PDF format. To make it usable for analysis, a PDF converter was used to transform the data into an Excel file. Since the extracted data was messy, it was cleaned and structured in Microsoft Excel before further processing.

# TOOLS
- Microsoft Excel: This was used for initial data loading and cleaning, transforming the raw dataset into a structured format suitable for analysis.
- Power BI: Employed for the main analysis and data visualization, enabling the extraction of key insights through DAX measures and visual tools.

# DATA PROCESSING
### Data Transformation:
Several steps were taken in Power Query (Microsoft Excel) to ensure the data was clean and well-structured:
- Data types were standardized.
- The first row was promoted to headers for consistency.
![axa cleaning](https://github.com/user-attachments/assets/66d9c389-07f7-4c4a-b357-470801289473)

### Data Preparation in Power BI:
After loading the cleaned data into Power BI, the following transformations and enhancements were made:

* Date column breakdown: The day, month, and year were extracted to facilitate time-based analysis.
![Axa cleaning 2](https://github.com/user-attachments/assets/ad4550df-3bd2-4f65-b6aa-6d2894202af2)

* Creation of a new table: A separate table was generated to highlight the largest withdrawals (sales).
![Axa Top withdraw](https://github.com/user-attachments/assets/bc506641-d079-48a1-9a14-a0ab847fcfed)

* Addition of key measures to enhance the analysis:

  - Total Inflow (sum of all deposits/purchases)
![Axa Inflow](https://github.com/user-attachments/assets/bd3b3aba-33a1-4202-9319-718dbc32a0b0)

  - Total Outflow (sum of all withdrawals/sales)
![Axa outflow](https://github.com/user-attachments/assets/1059e440-a46e-4d7c-9fd1-b4a1f42d51d6)

  - Net Cash Flow (difference between inflow and outflow)

  - Quarterly Returns (to track investment gains over time)
![Axa Quarter](https://github.com/user-attachments/assets/216a7258-9a03-4160-b84a-2a4345c9f152)

# SKILLS DEMONSTRATED
This analysis involved multiple data processing and analytical techniques, including:
- Data Extraction & Transformation: Converting PDF data and cleaning it in Excel.
- Data Processing & Cleaning: Structuring messy data using Power Query.
- Data Analysis & Quick Measures: Creating meaningful insights with DAX measures in Power BI.
- Visualization & Reporting: Presenting findings in a clear and actionable format.
- Critical Thinking & Problem-Solving: Identifying key financial trends and investment opportunities.

# OBJECTIVES / PROBLEM STATEMENT
The primary objectives of this analysis are to:
- Track the inflow and outflow of money over the investment period.
- Calculate the Return on Investment (ROI) to evaluate profitability.
- Determine the Net Cash Flow to assess overall financial standing.
- Track total profits earned over the years and identify areas for optimization.

# DATA ANALYSIS AND VISUALIZATION
The analysis reveals several key financial insights related to the investment performance:
- Net Cash Flow: The account shows a negative cash flow of -8,409,749.65 over the course of the investment period. This indicates that outflows (withdrawals or liquidations) exceeded the inflows (deposits or purchases), leading to a net cash loss.

- Return on Investment (ROI): The ROI stands at -19.69%, highlighting that the investment did not yield positive returns and resulted in a loss. For every 100 units invested, 19.69 units were lost.

- Total Investment Profit: Despite the negative cash flow and ROI, the total profit generated from the investment over the years amounts to 720,487.31.

- Monthly Inflow and Outflow:
   * The highest monthly inflow was recorded in March, totaling 6,498,004.10.
  ![Axa infow](https://github.com/user-attachments/assets/814de9e5-7a42-42ba-9cb4-ed0d0543bbe8)

   * The highest outflow occurred in the same month, with a total of 9,212,434.46. This suggests that March was a particularly active month for transactions, especially liquidations.
![Axa outflow2](https://github.com/user-attachments/assets/030fb9e1-8178-4d20-bd0a-ed833a75144d)

- Sales and Purchase Frequency:
   * October had the highest number of sales transactions, with 34 recorded sales.
   * April witnessed the highest number of purchase transactions, with 25 purchases made. This gives a sense of the transaction activity distribution across different months.
  ![Axa frequency](https://github.com/user-attachments/assets/4e72c3d4-0fdf-464c-99ae-25e42310db75)

- Top Largest Withdrawals:
   * The largest withdrawal occurred on March 31, 2021, with a transaction of 4,000,000.
   * The second-largest withdrawal was on March 30, 2021, amounting to 3,000,000. These transactions significantly contributed to the overall outflow.
![Axa withdrawals](https://github.com/user-attachments/assets/8eaa07d3-14a9-45b2-94c6-cc8cd3acb489)

- Highest Quarterly Profits:
   * The quarter with the highest profit was Q4 2024 (October), where a profit of 143,336.00 was recorded.
   * The second-highest profit occurred in Q2 2020 (April), with a total of 127,665.75. These figures show the periods when the investment performed well in terms of profits.
  ![Axa quarterly](https://github.com/user-attachments/assets/b34224ba-9c58-424b-8058-1f79f3f0e5fb)

- Sales and Purchase Proportion:
   * The total sum of sales (withdrawals) is 42,733,147.61, representing 55.46% of the total transactions.
   * The total sum of purchases (deposits) is 34,323,397.96, accounting for 44.54% of the transactions. This analysis shows that withdrawals exceeded deposits over the investment period, contributing to the negative net cash flow.
![Axa narration](https://github.com/user-attachments/assets/52c0d967-3dff-4eff-87da-4d46f09b9d54)

# DATA VISUALIZATION
![Axa dashboard](https://github.com/user-attachments/assets/462b418d-f586-4ca3-aa91-936de9d760c2)

Interact with the dashboard here

# INSIGHTS
- Negative Cash Flow and ROI: The Net Cash Flow of -8,409,749.65 and Return on Investment (ROI) of -19.69% indicate that the investment did not perform well overall. Outflows (withdrawals or liquidations) exceeded the inflows (deposits or purchases), resulting in a net loss.

- Large Transactions in March: March's high transaction volume, especially liquidations, significantly contributed to the overall losses. More cautious withdrawal strategies could have improved long-term profitability.

- Imbalance in Sales and Purchases: The imbalance between withdrawals and deposits was a key driver of the negative cash flow. The higher frequency and value of sales indicate that the investment suffered from too many liquidations.

- Sales and Purchase Frequency by Month: The pattern suggests seasonality in transaction activity, with sales peaking in October and purchases peaking in April. Understanding this seasonal pattern could be useful for planning future investments and liquidations.

- Top Largest Withdrawals: These significant liquidations would have substantially impacted the investment’s ability to grow. Avoiding large withdrawals in a short span of time might help mitigate the negative impact on cash flow and ROI. 

- Quarterly Profit Peaks: Despite the overall negative cash flow, these quarters (Q4 2024 and Q2 2020) saw positive returns, suggesting that specific periods were profitable.

- Total Profits: Despite the losses, a total profit of 720,487.31 was generated over the years. The investment had potential, but the key issue was excessive withdrawals which limited the overall profitability.

# RECOMMENDATIONS
- Reduce Withdrawals to Maximize Investment Growth: Develop a disciplined approach to withdrawals. Limit withdrawals to essential needs and avoid withdrawing large sums, especially in short intervals. Allow more time for the investment to accumulate profits.

- Plan Strategic Withdrawals During High-Return Quarters: Identify the quarters with historically higher returns and schedule withdrawals during these periods, if necessary, to optimize the value of the investment. Withdraw less during low-profit or negative cash flow periods to preserve capital.

-  Reinvest Profits and Minimize Liquidations in High-Inflow Months: Reinvest inflows during high-activity months like March instead of making large withdrawals. This will capitalize on the increased deposits and help balance the cash flow over the investment period.

-  Monitor and Reduce the Frequency of Sales (Withdrawals): Track the sales frequency and actively reduce it. Evaluate whether each withdrawal is necessary or if the funds can stay invested for longer. Use purchase opportunities to reinvest capital.

- Leverage Profitable Quarters to Reinvest and Grow Capital: Use high-return quarters to reinvest the profits back into the account. Reinvestment during profitable periods will allow the account to grow faster and potentially offset the negative impacts of previous withdrawals.

- Establish a Long-Term Growth Strategy: Focus on long-term growth by allowing the investment to remain intact for longer periods. Create an investment plan that minimizes early withdrawals and emphasizes reinvesting returns to maximize compounded growth over time.

- Consider Professional Financial Advice for Investment Management: Seek professional financial advice to develop a comprehensive investment strategy that focuses on optimizing returns, minimizing unnecessary liquidations, and planning strategic withdrawals based on market conditions.
