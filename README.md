# Awesome Payment Gateways [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Check links](https://github.com/atharvtathe/awesome-payment-gateways/actions/workflows/links.yml/badge.svg)](https://github.com/atharvtathe/awesome-payment-gateways/actions/workflows/links.yml)

> How indie founders get paid, wherever they live: merchant of record platforms, payment gateways and local options, with fees and the countries you can sell from.

**Scope:** ways for a SaaS, app or digital product business to accept online payments from customers. Fees and country support come from each provider's own pages. Not included: crypto-only processors, in-person card terminals, and invoicing tools that are not payment providers.

## Contents

- [Start Here: MoR or Gateway?](#start-here-mor-or-gateway)
- [Can I Sell From My Country?](#can-i-sell-from-my-country)
- [What a $20 Sale Costs](#what-a-20-sale-costs)
- [Merchant of Record Platforms](#merchant-of-record-platforms) (10)
- [Global Payment Gateways](#global-payment-gateways) (3)
- [Local Payment Gateways](#local-payment-gateways) (12)
- [No Option in Your Country? Open a US Company](#no-option-in-your-country-open-a-us-company) (3)
- [Related](#related)

**How to read the tables:** _Fee_ is the standard published rate for a card payment. _Extra fees_ lists the surcharges the provider publishes (international cards, payouts, currency conversion). _You can sell from_ means where you, the seller, can be based and get paid, which is different from where your customers can be. _Verified_ is the month the entry was last checked against the provider's own pages.

---

## Start Here: MoR or Gateway?

|                        | Merchant of Record (MoR)                                                                 | Payment gateway                                                      |
| ---------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| Who sells to the buyer | The MoR resells your product, so it is the legal seller                                  | You                                                                  |
| Sales tax, VAT and GST | The MoR collects, files and pays them worldwide                                          | You do (tools like Stripe Tax help)                                  |
| Chargebacks and fraud  | Handled by the MoR                                                                       | Handled by you                                                       |
| Typical fee            | About 4–5% + a fixed fee                                                                 | About 3% + a fixed fee                                               |
| Who it suits           | Solo founders selling SaaS or digital products to customers in many countries            | Businesses that sell mostly at home, or are big enough to handle tax |
| Where you can be based | Often many more countries than Stripe, because payouts are separate from card processing | Only where the gateway itself operates                               |

**A quick way to decide:**

1. **Stripe works in your country** (see the table below)? Stripe is the cheapest start. Add Stripe Tax, or Stripe Managed Payments if you are eligible, when sales tax becomes a problem.
2. **Stripe doesn't work in your country?** Pick an MoR that pays out to your country. It's the fastest way to sell worldwide.
3. **Most customers are in your own country?** Use a local gateway for local payment methods (UPI, Pix, mobile money).
4. **You need Stripe anyway** (investors, marketplace features)? [Open a US company](#no-option-in-your-country-open-a-us-company).

## Can I Sell From My Country?

Countries where founders most often can't use Stripe. ✅ means the provider's own country list includes it. Every provider still reviews each seller before approving them.

| Country      | Stripe       | Paddle | Lemon Squeezy | Polar | Creem | Dodo Payments | Local options                                    |
| ------------ | ------------ | ------ | ------------- | ----- | ----- | ------------- | ------------------------------------------------ |
| India        | Invite only  | ✅     | ✅            | ✅    | ✅    | ✅            | [Razorpay](#south-asia), [Cashfree](#south-asia) |
| Pakistan     | ❌           | ✅     | ✅            | ✅    | ⚠️    | ❌            | [Safepay](#south-asia)                           |
| Bangladesh   | ❌           | ✅     | ✅            | ✅    | ⚠️    | ❌            | [SSLCommerz](#south-asia)                        |
| Sri Lanka    | ❌           | ✅     | ✅            | ✅    | ✅    | ✅            | [PayHere](#south-asia)                           |
| Nepal        | ❌           | ✅     | PayPal only   | ❌    | ⚠️    | ✅            | [Khalti](#south-asia)                            |
| Indonesia    | Invite only  | ✅     | ✅            | ✅    | ✅    | ✅            | [Xendit](#southeast-asia)                        |
| Philippines  | ❌           | ✅     | ✅            | ✅    | ✅    | ✅            | [Xendit](#southeast-asia)                        |
| Vietnam      | ❌           | ✅     | ✅            | ✅    | ✅    | ✅            | –                                                |
| Nigeria      | Via Paystack | ✅     | ✅            | ✅    | ✅    | ❌            | [Paystack](#africa), [Flutterwave](#africa)      |
| Kenya        | Via Paystack | ✅     | ✅            | ✅    | ✅    | ❌            | [Paystack](#africa), [Flutterwave](#africa)      |
| Ghana        | Via Paystack | ✅     | ✅            | ✅    | ❌    | ✅            | [Paystack](#africa), [Flutterwave](#africa)      |
| South Africa | Via Paystack | ✅     | ✅            | ✅    | ✅    | ✅            | [Paystack](#africa), [Flutterwave](#africa)      |
| Egypt        | ❌           | ✅     | ✅            | ✅    | ✅    | ❌            | [Paymob](#middle-east--turkey)                   |
| Turkey       | ❌           | ✅     | ✅            | ✅    | ✅    | ✅            | [iyzico](#middle-east--turkey)                   |
| Brazil       | ✅           | ✅     | PayPal only   | ❌    | ✅    | ✅            | [Mercado Pago](#latin-america)                   |
| Argentina    | ❌           | ✅     | ✅            | ✅    | ✅    | ✅            | [Mercado Pago](#latin-america)                   |
| Mexico       | ✅           | ✅     | ✅            | ✅    | ✅    | ✅            | [Mercado Pago](#latin-america)                   |
| UAE          | ✅           | ✅     | ✅            | ✅    | ✅    | ✅            | –                                                |

Notes:

- **Stripe:** "Invite only" means [Stripe's country page](https://stripe.com/global) marks the country as Preview and sends you to sales. "Via Paystack" means Stripe sends sign-ups in that country to Paystack, a Stripe company.
- **Paddle:** Paddle publishes the countries it does _not_ support. None of the countries above are on [that list](https://www.paddle.com/help/start/intro-to-paddle/which-countries-are-supported-by-paddle).
- **Lemon Squeezy:** ✅ means bank payouts are available ([list](https://docs.lemonsqueezy.com/help/getting-started/supported-countries)). "PayPal only" means no bank payouts, so you need a PayPal account that can receive money in your country.
- **Creem:** ⚠️ means Creem lists the country with "partner restrictions" ([list](https://docs.creem.io/merchant-of-record/supported-countries)).
- **Dodo Payments:** based on its [accepted countries list](https://docs.dodopayments.com/miscellaneous/accepted-countries-and-territories). Some countries marked ❌ are kept only for existing merchants, not new sign-ups.
- **Polar:** pays out through Stripe Connect Express to the [118 countries it lists](https://polar.sh/docs/merchant-of-record/supported-countries).

## What a $20 Sale Costs

Headline fee on a $20 card payment from a US customer, at each provider's standard rate. This leaves out payout, currency conversion and dispute fees, which differ by provider.

| Provider                                                     | Fee on $20 | Handles sales tax and VAT   |
| ------------------------------------------------------------ | ---------- | --------------------------- |
| [Stripe](#global-payment-gateways) (2.9% + 30¢)              | $0.88      | No (Stripe Tax costs extra) |
| [Creem](#merchant-of-record-platforms) (3.9% + 40¢)          | $1.18      | Yes                         |
| [Dodo Payments](#merchant-of-record-platforms) (4% + 40¢)    | $1.20      | Yes                         |
| [Paddle](#merchant-of-record-platforms) (5% + 50¢)           | $1.50      | Yes                         |
| [Lemon Squeezy](#merchant-of-record-platforms) (5% + 50¢)    | $1.50      | Yes                         |
| [Polar](#merchant-of-record-platforms) (5% + 50¢, free plan) | $1.50      | Yes                         |
| [Fungies](#merchant-of-record-platforms) (5% + 50¢)          | $1.50      | Yes                         |
| [Gumroad](#merchant-of-record-platforms) (10% + 50¢)         | $2.50      | Yes                         |

---

## Merchant of Record Platforms

They sell your product on your behalf and handle sales tax, VAT, fraud and chargebacks.

| Provider                                                                     | Fee                                          | Extra fees                                                                                                                  | You can sell from                                                                                                                                          | Payouts                                                     | Verified                                                                 |
| ---------------------------------------------------------------------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------ |
| [Paddle](https://www.paddle.com/pricing)                                     | 5% + 50¢                                     | Products under $10 need custom pricing                                                                                      | Anywhere except a [sanctions list](https://www.paddle.com/help/start/intro-to-paddle/which-countries-are-supported-by-paddle)                              | Not stated on pricing page                                  | Nov 2026                                                                 |
| [Lemon Squeezy](https://www.lemonsqueezy.com/pricing)                        | 5% + 50¢                                     | Small extra fees on some payments, e.g. outside the US                                                                      | Bank payouts in [79 countries](https://docs.lemonsqueezy.com/help/getting-started/supported-countries), PayPal in 200+                                     | Bank wire or PayPal, twice a month                          | Nov 2026 (site shows a "Lemon Squeezy + Stripe Managed Payments" update) |
| [Polar](https://polar.sh/resources/pricing)                                  | 5% + 50¢ free; from 3.4% + 30¢ on paid plans | +1.5% non-US cards; Stripe payout fees ($2/mo while active, 0.25% + 25¢ per payout); $15 per dispute                        | [118 countries](https://polar.sh/docs/merchant-of-record/supported-countries)                                                                              | Stripe Connect Express                                      | Nov 2026                                                                 |
| [Creem](https://www.creem.io/pricing)                                        | 3.9% + 40¢                                   | Payout fee: 7 USD/EUR or 1%, whichever is higher                                                                            | [87 countries](https://docs.creem.io/merchant-of-record/supported-countries)                                                                               | Bank transfer, USDC, Alipay (China); no PayPal; $50 minimum | Nov 2026                                                                 |
| [Dodo Payments](https://dodopayments.com/pricing)                            | 4% + 40¢; domestic India 4% + 15¢            | +1.5% international; +0.5% subscriptions; +3% PayPal and BNPL; $25 SWIFT payouts outside the US; $5 on payouts under $1,000 | [177 countries](https://docs.dodopayments.com/miscellaneous/accepted-countries-and-territories)                                                            | Bank, SWIFT wire                                            | Nov 2026                                                                 |
| [Stripe Managed Payments](https://docs.stripe.com/payments/managed-payments) | Not published in the docs                    | Digital products only; works with Checkout and Payment Links, not Elements                                                  | [37 locations](https://docs.stripe.com/payments/managed-payments/eligibility): US, Canada, EU/EEA, UK, Switzerland, Australia, Hong Kong, Japan, Singapore | Stripe                                                      | Nov 2026                                                                 |
| [Gumroad](https://gumroad.com/pricing)                                       | 10% + 50¢                                    | 30% on sales through its Discover marketplace                                                                               | Not listed on pricing page                                                                                                                                 | Bank deposit or PayPal, depending on country                | Nov 2026 (MoR since Jan 2025)                                            |
| [Fungies](https://fungies.io/pricing)                                        | 5% + 50¢                                     | None listed; negotiable at higher volume                                                                                    | Not listed on pricing page                                                                                                                                 | Daily by default; weekly, monthly or manual                 | Nov 2026                                                                 |
| [Freemius](https://freemius.com/pricing/)                                    | 3.8% + 50¢ plus gateway fees                 | +2.3% for WordPress products; lower % above $50K/mo                                                                         | Not listed on pricing page                                                                                                                                 | Wise, PayPal, Payoneer or wire; monthly, $100 minimum       | Nov 2026                                                                 |
| [FastSpring](https://fastspring.com/pricing/)                                | On request (revenue share, varies by volume) | Not published                                                                                                               | Not listed on pricing page                                                                                                                                 | Not listed on pricing page                                  | Nov 2026                                                                 |

**Handles tax, but not an MoR:** [Payhip](https://payhip.com/pricing) collects and pays EU/UK VAT and US/Canadian sales tax for you, but payments go through your own Stripe or PayPal account, so you still need one of those in your country. Fees: 5% on the free plan, 2% on $29/mo, 0% on $99/mo, plus Stripe or PayPal fees.

## Global Payment Gateways

You are the seller and handle sales tax yourself.

| Provider                                                          | Fee                                                 | Extra fees                                                                 | You can sell from                                                          | Verified |
| ----------------------------------------------------------------- | --------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------- |
| [Stripe](https://stripe.com/pricing)                              | 2.9% + 30¢ (US cards)                               | +1.5% international cards; +1% currency conversion; Billing 0.7% of volume | [51 countries](https://stripe.com/global); India and Indonesia invite only | Nov 2026 |
| [PayPal](https://www.paypal.com/us/business/paypal-business-fees) | PayPal Checkout 3.49% + 49¢; cards 2.99% + 49¢ (US) | +1.5% international; 3–4% currency conversion                              | Depends on your country's PayPal account type                              | Nov 2026 |
| [Mollie](https://www.mollie.com/pricing)                          | 1.8% + €0.25 (EEA consumer cards)                   | Non-EEA cards 3.25% + €0.25; iDEAL €0.32                                   | Not listed on pricing page (Europe-focused)                                | Nov 2026 |

## Local Payment Gateways

Best for customers paying in their own currency with local methods. Most need a local business or bank account.

### South Asia

| Provider                                                                       | Country    | Fee                                   | International cards               | Other costs                     | Verified |
| ------------------------------------------------------------------------------ | ---------- | ------------------------------------- | --------------------------------- | ------------------------------- | -------- |
| [Razorpay](https://razorpay.com/pricing/)                                      | India      | 2% (cards, netbanking, wallets) + GST | Up to 3% + GST                    | No setup or annual fee          | Nov 2026 |
| [Cashfree](https://www.cashfree.com/payment-gateway-charges/)                  | India      | 1.95% + taxes                         | 2.99% Visa/Mastercard; 2.95% Amex | No setup fee                    | Nov 2026 |
| [Safepay](https://safepay.helpscoutdocs.com/article/131-safepay-fee-breakdown) | Pakistan   | 2.9% + Rs30 (excl. tax)               | 3.2% + Rs30 (excl. tax)           | No yearly fee                   | Nov 2026 |
| [SSLCommerz](https://sslcommerz.com/pricing/)                                  | Bangladesh | 2.5% (cards, bKash, Nagad, Rocket)    | Same 2.5%; Amex 3.5%              | Basic plan ৳25,500              | Nov 2026 |
| [PayHere](https://www.payhere.lk/fees)                                         | Sri Lanka  | 3.30% (Lite plan)                     | Premium cards (Amex etc.) +0.5%   | No setup or monthly fee on Lite | Nov 2026 |
| [Khalti](https://khalti.com/payment-gateway/)                                  | Nepal      | On request                            | Not published                     | Not published                   | Nov 2026 |

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

| Provider                                              | Country        | Fee                                         | International cards | Other costs | Verified |
| ----------------------------------------------------- | -------------- | ------------------------------------------- | ------------------- | ----------- | -------- |
| [iyzico](https://www.iyzico.com/en/business/easy-pos) | Turkey         | Per merchant, shown in your merchant panel  | Not published       | –           | Nov 2026 |
| [Paymob](https://paymob.com)                          | Egypt and more | Varies by merchant; adjusts as volume grows | Not published       | –           | Nov 2026 |

### Latin America

| Provider                                                                         | Country                            | Fee                                                           | International cards | Other costs    | Verified |
| -------------------------------------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------- | ------------------- | -------------- | -------- |
| [Mercado Pago](https://www.mercadopago.com.br/ferramentas-para-vender/check-out) | Brazil, Argentina, Mexico and more | Brazil: credit cards 3.98–4.98% (by payout timing); Pix 0.99% | Not published       | No monthly fee | Nov 2026 |

## No Option in Your Country? Open a US Company

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

Found a provider that's missing, or a fee that changed? Pull requests are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first, or [open an issue](../../issues/new/choose) without writing any markdown.

## Footnotes

Fees and country support change often. Everything here comes from the providers' public pages and may be out of date, so confirm with the provider before you sign up. This is not financial, legal or tax advice. No listing here is paid or endorsed.
