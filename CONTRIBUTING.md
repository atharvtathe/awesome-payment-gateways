# Contributing

Thanks for helping founders get paid. Three kinds of contributions are welcome:

1. **Add a provider**: an MoR, gateway or local gateway that indie founders can sign up for.
2. **Update an entry** whose fees or supported countries have changed.
3. **Fix the country table**: a "Yes" or "No" that is wrong for your country. Founders who actually live there are the best source for this.

Don't want to open a pull request? [Open an issue](../../issues/new/choose) and fill in the form instead.

## What qualifies

- It accepts online payments for SaaS, apps or digital products.
- A small business or solo founder can sign up (no enterprise-only sales process).
- It publishes its fees, or at least says how to get them.

Not accepted:

- Crypto-only processors.
- In-person card terminals.
- Invoicing or billing tools that are not payment providers themselves.
- Affiliate or tracking links. Link straight to the provider's pricing or docs page.

Working for the provider is fine. Just say so in the pull request.

## Adding or updating an entry

Every number must come from the provider's **own** page: pricing, docs or help center. Not from review sites, comparison blogs or a competitor's blog post.

| Column                 | What to write                                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Provider**           | `[Name](link to the pricing or fees page)`                                                                          |
| **Fee**                | The standard card rate, e.g. `2.9% + 30¢`. Say which country it's for if it varies. `On request` if not shown.      |
| **Extra fees**         | International cards, currency conversion, payouts, subscriptions, disputes. Only what the provider publishes.       |
| **Sell from**          | Where the **seller** can be based. Link to the provider's country list.                                             |
| **No company needed?** | MoRs only. "Yes" only if the provider's own page says individuals or sole traders can sell. Otherwise `Not stated`. |
| **Payouts**            | How you get your money (bank, PayPal, Wise, etc.) and any minimum.                                                  |
| **Verified**           | The month you checked, e.g. `Nov 2026`.                                                                             |

Style:

- Keep each cell short. Use `;` to separate items.
- Use the currency the provider uses (`$`, `€`, `₹`, `₦`).
- Don't rank providers or add opinions. Facts only.
- Update the count next to the section in **Contents**.

## Country table

- Use "Yes" only when the provider's own country list includes the country.
- Add a short note under the table if there's a catch (invite only, partner restrictions, PayPal only).
- Link the source in your pull request.

## Country guides

Guides live in `countries/`, one file per country. Copy an existing guide and keep the same sections: quick answer, Stripe, MoRs, local gateways, things to know. Only include facts from providers' own pages, and link each one.

Live in a country that doesn't have a guide yet? You're the best person to write it.

## Pull request checklist

- [ ] One provider (or one fix) per pull request.
- [ ] Link goes to the provider's pricing, docs or help page.
- [ ] Every number comes from the provider's own pages.
- [ ] **Verified** set to the month you checked.
- [ ] Country table and country guides updated if affected.
- [ ] CHANGELOG.md updated for fee or country changes.
- [ ] Section count in Contents updated (new or removed providers only).

By contributing, you agree to release your contribution under the [CC0 license](LICENSE) and to follow the [Code of Conduct](code-of-conduct.md).
