# Privacy Policy — KhewaLabs

> **Before publishing this anywhere**: this is a draft written to accurately reflect your actual data architecture (WhatsApp Business Platform, Supabase, Razorpay, Firebase) — it is not legal advice. Have it reviewed by a lawyer familiar with India's DPDP Act 2023 before it goes live, and fill in every `[ ]` placeholder with real details first.

**Effective date**: `[DATE]`
**Last updated**: `[DATE]`

## 1. Introduction

KhewaLabs ("**we**", "**us**", "**our**") operates a platform that enables businesses to receive and manage orders from their customers via WhatsApp. This Privacy Policy explains how we collect, use, disclose, and safeguard personal data when you interact with our platform — whether as a **business owner** using our dashboard, a **staff member** of a business on our platform, or an **end customer** placing an order through WhatsApp.

Under India's Digital Personal Data Protection Act, 2023 ("**DPDP Act**"), KhewaLabs acts as a **Data Fiduciary** for the personal data described below, and individuals whose data we process are **Data Principals**.

## 2. Data We Collect

**From end customers (via WhatsApp):**
- WhatsApp phone number
- Name, as provided in your WhatsApp profile or during ordering
- Order details — items selected, order history, order status
- Messages exchanged with a business through our platform

**From business owners and staff:**
- Account login information (email, authentication credentials)
- Business details — business name, WhatsApp Business Account (WABA) information, phone number
- Staff access credentials for inventory/order management

**Automatically collected:**
- Device push notification tokens (for order alerts on the owner dashboard)
- Basic technical/log data (IP address, access timestamps) for security and troubleshooting

We do not collect payment card details directly — payments are processed by Razorpay, a third-party payment processor (see Section 4).

## 3. How We Use Data

We use personal data to:
- Facilitate orders between customers and the specific business they're ordering from
- Send order confirmations and catalog/menu information via WhatsApp
- Enable business owners and staff to manage inventory, view and fulfill orders, and track payment status
- Send push notifications to business owners about incoming orders
- Maintain, secure, and improve the platform
- Comply with legal obligations

## 4. How We Share Data

We do not sell personal data. We share data only as necessary to operate the platform:

- **The specific business you're ordering from** — a customer's order and contact data is visible only to that business, enforced at the database level (row-level security ensures one business can never access another business's customer or order data).
- **Meta / WhatsApp Business Platform** — messages sent through WhatsApp are processed by Meta's infrastructure under [Meta's own data policies](https://www.facebook.com/privacy/policy/).
- **Razorpay** — for payment processing, subject to [Razorpay's privacy policy](https://razorpay.com/privacy/).
- **Firebase Cloud Messaging (Google)** — for delivering push notifications to business owners' devices.
- **Legal requirements** — if required by applicable law, regulation, or valid legal process.

Some of these third parties may process data outside India. Where this occurs, we take reasonable steps to ensure data is handled consistently with this policy and applicable law.

## 5. Data Storage & Security

Personal data is stored using Supabase (PostgreSQL), with row-level security policies enforcing that each business can only access its own data. Data is encrypted in transit. Access to underlying infrastructure is restricted to authorized KhewaLabs personnel.

`[State your actual hosting region here, e.g., "Our database is hosted in [region]." — confirm your Supabase project's region before publishing.]`

## 6. Data Retention

We retain personal data only as long as necessary for the purposes described in this policy, or as required by applicable law.

`[Placeholder — define actual retention periods, e.g., "Order data is retained for [X years] for tax and business record purposes. Account data is retained until the account is deleted, plus [X days]." This is a business decision that needs your input before publishing.]`

## 7. Your Rights Under the DPDP Act, 2023

As a Data Principal, you have the right to:
- **Access** — request a summary of the personal data we hold about you and how it is processed
- **Correction and erasure** — request correction of inaccurate data, or erasure of your personal data (subject to legal retention requirements)
- **Grievance redressal** — raise a complaint about how your data is handled, and receive a response within a reasonable timeframe
- **Nominate** — nominate another individual to exercise your rights in the event of death or incapacity
- **Withdraw consent** — where processing is based on consent, withdraw that consent at any time

To exercise any of these rights, contact us using the details in Section 9.

## 8. Children's Data

Our platform is not directed at children, and we do not knowingly collect personal data from individuals under 18. If you believe a child's data has been provided to us, contact us so we can remove it.

## 9. Grievance Officer & Contact

In accordance with the DPDP Act, 2023, our designated Grievance Officer can be reached at:

`[Name of Grievance Officer]`
`[Email address]`
`[Business address]`

For general privacy questions, contact: `[privacy contact email]`

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be reflected by updating the "Last updated" date above.
