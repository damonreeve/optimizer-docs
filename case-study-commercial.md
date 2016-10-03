---
layout: page
title: Case Study Commercial
---

Please find the attached spreadsheet that gives two real world examples of using Authenticated.

Example 1 - Reducing QPS (Constant Net Revenue Worksheet)
In this example, you can see the effect of using Authenticated at different filter rates, and the vastly lowered QPS needed to achieve the same spend levels.  At the highest filter setting, the same spend can be achieved with 1/3 of the inbound traffic.  This can reduce infrastructure costs by more than a third.

Example 2 - Increasing Bidstream Revenue (Constant QPS Worksheet)
In this example, Authenticated was used to improve the quality of the bidstream - and you can see the effect of different Authenticated settings for the same QPS levels.  Authenticated can deliver higher quality, more commercially viable inventory, so that if AOL advertisers have latent demand, the same QPS can generate 2.5x more profit (e.g. net revenues minus infrastructure costs and Authenticated fees), and 4x more revenues.

In both examples, Authenticated uses a commercial model and a quality model to achieve these results.  The underlying raw SSP traffic in this example had a 2% bid rate, 50% win rate, and 75% impression rate before Authenticated was enabled.

Authenticated fees are $1K + 30% revenue uplift in this case.

We will also send through the before/after metrics regarding supply quality for each of the cases (e.g. recycled/arbitraged inventory, accurately described inventory, etc.)


BIDSTREAM SUMMARY CONSTANT NET REVENUE | BASELINE	| FILTER SETTING LOW | FILTER SETTING	MEDIUM | FILTER SETTING	HIGH | FILTER SETTING MAX
--- | --- | --- | --- | --- | ---
FILTER | | | | | 
 Inbound QPS | 7,843 | 8,376 | 9,565 | 11,975 | 13,333 
 Inbound Net Revenue | $ 24,627.02 | $ 26,301.52 | $ 30,036.34 | $ 37,602.46 | $ 41,867.21 
| | | | | 
 Impression Filter Rate | 0.0% | 20.0% | 40.0% | 60.0% | 80.0%
 Revenue Filter Rate | 0.0% | 6.4% | 18.0% | 34.5% | 41.2%
| | | | | 
 Outbound QPS | 7,843 | 6,701 | 5,739 | 4,790 | 2,667 
 Outbound Net Revenue | $ 24,627.02 | $ 24,627.02 | $ 24,627.02 | $ 24,627.02 | $ 24,627.02 
| | | | | 
OTHER COSTS | | | | | 	
 Infrastructure | $ 11,764.50 | $ 10,051.54 | $ 8,609.14 | $ 7,185.18 | $ 4,000.05 
 Authenticated Fees | $ - | $ 1,513.89 | $ 1,946.61 | $ 2,373.80 | $ 3,329.33 
| | | | | 
Cost Reduction | 0.0% | 1.7% | 10.3% | 18.7% | 37.7%


## PUBLISHER DIRECT MODEL

By using the "publisher direct" quality model, and filtering out "recycled" and "secondary" suppliers, we are able to control the bidstream to allow the best supplier for inventory without reducing access to any publisher domains or apps. With be bidstreams we have live this is resulting in the ability to filter 20% of bid requests without reducing acccess to any supply (web domains or apps) and only reducing impression supply by 5%.

By using the "publisher direct" quality model, and filtering out "recycled" and "secondary" suppliers, you can bid on only the best supplier without reducing access to any publisher domains.  Our model in general will allow you to filter 20% of bids which are deemed duplicate supply, which removes only 5% of impressions. Note that the 5% of impressions will not necessarily be lost.  These are most likely impressions that will be won on the best supplier rather than the secondary supplier in the future if you implement these rules.  You just won't be bidding against yourself.