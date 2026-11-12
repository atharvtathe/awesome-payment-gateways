# Awesome Payment Gateways [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Check links](https://github.com/atharvtathe/awesome-payment-gateways/actions/workflows/links.yml/badge.svg)](https://github.com/atharvtathe/awesome-payment-gateways/actions/workflows/links.yml)

> How indie founders get paid online: merchant of record platforms, payment gateways, payout accounts and company formation services, with fees and where sellers can be based.

**Scope:** ways for a SaaS, app or digital product business to accept online payments from customers anywhere in the world. Fees and seller eligibility come from each provider's own pages. Not included: crypto-only processors, in-person card terminals, and invoicing tools that are not payment providers.

**Last full review:** November 2026 · [What changed](CHANGELOG.md)

## Contents

- [Start Here: MoR or Gateway](#start-here-mor-or-gateway)
- [What a $20 Sale Costs](#what-a-20-sale-costs)
- [Merchant of Record Platforms](#merchant-of-record-platforms) (14)
- [Payment Gateways](#payment-gateways) (8)
- [Regional Gateways](#regional-gateways) (16)
- [Payment Methods Buyers Can Use](#payment-methods-buyers-can-use)
- [Disputes and Refunds](#disputes-and-refunds)
- [Receive Your Payouts](#receive-your-payouts) (4)
- [Can't Use Stripe Where You Live: Open a US Company](#cant-use-stripe-where-you-live-open-a-us-company) (5)
- [Related](#related)

**How to read the tables:** _Fee_ is the standard published rate for a card payment. _Sell from_ means where you, the seller, can be based and get paid, which is different from where your customers can be. Always check your own country against the linked list. _Verified_ is the month the entry was last checked against the provider's own pages.

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
| Most customers pay with local methods            | A regional gateway for UPI, Pix, mobile money and similar.                                      |
| You don't want to deal with sales tax or VAT     | An MoR, wherever you are based.                                                                 |
| You need Stripe anyway (investors, marketplaces) | A US company (last section of this list).                                                       |

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

| Provider                                                                     | Fee                                          | Extra fees                                                                                                                                                                | Sell from                                                                                                                                                  | No company needed?                                                                                                                                   | Verified |
| ---------------------------------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [Paddle](https://www.paddle.com/pricing)                                     | 5% + 50¢                                     | Products under $10 need custom pricing                                                                                                                                    | Anywhere except a [sanctions list](https://www.paddle.com/help/start/intro-to-paddle/which-countries-are-supported-by-paddle)                              | Yes: [Business check skipped for individuals and sole traders](https://www.paddle.com/help/start/account-verification/what-is-business-verification) | Nov 2026 |
| [Lemon Squeezy](https://www.lemonsqueezy.com/pricing)                        | 5% + 50¢                                     | [+1.5% international; +1.5% PayPal; +0.5% subscriptions](https://docs.lemonsqueezy.com/help/getting-started/fees)                                                         | Bank payouts in [79 countries](https://docs.lemonsqueezy.com/help/getting-started/supported-countries), PayPal in 200+                                     | Not stated; needs a bank or verified PayPal account                                                                                                  | Nov 2026 |
| [Polar](https://polar.sh/resources/pricing)                                  | 5% + 50¢ free; from 3.4% + 30¢ on paid plans | +1.5% non-US cards; $15 per dispute                                                                                                                                       | [118 countries](https://polar.sh/docs/merchant-of-record/supported-countries)                                                                              | Not stated; [owner ID and selfie](https://polar.sh/docs/merchant-of-record/account-reviews)                                                          | Nov 2026 |
| [Creem](https://www.creem.io/pricing)                                        | 3.9% + 40¢                                   | Payout fee: 7 USD/EUR or 1%, whichever is higher                                                                                                                          | [87 countries](https://docs.creem.io/merchant-of-record/supported-countries)                                                                               | Not stated in docs                                                                                                                                   | Nov 2026 |
| [Kelviq](https://kelviq.com/pricing/)                                        | 3.5% + 40¢; 2.9% + 40¢ until $5,000 in sales | +1.5% non-US cards; +0.7% subscriptions; $15 per dispute                                                                                                                  | [120 countries](https://docs.kelviq.com/getstarted/review-process)                                                                                         | Not stated in docs                                                                                                                                   | Nov 2026 |
| [Dodo Payments](https://dodopayments.com/pricing)                            | 4% + 40¢; domestic India 4% + 15¢            | +1.5% international; +0.5% subscriptions; +3% PayPal and BNPL                                                                                                             | [177 countries](https://docs.dodopayments.com/miscellaneous/accepted-countries-and-territories)                                                            | Yes: [Choose "Individual" at verification](https://docs.dodopayments.com/miscellaneous/verification-process)                                         | Nov 2026 |
| [Stripe Managed Payments](https://docs.stripe.com/payments/managed-payments) | Not published in the docs                    | Digital products only; Checkout and Payment Links only                                                                                                                    | [37 locations](https://docs.stripe.com/payments/managed-payments/eligibility): US, Canada, EU/EEA, UK, Switzerland, Australia, Hong Kong, Japan, Singapore | Reviewed case by case                                                                                                                                | Nov 2026 |
| [Gumroad](https://gumroad.com/pricing)                                       | 10% + 50¢                                    | 30% on sales through its Discover marketplace                                                                                                                             | Not listed on pricing page                                                                                                                                 | Yes: [Choose "Individual" for payouts](https://gumroad.com/help/article/260-your-payout-settings-page)                                               | Nov 2026 |
| [Fungies](https://fungies.io/pricing)                                        | 5% + 50¢                                     | None listed; negotiable at higher volume                                                                                                                                  | [55 countries](https://help.fungies.io/getting-paid/global-availability)                                                                                   | Not stated in help center                                                                                                                            | Nov 2026 |
| [Freemius](https://freemius.com/pricing/)                                    | 3.8% + 50¢ plus gateway fees                 | +2.3% for WordPress products; lower % above $50K/mo                                                                                                                       | [190+ countries](https://freemius.com/help/documentation/selling-with-freemius/supported-countries) (via PayPal, Payoneer, Wise or wire)                   | Yes: [Can start as an individual](https://freemius.com/help/payout-methods/)                                                                         | Nov 2026 |
| [FastSpring](https://fastspring.com/pricing/)                                | On request (revenue share by volume)         | Not published                                                                                                                                                             | Not listed on pricing page                                                                                                                                 | Not stated                                                                                                                                           | Nov 2026 |
| [2Checkout (Verifone)](https://www.2checkout.com/pricing/)                   | By plan: 2Sell, 2Subscribe, 2Monetize        | [+2% cross-border fee](https://docs.2checkout.com/product-catalog/product-catalog/pricing-and-charge-scenarios/cross-border-payments-fee-charges) on 2Sell and 2Subscribe | Not listed on pricing page                                                                                                                                 | Not stated                                                                                                                                           | Nov 2026 |
| [PayPro Global](https://payproglobal.com/pricing/)                           | On request (one price, all features)         | Not published                                                                                                                                                             | Not listed on pricing page                                                                                                                                 | Not stated                                                                                                                                           | Nov 2026 |
| [Cleverbridge](https://grow.cleverbridge.com/pricing)                        | On request (a cut of each transaction)       | Not published                                                                                                                                                             | Not listed on pricing page                                                                                                                                 | Not stated                                                                                                                                           | Nov 2026 |

**How MoRs pay you:**

| Provider      | Payout methods                                                                                          | Minimum              | Schedule and payout fees                                                                     |
| ------------- | ------------------------------------------------------------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------------------- |
| Paddle        | Not stated on pricing page                                                                              | Not stated           | Not stated                                                                                   |
| Lemon Squeezy | Bank wire or PayPal                                                                                     | $50                  | Created on the 1st and 15th, after a 13-day hold; non-US bank 1%, non-US PayPal 3% (max $30) |
| Polar         | Stripe Connect Express                                                                                  | Not stated           | Stripe fees: $2/mo while active, 0.25% + 25¢ per payout                                      |
| Creem         | Bank transfer, USDC, Alipay (China only); no PayPal                                                     | $50                  | 1st and 15th; 7 USD/EUR or 1%, whichever is higher                                           |
| Kelviq        | Bank account or eligible debit card, via Stripe                                                         | Not stated           | Rolling 7-day schedule; no payout fee                                                        |
| Dodo Payments | Bank, SWIFT wire                                                                                        | Not stated           | $5 on payouts under $1,000; $25 for SWIFT outside the US                                     |
| Gumroad       | Local bank or PayPal, depending on country                                                              | Not stated           | Not stated on pricing page                                                                   |
| Fungies       | Your connected payout account                                                                           | Varies by country    | Daily by default; weekly, monthly or manual                                                  |
| Freemius      | PayPal, Payoneer, Wise or wire                                                                          | $100                 | Monthly                                                                                      |
| 2Checkout     | [Wire, PayPal or Payoneer prepaid card](https://docs.2checkout.com/get-started/getting-started/payouts) | $50 (2Monetize $100) | Weekly (2Monetize monthly); wire $15, PayPal and Payoneer no 2Checkout fee                   |

**Handles tax, but not an MoR:** [Payhip](https://payhip.com/pricing) collects and pays EU/UK VAT and US/Canadian sales tax for you, but payments go through your own Stripe or PayPal account, so you still need one of those in your country. Fees: 5% on the free plan, 2% on $29/mo, 0% on $99/mo, plus Stripe or PayPal fees.

## Payment Gateways

You are the seller and handle sales tax yourself.

| Provider                                                                      | Fee                                                 | Extra fees                                                                           | Sell from                                                                                                                                        | Verified |
| ----------------------------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | -------- |
| [Stripe](https://stripe.com/pricing)                                          | 2.9% + 30¢ (US cards)                               | +1.5% international cards; +1% currency conversion; Billing 0.7% of volume           | [51 countries](https://stripe.com/global); a few are invite only                                                                                 | Nov 2026 |
| [PayPal](https://www.paypal.com/us/business/paypal-business-fees)             | PayPal Checkout 3.49% + 49¢; cards 2.99% + 49¢ (US) | +1.5% international; 3–4% currency conversion                                        | Depends on your country's PayPal account type                                                                                                    | Nov 2026 |
| [Braintree](https://www.paypal.com/us/enterprise/paypal-braintree-fees)       | 2.89% + 29¢ (US cards and wallets)                  | +1% cards issued outside the US; +1% non-USD presentment                             | US rates shown; other countries need PayPal approval                                                                                             | Nov 2026 |
| [Mollie](https://www.mollie.com/pricing)                                      | 1.8% + €0.25 (EEA consumer cards)                   | Non-EEA cards 3.25% + €0.25; iDEAL €0.32                                             | Not listed on pricing page (Europe-focused)                                                                                                      | Nov 2026 |
| [Airwallex](https://www.airwallex.com/us/pricing)                             | 2.8% + 30¢ (US domestic cards)                      | International cards 4.3% + 30¢; FX 0.5% above interbank (major currencies)           | [69 countries and territories](https://help.airwallex.com/hc/en-gb/articles/4408591334937-Eligible-Countries-and-Territories)                    | Nov 2026 |
| [Square](https://squareup.com/us/en/payments/our-fees)                        | Online 3.3% + 30¢ (Free plan); API 2.9% + 30¢       | 2.9% + 30¢ online on paid plans                                                      | [8 countries](https://squareup.com/help/us/en/article/4956-international-availability): US, Canada, UK, Ireland, France, Spain, Australia, Japan | Nov 2026 |
| [Authorize.net](https://www.authorize.net/sign-up/pricing.html)               | 2.9% + 30¢ + $25/mo (All-in-One)                    | Gateway only (bring your own merchant account): 10¢ + $25/mo                         | Not listed on pricing page (US-focused)                                                                                                          | Nov 2026 |
| [Revolut Business](https://www.revolut.com/business/accept-payments-pricing/) | 1% + £0.20 (UK consumer cards)                      | 2.8% + £0.20 cards from outside the UK and EEA; UK/EEA commercial cards 2.5% + £0.20 | Not listed on pricing page; needs a Revolut Business account                                                                                     | Nov 2026 |

Stripe accepts individuals and [sole proprietors without a separate business entity](https://support.stripe.com/questions/selling-on-stripe-without-a-separate-business-entity), though requirements vary by country.

## Regional Gateways

Gateways built for one country or region. Use one when most of your customers pay with local methods (UPI, Pix, mobile money, bKash) or when Stripe and the MoRs above don't cover you. Most need a local business or bank account.

| Provider                                                                                                 | Sellers based in                                   | Fee                                                           | Verified |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------- | -------- |
| [Razorpay](https://razorpay.com/pricing/)                                                                | India                                              | 2% (cards, netbanking, wallets) + GST                         | Nov 2026 |
| [Cashfree](https://www.cashfree.com/payment-gateway-charges/)                                            | India                                              | 1.95% + taxes                                                 | Nov 2026 |
| [PayU](https://payu.in/pricing/)                                                                         | India                                              | 2% + GST                                                      | Nov 2026 |
| [Instamojo](https://www.instamojo.com/pricing/)                                                          | India                                              | 2% + ₹3 (gateway) + GST                                       | Nov 2026 |
| [Safepay](https://safepay.helpscoutdocs.com/article/131-safepay-fee-breakdown)                           | Pakistan                                           | 2.9% + Rs30 (excl. tax)                                       | Nov 2026 |
| [SSLCommerz](https://sslcommerz.com/pricing/)                                                            | Bangladesh                                         | 2.5% (cards, bKash, Nagad, Rocket)                            | Nov 2026 |
| [aamarPay](https://aamarpay.com/pricing)                                                                 | Bangladesh                                         | 2.55% cards; 2% bKash, Nagad (Growth plan)                    | Nov 2026 |
| [PayHere](https://www.payhere.lk/fees)                                                                   | Sri Lanka                                          | 3.30% (Lite plan)                                             | Nov 2026 |
| [Khalti](https://khalti.com/payment-gateway/)                                                            | Nepal                                              | On request                                                    | Nov 2026 |
| [Xendit](https://help.xendit.co/hc/en-us/articles/360039086452-What-are-the-pricing-for-Xendit-products) | Indonesia, Philippines and more                    | Indonesia: 2.9% + IDR 2,000; Philippines: 3.2% + ₱10          | Nov 2026 |
| [Paystack](https://support.paystack.com/hc/en-us/articles/360009881920)                                  | Nigeria, Ghana, Kenya, South Africa, Côte d'Ivoire | Nigeria: 1.5% + ₦100, capped at ₦2,000                        | Nov 2026 |
| [Flutterwave](https://flutterwave.com/us/pricing)                                                        | Nigeria, Kenya, Ghana, South Africa and more       | See pricing page                                              | Nov 2026 |
| [Telr](https://telr.com/pricing/)                                                                        | UAE, Saudi Arabia, Jordan, Bahrain                 | UAE: 2.25–2.45% + AED 0.50–1 (by monthly volume)              | Nov 2026 |
| [iyzico](https://www.iyzico.com/en/business/easy-pos)                                                    | Turkey                                             | Per merchant, shown in your merchant panel                    | Nov 2026 |
| [Paymob](https://paymob.com)                                                                             | Egypt and more                                     | Varies by merchant; adjusts as volume grows                   | Nov 2026 |
| [Mercado Pago](https://www.mercadopago.com.br/ferramentas-para-vender/check-out)                         | Brazil, Argentina, Mexico and more                 | Brazil: credit cards 3.98–4.98% (by payout timing); Pix 0.99% | Nov 2026 |

## Payment Methods Buyers Can Use

What your customers can pay with. Providers show each buyer only the methods that fit their country, currency and device, and many local methods work for one-time payments only.

| Provider      | Cards | PayPal                      | Apple Pay and Google Pay | Local methods                                                                                                                                                               | Full list                                                                         |
| ------------- | ----- | --------------------------- | ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Paddle        | Yes   | Yes                         | Yes                      | Alipay, WeChat Pay, iDEAL, Bancontact, BLIK, MB WAY, Pix, UPI, KakaoPay, Naver Pay, Payco, Samsung Pay, bank transfer                                                       | [Paddle docs](https://developer.paddle.com/concepts/payment-methods/overview)     |
| Lemon Squeezy | Yes   | Yes                         | Yes                      | Alipay, WeChat Pay, Cash App Pay, bank debits (ACH); subscriptions: cards, wallets and PayPal only                                                                          | [Lemon Squeezy docs](https://docs.lemonsqueezy.com/help/checkout/payment-methods) |
| Polar         | Yes   | No                          | Yes                      | Link, Amazon Pay, Cash App Pay, WeChat Pay, iDEAL, Bancontact, EPS, UPI, Kakao Pay, Naver Pay, Samsung Pay                                                                  | [Polar docs](https://polar.sh/docs/features/checkout/payment-methods)             |
| Creem         | Yes   | Not listed                  | Yes                      | Alipay and iDEAL (one-time only), Alipay HK                                                                                                                                 | [Creem docs](https://docs.creem.io/merchant-of-record/finance/payment-methods)    |
| Dodo Payments | Yes   | Paused for new transactions | Yes                      | UPI, RuPay, Pix, SEPA and ACH debit, iDEAL, Bancontact, EPS, BLIK, Multibanco, Klarna, Afterpay, Amazon Pay, Cash App Pay, WeChat Pay, GCash, Kakao Pay, Naver Pay and more | [Dodo docs](https://docs.dodopayments.com/features/payment-methods)               |

## Disputes and Refunds

What a chargeback or refund costs you. Fees are per dispute and are usually charged whether you win or lose.

| Provider      | Dispute fee                                             | Refunds                                                    | Source                                                                                        |
| ------------- | ------------------------------------------------------- | ---------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Stripe (US)   | $15, plus $15 if you counter it (returned if you win)   | No refund fee; the original processing fee is not returned | [Stripe support](https://support.stripe.com/questions/june-2025-pricing-updates-for-disputes) |
| Square        | None                                                    | Processing fee is not returned on a lost dispute           | [Square help](https://squareup.com/help/us/en/article/3882-payment-disputes-walkthrough)      |
| Paddle        | No separate fee listed; chargeback handling is included | Not stated                                                 | Pricing page                                                                                  |
| Polar         | $15, whatever the outcome                               | Not stated                                                 | Pricing page                                                                                  |
| Kelviq        | $15, whatever the outcome                               | The transaction fee is not returned                        | [Kelviq fees](https://docs.kelviq.com/getstarted/fees)                                        |
| Creem         | 25 USD/EUR                                              | No refund fee; the original processing fee is not returned | [Creem docs](https://docs.creem.io/merchant-of-record/finance/refunds-and-chargebacks)        |
| Dodo Payments | $30                                                     | $1 per refund                                              | Pricing page                                                                                  |

"Pricing page" means the provider's pricing link in the tables above.

## Receive Your Payouts

Accounts that give you USD, EUR or GBP bank details, so an MoR, client or marketplace can pay you like a local.

| Provider                                                   | What it does                                                                       | Fees                                                                            | Verified |
| ---------------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | -------- |
| [Wise](https://wise.com/us/pricing/receive)                | USD, EUR and GBP account details where you're eligible to hold money               | Free to receive local USD, EUR and GBP payments; USD wire/Swift $6.11           | Nov 2026 |
| [Payoneer](https://www.payoneer.com/fees/)                 | Receiving accounts in major currencies; a common MoR payout option                 | See fees page                                                                   | Nov 2026 |
| [Airwallex](https://www.airwallex.com/us/business-account) | Business account with local details in multiple currencies; also a gateway (above) | Explore plan $0/mo; FX 0.5% above interbank for major currencies, 1% for others | Nov 2026 |
| [Grey](https://grey.co/pricing)                            | USD, GBP and EUR accounts with US, UK and European bank details                    | Free to open; no maintenance fee; deposit fees not listed on pricing page       | Nov 2026 |

## Can't Use Stripe Where You Live: Open a US Company

A US company can open a Stripe account no matter where you live. It also adds US tax filings every year, so talk to an accountant first.

| Service                                       | Price to start                                                     | Yearly cost after that                                        | Verified |
| --------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------- | -------- |
| [Stripe Atlas](https://stripe.com/atlas)      | $500 one time (Delaware company, EIN, first-year registered agent) | $100/yr registered agent                                      | Nov 2026 |
| [doola](https://www.doola.com/pricing/)       | Starter $297/yr + state fees                                       | Same; Tax & Compliance plan $1,999/yr                         | Nov 2026 |
| [Firstbase](https://www.firstbase.io/pricing) | $99 one time + state fee                                           | Registered agent $299/state; optional Firstbase One $2,388/yr | Nov 2026 |

**A bank account for your US company:**

| Provider                               | Monthly fee                       | Fees                                                                    | Who can apply                                                                                                            | Verified |
| -------------------------------------- | --------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | -------- |
| [Mercury](https://mercury.com/pricing) | $0                                | Domestic and USD international wires $0; 1% conversion on non-USD wires | US-registered companies; [founders don't need to be US residents](https://mercury.com/faq), with some countries excluded | Nov 2026 |
| [Relay](https://relayfi.com/pricing)   | $0 (Starter); Grow $30; Scale $90 | Wire fees not shown in the plan table                                   | Not stated on pricing page                                                                                               | Nov 2026 |

---

## Related

- [Awesome Ad Spots](https://github.com/atharvtathe/awesome-ad-spots) - Websites that sell ad spots directly, for when you have a way to get paid and need customers.

---

## Contributing

Found a provider that's missing, or a fee that changed? Pull requests are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first, or [open an issue](../../issues/new/choose) without writing any markdown.

## Footnotes

Fees and country support change often. Everything here comes from the providers' public pages and may be out of date, so confirm with the provider before you sign up. This is not financial, legal or tax advice. No listing here is paid or endorsed.
