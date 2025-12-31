---
layout: default
title: "Pill Reminder - Photo & Track - Privacy Policy"
permalink: /policies/take-your-pill-medicine-reminder/
---


**Last Updated:** December 31, 2025

**Effective Date:** December 31, 2025

---

## Introduction

Welcome to Pill Reminder - Photo & Track ("we," "our," or "us"). We are committed to protecting your privacy. This Privacy Policy explains how our mobile application Pill Reminder - Photo & Track (the "App") handles information when you use our services.

Pill Reminder is designed to help you manage your medication schedule by setting reminders and tracking your medication intake. We believe in transparency and want you to understand exactly what data our App accesses and why.

**Important:** This App is intended for personal medication management only and is not a substitute for professional medical advice, diagnosis, or treatment.

---

## Information We DO NOT Collect

We want to be clear about what we **do not** do:

- **No Personal Data Collection:** We do not collect, store, or transmit your personal information such as name, email address, phone number, or location to any external servers.
- **No User Accounts:** The App does not require registration or login. There are no user accounts.
- **No Analytics or Tracking:** We do not use analytics services or any form of user behavior tracking.
- **No Cloud Storage:** Your medication data, reminders, and history are stored locally on your device only.
- **No Data Selling:** We never sell, trade, or rent any user data to third parties.
- **No Internet Required:** The App functions entirely offline. No internet connection is needed for core functionality.
- **No Health Data Sharing:** Your medication information never leaves your device.

---

## Information the App Stores Locally

To provide its functionality, Pill Reminder stores the following data locally on your device. All data remains on your device and is never transmitted externally.

### 1. Medication Information
- **What:** Pill names, descriptions, colors, and photos you add
- **Why:** To help you identify and manage your medications
- **Storage:** Local SQLite database on your device only

### 2. Reminder Schedules
- **What:** Reminder times and dosage amounts for each medication
- **Why:** To notify you when it's time to take your medication
- **Storage:** Local SQLite database on your device only

### 3. Intake History
- **What:** Records of when reminders were shown and when you confirmed taking medication
- **Why:** To track your medication adherence and provide statistics
- **Storage:** Local SQLite database on your device only

### 4. App Preferences
- **What:** Your settings (theme, delay duration, reminder preferences)
- **Why:** To remember your customization choices
- **Storage:** Android SharedPreferences on your device only

---

## Permissions Explained

The App requires certain permissions to function. Here's why each is needed:

### 1. Notifications (Required)
- **What:** Permission to display notifications
- **Why:** To alert you when it's time to take your medication
- **Permission:** `POST_NOTIFICATIONS` (Android 13+)
- **Your Control:** You can disable notifications in Android Settings

### 2. Exact Alarms (Required)
- **What:** Permission to schedule precise alarms
- **Why:** To ensure reminders fire at the exact times you set
- **Permission:** `SCHEDULE_EXACT_ALARM`
- **Note:** Required for reliable medication reminders

### 3. Boot Completed (Required)
- **What:** Permission to start after device restart
- **Why:** To restore your medication reminders after your device reboots
- **Permission:** `RECEIVE_BOOT_COMPLETED`
- **Note:** Ensures you don't miss reminders after restarting your phone

### 4. Photos/Storage (Optional)
- **What:** Access to photos on your device
- **Why:** To allow you to attach photos to your medications for easy identification
- **Permission:** `READ_MEDIA_IMAGES` (Android 13+), `READ_EXTERNAL_STORAGE` (older versions)
- **Your Control:** You can use the App without granting this permission

### 5. Foreground Service (Required)
- **What:** Permission to run a foreground service
- **Why:** To display fullscreen alerts for critical medication reminders (if enabled)
- **Permission:** `FOREGROUND_SERVICE`, `USE_FULL_SCREEN_INTENT`
- **Note:** Only used when fullscreen alert mode is enabled in settings

---

## Permissions Summary Table

| Permission | Purpose | Required? |
|------------|---------|-----------|
| `POST_NOTIFICATIONS` | Display medication reminders | Yes (Android 13+) |
| `SCHEDULE_EXACT_ALARM` | Schedule precise reminder times | Yes |
| `RECEIVE_BOOT_COMPLETED` | Restore reminders after restart | Yes |
| `READ_MEDIA_IMAGES` | Attach photos to medications | No |
| `READ_EXTERNAL_STORAGE` | Photo access (Android 12 and below) | No |
| `FOREGROUND_SERVICE` | Fullscreen alert mode | Yes |
| `USE_FULL_SCREEN_INTENT` | Critical reminder alerts | Yes |

---

## How the App Works

1. You add your medications with names, descriptions, and optional photos
2. You set reminder times and dosage amounts for each medication
3. The App schedules alarms using Android's alarm system
4. When reminder time arrives, you receive a notification
5. You can confirm taking the medication or delay the reminder
6. Your intake history is recorded locally for tracking
7. **All data stays on your device** - nothing is uploaded anywhere

---

## Data Storage and Security

### Local Storage Only
All your data is stored locally on your device:
- Medication details (name, description, photo, color)
- Reminder schedules (times and dosages)
- Intake history (reminder and confirmation timestamps)
- App settings and preferences

### No Cloud Sync
We do not offer cloud synchronization. Your health data never leaves your device.

### Data Deletion
Since all data is stored locally on your device:
- Uninstalling the App removes all App-related data
- You can clear App data anytime via Android Settings > Apps > Pill Reminder > Clear Data
- Individual medications can be deleted within the App
- History is automatically removed when you delete a medication

---

## Children's Privacy

Pill Reminder is not directed at children under the age of 13. We do not knowingly collect any personal information from children. Since our App does not collect personal information from any users, this applies to all age groups equally.

If a child needs medication reminders, a parent or guardian should set up and supervise the App usage.

---

## Your Rights and Choices

You have full control over your data:

1. **Deny Permissions:** You can deny optional permissions (like photo access). Core reminder features work without them.
2. **Clear Data:** Clear all App data anytime via Android Settings > Apps > Pill Reminder > Clear Data.
3. **Uninstall:** Remove the App and all associated data at any time.
4. **Delete Medications:** Remove individual medications and their history within the App.
5. **Disable Notifications:** Turn off notifications in Android Settings if desired.

---

## Medical Disclaimer

- This App is a reminder tool only and does not provide medical advice
- Always consult your healthcare provider about your medications
- Do not rely solely on this App for critical medication schedules
- The developers are not responsible for missed doses or health consequences
- Keep a backup reminder system for critical medications

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the "Last Updated" date at the top of this document. We encourage you to review this Privacy Policy periodically.

For significant changes, we will notify users through:
- App update release notes on Google Play Store
- In-app notification (for major changes)

---

## Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our privacy practices, please contact us at:

**Email:** cosmik.developer@gmail.com

---

## Summary

**In simple terms:**
- Your medication data stays on your device
- We don't collect your personal data
- We don't track you
- We don't require internet access
- No accounts or registration needed
- All data is stored locally in a secure database
- Uninstalling removes everything
- You have full control over your data

---

## Data Safety (Google Play Console)

When filling out the Data Safety form in Play Console:

| Data Type | Collected | Shared | Purpose |
|-----------|-----------|--------|---------|
| Health info (medications) | Stored locally only | No | App core functionality |
| Photos | Accessed locally only | No | Medication identification |
| App activity | Stored locally only | No | Reminder history |

**Security Practices:**
- No data transmitted off device
- No user accounts required
- Local database storage only
- No internet connection required

---

*This privacy policy is effective as of December 31, 2025.*
