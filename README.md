Superstore Sales Performance Dashboard



&#x20;What is this project?

I built a sales dashboard in Power BI using a retail superstore dataset with 4 years of data.

I wanted to understand what was actually driving revenue and profit across different 

regions and product categories.



This is my second portfolio project. I built it to practice DAX measures, 

interactive slicers and drill-through in Power BI.





What I was trying to find out

\- Which categories and regions make the most money?

\- Is the business actually growing or just selling more at lower margins?

\- Are there products being sold at a loss?







What surprised me



The negative profit on Tables caught me off guard.

Tables have solid sales volume but when I looked at profit — it was negative.

The business is literally losing money on every table it sells.

My guess is they are pricing too low or discounting too heavily on this category.

Same problem with Machines and Bookcases.

This was the finding I didn't expect and the one I'd bring straight to a manager.



The jump from 2015 to 2017 was sharp.

Sales were flat through most of 2015 then suddenly accelerated.

I noticed it clearly on the line chart — almost a hockey stick shape.

I didn't dig into which region or category drove it specifically — 

that would be the next question I'd investigate.



West and East dominate profit.

Central and South lag behind. My assumption is discounting in those regions

is hurting margins — but I'd need to look at discount rates by region to confirm.







Dashboard features

\- KPI cards at the top: Total Sales $2.30M, Total Profit $286K, 

&#x20; Profit Margin 12.5%, YoY Growth 46.9%

\- Sales by Category

\- Profit by Region

\- Monthly Sales Trend with year drill-down

\- Sales vs Profit by Sub-Category — this is where the negative profit shows up clearly

\- Region and Segment slicers that filter everything at once







&#x20;DAX measures I wrote

\- Total Sales — SUM of all sales

\- Total Profit — SUM of all profit  

\- Profit Margin — Total Profit divided by Total Sales

\- YoY Sales Growth — compares current year to previous year 

&#x20; using SAMEPERIODLASTYEAR function



&#x20;Tools

\- Power BI Desktop

\- DAX

\- Power Query for data loading

\- Dataset: Sample Superstore (Kaggle)

