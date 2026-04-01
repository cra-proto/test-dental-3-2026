# Default project dental

*description of the project*

**Timeframe** 2026-03-18 - 2026-06-24

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-dental-3-2026](https://cra-test-arc.canada.ca/test-dental-3-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-04-01

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(CRA Newsroom)
    node4(Get ready: the CRA is in its summertime benefit period!)
    node5(Tax tips - 2024)
    node6(Reminder - Apply by June 30 for period two of the interim Canada Dental Benefit!)
    node7(Taxes)
    node8(Tax credits and benefits for individuals)
    node9(Canada Dental Benefit - Closed)
    node10(If you disagree with the decision)
    node11(Contact us)
    node12(Return a payment)
    node13(Validating your application)
    node14(Who was eligible)
    node1 --x node2
    node2 --> node3
    node3 --x node4
    node3 --x node5
    node5 --> node6
    node1 --> node7
    node7 --> node8
    node8 --> node9
    node9 --> node10
    node9 --> node11
    node9 --> node12
    node9 --> node13
    node9 --> node14
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/news/newsroom.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2023/get-ready-cra-summertime-benefit-period.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2024.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2024/reminder-apply-by-june-30-for-period-two-of-the-interim-canada-dental-benefi.html" _blank
    click node7 "https://www.canada.ca/en/services/taxes.html" _blank
    click node8 "https://www.canada.ca/en/services/taxes/child-and-family-benefits.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/application-denied.html" _blank
    click node11 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/contact.html" _blank
    click node12 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/return-payment.html" _blank
    click node13 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/validation.html" _blank
    click node14 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/dental-benefit/who-apply.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node6,node9,node10,node11,node12,node13,node14 inscope
```
