# Outfox Customer Portal (v4)

This is the Outfox Energy version of the customer portal. It is a clickable prototype for reviewing UI refinements and change of tenancy (COT) functionality.

The screens use the Outfox palette: Purple `#7100F1`, Black `#001E28`, and White. Success, error, and information states use the Outfox utility colours (green, red, and blue).

> **Status:** Prototype / design review. Not connected to live customer data. Accounts, readings, bills, and appointments are demo data stored in the browser.

---

## Focus of this version

- **UI refinements.** Layout, colour, and interaction updates across the portal, in the Outfox brand.
- **COT functionality.** The change of tenancy journey, including moving out.

---

## What is included

| Area | Page | Notes |
|------|------|-------|
| Sign in | `index.html` | Demo sign-in |
| Home | `portal.html` | Account summary and switch progress |
| Meter readings | `readings.html` | Smart, traditional, and non-communicating meters |
| Bills and payments | `bills.html` | Electricity and gas |
| Your tariff | `tariff.html` | Current tariff, including time-of-use |
| Tariff journeys | `tariff-journey.html` | Change tariff, renewal, and Direct Debit |
| Your account | `account.html` | Account holder details and preferences |
| Smart meter booking | `booking.html` | Book, reschedule, cancel, and error screens |
| Change of tenancy | `moving-out.html` | Moving-out journey |
| Chat | On each signed-in page | Chat with us |

---

## How to run it

No installation is needed. It is plain HTML, CSS, and JavaScript.

**Option 1 – Double-click**

1. Open the project folder.
2. Double-click `index.html`.

**Option 2 – Local server (recommended)**

1. Open a terminal in the project folder.
2. Run:

   ```bash
   python -m http.server 8000
   ```

3. Open `http://localhost:8000` in your browser.

After a change, press **Ctrl + F5** so the browser loads the latest files.

---

## Demo sign-in

On the sign-in page, click **Continue as demo customer**. You can also type any email and a password of at least 6 characters.

Use the sun and moon control in the header to switch between light and dark.

---

## Project structure

```
├── index.html            Sign in
├── portal.html           Home
├── readings.html         Meter readings
├── bills.html            Bills and payments
├── tariff.html           Your tariff
├── tariff-journey.html   Tariff change, renewal, Direct Debit
├── account.html          Your account
├── booking.html          Smart meter booking
├── moving-out.html       Change of tenancy (moving out)
├── css/styles.css        Styles, including light and dark themes
└── js/
    ├── app.js            Page behaviour and demo data
    └── theme.js          Light and dark theme
```
