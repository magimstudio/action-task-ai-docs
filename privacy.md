# Privacy Policy

**Effective Date:** 2026-02-03

## 1. Introduction
ActionTask AI ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, store, and share your data when you use our mobile application.

---

## 2. Data Accessed

### Google User Data
When you sign in with Google and enable synchronization, ActionTask AI accesses the following Google user data:

- **Google Account Email Address**: Used to identify your account and enable sign-in.
- **Google Tasks Data**: Your task lists, tasks, and associated metadata (title, notes, due date, completion status) stored in your Google Tasks account.

We request the following OAuth scopes:
- `email` – To retrieve your Google account email address for identification.
- `https://www.googleapis.com/auth/tasks` – To read and write tasks and task lists in your Google Tasks account.

### Local Data
- **Tasks and Lists**: All tasks and lists you create are stored locally on your device using SQLite.
- **App Settings**: Your preferences and settings are stored locally.

### Analytics Data
- **Crash Reports**: We collect anonymous crash reports via Firebase Crashlytics to improve app stability. This data does not include personally identifiable information.

---

## 3. Data Usage

We use your data for the following purposes:

| Data Type | Purpose |
|-----------|---------|
| Google Email | To identify you and enable sign-in to the app. |
| Google Tasks Data | To synchronize your tasks between ActionTask AI and Google Tasks, enabling you to access your tasks across devices. |
| Local Tasks/Lists | To provide offline task management functionality. |
| Crash Reports | To diagnose and fix bugs, improving app reliability for all users. |

**We do NOT use your data for:**
- Advertising or ad targeting
- Selling to third parties
- Profiling or tracking beyond app functionality

---

## 4. Data Sharing

### Third-Party Services
We share data with the following third-party services, solely for the purposes described:

| Service | Data Shared | Purpose |
|---------|-------------|---------|
| **Google Tasks API** | Your tasks, task lists, and task metadata | Bi-directional sync between ActionTask AI and your Google Tasks account |
| **Firebase Crashlytics** | Anonymous crash logs (device info, stack traces) | Crash reporting and app stability improvement |
| **RevenueCat** | Anonymous purchase identifiers | Subscription and in-app purchase management |

### We Do NOT Share:
- Your Google user data with any other third parties
- Your data for advertising, marketing, or analytics beyond crash reporting
- Your personal information for sale or commercial purposes

---

## 5. Data Storage & Protection

### Local Storage
- All task data is stored locally on your device using an encrypted SQLite database (Drift).
- Your Google authentication tokens are stored securely using Flutter Secure Storage (Keychain on iOS).

### Server-Side
- **We do not operate servers that store your task data.** Your tasks are synced directly between your device and Google's servers via the Google Tasks API.
- We do not maintain copies of your Google Tasks data on our servers.

### Security Measures
- OAuth 2.0 is used for secure authentication with Google.
- All communication with Google APIs uses HTTPS encryption.
- Authentication tokens are stored in platform-secure storage (iOS Keychain).

---

## 6. Data Retention & Deletion

### Retention
- **Local Data**: Stored on your device until you delete it or uninstall the app.
- **Google Tasks Data**: Retained by Google according to their data retention policies. We do not maintain separate copies.
- **Crash Reports**: Retained by Firebase Crashlytics for up to 90 days.

### Deletion

**To delete your local data and sign out:**
1. Open ActionTask AI
2. Navigate to **Settings** (gear icon)
3. Scroll to the bottom and tap **"Delete Account / Wipe Data"**
4. Confirm the action

This will:
- Remove all locally stored tasks and settings from your device
- Sign you out of your Google account within the app
- Clear your authentication tokens

> [!NOTE]
> **Your Google Tasks data stored on Google's servers will NOT be deleted.** To delete that data, visit [Google Tasks](https://tasks.google.com) or use the Google Tasks app directly.

**To request complete data deletion:**
Contact us at [support@magim.online](mailto:support@magim.online) and we will:
- Confirm deletion of any data associated with your account
- Provide guidance on deleting your Google Tasks data from Google's servers

---

## 7. Children's Privacy
ActionTask AI is not intended for children under 13. We do not knowingly collect personal information from children under 13.

---

## 8. Changes to This Policy
We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date."

---

## 9. Contact Us
If you have any questions about this Privacy Policy, our data practices, or to request data deletion, please contact us:

**Email:** [support@magim.online](mailto:support@magim.online)

---

*This app uses [Google API Services](https://developers.google.com/terms). Use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.*
