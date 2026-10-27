# FlousFlow Community Accounting — Odoo 20

This repository is the FlousFlow foundation branch for Odoo 20 Community
Accounting. It contains the complete standard Odoo Community `account` addon,
with the product display name branded as **FlousFlow Community Accounting**.

## Important compatibility rule

The technical addon name remains `account`. Odoo's native modules, XML IDs,
migrations, and integrations depend on that technical name; changing the
directory or technical key would make the accounting stack uninstallable and
break standard dependencies. Only the product-facing name and ownership
metadata are branded here.

## Verification

- Odoo version: 20.0
- Branch: `20.0`
- Clean Community database: `ff_accounting_community20_tmp`
- Installed module: `account` / `20.0.1.5`

The next FlousFlow changes should extend this foundation with inherited models,
views, reports, and tests while keeping the upstream technical contract intact.
