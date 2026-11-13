# GST-2B vs Purchase Register Reconciliation Tool

**An Excel-based GST reconciliation and analysis tool**

**Project Contributor:** Ranjana Nagarajan  
**Project Group:** Advance-Autobots

## 1. Project Overview

The GST-2B vs Purchase Register Reconciliation Tool is an Excel-based solution designed to help businesses and accounting professionals compare their Purchase Register with GSTR-2B data.

The tool identifies invoice-level differences, missing invoices, duplicate entries and Input Tax Credit (ITC) discrepancies through automated formulas, dynamic reports and an interactive dashboard.

## 2. Key Features

- Automated invoice-level reconciliation.
- GSTIN and invoice number-based matching.
- Identification of matched and mismatched invoices.
- Detection of invoices missing in GSTR-2B.
- Detection of invoices missing in the Purchase Register.
- Duplicate invoice identification.
- Vendor-wise analysis.
- Tax-head-wise analysis (IGST, CGST, SGST and Cess).
- Interactive dashboard with KPIs and charts.
- Dynamic reports that update when data is entered.

## 3. Technology Used

- Microsoft Excel for Microsoft 365
- Advanced Excel formulas
- Dynamic Array Functions
- LET, LAMBDA, MAP, FILTER, UNIQUE, HSTACK, VSTACK and XLOOKUP

## 4. Workbook Structure

| Worksheet | Purpose |
|---|---|
| SETUP & USER GUIDE | Instructions for users |
| DASHBOARD | Summary and visual analysis |
| PURCHASE DATA | Purchase Register input |
| GSTR-2B DATA | GSTR-2B input |
| REPORTS | Detailed reconciliation reports |
| INVOICE DETAILS | Invoice-level information |
| Supporting sheets | Automated calculations and reconciliation logic |

## 5. How to Use

1. Download and open the Excel template.
2. Save a working copy in `.xlsx` format.
3. Enter or import Purchase Register data into the PURCHASE DATA sheet.
4. Enter or import GSTR-2B data into the GSTR-2B DATA sheet.
5. Enter data only in columns A:I. Columns J:L contain automatic formulas.
6. Open the DASHBOARD to review reconciliation results.
7. Use the REPORTS sheet to investigate differences and exceptions.

## 6. Matching Methodology

The workbook performs invoice-level matching using a combination of GSTIN and invoice number.

It identifies:
- Matched invoices
- Taxable value differences
- ITC differences
- Missing invoices
- Duplicate invoices

**Note:** This tool performs invoice-level reconciliation and does not perform line-item or tax-rate-wise matching.

## 7. System Requirements

- Microsoft Excel for Microsoft 365 desktop is recommended.
- Modern Excel functions and dynamic array support are required.
- Compatibility with older Excel versions and other spreadsheet applications is not guaranteed.

## 8. Important Disclaimer

This workbook is intended as a GST reconciliation and review aid. It does not replace professional accounting advice or independent verification of GST compliance.

Users should verify all results against original invoices, accounting records, GSTR-2B data and applicable GST provisions before making ITC or filing decisions.

## 9. License

This project is distributed under the MIT License. Refer to the LICENSE file for details.

---

**Developed as a project contribution to Advance-Autobots.**
