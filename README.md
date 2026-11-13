# TinyInvoice

<p align="center"><img src="assets/readme-banner.svg" alt="TinyInvoice animated banner" width="100%"></p>

A lightweight invoice maker that runs locally in your browser. Build an itemized invoice, calculate totals, and print or save it as PDF.

## Features
- Seller, client, invoice number, and issue date fields
- Editable line items with quantity and unit price
- Currency selection, discount, and tax percentage
- Live invoice preview
- Browser print dialog (choose **Save as PDF**)
- Save and reload a local draft
- No account, server, build tools, or external dependency

## Run it
1. Download **Code → Download ZIP** and extract the folder.
2. Open `index.html` in a modern browser.
3. Fill in the details and choose **Print / Save PDF**.

Optional: `python -m http.server 8000` then open `http://localhost:8000`.

## Notes
TinyInvoice is a general-purpose document helper, not tax, accounting, or legal advice. Check local invoice requirements before issuing business documents. The saved draft is stored in this browser only.

## License
MIT — see [LICENSE](LICENSE).
