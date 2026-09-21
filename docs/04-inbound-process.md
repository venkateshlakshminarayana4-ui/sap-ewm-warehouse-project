# 04 - Inbound Process

## Process steps
1. **Purchase order** is created in SAP MM.
2. **Inbound delivery** is created (from the ASN or manually) and distributed to EWM as an inbound delivery notification, then becomes the EWM inbound delivery.
3. **Goods arrival** at the door. The truck is checked in and unloaded.
4. **Goods receipt** is posted in EWM. Stock becomes available in the GR area and the goods movement is sent to S/4HANA.
5. **Putaway** warehouse tasks are created based on the storage type search sequence and the putaway control indicator. The operator confirms them, by RF or desktop.
6. **Stock** is now visible in the destination storage bin.

## Key transactions (verify in your system, they may differ by release)
| Step | Transaction or app |
|------|--------------------|
| Inbound delivery maintenance | /SCWM/PRDI |
| Warehouse management monitor | /SCWM/MON |
| Warehouse order and task processing | /SCWM/TODO and /SCWM/RFUI |

## Control points
- Putaway strategy: which storage type receives the product first, and how the bin is chosen.
- Quantity differences: handled through the delivery, with a difference-handling process.
- Documents: warehouse task, warehouse order, handling unit.

## Evidence
TODO: add screenshots for each step in `screenshots/inbound/`.
