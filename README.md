# Wine market study

The client, Domaine des Croix, is looking to define the price of its wine bottles for the US market. They have retrieved a set of 130k bottles of wine, with grape varieties, countries and regions of production, vintages (i.e. years of production), as well as notes ('points') and descriptions from oenologists (wine specialists), and the price of all these bottles on the American market.

**The objective will be to make a presentation of the market analysis and the price you recommend for the client's wines.**

## Data sets
- [Dataset American wine market](https://github.com/murpi/wilddata/raw/master/wine.zip)
- [Dataset American wine market](https://github.com/murpi/wilddata/raw/master/domaine_des_croix.csv)


## Expected deliverables
The client would like a presentation containing at least these elements:
- Reminder of the context and the problem
- Exploratory analysis of the data
- Methodology, tools and languages used
- Presentation of the technical part and the code created for this analysis
- Answer to the business question: price proposal or price range to the client to be correctly positioned against the competition on the American market

## Market analysis: KPI
- By country:
  - Distribution of number of wines per country (all)
  - Distribution of number of wines per country (top producers)
  - Top producer countries ranked by score
- By variety:
  - Total amount of wines produced by grape varieties (most produced)
  - Median score by grape variety (most produced)
  - Median price by grape variety (most produced)

- Time series:
  - Number of wines produced by year (top 10 most produced grape varieties)

- Pinot Noir variety:
  - Pinot Noir titles by price
  - Countries producing the most Pinot noir titles
  - Main Pinot Noir wineries
  - Number of Pinot Noir titles produced by year and country

- Descriptions:
   -What words stand out the most in the wine descriptions? And specifically for Pinot Noir, is it very different?  What about the Burgundi province in France?
   
## Business Intelligence
### Comparative analysis
The objective here will be to compare each of the client's wines to its competitors on the market. For example, compare the prices for French wines, then more and more precisely, Burgundy wines since our client is in Burgundy, then Burgundy Pinot Noir of the same year. Do not hesitate to be original in the presentation and the dataviz used. Use all the Business Intelligence functionalities in a dashboard to help the client to compare himself (tooltips, filters, etc...).

### Value proposition
With the dashboard you provided, the customer has a clear idea of his competitors. Make him a price proposal according to his positioning (for example: 'if you want to position yourself on the top of the range, the 25% most expensive of your competitors are at this price, we advise you to align yourself with this price').
