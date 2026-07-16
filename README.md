# TickMatch — Bank Reconciliation

A single-file web app that reconciles a bank statement against a general ledger.

- Upload a bank statement (CSV / Excel / PDF) and a GL export (CSV / Excel / PDF)
- Confirm the auto-detected columns
- Review matched and unmatched transactions, match manually, export a CSV report

**Privacy:** everything runs client-side in the browser — uploaded files are never sent to any server.

Built with an embedded pdf.js and a native XLSX parser; no build step, no dependencies. `index.html` is the entire app.
