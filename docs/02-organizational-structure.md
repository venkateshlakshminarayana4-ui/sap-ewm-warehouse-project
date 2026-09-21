# 02 - Organizational Structure

## ERP side (S/4HANA)
| Element | Example value | Purpose |
|---------|---------------|---------|
| Company code | 1000 | Legal entity |
| Plant | 1000 | Production and stock location |
| Storage location | 0001 | EWM-managed storage location |

## EWM side
| Element | Example value | Purpose |
|---------|---------------|---------|
| Warehouse number | WH01 | Top-level warehouse |
| Storage type | 0010 High rack, 0020 Fixed bin, 9010 GR area, 9020 GI area | Physical or logical zone |
| Storage section | Fast movers, slow movers | Grouping inside a storage type |
| Storage bin | 0010-A-01-01 | Smallest location for stock |
| Activity area | Picking area A | Grouping of bins for work assignment |
| Work center | Packing station 1 | Location for packing and deconsolidation |

## Mapping (ERP to EWM)
Plant and storage location are assigned to the warehouse number through the supply chain unit and the warehouse number assignment. TODO: add screenshots of the configuration.
