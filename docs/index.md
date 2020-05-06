---
title: "Explain-It 2020, Ayush Agarwal" 
author: "Explainers"
knit: (function(input_file, encoding) {
  out_dir <- 'docs';
  rmarkdown::render(input_file,
 encoding=encoding,
 output_file=file.path(dirname(input_file), out_dir, 'index.html'))})
output:
  prettydoc::html_pretty:
    keep_md: True
    theme: cayman
    highlight: github
---

# Day 3 : Let's talk Options!
***

## Options - Introduction

### Technical Terms -

* Strike Price :- The price at which an option can be exercised. 

* Underlying Price :- The underlying price is the price at which the underlying asset trades in the spot market.
Exercising of an option contract :-  The act of claiming your right to buy the options contract at the end of the expiry. 

* Option Expiry :- Similar to a futures contract, options contract also has expiry. 

* Option Premium :- Premium is the money required to be paid by the option buyer to the option seller/writer. Against the payment of premium, the option buyer buys the right to exercise the option. 

## Call Options - 

* The buyer of the call option has the right, but not the obligation to buy an agreed quantity of the underlying from the seller, at the expiration date for the strike price. The seller (or “writer”) is obligated to sell the commodity or financial instrument should the buyer so decide. The buyer pays a fee (called a premium) for this right. 



<table class="table" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Buying </th>
   <th style="text-align:left;"> Selling </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> It makes sense to be a buyer of a call option when you expect the underlying price to increase. If the underlying price remains flat or goes down then the buyer of the call option loses money. </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Selling a call option makes sense only when you believe that upon expiry, the underlying asset will not increase beyond the strike price. If the underlying price remains flat or goes up then the seller of the call option loses money. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> The call option buyer has limited risk (to the extent of the premium paid) and a potential to make an unlimited profit. </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> The profit of an option seller is restricted to the premium he receives, however his loss is potentially unlimited. Since a short option position carries unlimited risk, he is required to deposit margin. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Intrinsic value, IV = Spot Price – Strike Price </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Intrinsic value, IV = Spot Price – Strike Price </td>
  </tr>
</tbody>
</table>










# Day 2 : Peak into the Commodity Industry
***

## Contango vs Backwardation

The price quoted for a commodity is often the cash or spot price, but even more often it's the price of the active month futures contract traded on a futures exchange—and those prices tell only a part of the story when it comes to the value of a commodity. 

### How are Futures/Forwards Priced? 

**For Forwards (Using Annual compounding)**

![](/Users/mclaren/Desktop/Archive/Annual.png)

**For Futures (Using continuous compounding)**

![](/Users/mclaren/Desktop/Archive/Cont.png)


## Forward Curve

* The forward curve is a function graph in finance that defines the prices at which a contract for future delivery or payment can be concluded today.  
  + For example, a futures contract forward curve is prices being plotted as a function of the amount of time between now and the expiry date of the futures contract (with the spot price being the price at time zero)

* The traditional crude oil futures curve, for example, is typically humped: it is normal in the short-term but gives way to an inverted market for longer maturities.

![](/Users/mclaren/Desktop/Archive/forcur.png)
![](/Users/mclaren/Desktop/Archive/oilnorm.png)


## Convergence Property

* As we approach contract maturity—we might be long or short the futures contract—the futures price must move or converge toward the spot price. The difference between the two is the basis.

* That's because, on the maturity date, the futures price must equal the spot price. If they don't converge on maturity, anybody could make free money with an easy arbitrage.

* A convenience yield is an implied return on holding inventories.

![](/Users/mclaren/Desktop/Archive/graph.png)

## Contango 

* Contango is when the futures contracts are trading at a premium to the spot price, i.e. the futures price is above the expected future spot price. 

* Because the futures price must converge on the expected future spot price, contango implies futures prices are falling over time as new information brings them into line with the expected future spot price.

* A contango market is often confused with a normal futures curve. 

* If short-term interest rates were expected to fall in a contango market, this would narrow the spread between a futures contract and an underlying asset in good supply. This is because the cost of carry will fall.


**Why contango?**

* A surplus in a commodity will generally express itself as a contango when it comes to calendar spreads. 

* The theory behind contango is that abundant supplies on a close horizon do not guarantee abundant supplies in the more distant future. In fact, if supplies are extremely high, producers might cut back on future production. The surplus will then decrease and prices will rise by virtue of less production. 

* In commodities, contango markets also exist because financing, storage, and insurance of abundant supplies cause those progressively higher futures prices by virtue of the need to carry surplus inventories. (Cost of carry). With commodities, the cost of carry generally includes storage costs and depreciation due to spoiling, rotting, or decay in some cases. 


## Backwardation

* Normal backwardation, also sometimes called backwardation, is the market condition wherein the price of a commodities' forward or futures is trading below the expected spot price at contract maturity. 

* The resulting futures curve would typically be downward sloping (i.e. "inverted"), since contracts for further dates would typically trade at even lower prices. 

* It means there is the expectation that the current price is too high and the expected spot price will eventually fall in the future. For example, when futures contracts have lower prices than the spot price, traders will sell short the asset at its spot price and buy the futures contracts—for a profit—driving the expected spot price lower over time to converge with the futures price eventually.  

**Why Backwardation?**

* A backwardation starts when the difference between the forward price and the spot price is less than the cost of carry (when the forward price is less than the spot plus carry), or when there can be no delivery arbitrage because the asset is not currently available for purchase. 

* This is the case of a convenience yield that is greater than the risk free rate and the carrying costs. 

* In a state of backwardation, futures contract prices include compensation for the risk transferred from the underlying asset holder to the purchaser of the futures contract. 

* If there's a short-term or long-term supply shortage in a commodity, chances are the market structure will tend toward backwardation. Higher nearby prices might constrain demand or elasticity while at the same time encouraging producers to increase production as fast as they can to take advantage of higher prompt delivery prices.  


**WTI Contango**

![](/Users/mclaren/Desktop/Archive/Wti.png)

**Brent Contango**

![Black - Jun, Blue - July, Orange - Aug](/Users/mclaren/Desktop/Archive/brentcont.png)


## Upstream vs Downstream Companies  

![](/Users/mclaren/Desktop/Archive/uvsd.jpg)

## Upstream Companies

* The upstream oil and gas segment is also known as the exploration and production (E&P) sector because it encompasses activities related to searching for, recovering and producing crude oil and natural gas.

* The upstream segment is all about wells: where to locate them; how deep and how far to drill them; and how to design, construct, operate and manage them to deliver the greatest possible return on investment with the lightest, safest and smallest operational footprint. 

* It is a highly capital-intensive, highly risky, and highly regulated business.  Upstream investments are high-risk, given that results of every well drilled are unpredictable. Additional risk arises from safety and environmental issues. 

**Types of upstream oil and gas companies**

* Integrated oil companies 
  + These are "wellhead to end user" operations that span the upstream, midstream, and downstream segments of the oil market. 
  + ExxonMobil is the biggest publicly traded integrated oil company in the world. It operates one of the largest E&P businesses, with assets spanning the globe, a growing midstream segment, and a meaningful downstream portfolio. 
  + That diversification helps mute some of the impacts of oil price volatility, since their downstream assets benefit from lower prices.


* Independent E&P companies 
  + These companies focus primarily on the upstream segment, they make most of their money by producing oil and gas. 
  + They're much more susceptible to changes in oil prices since their earnings tend to rise and fall with commodity prices. 


* Diversified oil-field service companies 
  + They're akin to a one-stop shop for developing oil and gas resources. 
  + In addition to providing a variety of much-needed services, they often manufacture mission-critical equipment. 


* Pure-play oil-field service or equipment companies 
  + These companies focus on one aspect of the service sector. Some, for example, only own and operate offshore drilling rigs. Others provide services specific to completing newly-drilled oil wells, or they produce sand used in fracking wells. 
  + This focus on one aspect of the oil-field service sector enables these pure plays to make lots of money during boom times. But they can be much more susceptible to trouble when market conditions deteriorate. 


**Investing in upstream stocks**

* Investors need to be mindful of which upstream stocks they buy because oil price volatility enhances risk. 

* In order for exploration and production of crude to be commercially viable, the price needs to be high enough to make sense from a financial standpoint. 

* One of the better ways to reduce this risk is by focusing on larger, more diversified companies. Their scale and diversification should help mute some of the impacts of the inevitable ups and downs of the oil market. 

## Downstream Companies

* The downstream sector focuses on the last link in the industry's value chain by turning raw materials like crude oil and natural gas into higher-valued products such as fuels and petrochemicals. 

* They're less sensitive to oil price volatility, which enables them to generate more free cash flow that they tend to return to investors. 

* Marketing and distribution companies transport and sell the finished petroleum products to end users. Examples of marketing and distribution companies include retail gas stations, home heating fuel delivery companies, and natural gas distribution utilities. 

* Most downstream companies make money on the spread between what they pay to buy raw materials such as crude oil, and the price at which they sell higher-valued refined products or petrochemicals. Because of that, most downstream companies make more money when oil and natural gas prices are lower, because they can buy these raw materials or feedstocks at cheaper prices. 


**Types of downstream oil and gas companies**

* Companies only operate in the downstream segment, with some focusing on one activity (refining, chemicals, or distribution and marketing). These pure-plays on either the downstream sector or one of its activities give investors the opportunity to make outsized profits when market conditions are strong. 

* However, when the environment weakens, which tends to happen as commodity price volatility increases, it can put pressure on the profits and stock prices of downstream companies. Eg: Marathon Petroleum, Phillips 66. 


**Investing in downstream stocks**

* These companies typically cash in during periods of lower prices, which makes them a great option to pair with the stock of an oil-producing company since the performance of the downstream company's stock should help smooth out some of the oil price volatility that comes with investing in the upstream sector. 

* Downstream companies tend to generate lots of free cash flow because refineries aren't as capital intensive as oil fields, meaning refiners don't have to invest as much money to maintain their operations. 

* Downstream companies with more excess cash can return to shareholders via dividends and stock buybacks. 

**Comparison**

![Black-Oil, Blue-Exxon, Red-Schlumberger](/Users/mclaren/Desktop/Archive/comp.png)

***


# Day 1 : A Dip into Oil 
***

## Recent move in oil. [negative prices]

**Oil Production by Numbers**

![](/Users/mclaren/Desktop/Archive/OilProd.png)

**Oil Deal**

First of all, the markets are flooded with oil. Since the pandemic started, IEA estimated a 30% (29 million barrels/day in April 2020) of the world demand has perished while the output has majorly remained the same. Around April 13, Oil deal was announced. However, the cuts (9.8mn barrels/day) were much lower than expected.
And if you look closely within you’ll find the deal really isn’t as good as it sounds. Russia’s output has not fallen in years and it will continue to violate OPEC+ deals as it had been all this while, and the 2.5 mn/day cut Saudi announced was from a 11mn/day baseline which it has never been able to sustain daily anyway, it’s average is around 8.5 which means the remains 2.5 mn was coming from inventories, effectively amounting to no or meagre cuts. To sum it up, Oil deal failed to inspire confidence and offer the much needed respite. 


**How is WTI Oil traded?**

In the worldwide oil industry, an oil barrel is defined as 42 US gallons, which is about 159 litres. Now, Oil is traded in Futures contracts, and WTI in particular is a physically settled futures contract i.e when the WTI contract expires, a quantity of oil that previously existed only on paper is converted into physical barrels. Now, most of the WTI oil is delivered at Cushing, Oklahoma where you have to take delivery of the oil. Since the forward month was May, delivery was to be taken between 1st to 31st or else pay them to store.

**Speculative vs Hedging Trade**

Most of the trade is a speculative one, therefore do not want physical oil, and refiners given the glut, no demand, tough transport conditions don’t want it either. Some oil producers even wanted to induce Force Majeure. 

![](/Users/mclaren/Desktop/Archive/Oint.png)

**Storage of Oil - Costs**

On top of the daily charter costs for an oil tanker of about \$55,000 (U.S.), traders that use floating storage must pay for the ship's fuel (3 cents a month per barrel), port support costs (10 cents a month per barrel) and interest on the loan to finance the purchase of the oil (10 cents a month per barrel). This can add up to about \$1.10 a month per barrel. A LOOP oil storage futures price for Jun ‘20 is trading at \$0.55 at the moment.

**Conclusion**

With this comes the expiry date for May’s contract, April 20th. Removing oil would be impossible cause after all its 1000 barrels per contract. Even Cushing is dangerously close to its capacity and is left with 2 weeks of capacity, and due to the dynamic nature of pricing the storage cost is now disproportionately high. Even the offshore containers near the African coast are not available with 160 million barrels of oil now held in floating storage on ships. So much so that companies have now asked permissions to convert pipelines into temporary storage. The realisation hits the market and about 3 hours before expiry, WTI oil for May is dangerously flirting near \$0 levels. Panic starts to seep in, and within minutes the WTI contract has gone below 0\$. Anyone rolling over would have to pay as much as \$60 (since when at -40 levels, June forwards were still trading at \$20), Hence people figured it’s better to pay someone to get rid of the oil contacts instead of the alternatives. 

![](/Users/mclaren/Desktop/Archive/time.jpeg)



## Difference between WTI and Brent. Major Oil suppliers and importers.

First of all, WTI and Brent Crude are each major benchmarks for oil pricing. Since nobody will pay you to take cash, a negative Brent value would not make sense. (Side Note - MCX cash-settled derivatives based on WTI were deeply affected as well, and BSE is testing negative prices now). Brent is an indicator for sentiment rather than a physical metric.



<table class="table" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> WTI </th>
   <th style="text-align:left;"> BRENT </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> WTI is the main oil benchmark for North America </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Brent Crude is the International benchmark </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> WTI crude oil is sourced in North America, primarily from Texas </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Brent Crude is sourced from oil fields in the North Sea, near Norway. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> The WTI crude is produced in landlocked areas, leaving producers vulnerable to running out of storage capacity. </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Brent has unlimited storage capacity for oil producers because it's produced at sea. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> WTI forward contracts are settled with physical barrels </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Brent is a cash-settled forward. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> WTI has a sulfur content of 0.24%, API of 39.6 </td>
   <td style="text-align:left;width: 30em; border-right:1px solid;"> Brent has a sulfur content of 0.37%, API of 38 </td>
  </tr>
</tbody>
</table>


**Major Exporters (by net exports)**

![](/Users/mclaren/Desktop/Archive/Netexp.png)


**Major Importers**

![](/Users/mclaren/Desktop/Archive/Import.png)


**Dated Brent**

Platts Dated Brent is a benchmark assessment of the price of physical, light North Sea crude oil. The term "Dated Brent" refers to physical cargoes of crude oil in the North Sea that have been assigned specific delivery dates.

![](/Users/mclaren/Desktop/Archive/brent.jpg)

**Brent-WTI Spread**

![](/Users/mclaren/Desktop/Archive/BvsW.png)

## Contact Information :
***
**Email**          : ayush.agarwal50@gmail.com, ayuag@iitk.ac.in  
**GitHub handle**  : [ayushmclaren](http://github.com/ayushmclaren)  
**Telephone**      : +91 9815139259  
**LinkedIn**       : [Ayush Agarwal](https://www.linkedin.com/in/ayushmclaren/)
