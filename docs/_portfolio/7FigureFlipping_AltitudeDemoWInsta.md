---
layout: post
title: Posting Rmarkdowns to your Jekyll website
output:
  md_document:
    variant: markdown_github
    preserve_yaml: true
---

<style>
    body { background-color:  #F3F3F3; }
    pre, pre:not([class]) { background-color: red; }
</style>

![](C:/Users/tyler/Pictures/LTG_Analytics/7FigAlt/alt.png)

# [Click here for more information on 7 Figure Altitude!](https://7figurealtitude.com/home)

<br>
<iframe width="840" height="473" src="https://www.youtube.com/embed/KXwLt4kh__8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen data-external="1"></iframe>

# That is an AWESOME video Bill. But as we say in the data science world, in God we trust all others **BRING DATA**

##### This is going to be a **MASSIVE** amount of data. I would recommend initially skimming the charts, playing with the functionality, and going top to bottom on all the tables. After taking a look and becoming more familar with the information, take some time and digest it more slowly. As the months go on you’ll be able to really see trends as they emerge and become **proactive** instead of **reactive!**

edit

# **National Scope Macro Economic Factors**

**Cut through the noise to take a look at fundamentals**

## **Employment:**

### How does the state you are investing in stack up to the competition?

#### **TAKEAWAY:** Look at the total number of jobs in the state you invest in. This helps you to put job growth into context. If Texas has a company move there that is going to create 20,000 jobs that is much different than the same company moving to Montana. Context matters.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Employment%20Heat%20Map-1.png)

## **Job Market:**

### What does the typical job in your state make? How large is the spread between the bottom 25% of earners and the top 75% of earners? Here we took the median income of a job in each state, assumed that majority of house holds have two bread winners (one with a full time job one with a part time job), and created an estimate for household income that is the median wage multiplied by 1.5.

#### **TAKEAWAY:** When looking at housing markets it is important to understand the typical wage earner. The definition of median is the 50% point. The median wage point means that there are 50% of people that make more and 50% that make less. When defining your avatar it is useful to understand their capacity to pay. For most flippers it is important to try and have as large a buyers pool as possible. This means looking at deals that the majority of median wage and median house hold income people can afford.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Wage%20Data%20Graph-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Wage%20Data%20Graph-2.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Wage%20Data%20Graph-3.png)

## **Unemployment:**

### It is important to see where unemployment has gone in the past in order to understand where it could go in the future.

#### **TAKEAWAY:** The 70’s and 80’s both had periods of unemployment above 6% that lasted approximately 3 and 6 years. Currently we are seeing unemployment nationally below 4% with no real signs of a job crisis. If you want to put a tin foil hat on, I would say predicting a recession that lasts 4 years is more than conservative. Personally I do not think we will see something that drastic.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Unemployment%20Rate%20Line%20Graphs-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Unemployment%20Rate%20Line%20Graphs-2.png)

### Like most statistics, this is a metric that is best looked at in context. See the heat map below for where each state settles in at in terms of unemployment.

#### **TAKEAWAY:** There are a handful of states that are seeing +4% unemployment currently but for the most part the labor markets seem to be strong in each state. Even a mid 4% unemployment rate is not a cause for alarm. [Natural Unemployment is considered by some to be around 4-5%.](https://www.investopedia.com/terms/n/naturalunemployment.asp#:~:text=Many%20consider%20a%204%25%20to,employment%20and%20not%20particularly%20concerning.)

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Unemployment%20Heat%20Map-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Unemployment%20Heat%20Map-2.png)

## **Interest Rates (30 year and Fed Funds Rate):**

### This data is piped directly down from the Federal Reserve Economic Data (FRED) website and is the most up to date information that is publicly available. Due to plotting this information along side the Federal Funds Rate we do not have October shown, however the October 20th 30 Mortgage Average was 6.94.

### As you can see, the [Federal Funds Rate](https://www.investopedia.com/terms/f/federalfundsrate.asp#:~:text=The%20federal%20funds%20rate%20refers,at%20a%20Federal%20Reserve%20bank.) tracks pretty closely with the 30 Year Mortgage Rate, but not perfectly. It is safe to assume **generally** as the Fed raises rates it will apply upward pressure on the mortgage market, however it is not usually a 1 for 1 trade.

#### **TAKEAWAY:** Right now the interest rates seem to be poised for continual increases. While we have been spoiled by record low rates for extended periods of time, the 90’s saw rates in the 7’s for quite sometime. Over the next 12 months I would recommend underwriting at **least 8%** if you are relying on a refinance exit strategy.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Fed%20Funds%20and%2030%20Yr-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Fed%20Funds%20and%2030%20Yr-2.png)

## **Mortgage Payments at Current Rates:**

### Assumed a 30 year mortgage at that months average interest rate, that months median list price, and a 15% down payment.

#### **TAKEAWAY:** This is the sharpest rise in median mortgage payments we have seen in recent times. Would recommend staying as close to the median price point house in your area as you can if flipping. This will help you out in the short term by increasing the buyer pool you can draw from.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Payment%20Amounts-1.png)

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/unnamed-chunk-3-1.png)

### This is illustrating the percent change from the previous year in mortgage payments. During the period of low rates (sub 3.5%), housing was actually becoming more affordable. Currently the payment for a median priced home at todays rates with 15% down is over 60% more expensive than it was a year ago.

#### **TAKEAWAY:** Look when the graph dips into the negative numbers. The lower rates actually made housing more affordable, regardless of the increase in price. The current median priced home is 66% more expensive to own than the same median price point home a year ago.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Payment%20Amount%20Changes-1.png)

## **Consumer Price Index (Total):** See below for an excerpt from the FRED website explaining CPI.

The Consumer Price Index for All Urban Consumers: All Items (CPIAUCSL)
is a price index of a basket of goods and services paid by urban
consumers. Percent changes in the price index measure the inflation rate
between any two time periods. The most common inflation metric is the
percent change from one year ago. It can also represent the buying
habits of urban consumers. This particular index includes roughly 88
percent of the total population, accounting for wage earners, clerical
workers, technical workers, self-employed, short-term workers,
unemployed, retirees, and those not in the labor force.

The CPIs are based on prices for food, clothing, shelter, and fuels;
transportation fares; service fees (e.g., water and sewer service); and
sales taxes. Prices are collected monthly from about 4,000 housing units
and approximately 26,000 retail establishments across 87 urban areas. To
calculate the index, price changes are averaged with weights
representing their importance in the spending of the particular group.
The index measures price changes (as a percent change) from a
predetermined reference date. In addition to the original unadjusted
index distributed, the Bureau of Labor Statistics also releases a
seasonally adjusted index. The unadjusted series reflects all factors
that may influence a change in prices. However, it can be very useful to
look at the seasonally adjusted CPI, which removes the effects of
seasonal changes, such as weather, school year, production cycles, and
holidays.

The CPI can be used to recognize periods of inflation and deflation.
Significant increases in the CPI within a short time frame might
indicate a period of inflation, and significant decreases in CPI within
a short time frame might indicate a period of deflation. However,
because the CPI includes volatile food and oil prices, it might not be a
reliable measure of inflationary and deflationary periods. For a more
accurate detection, the core CPI (CPILFESL) is often used. When using
the CPI, please note that it is not applicable to all consumers and
should not be used to determine relative living costs. Additionally, the
CPI is a statistical measure vulnerable to sampling error since it is
based on a sample of prices and not the complete average.

## **Consumer Price Index (Core)**

The “Consumer Price Index for All Urban Consumers: All Items Less Food &
Energy” is an aggregate of prices paid by urban consumers for a typical
basket of goods, excluding food and energy. This measurement, known as
“Core CPI,” is widely used by economists because food and energy have
very volatile prices. The Bureau of Labor Statistics defines and
measures the official CPI, and more information can be found in the FAQ
or in this article.

#### **TAKEAWAY:** When looking at CPI it can be difficult to parse out the true meaning. I recommend going to this [link](https://www.bls.gov/cpi/) and familiarizing yourself with the market basket, but beyond that just continue on to the next graphs that translate CPI into measures of inflation.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/CPI%20Core%20Chart-1.png)

## **Inflation:**

### Good data exists back to 1957. Of note, the largest spike in history was in the 1980’s when inflation from both estimates was above 13%. Previously the 1970’s saw inflation in the double digits as well. Current estimates peg inflation above 8% using Total CPI and above 6% if using Core CPI.

#### **TAKEAWAY:** The Core inflation is typically lower than Total Inflation due to the exclusion of food and energy. I would recommend using Total to understand the state of the economy, while looking at Core to see what the impact food and energy are having.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Inflation%20Chart-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Inflation%20Chart-2.png)

# **National Real Estate Market**

## **Supply and Demand:**

### Going back to 2016 market supply had been consistantly trending downwards. However once the number of pending listings overtook the number of active listings on the market we experienced a massive sellers market. This change started in Febuary of 2021 and continued until June of 2022.

#### **TAKEAWAY:** We are still in the midst of a housing shortage. The timing of the return of a sub 100% pending ratio was when the Federal Reserve began raising rates. As soon as rates stabilize I think we will not see the same levels of demand in 2021-mid 2022, but we will be in a sellers market.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Supply%20and%20Demand-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Supply%20and%20Demand-2.png)

## **Pending Ratio Heat Map:**

### This is a snap shot of the pending ratios in each state. Markets that have a 50% and lower ratio are more indicative of a buyers market, whereas markets above a 100% ratio are still favorable to sellers, in theory.

#### **TAKEAWAY:** Places that are darker are also those that did not make as many headlines (Looking at you TX, FL, CA…). That being said the Midwest appears to have stronger demand at the moment than the West and South.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Pending%20Ratio%20Heat%20Map-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Pending%20Ratio%20Heat%20Map-2.png)

## **Median and Average List Price:**

### Large uptick in pricing as COVID kicked off. We are seeing Month to Month pricing fall, but still double digit pricing increases when we look at it from a yearly basis.

#### **TAKEAWAY:** Zoom in on the dates for this one to gain an appreciation of how much the prices jumped YoY. Also understand that when looking at housing, you should almost always use the median price point. This will keep you safe from having only a couple high priced homes mislead you about a market.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20and%20Avg%20Price%20Point%20Graphs-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20and%20Avg%20Price%20Point%20Graphs-2.png)

## **Median List Price Heat Map:** This gives you a look at overall cost in each state.

#### **TAKEAWAY:** No surprises here, the costs are more expensive than the midwest. You will also find the largest difference in median and average list prices there too (remember, averages are sensitive to extreme high and extreme low values).

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20List%20Price%20Heat%20Map-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20List%20Price%20Heat%20Map-2.png)

## **Median Days on Market (National):**

### This metric is from listing to closing on the sale. We can see the very cyclical nature, with days on market slowing down entering the winter. It is very possible people listing flips in the next two months will have over 80 days.

#### **TAKEAWAY:** We have been adjusting our underwriting to 90 days to close.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20Days%20on%20Market%20Line%20Graphs-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20Days%20on%20Market%20Line%20Graphs-2.png)

## **Median Days on Market Heat Map:** The darker the color the cooler the market.

#### **TAKEAWAY:** A surprising state for me was Ohio and Michigan. Both states in the mid and low 40s for DOM. Putting things into perspective, look back at 2017, you can see that DOM was around 60-95 days depending on the month. We still have a ways to go for properties sitting on the market.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20Days%20on%20Market%20Heat%20Map-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20Days%20on%20Market%20Heat%20Map-2.png)

## **Median Price Per Square Foot (National):**

### Median Price Per Sqft has been more stable than overall pricing, but has still seen a lot of growth in the recent months.

#### **TAKEAWAY:** Not as sharp of an increase relative to the median list prices, which is an indicator that people were buying slightly larger homes for the price.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20Price%20Per%20Square%20Foot%20Line%20Graph-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20Price%20Per%20Square%20Foot%20Line%20Graph-2.png)

## **Median Price Per Sqft Heat Map:**

#### **TAKEAWAY:** Again, the midwest wins at bang for your buck. Also take a look at the median sized home in those areas. Keeping an eye on both median price per square foot and median square footage are two ways to ensure you are maximizing your buyer pool.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20PPSqft%20Heat%20Map-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Median%20PPSqft%20Heat%20Map-2.png)

## **Price Drops:**

### The number of price drops has significantly increased in the past 5 months. They are now currently on par with the same number of price drops we saw in 2019. A major difference however is a lower amount of supply, which may be creating an even more benefical market for buyers. September saw a near 75% increase in total price drops nationwide year over year.

#### **TAKEAWAY:** This could also be considered a fear or greed chart. The more over priced a market the more price drops should occur. Also, selers with expectations that their house should sell in 24 seconds may be panicking and dropping their prices. All in all, this is an opportunity on the buy side for investors.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/unnamed-chunk-5-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/unnamed-chunk-5-2.png)

## **Price Drops Heat Map YoY:** The darker the color the more price drops relative to the last year same time frame.

#### **TAKEAWAY:** The midwest is steady again! If you are in Arizona there is a high chance you are seeing some serious price drops, with over 290% YoY increases in number of drops.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Price%20Drop%20Heat%20Map-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/Price%20Drop%20Heat%20Map-2.png)

## **New Construction Starts (US):**

### You can see the largest fluxuations in Single Family homes leading up to the 2008 Housing Crisis. The crash led to a severe lack of building for approximately two years, which can help to explain the current housing shortage.

### **NOTE: No data was collected from Dec 1984 - Dec 1990, which is displayed by the anomaly during that timeframe.**

#### **TAKEAWAY:** We are still not built out properly as a nation. We built very little post 2008 and are just now back on track with similar levels from the 90s. Multifamily however is doing building proportionally much more.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/US%20Data-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/US%20Data-2.png)

## **New Construction Starts (heat map):** Showing the areas with the largest number of housing starts in Sept 2022.

#### **TAKEAWAY:** Texas and Florida are building more houses than the 3-6 place states **COMBINED**. I would keep my eyes out for overbuilding in those states.

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/New%20Construction%20Heat%20Map-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/New%20Construction%20Heat%20Map-2.png)

### Thanks for diving into the data with us! Here at 7 Figure Flipping **we are about more than just making tons of profits for ourselves.**

## [Click here for more information on the 7 Figure Foundation!](https://7figurefoundation.com/)

![](C:/Users/tyler/Pictures/LTG_Analytics/7FigAlt/foundation.png)

<br>

<br>

<br>

<br>

##### Data powered by LTG Analytics, the data science branch of LTG Investments. To learn more about LTG Investments and their mission to combat human trafficking through real estate investing click [here!](https://podcasts.apple.com/us/podcast/e239-flipping-to-fight-human-trafficking-with-lindsey/id1453040812?i=1000567488116)

![](C:/Users/tyler/Pictures/LTG_Analytics/7FigAlt/tylerandLindsey.png)
![](C:/Users/tyler/Dropbox/My%20PC%20(DESKTOP-IURTLKF)/Desktop/LTG%20Investments%20LLC/LTG%20Analytics/ltganalyticsbanner.png)

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-1.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-2.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-3.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-4.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-5.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-6.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-7.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-8.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-9.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-10.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-11.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-12.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-13.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-14.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-15.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-16.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-17.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-18.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-19.png)![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/ALL%20GRAPHS%20AND%20MAPS-20.png)

``` r
UnemploymentMap
```

![](7FigureFlipping_AltitudeDemoWInsta_files/figure-markdown_github/unnamed-chunk-6-1.png)

``` r
TimeRunning
```

    ## Time difference of -16.43796 mins
