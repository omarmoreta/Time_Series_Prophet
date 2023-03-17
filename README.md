### CLONE REPO SO YOU CAN VIEW THE NOTEBOOK LOCALLY, IT IS TOO BIG FOR GITHUB.

# Time_Series_Prophet

You’re a growth analyst at [MercadoLibre](http://investor.mercadolibre.com/investor-relations). With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

# Instructions

## Step 1: Find Unusual Patterns in Hourly Google Search Traffic

## Step 2: Mine the Search Traffic Data for Seasonality

## Step 3: Relate the Search Traffic to Stock Price Patterns

## Step 4: Create a Time Series Model with Prophet

## Step 5 (Optional): Forecast Revenue by Using Time Series Models

## Questions & Answers Section

**Question:** Did the Google search traffic increase during the month that MercadoLibre released its financial results?

**Answer:** Yes, the Google search traffic increased by 3,008 or 8.5% compared to the average monthly search trend during the month of May 2020 due to MercadoLibre releasing their financial results.

**Question:** Does any day-of-week effect that you observe concentrate in just a few hours of that day?

**Answer:** There seems to be a huge upsurge of searches during the first few and last few hours of the days. There seems to be fewer searches happening between the fifth and 11th hour of the days. This could be because people may search more frequently on their free time, in the morning before work and after work, but not so much during work hours.

**Question:** Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?

**Answer:** There is a small decline to start off the winter holiday season from weeks 40 to 42, but afterwards it increases all the way until the last week of the year where is decreases dramatically perhaps because of late december holidays and the new year. 

**Question:** Do both time series indicate a common trend that’s consistent with this narrative?

**Answer:** It seems that there is some correlation between both of the time series. During the February 25th - March 11th there was a big drop in the stock price and also a huge drop in search traffic, possibly impacted by the pandemic. During May 5th there was a sharp spike in stock price from 600 to over 700, which looks like the largest daily increase as well as the largest search traffic recorded during the first half of 2020, I wonder if this was the exact day of the financial release.

**Question:** Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?

**Answer:** There doesn't seem to be any strong predictable relationship between the lagged search traffic and the stock volatility it is pointing towards a weak negative correlation. Between the lagged search traffic and the stock price returns there seems to be a very weak positive correlation.

**Question:**  How's the near-term forecast for the popularity of MercadoLibre?

**Answer:** The near-term forecast for the popularity of MercadoLibre seems to decrease towards the last part of 2020.

**Question:** What time of day exhibits the greatest popularity?

**Answer:** During the end and beginning of the day at 12AM.

**Question:** Which day of week gets the most search traffic?   

**Answer:** Tuesday

**Question:** What's the lowest point for search traffic in the calendar year?

**Answer:** September and October by far are the lowest points for search traffic in the calendar year.

**Question:** For example, what are the peak revenue days? (Mondays? Fridays? Something else?)

**Answer:** The revenue increases from Sunday to Wednesday but it peaks on Wednesday.

### Based on the forecast information generated above, produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan.

**Answer:** A sales forecast for the finance division, given the forecast information generated, could be a range between 888M and 1B in sales or the most likely case of 969M in sales.
