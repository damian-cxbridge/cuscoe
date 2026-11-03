# Pricing model

Services that contain AI cannot be sold safely on the fixed-price, fixed-outcome basis that has traditionally worked for software projects. CUSCOE uses a three-layer structure instead, documented in the [Portfolio](portfolio.md) so that sales, Customer Success and finance all describe it the same way.

## Why fixed price fails

Fixed price works for traditional software because the cost of delivery is predictable and support costs after go-live are stable. That assumption fails for AI in three ways.

- **There is no natural end point.** An AI service needs permanent monitoring and tuning, so there is no point at which the work is finished.
- **Infrastructure costs move.** The provider usually resells cloud hosting and inference from vendors who can raise prices during a contract.
- **End users drive consumption.** Token use depends on how long and how complex users' interactions are, which neither the provider nor the vendor controls.

## The three layers

| Layer | What it covers | How it is sold |
|---|---|---|
| 1. MVP | The initial build. | Fixed price, but the MVP must be deterministic by design. AI can be used to decide the next best action, but that action must then hand off to a directed flow or to a human. |
| 2. Operational outcomes | Ongoing monitoring, evaluation, tuning and retraining, and further AI components with agreed outcomes once the MVP is live. | A recurring service agreement, normally a monthly retainer. |
| 3. Consumption | Cloud hosting and inference. | Billed on usage at cost plus a defined margin. |

Layer 2 is where most of the skilled work sits after go-live, and it is what pays for the [Centres of Excellence](centres-of-excellence.md) to keep the service healthy. Layer 3 passes through the cost risk that the provider cannot control.

## Who needs to understand it

Sales must be able to explain the three layers to a customer and build proposals on them. Customer Success must understand them well enough to manage margin on the account. Finance must forecast and recognise revenue on the same basis. See [Sales](sales.md) and [Finance](finance.md).

## Evidence status

Evaluated against an illustrative scenario. Not yet tested in a live organisation.
