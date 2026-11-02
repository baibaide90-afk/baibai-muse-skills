# TikTok Mexico Operations Reporting

## Analyze from files before asking

- Check the inventory table, procurement table, sales history and product pool pricing already on file before you ask the user a question those files can answer.

- Return an answer with a working read when files support one and flag any genuine tension between files instead of asking the user to resolve a tension you have not examined.

- Say plainly that data is insufficient when files do not support a conclusion and do not fill the gap with a guess.

- Keep the original file untouched when you archive or copy data and record the source file for every figure you quote.

## Count and classify shipments

- Archive each daily shipment table under the daily shipments folder for that date and append that day per family numbers to the running history.

- Count outbound units as pieces and count a combo by the pieces it contains.

- Treat an order as a sample only when its order mark contains the word sample and count samples in outbound totals while showing samples separately.

- Merge variants into one family and split a combo by its SKU code first with its name only as an aid.

- Place any SKU you cannot map in an unclassified group and never invent a family for it.

- Count a pack described as a set as one pack and count a pack marked with a number and P as that many packs, except for the confirmed 2P-TCY exception which counts as one pack and do not generalize that exception.

- Check date coverage before you call a single day a spike and treat a column that covers two days as two days combined.

- Flag any level break in the history when counting rules change and keep the older history as recorded.

## Build profit with separate lines

- Build product cost as purchase cost plus first leg freight and keep warehouse cost as a separate line.

- Estimate warehouse cost from the latest monthly bill and recalibrate the estimate when a new monthly bill arrives.

- Use the batch day live exchange rate for every conversion and note the rate date and never reuse a fixed conversion rate.

- Treat the settlement receipt rate as the cash fact and never use an operating view for cash flow forecasting.

- Report profit excludes advertising entirely: do not estimate, deduct, or report advertising inside daily or weekly report profit figures, and do not present a net profit after advertising in reports. (Supersedes the earlier daily estimated advertising and weekly actual advertising deduction, user 2026-10-26.)

- Use GMV as the denominator for every profit margin (gross margin, net margin, family and shop margins, daily and weekly); never divide by expected receipts.

- Include the United States block normally in daily and weekly reports and do not calculate United States warehouse cost.

- Treat refunds as refund only by default and do not reverse outbound units for a return and do not return returned goods to inventory.

- Leave cross family combo splits, unsettled cost mapping choices and advertising account to shop mapping open until the user confirms them and flag each open item instead of deciding it.

## Lead with trends and recommendations

- Lead every report with trend analysis, operational watch points and recommendations and place number tables after that lead.

- Compare the current period with the running history and note where a trend is based on a single day.

- Judge slow and dead products from sales history together with inventory and procurement data and separate a slow product caused by no stock from a slow product that has stock.

- Give an overview in chat with the conclusion, key numbers and gaps and keep full lists and detail in files for lookup.

- Confirm the scope in one short question before you restructure a deliverable when a short or voice message leaves scope ambiguous.

## Use competitor data carefully

- Use competitor platform data as a reference for product and market patterns and never treat a platform group name or a similar shop name as proof of ownership.

- Use the user confirmed own shop list from memory as the basis for own shop identity and do not re infer ownership from collections.

- Treat a single item value that recurs across loads as more reliable than a platform total that fluctuates between loads and do not quote a fluctuating total as precise.

- Record price, recent sales, total sales, revenue, shop sales, rating, linked creators and trend direction for each competitor item you check and note platform anomalies instead of using them to infer a conclusion.

- Make no purchase, subscription, deletion or group move on a competitor platform unless the user explicitly approves that action.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.

## Websites

- [Chuhaijiang](https://chuhaijiang.com/) for Mexico product and shop reference data. Carry Spanish or English search terms into `browser.browse` and verify recurring single item values there.

## Alternatives for better results

- Use a raw workbook or bill instead of a second hand summary when a figure is disputed.

- Ask the user for a direct data file when a login or verification flow has more than two steps instead of pushing the user through that flow.

- Recompute totals and formulas before you close a report and correct a delivered figure with a clear correction note when you find an error.
