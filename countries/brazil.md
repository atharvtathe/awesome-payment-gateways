# Getting Paid From Brazil

[← Back to Awesome Payment Gateways](../README.md)

**Quick answer:** Stripe is available in Brazil. For customers worldwide without handling foreign sales tax, use a merchant of record (MoR): Paddle, Creem, Dodo Payments or Fungies pay out to Brazil. For Brazilian customers, Mercado Pago supports Pix, which is much cheaper than cards.

_Last checked: November 2026. Confirm on each provider's page before you sign up._

## Stripe

Brazil is on [Stripe's country list](https://stripe.com/global), so you can sign up directly.

## Selling to customers worldwide (MoRs)

| Provider                                                                                | Pays out to Brazil | Fee        | Notes                                                   |
| --------------------------------------------------------------------------------------- | ------------------ | ---------- | ------------------------------------------------------- |
| [Paddle](https://www.paddle.com/pricing)                                                | Yes                | 5% + 50¢   | Business check skipped for individuals and sole traders |
| [Creem](https://www.creem.io/pricing)                                                   | Yes                | 3.9% + 40¢ | Payout fee: 7 USD or 1%, whichever is higher            |
| [Dodo Payments](https://dodopayments.com/pricing)                                       | Yes                | 4% + 40¢   | "Individual" sign-up path                               |
| [Fungies](https://help.fungies.io/getting-paid/global-availability)                     | Yes                | 5% + 50¢   | Daily payouts by default                                |
| [Lemon Squeezy](https://docs.lemonsqueezy.com/help/getting-started/supported-countries) | PayPal only        | 5% + 50¢   | No bank payouts to Brazil                               |
| [Polar](https://polar.sh/docs/merchant-of-record/supported-countries)                   | No                 | –          | Not on its payout list                                  |

## Selling to customers in Brazil (local gateway)

| Provider                                                                         | Credit cards                          | Pix   | Other costs    |
| -------------------------------------------------------------------------------- | ------------------------------------- | ----- | -------------- |
| [Mercado Pago](https://www.mercadopago.com.br/ferramentas-para-vender/check-out) | 3.98–4.98% (depends on payout timing) | 0.99% | No monthly fee |

## Things to know

- **Polar doesn't pay out to Brazil,** and Lemon Squeezy pays out only through PayPal. Check this before you build on either.
- **Pix costs 0.99%** on Mercado Pago, against 3.98–4.98% for credit cards, so offering Pix to Brazilian customers can save a lot.

Something wrong or missing for Brazil? [Open an issue](https://github.com/atharvtathe/awesome-payment-gateways/issues/new/choose).
