# Income Growth in South and Central America Relative to Aid by US and UK

I am looking at the growth of incomes in given South and Central American countries relative to the foreign aid from the US and UK they've received. The U.S. Congressional Research Service details how the U.S. provides aid to Latin America,

>The United States has long been a major contributor of foreign assistance to countries in Latin America and the Caribbean. Between 1946 and 2019, the United States provided nearly $94 billion ($195 billion in constant 2017 dollars) of assistance to the region.

>The United States provides foreign assistance to Latin American and Caribbean countries to support development and other U.S. objectives. U.S. policymakers have emphasized different strategic interests in the region at different times, from combating Soviet influence during the Cold War to promoting democracy and open markets, as well as countering illicit narcotics, since the 1990s

Further detailing specific contributions, the U.S. currently provides

> * $505.9 million to address the underlying factors driving irregular migration fromCentral America ($129 million more than the Administration requested but $27 million less than allocated to the region in FY2020);
> * $461.4 million to support the peace process and security and development efforts in Colombia ($48.5 million more than requested and nearly $10 million more than allocated to the country in FY2020);
> * $158.9 million to support security and rule-of-law efforts in Mexico ($95 million more than requested and $1 million more than allocated to the country in FY2020);
> * $33 million to support a democratic transition in Venezuela ($172 million less than requested and $2 million less than allocated to the country in FY2020); and
> * $38 million for the Inter-American Foundation ($344 million more than requested and $500,000 more than Congress appropriated for the agency in FY2020).

Generally, the stated goal of the U.S. is to assist in the development of those countries in return for them

1. "consolidating democratic governance and improving living conditions"
2. Mantaining a relationship with the United States

Government aid in pure dollar amounts decreases as countries establish themselves, however, they "typically receive some U.S. support to address shared security challenges, such as transnational crime"


I came into this believing the US and UK would have relatively similar interests in terms of where their aid was going.

I am additionally looking at the income growth of their countries, and I believe that's important, as I'd expect every country giving aid to want to know that what they're giving has a positive impact on the country they're giving it to.

1. Do the US and UK tend to give aid in the same places?
2. How does the aid the US and UK give relate to the financial growth of the countries they give to?

To get the charts, I used:

2004 Net bilateral aid flows from DAC donors, United States (current US$)
2004 Net bilateral aid flows from DAC donors, United Kingdom (current US$)
Annualized Mean Income Growth (2004-2009)

With a filter on the Latin America & Carribean region. I did this because most of the unfiltered data where I saw intersections was in that region, so it made sense to isolate it.

## Growth by country

![](https://i.imgur.com/N81CuHj.png)

## 3D Graph of all 3 factors, from 3 viewing angles

![](https://i.imgur.com/41WYkte.png)

![](https://i.imgur.com/JpwS5Ni.png)

![](https://i.imgur.com/5wKJJBF.png)

## Comparison of US vs UK aid with an OLS line

![](https://i.imgur.com/SXWUhjE.png)

## Growth compared to UK aid with OLS line

![](https://i.imgur.com/YUHNB8a.png)

## Growth compared to US aid with OLS line

![](https://i.imgur.com/T6Q70kb.png)

Overall, the data seems to suggest that the US and UK give aid *relatively* similarly, but not nearly as closely as I may have expected.

The interesting part of what I found, in my opinion, that more aid seemed to **decrease** the raw growth of a country. However, I think there could be a few explanations:

* Is more aid in dollar amounts given to countries that have started to need larger amounts to be successful?
* Is more aid in dollar amounts given to larger countries, that would need a larger proportion to see similar results?
* Country sample size is low, so it seems plausible that difficulties specific to individual countries could skew results
* "Aid" may be building towards financial growth, but not necessarily showing itself immediately, as it could be solving problems that set the country up for future success

Or even, plausibly, some combination of the above.

[Wang, C. (2021). The world development explorer. Available from http﻿://www.worlddev.xyz](https://www.worlddev.xyz/)
