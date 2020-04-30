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
