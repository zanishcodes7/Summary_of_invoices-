
# Summary of Invoices

A custom Odoo 19 module that allows users to generate a PDF summary report for selected customer invoices through a simple wizard interface.

## Features

- Select multiple customer invoices
- Generate a professional PDF report
- Displays invoice details in a clean tabular format
- Includes report generation date
- Easy-to-use wizard interface
- Built using Odoo 19 best practices

## Technologies Used

- Python
- Odoo 19
- XML
- QWeb Reports

## Module Structure

```
summary_of_invoices/
├── models/
│   └── invoice_summary_wizard.py
├── report/
│   ├── invoice_summary_report.xml
│   └── invoice_summary_templates.xml
├── views/
│   └── invoice_summary_wizard_views.xml
├── security/
│   └── ir.model.access.csv
├── __init__.py
├── __manifest__.py
```

## How It Works

1. Open the **Invoice Summary** wizard.
2. Select one or more customer invoices.
3. Click **Generate Report**.
4. A PDF report is generated containing the selected invoices and their details.

## Report Information

The report includes:

- Invoice Number
- Customer Name
- Invoice Date
- Due Date
- Total Amount
- Invoice Status
- Report Generation Date

## Dependencies

- account

## Installation

1. Copy the module into your custom addons directory.
2. Restart the Odoo server.
3. Update the Apps list.
4. Install **Summary of Invoices**.

## Learning Outcomes

This project helped me learn:

- Creating Transient Models (Wizards)
- Working with Many2many fields
- Generating PDF reports using QWeb
- Passing data from a wizard to a report
- Creating XML views
- Odoo module structure
- Report actions and templates

## Author

**Zanish Rohail**

BS Data Science Student | Python & Odoo Developer
