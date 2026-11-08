# Awesome Payment Gateways [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Check links](https://github.com/atharvtathe/awesome-payment-gateways/actions/workflows/links.yml/badge.svg)](https://github.com/atharvtathe/awesome-payment-gateways/actions/workflows/links.yml)

> How indie founders get paid, wherever they live: merchant of record platforms, payment gateways and local options, with fees and the countries you can sell from.

**Scope:** ways for a SaaS, app or digital product business to accept online payments from customers. Fees and country support come from each provider's own pages. Not included: crypto-only processors, in-person card terminals, and invoicing tools that are not payment providers.

**Last full review:** November 2026 · [What changed](CHANGELOG.md)

## Contents

- [Start Here: MoR or Gateway](#start-here-mor-or-gateway)
- [Can I Sell From My Country](#can-i-sell-from-my-country)
- [Country Guides](#country-guides)
- [What a $20 Sale Costs](#what-a-20-sale-costs)
- [Merchant of Record Platforms](#merchant-of-record-platforms) (11)
- [Global Payment Gateways](#global-payment-gateways) (4)
- [Local Payment Gateways](#local-payment-gateways) (16)
- [Receive Your Payouts](#receive-your-payouts) (2)
- [No Option in Your Country: Open a US Company](#no-option-in-your-country-open-a-us-company) (3)
- [Related](#related)

**How to read the tables:** _Fee_ is the standard published rate for a card payment. _Sell from_ means where you, the seller, can be based and get paid, which is different from where your customers can be. _Verified_ is the month the entry was last checked against the provider's own pages.

---

## Start Here: MoR or Gateway

|                        | Merchant of Record (MoR)                                 | Payment gateway                                                |
| ---------------------- | -------------------------------------------------------- | -------------------------------------------------------------- |
| Who sells to the buyer | The MoR resells your product, so it is the legal seller  | You                                                            |
| Sales tax, VAT and GST | The MoR collects, files and pays them worldwide          | You do (tools like Stripe Tax help)                            |
| Chargebacks and fraud  | Handled by the MoR                                       | Handled by you                                                 |
| Typical fee            | About 4–5% + a fixed fee                                 | About 3% + a fixed fee                                         |
| Who it suits           | Solo founders selling SaaS or digital products worldwide | Businesses selling mostly at home, or big enough to handle tax |
| Where you can be based | Often far more countries than Stripe                     | Only where the gateway itself operates                         |

**A quick way to decide:**

| Your situation                                   | Start with                                                                                      |
| ------------------------------------------------ | ----------------------------------------------------------------------------------------------- |
| Stripe works in your country                     | Stripe, the cheapest start. Add Stripe Tax or Stripe Managed Payments when sales tax gets hard. |
| Stripe doesn't work in your country              | An MoR that pays out to your country. The fastest way to sell worldwide.                        |
| Most customers are in your own country           | A local gateway, for local payment methods like UPI, Pix and mobile money.                      |
| You need Stripe anyway (investors, marketplaces) | A US company (last section of this list).                                                       |

## Can I Sell From My Country

Countries where founders most often can't use Stripe. "Yes" means the provider's own country list includes it. Every provider still reviews each seller before approving them.

| Country      | Stripe       | Paddle | Lemon Squeezy | Polar | Creem   | Dodo | Kelviq | Local options                       |
| ------------ | ------------ | ------ | ------------- | ----- | ------- | ---- | ------ | ----------------------------------- |
| India        | Invite only  | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | Razorpay, Cashfree, PayU, Instamojo |
| Pakistan     | No           | Yes    | Yes           | Yes   | Limited | No   | Yes    | Safepay                             |
| Bangladesh   | No           | Yes    | Yes           | Yes   | Limited | No   | Yes    | SSLCommerz, aamarPay                |
| Sri Lanka    | No           | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | PayHere                             |
| Nepal        | No           | Yes    | PayPal only   | No    | Limited | Yes  | No     | Khalti                              |
| Indonesia    | Invite only  | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | Xendit                              |
| Philippines  | No           | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | Xendit                              |
| Vietnam      | No           | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | –                                   |
| Nigeria      | Via Paystack | Yes    | Yes           | Yes   | Yes     | No   | Yes    | Paystack, Flutterwave               |
| Kenya        | Via Paystack | Yes    | Yes           | Yes   | Yes     | No   | Yes    | Paystack, Flutterwave               |
| Ghana        | Via Paystack | Yes    | Yes           | Yes   | No      | Yes  | Yes    | Paystack, Flutterwave               |
| South Africa | Via Paystack | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | Paystack, Flutterwave               |
| Egypt        | No           | Yes    | Yes           | Yes   | Yes     | No   | Yes    | Paymob                              |
| Turkey       | No           | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | iyzico                              |
| UAE          | Yes          | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | Telr                                |
| Brazil       | Yes          | Yes    | PayPal only   | No    | Yes     | Yes  | No     | Mercado Pago                        |
| Argentina    | No           | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | Mercado Pago                        |
| Mexico       | Yes          | Yes    | Yes           | Yes   | Yes     | Yes  | Yes    | Mercado Pago                        |

| Column        | What it means                                                                                                                                         |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Stripe        | "Invite only": Stripe marks the country as Preview and sends you to sales. "Via Paystack": Stripe sends sign-ups there to Paystack, a Stripe company. |
| Paddle        | Paddle publishes the countries it does _not_ support. None of these countries are on that list.                                                       |
| Lemon Squeezy | "Yes" means bank payouts. "PayPal only" means you need a PayPal account that can receive money in your country.                                       |
| Polar         | Pays out through Stripe Connect Express to the countries it lists.                                                                                    |
| Creem         | "Limited" means Creem lists the country with "partner restrictions".                                                                                  |
| Dodo          | Some countries marked "No" are kept only for existing merchants, not new sign-ups.                                                                    |
| Kelviq        | Supports businesses registered in the 120 countries it lists. Payouts go through Stripe.                                                              |

Each provider's country list is linked in the Merchant of Record Platforms table below.

## Country Guides

Step-by-step options for founders in each country: what works, what it costs, and how the money reaches you.

| Country                               | Stripe       | Best place to start                           |
| ------------------------------------- | ------------ | --------------------------------------------- |
| [India](countries/india.md)           | Invite only  | An MoR, or Razorpay, Cashfree or PayU at home |
| [Pakistan](countries/pakistan.md)     | No           | Paddle, Lemon Squeezy, Polar or Kelviq        |
| [Bangladesh](countries/bangladesh.md) | No           | Paddle, Lemon Squeezy, Polar or Kelviq        |
| [Nigeria](countries/nigeria.md)       | Via Paystack | Paystack, or an MoR for worldwide sales       |
| [Indonesia](countries/indonesia.md)   | Invite only  | Any MoR on this list, or Xendit at home       |
| [Brazil](countries/brazil.md)         | Yes          | Stripe, an MoR, or Mercado Pago with Pix      |

Want a guide for your country? Open an issue (see [Contributing](#contributing)).

## What a $20 Sale Costs

Headline fee on a $20 card payment from a US customer, at each provider's standard rate. This leaves out payout, currency conversion and dispute fees.

| Provider                                             | Fee on $20             | Handles sales tax and VAT   |
| ---------------------------------------------------- | ---------------------- | --------------------------- |
| Stripe (2.9% + 30¢)                                  | $0.88                  | No (Stripe Tax costs extra) |
| Kelviq (3.5% + 40¢; 2.9% + 40¢ on your first $5,000) | $1.10 ($0.98 at first) | Yes                         |
| Creem (3.9% + 40¢)                                   | $1.18                  | Yes                         |
| Dodo Payments (4% + 40¢)                             | $1.20                  | Yes                         |
| Paddle (5% + 50¢)                                    | $1.50                  | Yes                         |
| Lemon Squeezy (5% + 50¢)                             | $1.50                  | Yes                         |
| Polar (5% + 50¢, free plan)                          | $1.50                  | Yes                         |
| Fungies (5% + 50¢)                                   | $1.50                  | Yes                         |
| Gumroad (10% + 50¢)                                  | $2.50                  | Yes                         |

---

## Merchant of Record Platforms

They sell your product on your behalf and handle sales tax, VAT, fraud and chargebacks.

| Provider                                                                     | Fee                                          | Extra fees                                                    | Sell from                                                                                                                                                  | No company needed?                                                                                                                                   | Verified |
| ---------------------------------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [Paddle](https://www.paddle.com/pricing)                                     | 5% + 50¢                                     | Products under $10 need custom pricing                        | Anywhere except a [sanctions list](https://www.paddle.com/help/start/intro-to-paddle/which-countries-are-supported-by-paddle)                              | Yes: [Business check skipped for individuals and sole traders](https://www.paddle.com/help/start/account-verification/what-is-business-verification) | Nov 2026 |
| [Lemon Squeezy](https://www.lemonsqueezy.com/pricing)                        | 5% + 50¢                                     | Small extra fees on some payments, e.g. outside the US        | Bank payouts in [79 countries](https://docs.lemonsqueezy.com/help/getting-started/supported-countries), PayPal in 200+                                     | Not stated; needs a bank or verified PayPal account                                                                                                  | Nov 2026 |
| [Polar](https://polar.sh/resources/pricing)                                  | 5% + 50¢ free; from 3.4% + 30¢ on paid plans | +1.5% non-US cards; $15 per dispute                           | [118 countries](https://polar.sh/docs/merchant-of-record/supported-countries)                                                                              | Not stated; [owner ID and selfie](https://polar.sh/docs/merchant-of-record/account-reviews)                                                          | Nov 2026 |
| [Creem](https://www.creem.io/pricing)                                        | 3.9% + 40¢                                   | Payout fee: 7 USD/EUR or 1%, whichever is higher              | [87 countries](https://docs.creem.io/merchant-of-record/supported-countries)                                                                               | Not stated in docs                                                                                                                                   | Nov 2026 |
| [Kelviq](https://kelviq.com/pricing/)                                        | 3.5% + 40¢; 2.9% + 40¢ until $5,000 in sales | +1.5% non-US cards; +0.7% subscriptions; $15 per dispute      | [120 countries](https://docs.kelviq.com/getstarted/review-process)                                                                                         | Not stated in docs                                                                                                                                   | Nov 2026 |
| [Dodo Payments](https://dodopayments.com/pricing)                            | 4% + 40¢; domestic India 4% + 15¢            | +1.5% international; +0.5% subscriptions; +3% PayPal and BNPL | [177 countries](https://docs.dodopayments.com/miscellaneous/accepted-countries-and-territories)                                                            | Yes: [Choose "Individual" at verification](https://docs.dodopayments.com/miscellaneous/verification-process)                                         | Nov 2026 |
| [Stripe Managed Payments](https://docs.stripe.com/payments/managed-payments) | Not published in the docs                    | Digital products only; Checkout and Payment Links only        | [37 locations](https://docs.stripe.com/payments/managed-payments/eligibility): US, Canada, EU/EEA, UK, Switzerland, Australia, Hong Kong, Japan, Singapore | Reviewed case by case                                                                                                                                | Nov 2026 |
| [Gumroad](https://gumroad.com/pricing)                                       | 10% + 50¢                                    | 30% on sales through its Discover marketplace                 | Not listed on pricing page                                                                                                                                 | Yes: [Choose "Individual" for payouts](https://gumroad.com/help/article/260-your-payout-settings-page)                                               | Nov 2026 |
| [Fungies](https://fungies.io/pricing)                                        | 5% + 50¢                                     | None listed; negotiable at higher volume                      | [55 countries](https://help.fungies.io/getting-paid/global-availability)                                                                                   | Not stated in help center                                                                                                                            | Nov 2026 |
| [Freemius](https://freemius.com/pricing/)                                    | 3.8% + 50¢ plus gateway fees                 | +2.3% for WordPress products; lower % above $50K/mo           | [190+ countries](https://freemius.com/help/documentation/selling-with-freemius/supported-countries) (via PayPal, Payoneer, Wise or wire)                   | Yes: [Can start as an individual](https://freemius.com/help/payout-methods/)                                                                         | Nov 2026 |
| [FastSpring](https://fastspring.com/pricing/)                                | On request (revenue share by volume)         | Not published                                                 | Not listed on pricing page                                                                                                                                 | Not stated                                                                                                                                           | Nov 2026 |

**How MoRs pay you:**

| Provider      | Payout methods                                      | Minimum           | Schedule and payout fees                                                    |
| ------------- | --------------------------------------------------- | ----------------- | --------------------------------------------------------------------------- |
| Paddle        | Not stated on pricing page                          | Not stated        | Not stated                                                                  |
| Lemon Squeezy | Bank wire or PayPal                                 | $50               | Created on the 1st and 15th, after a 13-day hold; small fee on some payouts |
| Polar         | Stripe Connect Express                              | Not stated        | Stripe fees: $2/mo while active, 0.25% + 25¢ per payout                     |
| Creem         | Bank transfer, USDC, Alipay (China only); no PayPal | $50               | 1st and 15th; 7 USD/EUR or 1%, whichever is higher                          |
| Kelviq        | Bank account or eligible debit card, via Stripe     | Not stated        | Rolling 7-day schedule; no payout fee                                       |
| Dodo Payments | Bank, SWIFT wire                                    | Not stated        | $5 on payouts under $1,000; $25 for SWIFT outside the US                    |
| Gumroad       | Local bank or PayPal, depending on country          | Not stated        | Not stated on pricing page                                                  |
| Fungies       | Your connected payout account                       | Varies by country | Daily by default; weekly, monthly or manual                                 |
| Freemius      | PayPal, Payoneer, Wise or wire                      | $100              | Monthly                                                                     |

**Handles tax, but not an MoR:** [Payhip](https://payhip.com/pricing) collects and pays EU/UK VAT and US/Canadian sales tax for you, but payments go through your own Stripe or PayPal account, so you still need one of those in your country. Fees: 5% on the free plan, 2% on $29/mo, 0% on $99/mo, plus Stripe or PayPal fees.

## Global Payment Gateways

You are the seller and handle sales tax yourself.

| Provider                                                                | Fee                                                 | Extra fees                                                                 | Sell from                                                                  | Verified |
| ----------------------------------------------------------------------- | --------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------- |
| [Stripe](https://stripe.com/pricing)                                    | 2.9% + 30¢ (US cards)                               | +1.5% international cards; +1% currency conversion; Billing 0.7% of volume | [51 countries](https://stripe.com/global); India and Indonesia invite only | Nov 2026 |
| [PayPal](https://www.paypal.com/us/business/paypal-business-fees)       | PayPal Checkout 3.49% + 49¢; cards 2.99% + 49¢ (US) | +1.5% international; 3–4% currency conversion                              | Depends on your country's PayPal account type                              | Nov 2026 |
| [Braintree](https://www.paypal.com/us/enterprise/paypal-braintree-fees) | 2.89% + 29¢ (US cards and wallets)                  | +1% cards issued outside the US; +1% non-USD presentment                   | US rates shown; other countries need PayPal approval                       | Nov 2026 |
| [Mollie](https://www.mollie.com/pricing)                                | 1.8% + €0.25 (EEA consumer cards)                   | Non-EEA cards 3.25% + €0.25; iDEAL €0.32                                   | Not listed on pricing page (Europe-focused)                                | Nov 2026 |

Stripe accepts individuals and [sole proprietors without a separate business entity](https://support.stripe.com/questions/selling-on-stripe-without-a-separate-business-entity), though requirements vary by country.

## Local Payment Gateways

Best for customers paying in their own currency with local methods. Most need a local business or bank account.

### South Asia

| Provider                                                                       | Country    | Fee                                        | International cards               | Other costs                                                | Verified |
| ------------------------------------------------------------------------------ | ---------- | ------------------------------------------ | --------------------------------- | ---------------------------------------------------------- | -------- |
| [Razorpay](https://razorpay.com/pricing/)                                      | India      | 2% (cards, netbanking, wallets) + GST      | Up to 3% + GST                    | No setup or annual fee                                     | Nov 2026 |
| [Cashfree](https://www.cashfree.com/payment-gateway-charges/)                  | India      | 1.95% + taxes                              | 2.99% Visa/Mastercard; 2.95% Amex | No setup fee                                               | Nov 2026 |
| [PayU](https://payu.in/pricing/)                                               | India      | 2% + GST                                   | 3% + GST                          | No setup or annual fee                                     | Nov 2026 |
| [Instamojo](https://www.instamojo.com/pricing/)                                | India      | 2% + ₹3 (gateway) + GST                    | On request; charged in INR        | Store plans charge up to 5–10% + ₹3                        | Nov 2026 |
| [Safepay](https://safepay.helpscoutdocs.com/article/131-safepay-fee-breakdown) | Pakistan   | 2.9% + Rs30 (excl. tax)                    | 3.2% + Rs30 (excl. tax)           | No yearly fee                                              | Nov 2026 |
| [SSLCommerz](https://sslcommerz.com/pricing/)                                  | Bangladesh | 2.5% (cards, bKash, Nagad, Rocket)         | Same 2.5%; Amex 3.5%              | Basic plan ৳25,500                                         | Nov 2026 |
| [aamarPay](https://aamarpay.com/pricing)                                       | Bangladesh | 2.55% cards; 2% bKash, Nagad (Growth plan) | Bank-issued cards only            | One-time setup fee on request; business documents required | Nov 2026 |
| [PayHere](https://www.payhere.lk/fees)                                         | Sri Lanka  | 3.30% (Lite plan)                          | Premium cards (Amex etc.) +0.5%   | No setup or monthly fee on Lite                            | Nov 2026 |
| [Khalti](https://khalti.com/payment-gateway/)                                  | Nepal      | On request                                 | Not published                     | Not published                                              | Nov 2026 |

### Southeast Asia

| Provider                                                                                                 | Country                         | Fee                                                  | International cards                      | Other costs  | Verified |
| -------------------------------------------------------------------------------------------------------- | ------------------------------- | ---------------------------------------------------- | ---------------------------------------- | ------------ | -------- |
| [Xendit](https://help.xendit.co/hc/en-us/articles/360039086452-What-are-the-pricing-for-Xendit-products) | Indonesia, Philippines and more | Indonesia: 2.9% + IDR 2,000; Philippines: 3.2% + ₱10 | Philippines: 4.2% + ₱10 (charged in PHP) | Excludes VAT | Nov 2026 |

### Africa

| Provider                                                                | Country                                            | Fee                                    | International cards    | Other costs     | Verified |
| ----------------------------------------------------------------------- | -------------------------------------------------- | -------------------------------------- | ---------------------- | --------------- | -------- |
| [Paystack](https://support.paystack.com/hc/en-us/articles/360009881920) | Nigeria, Ghana, Kenya, South Africa, Côte d'Ivoire | Nigeria: 1.5% + ₦100, capped at ₦2,000 | 3.9% + ₦100; Amex 4.5% | Owned by Stripe | Nov 2026 |
| [Flutterwave](https://flutterwave.com/us/pricing)                       | Nigeria, Kenya, Ghana, South Africa and more       | See pricing page                       | See pricing page       | –               | Nov 2026 |

### Middle East & Turkey

| Provider                                              | Country                            | Fee                                              | International cards | Other costs                                           | Verified |
| ----------------------------------------------------- | ---------------------------------- | ------------------------------------------------ | ------------------- | ----------------------------------------------------- | -------- |
| [Telr](https://telr.com/pricing/)                     | UAE, Saudi Arabia, Jordan, Bahrain | UAE: 2.25–2.45% + AED 0.50–1 (by monthly volume) | +0.5%               | AED 0–249/mo by plan; trade license required; +5% VAT | Nov 2026 |
| [iyzico](https://www.iyzico.com/en/business/easy-pos) | Turkey                             | Per merchant, shown in your merchant panel       | Not published       | –                                                     | Nov 2026 |
| [Paymob](https://paymob.com)                          | Egypt and more                     | Varies by merchant; adjusts as volume grows      | Not published       | –                                                     | Nov 2026 |

### Latin America

| Provider                                                                         | Country                            | Fee                                                           | International cards | Other costs    | Verified |
| -------------------------------------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------- | ------------------- | -------------- | -------- |
| [Mercado Pago](https://www.mercadopago.com.br/ferramentas-para-vender/check-out) | Brazil, Argentina, Mexico and more | Brazil: credit cards 3.98–4.98% (by payout timing); Pix 0.99% | Not published       | No monthly fee | Nov 2026 |

## Receive Your Payouts

Accounts that give you USD, EUR or GBP bank details, so an MoR, client or marketplace can pay you like a local.

| Provider                                    | What it does                                                         | Fees                                                                  | Verified |
| ------------------------------------------- | -------------------------------------------------------------------- | --------------------------------------------------------------------- | -------- |
| [Wise](https://wise.com/us/pricing/receive) | USD, EUR and GBP account details where you're eligible to hold money | Free to receive local USD, EUR and GBP payments; USD wire/Swift $6.11 | Nov 2026 |
| [Payoneer](https://www.payoneer.com/fees/)  | Receiving accounts in major currencies; a common MoR payout option   | See fees page                                                         | Nov 2026 |

## No Option in Your Country: Open a US Company

A US company can open a Stripe account no matter where you live. It also adds US tax filings every year, so talk to an accountant first.

| Service                                       | Price to start                                                     | Yearly cost after that                                        | Verified |
| --------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------- | -------- |
| [Stripe Atlas](https://stripe.com/atlas)      | $500 one time (Delaware company, EIN, first-year registered agent) | $100/yr registered agent                                      | Nov 2026 |
| [doola](https://www.doola.com/pricing/)       | Starter $297/yr + state fees                                       | Same; Tax & Compliance plan $1,999/yr                         | Nov 2026 |
| [Firstbase](https://www.firstbase.io/pricing) | $99 one time + state fee                                           | Registered agent $299/state; optional Firstbase One $2,388/yr | Nov 2026 |

---

## Related

- [Awesome Ad Spots](https://github.com/atharvtathe/awesome-ad-spots) - Websites that sell ad spots directly, for when you have a way to get paid and need customers.

---

## Contributing

Found a provider that's missing, or a fee that changed? Pull requests are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first, or [open an issue](../../issues/new/choose) without writing any markdown. Founders who live in a country are the best source for its row in the country table.

## Footnotes

Fees and country support change often. Everything here comes from the providers' public pages and may be out of date, so confirm with the provider before you sign up. This is not financial, legal or tax advice. No listing here is paid or endorsed.
