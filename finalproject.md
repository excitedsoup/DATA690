# Income Growth in South and Central America Relative to Aid by US and UK

I am looking at the growth of incomes in given South and Central American countries relative to the foreign aid from the US and UK they've received. The U.S. Congressional Research Service details how the U.S. provides aid to Latin America,

> The United States has long been a major contributor of foreign assistance to countries in Latin America and the Caribbean. Between 1946 and 2019, the United States provided nearly $94 billion ($195 billion in constant 2017 dollars) of assistance to the region.

> The United States provides foreign assistance to Latin American and Caribbean countries to support development and other U.S. objectives. U.S. policymakers have emphasized different strategic interests in the region at different times, from combating Soviet influence during the Cold War to promoting democracy and open markets, as well as countering illicit narcotics, since the 1990s

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

Additionally, the U.S. Congressional Research Service says most of this began through the Cold War, starting with Cuba,

> U.S. assistance to the region spiked in the early 1960s, following the introduction of President John F. Kennedy’s Alliance for Progress, an anti-poverty initiative that sought to counter Soviet and Cuban influence in the aftermath of Fidel Castro’s 1959 seizure of power in Cuba. After a period of decline, U.S. assistance to the region increased again following the 1979 assumption of power by the leftist Sandinistas in Nicaragua. Throughout the 1980s, the United States provided considerable support to Central American governments battling leftist insurgencies to prevent potential Soviet allies from establishing political or military footholds in the region

showing that the Cold War was a large reason for the U.S. becoming involved in the region.

I came into this believing the US and UK would have relatively similar interests in terms of where their aid was going. To some degree, I was correct, however, a BBC article by Gorden Corera shows their intentions, "At the start of the 1960s, the UK dramatically increased covert action in Latin America, undertaking what was called 'special political action', including propaganda and forgeries which aimed to influence the public, primarily against communism" (Corera). He additionally mentions why their goals were so aligned with the U.S., "...the UK, Prof Cormac says, became involved partly as a means of currying influence with America and also to increase trade in the region" (Corera). However, that goal he says, was somewhat in opposition to U.S. interests, "'The UK conducted these covert operations for two reasons... First, to demonstrate partnership to the US in order to inject leverage into an increasingly one-sided relationship. Second, the British wanted to exploit a perceived US decline in the region and capture a growing economic market...'" (Corera)

Even so, the UK was explicitly against the expansion of Soviet Communism, and their first priority was preventing the USSR from exerting their influence in the region. The UK has maintainted those relationships up until very recently, as this figure points out countries that will no longer be receiving bilateral aid from the UK due to budget constraints as of this year:

![](https://res.cloudinary.com/devex/image/fetch/c_scale,f_auto,q_auto,w_720/https://lh3.googleusercontent.com/I4XJQWUIohHefP5XPlgGKd-TKaNP82KKw5ZgWWpqa5BQEjZWnBmjSC3M_SDwvyU_YNcTH6gA4OGgUbKIl2wBfIuYOMfv2NkjAE5ilt90ySCi19LClmYyavTBlltP0ujFM7-xw7Hy)

The amount of aid given being reduced significantly may have an impact on the growth and stability of those countries, and may have to be made up in other places, or may reduce progress in those countries.

I am additionally looking at the income growth of their countries, and I believe that's important, as I'd expect every country giving aid to want to know that what they're giving has a positive impact on the country they're giving it to - as previously mentioned, a specified goal of both countries was to develop beneficial relationships between the region and the UK/U.S.

1. Do the US and UK tend to give aid in the same places? I would expect them to have relatively similar places, as their motivations seemed to be aligned on the Communism front, and the UK was working towards a growing relationship with the U.S., as well as relationships with the Latin American countries.
2. How does the aid the US and UK give relate to the financial growth of the countries they give to? I would expect the financial growth of those countries to grow to some degree, but as stated prior, pure dollar donation amounts tend to be greatest in countries that are the least far along in development, and as a result, maybe not show simple linear growth, as they are in a transitory period towards a more prosperous future.

I believe these are important questions for both the UK and U.S., as well as the South and Central American Countries, for fairly obvious reasons: aid being given is taxpayer money, and politicans want taxpayer money to be used effectively, lest they lose an election. Additionally, receiving aid and increasing prosperity in a is important to any country.

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

Overall, the data seems to suggest that the US and UK give aid *relatively* similarly, but not nearly as closely as I may have expected. Given that the UK was also looking to expand their own influence due to a perceived weakness in the U.S., it makes some sense that their aid would line up with countries they would hope to influence more than the U.S.

The interesting part of what I found, in my opinion, that more aid seemed to **decrease** the raw growth of a country, like I figured it possibly could. However, I think there could be a few explanations:

* Is more aid in dollar amounts given to countries that have started to need larger amounts to be successful?
* Is more aid in dollar amounts given to larger countries, that would need a larger proportion to see similar results?
* Country sample size is low, so it seems plausible that difficulties specific to individual countries could skew results
* "Aid" may be building towards financial growth, but not necessarily showing itself immediately, as it could be solving problems that set the country up for future success
* Given this is not an entire economic analysis of each country; aid is a minority of the story of the economy of these countries, which would not be captured in this data

Likely, some combination of the above factors plays into how this data turns out. Overall, I gained insight into how and why the U.S. and UK were aligned (and even misaligned) through their aid given to South and Central America, as well as how large of a part the Cold War influenced the genesis of the aid given and relationships curated.

[Wang, C. (2021). The world development explorer. Available from http﻿://www.worlddev.xyz](https://www.worlddev.xyz/)


