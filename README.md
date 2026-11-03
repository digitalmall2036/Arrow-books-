# Arrow — Business Record Keeping

Arrow is a web app for keeping business records.

## What it does
- **Business sign-in.** Enter a business name and password. A new name creates a business dashboard; the same name and password opens it again. Passwords are stored as salted hashes and can be changed from the dashboard.
- **Word records**
  - **Words**: notes and write-ups, such as "Business goals".
  - **Calculations**: line items (asset, liability, income, expense) with automatic totals and graphs.
- Every file has pages. Each page needs a title, and the created and saved dates are added automatically.
- **Upload**: drop or choose files or whole folders, then rename them and edit text files.
- **Arrow agent command bar** (type or speak), for example:
  - `open a new file called profits, on the first page write 2026 profits as the title`
  - `add van 6000 as asset`
  - `total assets`
  - `subtract liabilities from assets`
  - `graph liabilities over assets`
- **Admin**: separate admin sign-in; lock or unlock a business, reset a business's password.

## Running it
Open `index.html` in a browser. This is a prototype: everything is stored in the browser's local storage, so records stay on that device. A shared server and database are the next step for multi-device use.
