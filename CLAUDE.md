# Instructions for Claude

The owner runs **two separate businesses**, each its own LLC. They are NOT one company.

| Folder | Business | Legal entity |
|---|---|---|
| `rental/` | Car rental business | _[Rental LLC legal name]_ |
| `custom-shop/` | Car customization shop | _[Shop LLC legal name]_ |
| `owner/` | The owner's personal planning across both | (not a business) |
| `between-businesses/` | Any work, money or cars that move between the two LLCs | — |

## Rules (always follow)

1. **Keep the businesses separate.** Never mix one LLC's customers, money, expenses,
   invoices, contracts or records into the other's folder. Separate books protect the
   liability shield of each LLC.
2. **If it's unclear which business something is for, ask** before writing it down.
3. **Label everything** with `[RENTAL]` or `[SHOP]` when it shows up in `owner/` files.
4. If one business does work for or sells to the other (e.g. the shop installs
   parts on a rental car), log it in `between-businesses/log.md` and remind the owner
   it should be invoiced and paid like any outside customer.
5. Each business folder has its own `CLAUDE.md` with details — read it when working there.
6. Do not store full card numbers, SSNs, driver's license numbers or passwords here.
   Refer to the system where those live instead.
7. Keep language plain and practical. The owner is busy — short lists beat long essays.

## Common requests and where they go
- "Add a task" → that business's `tasks.md` (also show it in `owner/this-week.md` if due this week)
- "Log an expense" → that business's `expenses.md`
- "What do I have going on?" → summarize `owner/this-week.md` + both `tasks.md` files, grouped by business
- Deadlines (taxes, registrations, insurance renewals, LLC annual reports) → `owner/deadlines.md`
