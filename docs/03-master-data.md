# 03 - Master Data

| Object | Key fields | Notes |
|--------|-----------|-------|
| Product | Product number, base unit, warehouse data view | Warehouse-specific data such as storage type search sequence and putaway control indicator |
| Business partner | Supplier, customer, carrier | Created as business partners in S/4HANA |
| Storage bin | Bin, storage type, section, bin type, max weight | Created manually or by mass upload |
| Packaging specification | Packaging materials, levels | Used for packing and handling units |
| Resources and users | RF users, resource types | Needed for RF-guided tasks |

## Sample products
| Product | Description | Storage type search sequence |
|---------|-------------|-------------------------------|
| PANEL-100 | Control panel enclosure | High rack |
| PLC-200 | PLC module | Fixed bin |
| CABLE-300 | Cable drum | High rack |

TODO: add screenshots of the product master warehouse view.
