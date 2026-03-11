---
type: odoo_invoice
status: done
customer_name: nausea
invoice_date: '2026-03-05'
lines:
- product: abc
  quantity: 1
  price_unit: 100.0
approved_at: '2026-03-05'
customer_id: 7
odoo_invoice_id: 1
odoo_invoice_ref: INV/2026/00001
completed_at: '2026-03-05T22:33:44Z'
---
# Invoice Review

**Customer**: nausea
**Date**: 2026-03-05

## Line Items

- abc x 1 @ $100.00

**Estimated Total**: $100.00

---
## How to use:
## 1. Copy this file to vault/Approved/
## 2. Rename it to ODOO_INVOICE_<date>_<name>.md
## 3. Replace all CHANGE_ME with your values
## 4. Run: uv run python -m backend.orchestrator
## 5. Customer is auto-created in Odoo if not exists
## 6. File moves to vault/Done/ when processed
