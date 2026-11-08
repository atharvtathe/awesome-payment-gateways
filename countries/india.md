# Getting Paid From India

[← Back to Awesome Payment Gateways](../README.md)

**Quick answer:** to sell to customers worldwide, start with a merchant of record (MoR). Paddle, Lemon Squeezy, Polar, Creem and Dodo Payments all pay out to India. To sell to customers in India (UPI, netbanking, Indian cards), use a local gateway such as Razorpay, Cashfree or PayU.

_Last checked: November 2026. Confirm on each provider's page before you sign up._

## Stripe

[Stripe's country page](https://stripe.com/global) lists India as **Preview**, and sign-ups go to sales. Lemon Squeezy's docs note that [from May 2024, Stripe only accepts new accounts from India on an invite-only basis](https://docs.lemonsqueezy.com/help/getting-started/supported-countries).

If you do get access, Stripe India charges 2% on cards issued in India, and 3% on Visa and Mastercard cards issued outside India, plus 2% when currency conversion is needed ([pricing](https://stripe.com/in/pricing)).

## Selling to customers worldwide (MoRs)

| Provider                                                            | Pays out to India   | Fee                                 | Notes                                                          |
| ------------------------------------------------------------------- | ------------------- | ----------------------------------- | -------------------------------------------------------------- |
| [Paddle](https://www.paddle.com/pricing)                            | Yes                 | 5% + 50¢                            | Business check skipped for individuals and sole traders        |
| [Lemon Squeezy](https://www.lemonsqueezy.com/pricing)               | Yes: Bank or PayPal | 5% + 50¢                            | $50 minimum payout                                             |
| [Polar](https://polar.sh/resources/pricing)                         | Yes                 | 5% + 50¢ (free plan)                | +1.5% on non-US cards; payouts through Stripe Connect Express  |
| [Creem](https://www.creem.io/pricing)                               | Yes                 | 3.9% + 40¢                          | Payout fee: 7 USD or 1%, whichever is higher                   |
| [Dodo Payments](https://dodopayments.com/pricing)                   | Yes                 | 4% + 40¢; Indian customers 4% + 15¢ | Accepts Indian cards and UPI in INR; "Individual" sign-up path |
| [Fungies](https://help.fungies.io/getting-paid/global-availability) | Yes                 | 5% + 50¢                            | Daily payouts by default                                       |
| [Gumroad](https://gumroad.com/pricing)                              | Bank or PayPal      | 10% + 50¢                           | Best for simple digital products, not SaaS                     |

## Selling to customers in India (local gateways)

| Provider                                                      | Indian payments                       | International cards               | Other costs             |
| ------------------------------------------------------------- | ------------------------------------- | --------------------------------- | ----------------------- |
| [Razorpay](https://razorpay.com/pricing/)                     | 2% (cards, netbanking, wallets) + GST | Up to 3% + GST                    | No setup or annual fee  |
| [Cashfree](https://www.cashfree.com/payment-gateway-charges/) | 1.95% + taxes                         | 2.99% Visa/Mastercard; 2.95% Amex | No setup fee            |
| [PayU](https://payu.in/pricing/)                              | 2% + GST                              | 3% + GST                          | No setup or annual fee  |
| [Instamojo](https://www.instamojo.com/pricing/)               | 2% + ₹3 + GST (gateway)               | On request; charged in INR        | Store plans charge more |

GST (18%) is charged on the gateway's fee, not on your sale amount.

## Things to know

- **An MoR handles foreign sales tax for you.** With a gateway, VAT, GST and US sales tax on foreign customers are your responsibility.
- **Instamojo** charges international cards in INR and enables international payments only on request, after KYC ([pricing](https://www.instamojo.com/pricing/)).
- **Dodo Payments** has separate domestic pricing for Indian customers, 4% + 15¢, so you can serve Indian and foreign buyers from one checkout ([pricing](https://dodopayments.com/pricing)).

Something wrong or missing for India? [Open an issue](https://github.com/atharvtathe/awesome-payment-gateways/issues/new/choose).
