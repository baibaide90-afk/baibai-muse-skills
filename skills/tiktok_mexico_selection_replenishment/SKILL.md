# TikTok Mexico Selection and Replenishment

## Qualify on profit first

- Reject a product that fails the profit gate regardless of its volume.

- Define g as base price minus cost anchor divided by base price.

- Build the cost anchor from purchase and first leg costs plus the taxes, commission, service and SFP that apply, and do not count any of those items twice.

- Compute margin on GMV, exclude advertising from the margin, use a live exchange rate, note the rate date, and never reuse a fixed rate from an old table.

- Compare the result with the ball and tinfoil benchmark band of about 27 to 31 percent and treat g of at least 20 percent as healthy for a promo pool.

- Convert the box dimensions to the volume unit the sea rate uses, multiply by the sea rate and divide by units per box to get first leg cost per unit.

- Treat Hit as a 15 percent discount, Super as a 10 percent discount and General as a 5 percent discount when you check a promo pool.

- Reject Hit for a product with g below 15 percent, reject Super below 10 percent and reject General below 5 percent because each pool price would lose money.

## Check volume and the other gates

- Measure baseline with the near 30 day median and measure burst with the single day peak.

- Require a median of at least about 20 orders per day and a peak of at least 100 orders per day for a good product.

- Treat a product with a margin at the lower edge but a baseline below the volume bar as observe, not qualified.

- Check filmability, listing conversion on its own, local market demand and interest ecommerce logic where content creates demand, and do not qualify a product on margin or volume alone.

- Treat any external selection SOP as a reference only and adapt it before you use it.

- Replace SOP sources with Chuhaijiang Mexico data plus the user own history, lock the market to Mexico, recompute profit on GMV excluding advertising with a live rate, and add the listing conversion gate.

- Do not assume that following bestsellers is an approved strategy when the user has not confirmed it.

## Set replenishment from stock position

- Define stock position as units in warehouse plus units in transit.

- Set the base target to average daily sales times 60 days.

- Add 10 days to reach 70 days for an A class product with an average of at least 20 and for a spike prone family.

- Define a spike prone family as one with a day at least 3 times the mean and at least 15 units in the last 30 days with an average of at least 5.

- Use the last 14 day mean as the average and show the 30 day mean as a reference.

- Order immediately when position falls below average daily sales times 52 days, using 7 days of production plus 45 days of sea freight as the lead time.

- Treat days of cover as the discipline, not a budget cap, and flag cover above 180 days as a warning and cover above 365 days as severe with a stop on replenishment and a clearance plan.

- Set the target to zero for a C class product with an average below 1 and sell through its stock.

- Use air freight only when a stockout is imminent and the margin survives the air cost, and accept a short stockout otherwise.

- Review replenishment monthly and watch the 52 day line and spike signals weekly.

## Use reference data sparingly

- Use Chuhaijiang only for Mexico product and market reference data and never treat a platform group name or a similar shop name as proof of ownership.

- Search with Spanish or English keywords because Chinese keywords do not filter reliably.

- Plan each query, fetch a full page once, reuse results and report the remaining credits after each call.

- Treat a single item value that recurs across loads as more reliable than a total that fluctuates between loads and do not quote a fluctuating total as precise.

## Available connectors

- [Chuhaijiang](~/workspace/custom-connectors/custom.chuhaijiang/CONNECTOR.md) for Mexico product and market reference data.

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.

## Alternatives for better results

- Give the conclusion first in chat and keep full detail in files for lookup.

- Label every estimate as an estimate and say plainly when data is insufficient.

- Ask the user for purchase price and box dimensions when either is missing instead of guessing them.
