# SC Trade Tools
[SC Trade Tools](https://sc-trade.tools) is a platform where you can find trading-related tools for Star Citizen, tailored precisely to you! With always up-to-date data, powerful filters and fancy optimization algorithms, you're sure to find your ideal trade route!

![](https://sc-trade.tools/assets/home.png)

## Links
|Resource|Link|
|:--|:--|
|SC Trade Tools|https://sc-trade.tools|
|Sponsor|https://patreon.com/sc_trade_tools|
|Tip jar|https://ko-fi.com/sc_trade_tools|
|Discord server|https://discord.gg/fdCxQAccpG|
|What's new?|https://github.com/EtienneLamoureux/sc-trade-tools/blob/master/CHANGELOG.md|
|API documentation|https://sc-trade.tools/swagger-ui/index.html|

## About
SC Trade Tools is a passion project from a Star Citizen trader who got tired of looking at spreadsheets! It aims to fill the sweet spot between ease-of-use and fine data-tuning. It does so by providing powerful search filters which allow any trader to gradually refine their trade runs until they find the perfect one for them.

The data is sourced from the Star Citizen community, mostly from contributions from [traders like yourself](https://github.com/EtienneLamoureux/sc-trade-companion)! That means prices reflect real, player-reported values from across the verse and are continuously updated as the community submits new data. The tools support multi-system trades via built-in pathing algorithms, so SC Trade Tools will know the optimal routes as new locations become available.

Since the universe simulation makes prices vary based on supply and demand, reported profits are based on the best available community data at the time of your query. You can help keep the data accurate by submitting price updates through [our very own companion application](https://github.com/EtienneLamoureux/sc-trade-companion)!

## Features
- **Trade route optimization**: find the most profitable routes between locations, with support for multi-stop and multi-system journeys
- **Powerful filters**: narrow down results by location, ship, cargo capacity, budget, and more
- **Shop & commodity browser**: look up what's bought and sold where, with community-reported prices
- **Always up-to-date**  data is continuously refreshed from community sources after each patch
- **Starmap integration**: travel times and routes are computed using in-game starmap data

## API
SC Trade Tools exposes its data programmatically. *An API token is required for authenticated endpoints*.

### REST
The full REST API is documented via Swagger UI and follows standard HTTP conventions.

|Resource|Link|
|:--|:--|
|Interactive docs|https://sc-trade.tools/swagger-ui/index.html|

### MCP (Model Context Protocol)
SC Trade Tools exposes an [MCP](https://modelcontextprotocol.io) server, allowing AI assistants and agentic tools to query trade data directly.

**Configuration:**
```json
{
	"sc-trade-tools": {
		"type": "http",
		"url": "https://sc-trade-tools.com/mcp",
		"headers": {
			"Authorization": "Bearer <API token>"
		}
	}
}
```

The server is stateless, so no session management is required on your end.

## F.A.Q.
See the [official website](https://sc-trade.tools/help).

## Disclaimer
<sup>SC Trade Tools is an unofficial Star Citizen fansite, not affiliated with the Cloud Imperium group of companies. All content on SC Trade Tools not authored by its host or users are property of their respective owners. Star Citizen®, Roberts Space Industries® and Cloud Imperium® are registered trademarks of Cloud Imperium Rights LLC</sup>
