# Website Traffic Analysis

A beginner Excel analytics project exploring website traffic data 
(Jan–Jun 2024) to understand how users, sessions, and conversions vary across 
traffic sources and devices. Dataset sourced from Kaggle.

## Dataset

42 daily records with the following fields:

| Column | Description |
|---|---|
| Date | Date of recorded traffic |
| Users | Unique visitors that day |
| Sessions | Total visits (a user can have multiple) |
| Source | Organic, Direct, Paid, or Social |
| Device | Mobile or Desktop |
| Bounce rate | % of visitors who left after one page |
| Pages per session | Avg. pages viewed per visit |
| Conversions | Visitors who completed a target action |
| Conversion Rate | Conversions ÷ Sessions |

## Analysis

The workbook includes three analysis layers built on top of the raw data:

- **Pivot Tables** - total users aggregated by month
- **Bounce Rate** - average bounce rate by traffic source
- **Dashboard** - summary view of total users, total sessions, overall 
  conversion rate, average bounce rate, and monthly trends

## Key Insights

- **Traffic is growing steadily month over month** - users rose from ~1,535 in 
  January to ~9,450 in June, a roughly 6x increase over the period.
- **Paid traffic drives the most sessions but converts worst** - Paid brings in 
  the largest share of sessions (~10,290) yet has the lowest conversion rate 
  (1.64%) and the highest bounce rate (76.17%), suggesting ad spend isn't 
  translating into engaged visitors.
- **Organic search is the strongest-performing channel** - it has the highest 
  conversion rate (2.33%) combined with a moderate bounce rate, making it the 
  most efficient source of traffic.
- **Direct visitors are the most engaged** - Direct traffic has the lowest 
  bounce rate (57.43%) and the highest pages-per-session (3.1), indicating 
  visitors who arrive directly explore the site more thoroughly.
- **Device type barely affects performance** - Mobile and Desktop have nearly 
  identical conversion rates (~1.98% vs ~1.99%) and bounce rates (~65.6% vs 
  ~65.5%), so the site performs consistently across devices.
- **Overall conversion rate sits at ~2%** - out of 34,730 total sessions, only 
  690 resulted in a conversion, leaving clear room for optimization, 
  particularly on the Paid channel.

## Tools

Microsoft Excel - pivot tables, aggregation formulas, dashboard design

