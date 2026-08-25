# EUL Student — Terms of Use & Privacy Policy (EULA)

**Last Updated:** August 2026  
**Application Version:** 9.3+  
**Developer:** Sana Mngadi (`snm.developer@gmail.com`)  
**Apple Standard EULA:** [https://www.apple.com/legal/internet-services/itunes/dev/stdeula/](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)

---

## 1. Introduction & Acceptance of Terms

Welcome to the **EUL Student** mobile application ("**the App**"). By downloading, installing, accessing, or using the App, you agree to be bound by these **Terms of Use (End User License Agreement)** and **Privacy Policy**. If you do not agree to these terms, please do not use or access the App.

### Independent Student Community Project
The App is an independent, community-driven academic utility developed for students of the **European University of Lefke (Lefke Avrupa Üniversitesi)**. The App is **not** officially affiliated with, maintained by, or endorsed by the university administration.

---

## 2. Terms of Use & End User License Agreement (EULA)

### A. Authorized Student Access & Acceptable Use
1. **Authorized Authentication**: You may only sign in using your own valid student number and university credentials. Unauthorized access to third-party student accounts, credential harvesting, or impersonation is strictly prohibited.
2. **Acceptable Automation**: The App acts as a client-side relay to connect to official university portals (OIBS, SIS, Moodle, and Portal Accounting). Tampering with request headers, overloading campus servers, or malicious reverse-engineering of campus APIs is strictly prohibited.

### B. EUL PRO PASS Auto-Renewable Subscriptions & In-App Purchases
The App offers optional premium access through **EUL PRO PASS** auto-renewable subscriptions managed via **RevenueCat**, the **Apple App Store**, and **Google Play Store**.

1. **Subscription Plans**:
   - **Monthly Subscription**: Month-to-month access with flexible renewal.
   - **Annual Subscription**: 12-month academic year access.
2. **Payment & Billing**:
   - Payment will be charged to your **Apple ID / Google Play account** upon confirmation of purchase.
   - Subscriptions automatically renew unless auto-renew is cancelled **at least 24 hours before the end of the current billing period**.
   - Your account will be charged for renewal within 24 hours prior to the end of the current period at the then-current plan price.
3. **Management & Cancellations**:
   - You can manage, switch, or cancel your subscription at any time via your device's store settings:
     - **iOS**: *Settings > Apple ID > Subscriptions* or [Manage Apple Subscriptions](https://apps.apple.com/account/subscriptions).
     - **Android**: *Google Play Store > Profile > Payments & Subscriptions*.
4. **Standard Apple EULA Incorporation**:
   - For all iOS installations, this agreement incorporates Apple's [Standard Licensed Application End User License Agreement (EULA)](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/).

### C. Feature Scope & Disclaimers
1. **Academic Data (OIBS / SIS)**: Timetable schedules, 4-year curriculum matrix, GPA/CGPA, and transcripts are retrieved from official campus systems with your consent and cached locally for offline convenience. Official binding records remain those on the official university servers.
2. **Financial Ledger & Accounting**: Tuition balances, debt figures, and transaction logs reflect cached data from student accounting portals. For legally binding financial clearances, fee receipts, and bank deposit confirmations, always consult the university accounting office.
3. **Moodle LMS & QR Attendance**: 1-Tap course enrollment and classroom QR attendance scanning are provided to streamline classroom workflows. Always verify critical course enrollments on the official Moodle website.
4. **Campus Shuttle Radar**: Transit schedules, bus stops, and countdown timers are subject to changes by university transport coordinators and campus traffic conditions.
5. **Intellectual Property**: All university logos, trademarks, course codes, and building names belong to their respective owners at European University of Lefke.

---

## 3. Privacy Policy & Data Handling

We operate under strict **zero-sharing** and **privacy-first** principles:

### A. Credential Security & Local Keychain Storage
- Your university portal credentials (OIBS, SIS, Moodle, and Accounting) are stored encrypted in your device's native hardware security enclave (**Apple Keychain / Android Keystore**).
- Credentials are transmitted strictly over encrypted TLS connections directly to university authentication gateways. We **never** sell, rent, monetize, or share your credentials with third parties.

### B. Academic Data Ingestion & Offline SQLite Storage
- Academic schedules, curriculum requirements, and transcripts are ingested upon student login and cached in a local, encrypted **SQLite** database on your device to enable instant offline access without requiring internet connectivity.

### C. Third-Party Subprocessors
To operate reliable, real-time services, we partner with industry-standard, privacy-compliant infrastructure providers:
- **Supabase Cloud**: Authenticated database synchronization protected by Row Level Security (RLS) policies.
- **RevenueCat**: Secure in-app purchase validation communicating directly with Apple App Store and Google Play.
- **Sentry**: Anonymized crash telemetry and runtime error monitoring to improve app stability.
- **Expo Notifications**: Anonymous device push token delivery for lecture countdowns and morning briefings.

### D. Account Deletion & GDPR Compliance (Apple Guideline 5.1.1(v))
You maintain full ownership of your data:
- **Local Cache Purge**: You can flush all locally cached academic schedules and ledger checkpoints at any time from *Settings*.
- **Permanent Account Deletion**: You can permanently delete your account and all associated cloud records instantly from *Settings > Security > Delete Account*.

---

## 4. Contact & Inquiries

For support, questions regarding your data privacy, or general feedback, contact the independent developer team:

- **Email**: `snm.developer@gmail.com`
- **In-App Feedback**: Available within the *Settings* screen of the EUL Student App.
