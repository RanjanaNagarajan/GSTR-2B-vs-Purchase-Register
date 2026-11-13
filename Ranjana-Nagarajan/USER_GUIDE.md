# User Guide

## 1. Before you begin

Use Microsoft Excel for Microsoft 365 desktop. Keep an untouched copy of the downloaded template. Open the `.xltx` file and save a separate working workbook as `.xlsx`.

## 2. Enter Purchase Register data

1. Open **PURCHASE DATA**.
2. Paste/import the Purchase Register into columns **A:I**, starting at the first data row below the headings.
3. Keep the field order exactly as shown in the workbook.
4. Do not paste into columns **J:L**. They contain calculated fields.

## 3. Enter GSTR-2B data

1. Open **GSTR-2B DATA**.
2. Paste/import the GSTR-2B data into columns **A:I**.
3. Use the same field order as the Purchase Register input.
4. Do not overwrite columns **J:L**.

## 4. Data preparation checks

Before reviewing the output:

- Confirm the GSTINs are complete and correctly assigned.
- Check invoice numbers for leading/trailing spaces and inconsistent punctuation.
- Confirm invoice dates are recognised by Excel as dates.
- Confirm taxable values and tax amounts are numeric, not text.
- Ensure the selected Purchase Register and GSTR-2B periods are comparable.
- Review duplicate invoices and source-data quality.

## 5. Review the Dashboard

Open **DASHBOARD** to review the high-level counts, values, exception summary, and charts. Treat these as navigation and review aids; investigate the underlying invoice details before reaching a conclusion.

## 6. Review reports

Open **REPORTS** and use the report selector to view the available reports, including:

- Invoice-wise Reconciliation
- Exception Analysis
- Missing in GSTR-2B
- Missing in Purchase Register
- Duplicate Invoice Register
- Vendor-wise Analysis
- Tax-head-wise Analysis

Read each exception in context. A mismatch or missing invoice is a prompt for review, not an automatic tax conclusion.

## 7. Understand the match

The workbook uses an invoice-level key built from GSTIN and invoice number. Differences in invoice numbering or GSTIN can prevent a match. This workbook does not perform line-item matching or determine tax-rate-level correctness.

## 8. Refreshing and replacing data

For a new reconciliation, use a fresh working copy of the original `.xltx` template whenever possible. This reduces the risk of leaving old records in the input tables. If replacing data in an existing workbook, clear only the manually entered input fields in columns A:I and preserve formula columns J:L.

## 9. Protect client confidentiality

This workbook may contain sensitive commercial and tax information. Store it securely, share it only with authorised people, and remove or anonymise client data before sharing screenshots, support requests, or public issue reports.

## 10. Troubleshooting

- **Formulas show errors:** Confirm the workbook is opened in a supported Microsoft 365 version and that formula columns J:L were not overwritten.
- **Unexpected missing invoices:** Check GSTIN and invoice-number consistency, date/period selection, and source-data completeness.
- **Unexpected duplicates:** Check repeated GSTIN + invoice-number combinations in the Purchase Register.
- **Unexpected differences:** Compare the source invoice, books, and downloaded GSTR-2B data. Check whether amendments, credit/debit notes, or timing differences are relevant.
- **Report output looks stale:** Confirm Excel calculation is set to Automatic and recalculate the workbook.

For support, provide the Excel version and a sanitised sample. Never publish real client GST data.
