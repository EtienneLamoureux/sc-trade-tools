# SC Trade Tools
[SC Trade Tools](http://sc-trade.tools) is a platform where you can find trading-related tools for Star Citizen, tailored precisely to you! With always up-to-date data, powerful filters and fancy optimization algorithms, you're sure to find your ideal trade route!

## Table of contents
- [SC Trade Tools](#sc-trade-tools)
  * [Table of contents](#table-of-contents)
  * [Links](#links)
  * [About](#about)
    + [Features](#features)
      - [Trade routes](#trade-routes)
      - [Best buyer](#best-buyer)
      - [En route](#en-route)
  * [F.A.Q.](#faq)
    + [Why are the prices reported different from the ones in-game?](#why-are-the-prices-reported-different-from-the-ones-in-game-)
    + [How can I see more results?](#how-can-i-see-more-results-)
  * [Disclaimer](#disclaimer)

## Links
|Resource|Link|
|:--|:--|
|SC Trade Tools|http://sc-trade.tools<br />[Mirror 1](http://sctradedata-env.eba-crh3jdvz.us-east-2.elasticbeanstalk.com)|
|Patreon|http://patreon.com/sc_trade_tools|
|Supported Star Citizen version|http://sc-trade.tools/api/system/sc-version|
|API documentation|http://sc-trade.tools/swagger-ui.html|

## About
SC Trade Tools is a passion project from a Star Citizen trader who got tired of looking at spreadsheets! It aims to fill the sweetspot between ease-of-use and fine data-tuning . It does so by providing powerful search filters which allow any trader to gradually refine their trade runs until they find the perfect one for them.

The data comes directly from the game's files, thanks to the awesome contributors over at [unp4k](https://github.com/dolkensp/unp4k). That means that the prices are rapidly updated after a new patch hits. If a new location or item makes it in, they are equally quickly included. The tools also already support multi-system trades via the pathing algorithms that have been built-in: as soon as Pyro is made available to us, SC Trade Tools will know the optimal trade routes.

Since the universe simulation makes the prices vary based on supply and demand, the tools will currently only report the most optimistic profit to be made. In the future, I hope to be able to tap into whichvever APIs are released to continuously update the data. I'll also look into manual submission of price corrections if the former takes too long to come!

### Features
#### Trade routes
> Figuring out the optimal trade run can be a daunting task. Make it easy by using powerful filters to find the best Star Citizen trade routes, tailored specifically to your exact situation and preferences.

![](https://raw.githubusercontent.com/EtienneLamoureux/sc-trade-tools/master/documentation/trade-routes.PNG)

#### Best buyer
> Wondering where to sell all that ore you mined? Maybe you've "acquired" some goods and are in need of an unscrupulous buyer. Whatever your hold holds, someone will buy it: find out who will pay the most!

![](https://raw.githubusercontent.com/EtienneLamoureux/sc-trade-tools/master/documentation/best-buyer.PNG)

#### En route
> Maybe you're on your way to meet friends, or maybe you're simply going to the start of your usual trade run. Either way, might as well make an extra buck by carrying something in your cargo hold!

![](https://raw.githubusercontent.com/EtienneLamoureux/sc-trade-tools/master/documentation/en-route.PNG)

## F.A.Q.
### Why are the prices reported different from the ones in-game?
The universe simulation makes the prices vary based on supply and demand. Since the data comes from the static game files, the tools will currently only report the most optimistic profit to be made. 
I hope have dynamic prices in the future.

### How can I see more results?
To be as optimized as it is, SC Trade Tools must limit the number of results returned. Don't worry though! If you don't like what you get, filter it out using the facets on the left.

### What's this 'AU' I keep seeing in the results?
AU stands for [astronomical unit](https://en.wikipedia.org/wiki/Astronomical_unit). It's the only good way to report distances on the scale of a solar system without the numbers getting way too big.

## Disclaimer
<sup>SC Trade Tools is not endorsed by or affiliated with the Cloud Imperium or Roberts Space Industries group of companies. All game content and materials are copyright Cloud Imperium Rights LLC and Cloud Imperium Rights Ltd.. Star Citizen®, Squadron 42®, Roberts Space Industries®, and Cloud Imperium® are registered trademarks of Cloud Imperium Rights LLC. All rights reserved.</sup>
