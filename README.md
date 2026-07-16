Invoice Generator Pro

A modern, fully-featured invoice generator web application that runs entirely in your browser. No backend, no database – just pure HTML, CSS, and JavaScript. Create, edit, save, and export professional invoices with ease.

🚀 Features

· Complete Invoice Management
  · Editable company details (name, logo, phone, email, address, website, TIN/VRN)
  · Editable customer information (name, company, phone, email, address, city)
  · Dynamic item table with unlimited rows – add, delete, or edit any cell
  · Auto‑calculates Amount = Quantity × Unit Price
· Smart Calculations
  · Subtotal, Discount, VAT (%), Shipping, and Grand Total update instantly
  · Grand Total formula: Subtotal – Discount + VAT + Shipping
  · Currency support: TZS, USD, EUR, GBP (switchable via dropdown)
· Data Persistence
  · Save drafts automatically to LocalStorage (restored on page reload)
  · Invoice history – store, open, duplicate, or delete past invoices
  · Search history by invoice number, customer name, or date
· Export & Print
  · One‑click Download PDF – multi‑page A4 export with html2canvas + jsPDF
  · Print Invoice – hide UI buttons and print only the invoice content
· User Experience
  · Dark / Light theme (saved in LocalStorage)
  · Glassmorphism cards, soft shadows, smooth transitions
  · Toast notifications for feedback, modal dialogs for confirmations
  · Responsive design – works on desktop, tablet, and mobile
· Keyboard Shortcuts
  · Ctrl+S – Save draft
  · Ctrl+P – Print invoice
  · Ctrl+D – Download PDF

🛠️ Technologies

· HTML5 – semantic markup
· CSS3 – custom properties, flexbox, grid, animations
· Vanilla JavaScript – no frameworks, no dependencies
· Libraries (CDN):
  · html2canvas – capture invoice as image
  · jsPDF – generate PDF files

📁 Project Structure

The entire application is contained in a single file:

```
index.html
```

All HTML, CSS, and JavaScript are embedded in this one file for easy deployment.

🧪 How to Use

1. Open the file in any modern browser (Chrome, Firefox, Edge, Safari).
2. Fill in your company details – upload a logo, edit contact info.
3. Add customer information – name, company, phone, email, address, city.
4. Manage invoice items – click “Add Item” to insert rows, edit description, quantity, and unit price.
5. Adjust discounts, VAT, and shipping – all totals update automatically.
6. Save your draft – click the Save Draft button or press Ctrl+S.
7. Export or print – use the Download PDF (Ctrl+D) or Print (Ctrl+P) buttons.
8. View history – click the History button to see all saved invoices; open, duplicate, or delete any entry.

🌐 Deployment Options

Because it’s a single static file, you can host it anywhere:

· GitHub Pages – push index.html to a repository and enable Pages.
· Firebase Hosting – upload via the Firebase console or CLI.
· Netlify / Vercel – drag and drop the file.
· Any web server – just place the file in the root directory.

📄 License

This project is open source and available under the MIT License.

---

Enjoy generating professional invoices! If you have any questions or suggestions, feel free to open an issue or contribute.
