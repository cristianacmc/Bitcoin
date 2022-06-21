# Bitcoin and Cryptocurrencies: Full dataset, filtering, and reproducibility¶

Since the launch of Bitcoin in 2008, hundreds of similar projects based on the blockchain technology have emerged. We call these cryptocurrencies (also coins or cryptos in the Internet slang). Some are extremely valuable nowadays, and others may have the potential to become extremely valuable in the future1. In fact, on the 6th of December of 2017, Bitcoin has a market capitalization above $200 billion.

![](bitcoint_market_cap_2017.png)
The astonishing increase of Bitcoin market capitalization in 2017.


**WARNING:** The cryptocurrency market is exceptionally volatile and any money you put in might disappear into thin air. Cryptocurrencies mentioned here **might be scams** similar to <em>Ponzi Schemes</em> or have many other issues (overvaluation, technical, etc.). **Please do not mistake this for investment advice**.
<em><strong> Update on March 2020</em></strong>: Well, it turned out to be volatile indeed :D That said, let's get to business. We will start with a CSV we conveniently downloaded on the 6th of December of 2017 using the coinmarketcap API (NOTE: The public API went private in 2020 and is no longer available) named <code>datasets/coinmarketcap_06122017.csv</code>.
