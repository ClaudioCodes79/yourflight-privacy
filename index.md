# Privacy Policy for YourFlight B2E

**Effective Date:** October 28, 2026

YourFlight B2E ("YourFlight") is a personal flight-duty companion and reference tool for cabin crew. YourFlight is designed so that your schedule, checklist progress, and notes stay under your control on your devices and‚Äîif you keep iCloud sync enabled‚Äîin your private iCloud account.

---

## 1. Information YourFlight Accesses and Stores

### Flight Plan, Checklist Progress, Custom Steps, and Flight Log
- **What is stored:** Flight numbers, pairing numbers, airports, scheduled times, crew position, optional crew first names or notes you type into your roster, checklist completion status, custom checklist steps you create, app preferences, and your completed-leg flight log (retained for up to 2 years).
- **Where it is stored:** Locally on your device (including a shared App Group container on your device so the Home Screen / Lock Screen Widget and Live Activity can display your current and upcoming legs). Note: Crew roster names are never shared with widgets or Live Activities.

### Optional Private iCloud Sync
- If **Sync across my devices** is enabled in the **Flight Plan** tab, YourFlight uses Apple's `NSUbiquitousKeyValueStore` to sync your current flight plan, checklist checkmarks, custom checklist steps, preferences, and 2-year flight log across devices signed in to your personal Apple ID.
- This data is stored solely in your private iCloud key-value container managed by Apple. The developer of YourFlight has no access to your iCloud account or any data stored in it.
- You can turn off **Sync across my devices** at any time in the **Flight Plan** tab.

### Optional Calendar Import
- If you grant Calendar permission and tap **Sync Calendar** (or enable automatic sync while the app is open), YourFlight reads events on your device within a window of 3 days in the past to 30 days in the future.
- Only events whose title or location begins with `"Trip:"` are parsed into pairings and legs. All other personal calendar events are ignored.
- Calendar reading and parsing happen **100% on your device**. Your calendar events are never uploaded to any external server, and YourFlight never writes to, modifies, or deletes events in your Calendar.
- You can revoke Calendar access at any time in **Settings > Privacy & Security > Calendars**.

### Optional Local Notifications
- If you enable **Report reminder** or **Hotel van reminder**, YourFlight schedules local notifications on your device (`UNUserNotificationCenter`) before your report time or hotel van pickup time.
- Notifications are generated locally on your device and do not use remote push notification servers.

---

## 2. Information YourFlight Does Not Collect

- **No accounts or sign-in:** YourFlight does not require or offer user accounts.
- **No external servers:** The developer operates no backend servers that receive your flight plans, calendar events, or usage data.
- **No analytics, tracking, or advertising:** YourFlight includes no third-party analytics SDKs, crash-reporting trackers, advertising networks, or cross-app tracking.
- **No sale or sharing of data:** Because the developer never receives your data, your information is never sold, rented, or shared with third parties.

---

## 3. How to Delete Your Data

You can erase all data stored by YourFlight at any time:

1. Open YourFlight and go to the **Flight Plan** tab.
2. Scroll to the bottom and tap **Delete All Local Data**, then confirm.
   - This immediately removes your saved flight plan, imported trips, flight log, custom checklist steps, widget snapshots, active Live Activities, pending local notifications, **and** all YourFlight keys stored in your private iCloud key-value store.
3. Uninstalling YourFlight from your devices also removes all local app data on those devices.

---

## 4. Disclaimer

YourFlight is an independent personal organization and reference aid. It is not affiliated with, endorsed by, or sponsored by any airline, and it is not an FAA-approved or company-approved flight operations manual. Always defer to your airline's official Flight Attendant Manual, operations bulletins, and Flight Deck instructions.

---

## 5. Contact

If you have questions about this Privacy Policy, please contact the developer at **Claudioadamss@icloud.com**.

