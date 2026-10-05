# LOTUS 365 ERP — HTML Edition

LOTUS 365 is being rebuilt from the previous ERP stage with the implementation changed to plain **HTML + CSS + JavaScript**.

## Current build
- Executive dashboard
- Permanent dark-red ERP sidebar
- Customers master
- Products master
- Inventory & low-stock view
- Sales invoices
- Purchase bills
- Accounting / expenses
- Reports
- Settings
- Add-record forms and browser persistence
- Responsive desktop/mobile layout
- No framework dependency and no build step

## Run
Open `index.html` in Chrome.

## Data
The current HTML edition stores records in browser localStorage so CRUD works immediately without a server. The next database stage can replace the storage adapter with a real PostgreSQL/Supabase API without changing the ERP screens.

Built for LOTUS 365 ERP.
