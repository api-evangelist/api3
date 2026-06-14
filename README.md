# API3

API3 is a first-party blockchain oracle network that connects real-world APIs directly to smart contracts without intermediary nodes. Its core technology is Airnode, a serverless oracle node that API providers operate themselves, cryptographically signing data before serving it on-chain.

The API3 Market enables dApp developers to subscribe to managed decentralized APIs (dAPIs) — aggregated, multi-source data feeds covering 150+ price pairs across 40+ EVM chains. API3's OEV (Oracle Extractable Value) mechanism captures MEV that traditionally leaks to bots around oracle updates and redistributes 80% of that revenue to the dApps reading the feeds.

## APIs

- **dAPI Data Feeds** — Managed on-chain price and data feeds for 150+ asset pairs across 40+ EVM networks, readable via AggregatorV2V3Interface-compatible proxy contracts.
- **OEV Rewards** — Revenue-sharing mechanism returning 80% of oracle MEV auction proceeds to participating dApps monthly in native gas token.
- **Airnode HTTP Gateway** — REST endpoint exposed by individual Airnode operators for off-chain signed-data access, testing, and OEV auction fulfillment.

## Links

- Website: https://api3.org/
- Documentation: https://docs.api3.org/
- Market: https://market.api3.org/
- Blog: https://blog.api3.org/
- GitHub: https://github.com/api3dao
- Discord: https://discord.gg/qnRrcfnm5W

## Profile

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/api3-plans.yml` — Subscription plan details
- `rate-limits/api3-rate-limits.yml` — Rate limit documentation
- `finops/api3-finops.yml` — FinOps Framework cost model
