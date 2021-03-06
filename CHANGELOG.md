# SC Trade Tools
## 4.0.0
### Features
- New tool: /deposits

### Bugs
- Fix Ore Value Index (OVI) for ship deposits

### Other
- Improve UI performance
- Improve client-side caching

### Breaking changes
- Changes to the mining-related APIs' DTOs

## 3.1.3
### Bugs
- Fix Clio's shops inventories

## 3.1.2
### Features
- Load 3.12.1 data

### Other
- Various performance and security fixes

## 3.1.1
### Features
- Load 3.12.0b data

### Bugs
- Fix missing commodity: SLAM

## 3.1.0
### Features
- Add the refined value to the minables price list pop-up

### Bugs
- Fix minimum refresh rate of 0 fails form validation
- Fix routing when path parameter contains a special character

### Other
- Rework the top navigation
- Shorten results links by removing the default values
- Improve loading times

## 3.0.1
### Other
- Update 3.12.0a data
   - Luminalia gifts can now be sold at select locations for 1000 UEC

## 3.0.0
### Features
- New tool: /ores
- Updated 3.12 data

### Breaking changes
- Changes to the items-related APIs' DTOs

## 2.2.0
### Features
- Load 3.12 data
- Add a new tool: /refineries

## 2.1.5
### Other
- Add the Nomad to the ship list

## 2.1.4
### Other
- Add the Mercury Star Runner to the ship list
- Add links to a [video tutorial](https://youtu.be/dqVhs1cGhmo)

## 2.1.3
### Bugs
- Fix the listings of the "Shubin Mining Facility SM0-" shops on microTech

## 2.1.2
### Features
- Load 3.11 data
- Don't display refinery terminals in trade results

### Bugs
- Fix the names of the HDMS outposts on Hurston

## 2.1.1
### Bugs
- Fix Levski's travel times

## 2.1.0
### Features
- Add new tool: /mining

### Other
- Improve mobile navigation
- Clarify the function of the buttons in the results of /trade-routes & /en-route
- Clarify the poorly-supplied-trades warning message

## 2.0.1
### Features
- Add hyperlinks to all commodities and shops, linking to the /commodities and /shops tools

### Other
- In addition to [Patreon](https://www.patreon.com/sc_trade_tools), users can now tip the project through [Ko-fi](https://ko-fi.com/sc_trade_tools)
- Fixed the headings in /commodities

## 2.0.0
### Features
- New tool: /commodities
- New tool: /shops
- Add bookmarkable links

### Bugs
- Fix the listings of the Calliope shops
- Fix the listings of the "Shubin Mining Facility SM0-" shops on microTech

### Other
- Correctly assess travel time for hidden locations
- Rework the main cities' shops name to better reflect their location
- Fix the refinery terminal names

### Breaking changes
- The API model `TradeDto` has had some of its attributes moved to `TransactionDTO`
- The `itemAmount` attribute has been renamed `itemQuantity` in all API models for consistency

## 1.7.0
### Features
- #8 Suggest alternatives for each trade
- #55 Display buy price, sell price & profit per unit when hovering over aggregate prices
- #51 Add a warning when user is at risk of not being able to buy/sell as much as displayed
- #53 Add tips & tricks to the website

### Other
- #56 Rework planet and moon location type filters into outpost type filters

## 1.6.1
### Bugs
- #50 Correctly flag all hidden locations as such
- Circular trade routes now respect the chosen profit type, instead of defaulting to "by time"

## 1.6.0
### Features
- #36 Add a filter to ignore hidden locations
  - Add warning icon next to hidden shops in result
- Load 3.10.2 data

### Bugs
- #48 Fix the planetary rest stops names
- #49 Fix listings of Rayari shops located on Clio

### Other
- Add "Red Festival Envelope" commodity
- Add tooltip for Maximum wait time

## 1.5.0
### Features
- #26 New profit type: over time
- #34 Add a "reset form" button

### Bugs
- #33 Fix form values not being saved without changing page

### Other
- #40 Show no results instead of empty cargo runs when a trade search returns no results
- Realign help icons
- Add the F.A.Q. to the website

## 1.4.4
### Features
- Load 3.10.1 data

### Bugs
- #39 Fix Outpost 54's name

### Other
- #46 Add a note about inventories and refresh rates being shared across servers
- Reworked the help tooltips

## 1.4.3
### Bugs
- Fix "maximum wait time" filter incorrect behaviour
- Fix "item" and "item type" filters preventing empty cargo runs from being suggested

## 1.4.2
### Bugs
- #31 Fix itineraries including multiple empty cargo runs in a row

### Other
- #18 Save user preferences between pages
- #19 Save user preferences between visits

## 1.4.1
### Features
- #29 Add maximum wait time filter
- #17 Add a filter for transactions with low inventory refresh rates

### Bugs
- Fix chains of empty cargo runs when doing business on large planetary bodies
- Fix the cargo capacity of the 315p

### Other
- #23 Improve large numbers display

## 1.4.0
### Features
- Update data for Star Citizen 3.10
- #7 Add toggle to display stock details in results
- Improve results ordering
  - When multiple trades yield the same profit, the shortest routes will now be first
- Use proper popovers for help icons

### Bugs
- Remove duplicate shops
  - e.g. "Stanton > Crusader > Port Olisar > Admin"
- Fix an issue where using the "Maximum commodity volume" filter would prevent the pathing algorithm from using empty cargo runs
- Fix POST requests using `www.` failing with 403 "Invalid CORS request"
- Fix alt text for images in /home

### Other
- #11 Better indicate when no results are returned
- Improve navigation of the form facets (filter menu)
- Improve display of numbers
- Add content to /home
  - Sponsors (see the [project's Patreon](https://www.patreon.com/sc_trade_tools))
  - About information and use cases
- Add terms & conditions
- Add privacy policy
- Rework footer
- Remove "Join Star Citizen" button in the navbar

## 1.3.1
### Features
- Add individual shops to the locations dropdown in the facets
  - which allows to blacklist/whitelist individual shops

### Bugs
 - Correctly show all shops in /best-buyer when cargo is not marked as stolen

## 1.3.0
### Features
- Support empty cargo run for close-by shops
- Support stolen cargo

## 1.2.0
### Features
- Add a "maximum number of stops" option for /en-route
  - Also applies for circular trade routes

### Other
- Speed-up dropdowns population time by enabling better client-side caching

## 1.1.0
### Features
- Add circular trade routes in /trade-routes
- Add supported Star Citizen version in /home

### Other
- Increase the maximum allowable detour to 100% in /en-route

## 1.0.4
### Other
- Open the Miscellaneous facet group by default
- Display the total sell price in /best-buyer

## 1.0.3
### Bugs
- #10 Fix POST requests over HTTPS fail with 403 "Invalid CORS request"

## 1.0.2
### Bugs
- #6 Remove "Stanton > Hurston > Aberdeen > Klescher Rehabilitation Facility" as a shop

## 1.0.1
### Features
- #5 Expose API documentation
  - See [sc-trade.tools/swagger-ui.html](http://sc-trade.tools/swagger-ui.html)

## 1.0.0
### Features
- Tools
  - Trade routes
  - Best buyer
  - En route
