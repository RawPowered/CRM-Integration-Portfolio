# RawOps Suite: crm delivery across the customer journey

[Portfolio overview](../README.md) · [RawOps Suite](https://github.com/RawPowered/RawOps-Suite) · [Evidence scope](EVIDENCE.md)

![RawOps case: CRM delivery across the customer journey](../assets/rawops/section.svg)

RawOps Suite shows the custom business application behind the sales journey: prepare an agent, find a suitable shop, review outreach, fulfill a sample and maintain the account relationship.

**Status:** This is a custom PHP/MySQL CRM and operations platform. Zoho administration and GoHighLevel adapter work are covered by the separate cases below. RawOps preserves historical usage evidence and source; current deployment remains unvalidated.

## 1. Connect prospecting to a useful customer record

The Places adapter supports shop-category and geographic discovery with cached details. Agent pages provide leads, account contacts, notes, calls, tags and tasks. The historical quality panel makes missing fields and follow-up coverage visible, giving the team a concrete maintenance task.

[Places adapter](https://github.com/RawPowered/RawOps-Suite/blob/main/api/google-places-proxy.php) · [Lead workspace](https://github.com/RawPowered/RawOps-Suite/blob/main/onboarding/sales-agent/leads.php) · [CRM quality capture](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/evidence/GALLERY.md#crm-data-quality--20-october-2025)

**Evidence boundary:** The capture contains 143 detailed and 241 incomplete leads in its own dated view. These counts do not establish qualification, revenue or a campaign conversion rate.

## 2. Preserve the handoff from outreach to fulfillment

Sample outreach enrollment can link to a lead while the physical sample request remains separate. The engineering notes document the correction that prevented email kickoff from creating placeholder fulfillment jobs. Request handling, fulfillment and scheduled follow-up each have their own responsibility.

[Handoff design](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/ENGINEERING-CASE-NOTES.md#1-keep-sample-outreach-separate-from-fulfillment-work) · [Sample suite](https://github.com/RawPowered/RawOps-Suite/blob/main/api/sample-suite.php) · [Fulfillment workspace](https://github.com/RawPowered/RawOps-Suite/blob/main/operations/sample-fulfillment.php) · [Scheduled follow-up](https://github.com/RawPowered/RawOps-Suite/blob/main/scheduled/sample-email-automation.php) · [Store accounts](https://github.com/RawPowered/RawOps-Suite/blob/main/onboarding/sales-agent/accounts.php)

**Evidence boundary:** Account creation is a separate workflow. An outreach enrollment alone does not prove a sample shipment, a new customer or a successful provider delivery.

## 3. Equip agents with the product context they need

Catalog-backed learning, quizzes and practice prepare agents for conversations. The email assistant assembles product, lead, sample and promotion context. Shareable cards carry agent context into signup and sample entry points. Together these features connect sales enablement with CRM delivery.

[Product, LMS and marketing design](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/PRODUCT-LEARNING-DESIGN.md) · [Assisted drafts](https://github.com/RawPowered/RawOps-Suite/blob/main/api/ai-email-composer.php) · [Agent card implementation](https://github.com/RawPowered/RawOps-Suite/blob/main/agent/card.php) · [Historical agent card](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/evidence/GALLERY.md#agent-digital-business-card--24-october-2025)

**Evidence boundary:** The card capture and composer capture establish interface states. The handlers establish implementation. Historical delivery, learning gains and attributable sales require separate records.

## Discuss the work

Ask me to trace a shop from discovery through sample follow-up, or explain how an agent learns and communicates a changed product price.

The [systems diagram](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/SYSTEMS-ORCHESTRATION.md) provides the wider context. The [feature walkthrough](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/FEATURE-WALKTHROUGH.md) and [capability catalog](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/CAPABILITY-CATALOG.md) cover the rest of the platform.

## Evidence and maintenance

The source project preserves partial history of a previously functional application. Its published gallery contains 11 genuine historical captures with opaque redactions. [Publication checks](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/PUBLICATION-REVIEW.md) cover syntax and secret scanning; business workflows were not executed by those checks. Review [security and privacy](https://github.com/RawPowered/RawOps-Suite/blob/main/docs/SECURITY-AND-PRIVACY.md) before considering restoration.

This case was added October 26, 2026. Project source and evidence remain authoritative in RawOps Suite. No live CRM records were changed and no flows were run for this portfolio update.
