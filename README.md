# Personal & Business Unified Budget Framework
### Separate personal and business money without losing the ability to make integrated financial decisions.

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Tool](https://img.shields.io/badge/Type-Decision%20Support-orange.svg)

**A free browser and Excel toolkit that turns scattered transactions into a structured financial operating system—without installation, subscriptions, or accounting software.**

> **No signup. No installation. Free.**
>
> 🌐 Open in Browser → *HTML live demo link*  
> 📥 Download Excel → *Release or Gumroad link*

---

## Screenshots

<img width="1667" height="954" alt="image" src="https://github.com/user-attachments/assets/36fd77eb-f4f3-44ce-a676-89ffc4bcc7a0" />


**Browser Version**  
A lightweight interface for capturing transactions, reviewing weekly exceptions, and monitoring cash health from any device.

<img width="1536" height="1024" alt="ChatGPT Image Jul 10, 2026, 10_24_04 AM" src="https://github.com/user-attachments/assets/ce5e2a0a-3c94-4e75-bec8-d909e611f20a" />

**Excel Version**  
The complete operating workbook with categorization logic, budget controls, reconciliation workflows, and financial pulse indicators.

---

## What It Helps You Track

- Personal spending versus business operating costs without mixing the two.
- Actual business profitability after owner withdrawals.
- Minimum personal survival costs versus discretionary lifestyle spending.
- Weekly budget drift before overspending becomes a monthly surprise.
- Business runway and the ability to cover upcoming commitments.
- Savings progress and asset accumulation alongside operating performance.

---

## Why I Built This

Most small businesses and solo operators do not fail because they lack transaction records.

They fail because they cannot interpret those records correctly.

Personal expenses leak into business accounts. Business profits appear larger than reality because owner withdrawals are ignored. Lifestyle inflation hides inside dozens of small transactions. Decisions get made using balances instead of understanding what those balances actually represent.

The most common response is either doing nothing or adopting accounting systems that feel too heavy for daily use.

I built this framework after repeatedly seeing the same analytical failure:

> Money was being tracked.
>
> Decisions were not.

For example:

**Before**

A business owner sees \$12,000 in the bank and concludes:

> "The business is healthy."

No distinction exists between:

- future operating obligations,
- personal living requirements,
- business profitability,
- savings commitments.

Owner withdrawals happen randomly.

Personal expenses occasionally pass through business accounts.

The available cash number becomes misleading.

**After**

The same \$12,000 is separated into:

- \$4,500 committed business obligations,
- \$2,500 owner draw allocation,
- \$2,000 personal survival expenses,
- \$1,500 discretionary budget,
- \$1,500 savings target.

The question changes from:

> "How much money is available?"

to:

> "What decisions can safely be made?"

This workbook productizes that reasoning.

It is not an accounting replacement.

It is a reusable decision framework that makes financial trade-offs visible before mistakes compound.

---

## Common Financial Problems This Solves

| Problem | Without This Tool | With This Tool |
|---|---|---|
| Personal and business money become mixed | True profitability becomes impossible to estimate | Entity separation preserves both clarity and flexibility |
| Large bank balances create false confidence | Future obligations remain invisible | Cash is interpreted through commitments and runway |
| Owner withdrawals happen inconsistently | Lifestyle spending destabilizes operations | Draws become intentional and measurable |
| Weekly overspending goes unnoticed | Budget failures appear after the month ends | Threshold alerts identify drift early |
| Savings goals compete with daily expenses | Saving happens only when convenient | Savings become explicit allocations |
| Ambiguous transactions accumulate | Reconciliation becomes painful and delayed | Pending items are resolved during short weekly reviews |

---

## Who This Is For

Designed for:

- Freelancers managing both business income and personal expenses.
- Small business owners without dedicated finance staff.
- Consultants operating through simple banking setups.
- Entrepreneurs overwhelmed by fragmented transaction records.
- People seeking operational clarity rather than full accounting systems.

Not designed for:

- Multi-entity corporate consolidations.
- Enterprise ERP environments.
- Statutory accounting and tax filing workflows.
- Teams requiring advanced approval hierarchies.

No spreadsheet expertise needed.

Open the browser version and start tracking immediately, or download the Excel version for full control.

---

## About

I build lightweight trackers and decision-support tools for situations with too many moving parts to reliably hold in memory.

The question behind each tool is simple:

> What information needs to exist in one place to support the next decision confidently?

This framework applies that philosophy to personal and business finances. Rather than replacing accounting systems, it helps reveal the information required to operate responsibly between major decisions.

---

## Technical Details

<details>
<summary>For technical reviewers, Excel practitioners, and collaborators</summary>

---

### Workbook Architecture

| Layer | Function | Purpose |
|---|---|---|
| Transaction Capture | Raw entries and imports | Store all activity |
| Classification | Entity and category assignment | Preserve analytical integrity |
| Validation | Pending review and controls | Reduce classification errors |
| Calculations | Budgets and financial metrics | Generate decision indicators |
| Outputs | Pulse dashboards and summaries | Support weekly decisions |

Data flow:

```text
Transactions
    ↓
Entity Classification
    ↓
Category Assignment
    ↓
Validation Checks
    ↓
Budget Calculations
    ↓
Pulse Indicators
    ↓
Decision Outputs
````

Validation dependencies:

```text
Pending Transactions
        ↓
Weekly Review
        ↓
Approved Classification
        ↓
Financial Reporting
```

---

### Three Traps That Catch Even Experienced Operators

#### Trap 1: Bank Balance Equals Available Cash

A decision was made.

Expansion spending was approved.

The decision relied on the bank balance alone.

| Wrong Approach             | Correct Approach             |
| -------------------------- | ---------------------------- |
| Use total balance          | Deduct obligations first     |
| Ignore future commitments  | Calculate operational runway |
| Treat cash as unrestricted | Allocate by purpose          |

The flaw:

Cash and available cash are not identical.

Corrected outcome:

Expansion decisions occur only after committed expenses are covered.

<details>
<summary>Formula Logic</summary>

```excel
Available Cash
=
Bank Balance
- Committed Expenses
- Planned Draws
```

</details>

---

#### Trap 2: Personal Spending Hidden Inside Business Costs

A decision was made.

Profitability was evaluated.

Personal expenses embedded in business accounts distorted margins.

| Wrong Approach               | Correct Approach    |
| ---------------------------- | ------------------- |
| Mixed transactions           | Entity separation   |
| Estimated withdrawals        | Explicit owner draw |
| Inflated expenses or profits | Traceable transfers |

The flaw:

Mixed entities destroy interpretability.

Corrected outcome:

Business performance and personal consumption become independently measurable.

<details>
<summary>Formula Logic</summary>

```excel
Entity
=
Business
OR
Personal
OR
Owner Draw
```

</details>

---

#### Trap 3: Monthly Reviews Detect Problems Too Late

A decision was made.

Lifestyle spending continued unchanged.

Budget overruns were discovered after the fact.

| Wrong Approach             | Correct Approach             |
| -------------------------- | ---------------------------- |
| Monthly discovery          | Weekly pulse reviews         |
| No warning thresholds      | Early indicators             |
| Large corrections required | Small adjustments sufficient |

The flaw:

Feedback loops arrived too slowly.

Corrected outcome:

Overspending becomes manageable before compounding.

<details>
<summary>Formula Logic</summary>

```excel
Discretionary Usage %
=
Actual Spend
/
Budget

Alert Trigger
=
Usage % > 85%
```

</details>

---

### Example Scenario

A consultant finishes the week with:

| Input                    |  Amount |
| ------------------------ | ------: |
| Business Account Balance | $12,000 |
| Upcoming SaaS Costs      |    $800 |
| Contractor Payments      |  $2,200 |
| Planned Owner Draw       |  $2,500 |
| Personal Survival Costs  |  $2,000 |
| Savings Target           |  $1,500 |

Intermediate interpretation:

```text
Business Obligations
=
800 + 2,200
=
3,000

Remaining After Operations
=
12,000 − 3,000
=
9,000

Remaining After Draw
=
9,000 − 2,500
=
6,500

Remaining After Personal Allocation
=
6,500 − 2,000 − 1,500
=
3,000
```

Recommendation:

The business can support planned obligations and owner compensation while preserving savings objectives.

Decision implication:

Additional discretionary spending should remain below the remaining buffer until new revenue arrives.

The balance itself did not answer this question.

Structured allocation did.

---

### Formula Reference

<details>
<summary>Entity Classification</summary>

Purpose:

Separate analytical contexts.

```excel
Business
Personal
Owner Draw
```

</details>

<details>
<summary>Budget Monitoring</summary>

Purpose:

Detect overspending early.

```excel
Actual / Budget
```

Threshold:

```excel
>85%
```

</details>

<details>
<summary>Cash Allocation</summary>

Purpose:

Estimate decision-safe liquidity.

```excel
Balance
− Obligations
− Planned Transfers
```

</details>

---

### Validation Rules

| Field                   | Rule                     | Error Behavior        |
| ----------------------- | ------------------------ | --------------------- |
| Entity                  | Must be selected         | Flag as Pending       |
| Category                | Must match entity        | Reject classification |
| Amount                  | Numeric and non-zero     | Input warning         |
| Transaction Date        | Required                 | Excluded from reports |
| Owner Draw              | Must bridge entities     | Validation alert      |
| Budget Threshold        | Warning above 85%        | Highlight overspend   |
| Reconciliation Variance | Minor variance tolerated | Review required       |

</details>

---

## Other Tools in This Series

* **Inventory Forecasting & Reorder Planning** — Determine replenishment timing before stockouts occur.
* **CRM Decision Support Tracker** — Convert lead activity into structured pipeline decisions.
* **Vendor Spend Planning Toolkit** — Monitor commitments against approved budgets.
* **Project Financial Pulse Tracker** — Surface delivery risk through lightweight operating reviews.

GitHub Profile: *Profile link*
Gumroad Store: *Store link*

---

## License

This project is licensed under the **Apache License 2.0**.

You are free to use, modify, and distribute this work under the terms of the Apache License 2.0. See the `LICENSE` file for details.


