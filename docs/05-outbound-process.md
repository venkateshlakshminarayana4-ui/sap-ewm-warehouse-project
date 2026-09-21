# 05 - Outbound Process

## Process steps
1. **Sales order** is created in SD.
2. **Outbound delivery** is created and distributed to EWM as an outbound delivery request, then becomes the outbound delivery order.
3. **Wave** (optional) groups delivery items for release.
4. **Picking** warehouse tasks and warehouse orders are created (stock removal strategy, for example FIFO). The picker confirms them.
5. **Packing** at the packing work center. Handling units are created and closed.
6. **Loading and goods issue**. The goods issue is posted in EWM and updates SD and MM.

## Key transactions (verify in your system, they may differ by release)
| Step | Transaction or app |
|------|--------------------|
| Outbound delivery order | /SCWM/PRDO |
| Wave management | /SCWM/WAVE |
| Packing | /SCWM/PACK |
| Warehouse management monitor | /SCWM/MON |

## Control points
- Stock removal strategy and stock removal rules.
- Picking method: order-based or wave-based.
- Handling of shortages: allocation and partial deliveries.

## Evidence
TODO: add screenshots for each step in `screenshots/outbound/`.
