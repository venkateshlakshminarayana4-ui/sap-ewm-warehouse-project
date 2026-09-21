# SAP EWM Warehouse Project

End-to-end documentation of a warehouse process design in **SAP S/4HANA Extended Warehouse Management (EWM)**: inbound, putaway, picking, outbound, configuration and test cases.

> Learning and portfolio project. It is based on my SAP training, my C_S4EWM exam preparation and my supply chain and logistics experience. It does not contain any confidential employer data.

## Why this project
I am moving from supply chain and logistics operations into SAP consulting. This repository shows how I structure a business scenario, translate it into system configuration, and test the result.

## Scope
| Area | Covered |
|------|---------|
| Inbound | Inbound delivery, goods receipt, putaway |
| Internal | Stock transfer, physical inventory |
| Outbound | Outbound delivery order, picking, packing, goods issue |
| Integration | SAP MM (purchase order), SD (sales order and delivery) |

## Contents
1. [Business scenario](docs/01-business-scenario.md)
2. [Organizational structure](docs/02-organizational-structure.md)
3. [Master data](docs/03-master-data.md)
4. [Inbound process](docs/04-inbound-process.md)
5. [Outbound process](docs/05-outbound-process.md)
6. [Configuration steps](docs/06-config-steps.md)
7. [Test cases](docs/07-test-cases.md)
8. [Lessons learned](lessons-learned.md)

## Tools
SAP S/4HANA EWM (embedded or decentralized), SAP Fiori and SAP GUI, draw.io for process diagrams.

## Author
Venkatesh Lakshminarayana, supply chain and logistics professional based in Berlin, with an SAP MM certification. Preparing for C_S4EWM.

## Status
Work in progress. Sections marked TODO get filled in as I complete each part.
