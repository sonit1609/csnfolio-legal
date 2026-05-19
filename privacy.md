# Privacy Policy — CSN Folio

**Effective Date:** May 14, 2026
**Last Updated:** May 14, 2026

CSN Folio ("we", "our", "the app") respects your privacy. This document explains what data we collect, how we use it, and your rights.

## 1. Information We Collect

### 1.1 Account information
- **Email address** — used for authentication only
- **Display name** — shown in the app UI
- **User ID** — internal Firebase Auth UID

### 1.2 Financial data you enter
- Assets you track (coins, stocks, cash, gold, etc.) — values, quantities, prices
- Expense and income transactions
- Snapshot history of your total portfolio value

This data is stored encrypted in Google Firestore under your user ID. You are the only one who can read it.

### 1.3 Device data (anonymous)
- Crash reports (via Firebase Crashlytics, optional)
- App version and iOS version
- No tracking identifiers (IDFA), no location, no contacts, no photos.

### 1.4 Third-party API requests
The app makes anonymous requests to:
- **Binance** (`api.binance.com`) — crypto prices
- **VPS Securities** (`bgapidatafeed.vps.com.vn`) — Vietnamese stock prices
- **TCBS / Fireant / VNDirect** — historical stock data
- **consaunho.vn** — USDT/VND exchange rate
- **ExchangeRate-API** — multi-currency rates

These services do not receive your personal data — only the symbol names you choose to track.

## 2. How We Use Your Data

- To authenticate you and load your portfolio
- To compute aggregate statistics on your data
- To send you local price alert notifications you configured
- To respond to support requests

We do **not**:
- Sell or share your data with third parties
- Use your data for advertising
- Track your behavior across other apps or websites
- Access your contacts, photos, or location

## 3. Data Storage and Security

- Your data is stored in Google Firestore (Firebase) with encryption in transit (TLS 1.3) and at rest (AES-256).
- Firestore security rules ensure only you (authenticated as your UID) can read or write your data.
- The app supports Face ID / Touch ID to lock access on your device.

## 4. Your Rights

You can at any time:
- **Edit** your profile (Settings → Profile)
- **Export** all your data to CSV (Settings → Export Data)
- **Delete** your account permanently, including all associated data (Settings → Delete Account)
- **Disable cloud sync** by signing out and using Local mode

Deletion is permanent and immediate. Data cannot be recovered.

## 5. Children's Privacy

CSN Folio is not directed at children under 13. We do not knowingly collect data from children.

## 6. Changes to This Policy

We may update this policy occasionally. When we do, we'll update the "Last Updated" date above and notify you in the app.

## 7. Donor Recognition (Optional)

CSN Folio accepts **voluntary donations** via external bank transfer (Techcombank QR / VietQR). Donations are:
- 100% **optional** and **not required** to use any feature of the app
- Processed **outside the app** via the user's banking app
- Used to support continued development of CSN Folio

If you choose to donate and include your name + message in the bank transfer note, you provide **explicit consent** for that name and message to be displayed publicly on the app's home screen as a thank-you tribute. By writing this information in the transfer note, you:

1. Agree to public display on the app home screen
2. Confirm the content does not contain confidential personal information
3. Acknowledge we reserve the right to **moderate, edit, or refuse** content that is offensive, illegal, or inappropriate
4. May request **removal at any time** by emailing **csnfolio@gmail.com**

To donate **anonymously**, write `"anon - [your message]"` in the transfer note. Your name will not be displayed.

Donor recognition does NOT unlock any app feature, premium content, or special access. It is purely a public thank-you and creates no obligation on our part.

## 8. Contact

For privacy questions or concerns:
- Email: **csnfolio@gmail.com**

## 9. Sources & Disclaimers

CSN Folio is an asset tracking tool, **not a financial advisor**. Prices shown are sourced from third-party APIs and may be delayed or inaccurate. Do not make investment decisions based solely on this app. Past performance is not indicative of future results.
