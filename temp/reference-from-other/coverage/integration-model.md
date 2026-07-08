# Integration Models - Iron

[Skip to main content](https://docs.iron.xyz/integration-models#content-area)

Iron supports three integration models: direct use (B2B), serving business customers (B2B2B), and serving individual consumers (B2B2C).

## At a Glance

| Model | Who uses Iron’s services | Example | Integration |
| --- | --- | --- | --- |
| **B2B** | Your company directly | Fintech using stablecoin rails for treasury | API or Dashboard |
| **B2B2B** | Your business customers | PSP offering stablecoin payouts to merchants | API or Dashboard + Iron App |
| **B2B2C** | Your individual users | Neobank offering EUR virtual accounts to retail customers | API or Dashboard + Iron App |

## B2B: Direct Use

Use Iron for your own operations such as treasury, payroll, and settlement.

**Examples:**

- Cross-border payroll, converting USDC to EUR and paying employees via SEPA
- Exchange settlement through stablecoin-to-fiat [Offramps](https://docs.iron.xyz/offramp)
- Corporate treasury across fiat and stablecoins via [Virtual Accounts](https://docs.iron.xyz/account)

Integrate through the [API](https://docs.iron.xyz/api-access) or the [Partner Dashboard](https://docs.iron.xyz/partner-dashboard).

> B2B is not exclusive. The same company can use Iron directly and act as a Partner under B2B2B or B2B2C, onboarding its own customers or subsidiaries. See [Roles & Entities](https://docs.iron.xyz/roles-entities).

## B2B2B: Serving Business Customers

Embed Iron into your product. You act as a **Partner**. Your business customers become **Customers** of Iron.

**Examples:**

- PSP offering stablecoin money transfers to merchant clients
- Banking-as-a-service platform enabling neobank clients to issue virtual EUR accounts
- Payroll provider letting companies pay contractors in stablecoins

Each business customer completes [KYB onboarding](https://docs.iron.xyz/kyb) and gains access to [Onramp](https://docs.iron.xyz/onramp), [Offramp](https://docs.iron.xyz/offramp), [Swap](https://docs.iron.xyz/swap), [Virtual Accounts](https://docs.iron.xyz/account), and [Stablecoin Issuance](https://docs.iron.xyz/issuance/create-your-stablecoin).

## B2B2C: Serving Individual Users

Embed Iron into your consumer-facing product. You act as a **Partner**. Your individual users become **Customers** of Iron.

**Examples:**

- Neobank offering named EUR and USD virtual bank accounts to retail customers
- Crypto wallet enabling users to onramp fiat to stablecoins via personal vIBAN
- Remittance app letting users send stablecoins and have recipients cash out to local bank accounts

Individual customers complete KYC through one of three frameworks:

| Framework | How it works |
| --- | --- |
| [KYC Reliance](https://docs.iron.xyz/reliance-kyc-token-sharing) | Iron relies on your existing KYC, shared via SumSub token sharing. Requires a regulatory agreement |
| [KYC Outsourcing](https://docs.iron.xyz/outsourcing) | You collect KYC data on Iron’s behalf and submit via API |
| [Direct Onboarding](https://docs.iron.xyz/hosted) | Iron handles KYC through a hosted verification flow |

> Regardless of the onboarding framework, every customer is a direct customer of Iron for compliance purposes. See [Onboarding Lifecycle](https://docs.iron.xyz/onboarding) for the full flow.

## Iron App: Whitelabel Frontend

For B2B2B and B2B2C setups, Iron offers **Iron App**, a whitelabel frontend that your end customers (the last B or C) use directly.

Iron App gives your customers account management, transaction history, onboarding, and access to Iron’s products. No custom UI needed. You manage configuration through the Partner Dashboard or API. Iron App handles the end-customer experience.

**When to use Iron App:**

- Go live without building a frontend
- End customers need direct access to onboarding, account management, and transaction history
- Keep the customer-facing experience up to date with new Iron features automatically

## How to Integrate

Two integration paths. Use both simultaneously.

[app.iron.xyz](https://app.iron.xyz/).

Most partners use the **API for programmatic workflows** (customer creation, Autoramp setup, webhook-driven monitoring) and the **Dashboard for operations** (reviewing customer status, managing API keys, inspecting transactions).

Was this page helpful?

[Previous](https://docs.iron.xyz/country)[Next](https://docs.iron.xyz/support)

⌘I