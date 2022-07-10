# Concepts and Terms Explained

## Failure to Deliver

"In finance, a failure to deliver (also FTD, plural: fails-to-deliver or FTDs) is the inability of a party to deliver a tradable asset, or meet a contractual obligation. A typical example is the failure to deliver shares as part of a short transaction."  
"Stocks bought and sold in transaction must be settled within 2 days. The buyer must deliver the cash and the seller the stock."  
[Wikipedia as of 2022-07-10](https://en.wikipedia.org/wiki/Failure_to_deliver)

### Regarding Officially Reported FTD Data

From [the SEC website (as of 2022-07-10)](https://www.sec.gov/data/foiadocsfailsdatahtm), regarding the data that is available from the same site:  
"The values of total fails-to-deliver shares represent the aggregate net balance of shares that failed to be delivered as of a particular settlement date. [...] Fails to deliver on a given day are a cumulative number of all fails outstanding until that day, plus new fails that occur that day, less fails that settle that day. The figure is not a daily amount of fails, but a combined figure that includes both new fails on the reporting day as well as existing fails. In other words, these numbers reflect aggregate fails as of a specific point in time, and may have little or no relationship to yesterday's aggregate fails. Thus, it is important to note that the age of fails cannot be determined by looking at these numbers. In addition, the underlying source(s) of the fails-to-deliver shares is not necessarily the same as the underlying source(s) of the fails-to-deliver shares reported the day prior or the day after."

So we do not have to/cannot add up FTD numbers, but instead the newest reported number already includes past FTDs and settlements of FTDs. It is lower than the previous number, if more FTDs have been settled than new ones occured from the last reported data. It is higher than the previous number, if more new FTDs occured than have been settled in that period of time.

Thanks to u/rabbitboy868 [for pointing out that there is a common misunderstanding as well as providing the source](https://www.reddit.com/r/Superstonk/comments/vvh7zr/clearing_up_misunderstandings_about_ftds/).

## Utilization

*Utilization := Number of shares borrowed / Number of shares available to borrow*

Note that utilization data from a single data vendor might not be complete/precise. This is because not all brokers, banks, etc. that lend out shares have necessarily reported their numbers to the data vendor.

#### Example:
Imagine, from Xxx outstanding shares of a stock, 20 shares are available to borrow. If now 10 have been borrowed, then the utilization is 50%. This number does not depend on the number of outstanding shares.

#### Explanations from the Internet:

"Utilization is defined as loaned shares divided by available shares in the securities lending market, expressed as a percentage."  
"Generally, Utilization is the ratio of demand to supply. For example, Apple Inc. (AAPL) may have utilization of less than 1% because the stock has vast availability relative to the demand to borrow shares for shorting. Roku Inc. (ROKU) may have utilization above 90% because of higher demand to short shares as compared to the number of available shares."  
[ibkr](https://ibkr.info/article/3044)

"Utilization:  
The ratio between the number of shares on loan across all outstanding loans in the wholesale market and the number of shares available for lending at lending programs. 0% means that no shares have been borrowed or lent at these lending programs; 100% means that all shares available to borrow or lend at a lending program have, in fact, been lent. This does not represent the number of shares listed on the exchange that have been lent, because not all listed shares are available for lending; it indicates how much of the supply actually available for lending has been lent."  
[Ortex](https://public.ortex.com/help-stock-short-interest-chart/)
