# SC Trade Tools
## 1.4.4
### Bugs
- #39 Fix Outpost 54's name

### Other
- Load 3.10.1 data
- #46 Add a note about inventories and refresh rates being shared across servers

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
