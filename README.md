# investment-analyis-upgrad

## Project Brief:
You work for __Spark Funds__, an asset management company. Spark Funds wants to make investments in a few companies. The CEO of Spark Funds wants to understand the global trends in investment so that she can take the investment decision effectively.

## Business and Data Understanding

Spark Funds has two minor constraints for investments:
  1. It wants to invest between __5 to 15 million USD__ per round of investment
  2. It wants to invest only in __English-speaking countries__ because of the ease of communication with the companies it would invest in
    
    - For the analysis, consider a country to be English speaking only if English is one of the official languages in the country.
    - https://en.wikipedia.org/wiki/List_of_territorial_entities_where_English_is_an_official_language

### Understanding the problem and the data:

__1. What is the stratergy?__
Spark Funds want to invest where most __other investors are investing__. This pattern is often observed among early stage startup investors.

__2. Where was the data acquired from?__
It is the real investment data from __crunchbase.com__, so the insights that can be extracted may be incredibly useful.

__3. What is Spark Funds business objective?__
The business objectives and goals of data analysis are pretty straightforward.

  1. __Business objective__: The objective is to identify the best sectors, countries and a suitable investment type for making investments. The overall stratergy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.
  
  2. __Goals of data analysis__: The goals are divided into three sub-goals:
    
  - __Investment type analysis__: Comparing the typical investment amounts in the venture, seed, angel, private equity, etc. so that Spark Funds can choose the type that is best suited for their stratergy.
    
  - __Country analysis__: Identifying the countries which have been the most heavily invested in the past. These will be Spark Sunds favourites as well.
  
  - __Sector analysis__: Understanding the distribution of investments across the eight main sectors. (Note that we are intrested in the eight 'main sectors' provided in the __mapping file__. The two files -- __companies and rounds2__ -- have numerous sub-sectors names; hence you will need to map each sub-sector to it's main sector.)
  
