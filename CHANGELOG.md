# SC Trade Tools
## 1.3.1
### Features
- Add individual shops to the locations dropdown in the facets
  - which allows to blacklist/whitelist individual shops

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
