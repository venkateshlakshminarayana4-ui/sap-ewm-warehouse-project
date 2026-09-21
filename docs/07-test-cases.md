# 07 - Test Cases

| ID | Scenario | Steps | Expected result | Actual result | Status |
|----|----------|-------|-----------------|---------------|--------|
| TC-01 | Standard inbound | PO, inbound delivery, GR, putaway | Stock in a high rack bin | TODO | Open |
| TC-02 | Inbound with quantity difference | Receive less than the delivery quantity | Difference recorded and delivery updated | TODO | Open |
| TC-03 | Standard outbound | Sales order, delivery, pick, pack, GI | GI posted and stock reduced | TODO | Open |
| TC-04 | Removal by FIFO | Two receipts, then one issue | Oldest stock is picked first | TODO | Open |
| TC-05 | Stock transfer | Move stock between bins | Stock in the new bin | TODO | Open |
| TC-06 | Physical inventory | Count and post the difference | Stock matches the count | TODO | Open |
