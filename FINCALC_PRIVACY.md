# Privacy Policy — FinCalc Pro

**Effective Date:** November 1, 2026  
**Application:** FinCalc: 1099 Tax & Loan Calc (`com.vashudev.fincalc`)  
**Developer:** vashudev (Raghavendra Ojha) — `mr.raghavendraojha@gmail.com`

---

## 🔒 100% Client-Side Privacy Guarantee
FinCalc Pro operates **100% offline**. All financial calculations, gross income numbers, expense deductions, filing statuses, and loan amortization numbers are computed strictly in-memory on your local Android device. **We never transmit, store, or sell your financial data to external servers.**

---

## 1. Information We Do NOT Collect
Because the application is designed offline-first:
* We do **NOT** collect names, email addresses, phone numbers, or passwords.
* We do **NOT** transmit your financial inputs to any cloud server.
* We do **NOT** maintain user accounts or cloud databases.

---

## 2. Local File Storage & PDF Reports
* All calculation results (1099 Self-Employment Tax, Schedule SE estimates, IRS Form 1040-ES quarterly schedules, and loan amortization tables) are generated entirely on-device.
* When you choose to export a PDF summary report, the document is generated using native Android `PdfDocument` and stored in temporary application cache (`cacheDir/reports/`).
* The PDF is shared strictly through the official Android system share sheet (`ACTION_SEND`) only when initiated by you.

---

## 3. Third-Party Services & Advertising
To keep the application free while supporting development, the App integrates **Google AdMob** and **Google User Messaging Platform (UMP)**:
* **Google AdMob:** May process device identifiers (such as the Google Advertising ID), IP addresses, and general diagnostic telemetry to serve non-personalized or personalized ads based on your consent.
* **Google UMP:** Displays privacy consent dialogs for users in the European Economic Area (EEA), UK, and other jurisdictions subject to GDPR and CCPA.
* Learn more at [Google's Privacy & Terms](https://policies.google.com/technologies/ads).

---

## 4. Permissions
* `INTERNET` and `ACCESS_NETWORK_STATE`: Required exclusively by the Google Mobile Ads SDK for ad serving and consent dialogs. The calculation engines function completely in Airplane Mode.

---

## 5. User Control & Data Deletion (GDPR / CCPA)
Because no personal financial data is stored on any server, there is no server-side data to delete. You can reset or delete your advertising identifier at any time via your device settings:  
`Settings > Google > Ads > Reset advertising ID` (or `Delete advertising ID`).

---

## 6. Contact Us
For any questions regarding this Privacy Policy, please contact:
* **Email:** mr.raghavendraojha@gmail.com
* **Developer:** vashudev
