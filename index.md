# Awalk Privacy Policy

*Last updated: July 31, 2026*

Awalk ("the app", "we", "us") is developed by Awalk Health. This policy is written directly from the app's source code — it describes exactly what Awalk does and does not do with your data.

## Summary

Awalk has no account system and no backend server of its own. Everything you enter or that the app measures is stored only on your device, in an encrypted local database. Nothing leaves your phone except the purchase check the Play Store app itself performs when you buy Awalk Pro. We don't collect analytics, we don't show ads, and we don't sell anything.

## Data we collect

### Step and activity data
Awalk reads step counts from your phone's hardware step-counter sensor (via Android's activity-recognition APIs) to detect when you've completed a walk and dismiss the walk alarm. Step counts are written to an encrypted local database on your device and never transmitted anywhere.

### Onboarding information
When you set up Awalk, you choose a self-reported condition tag from a fixed list (e.g. a general reason you want to walk more) and set your meal times. This is stored in the same encrypted local database and used only to schedule your walk alarms.

### Purchase data
If you buy Awalk Pro, the purchase is handled entirely by Google Play Billing through Android's standard in-app purchase system. Awalk never talks to any server of ours — it only asks the Play Store app on your device whether you own the purchase. We don't collect or see your payment details; Google handles that per its own privacy policy.

## Data we do NOT collect

- Awalk has no account or sign-in of any kind — there is nothing to create, and no personal identifier (name, email, phone number) is ever requested or stored.
- Awalk does not collect app-usage analytics, crash reports, or telemetry of any kind. No analytics or crash-reporting SDK is included in the app.
- Awalk does not log glucose, blood pressure, or any other manually entered health reading — no such feature exists in the app.
- Awalk does not sync or back up your data to any cloud service. There is no "backup" feature; uninstalling the app deletes your data permanently, with nothing recoverable from our end because nothing was ever sent to us.
- We do not access your contacts, camera, microphone, location, or files.
- We do not share or sell any data to any third party, including advertisers.
- We do not show ads in Awalk.
- The app holds Android's Internet permission only because Google's Play Billing library requires it to process purchases — Awalk's own code never makes a network call. The only network activity related to Awalk is the Play Store app itself handling purchases, which is between you and Google, not us.

## How your data is stored

All app data (step counts, walk history, your condition tag, meal times, purchase entitlement) lives in an encrypted local database on your device. The encryption key itself is stored using Android's secure keystore-backed storage. This data is not backed up by Android's own backup system either — the app explicitly opts out of Android auto-backup.

## Permissions Awalk requests

- **Notifications** — to show the walk alarm.
- **Schedule exact alarm / use exact alarm** — so walk alarms fire at the right time.
- **Use full-screen intent** — so the walk alarm can show as a full-screen alarm rather than a dismissible notification.
- **Activity recognition** — to read your step count from the phone's step sensor.
- **Receive boot completed** — so scheduled alarms survive a phone restart.
- **Wake lock / vibrate / disable keyguard** — needed for the full-screen alarm to wake and vibrate the device like a normal alarm clock.
- **Foreground service** — keeps the alarm/step-tracking reliable while active.
- **Internet / access network state** — required by Google's Play Billing library to process in-app purchases. Not used by any of Awalk's own code.
- **Billing** — lets the app talk to the Play Store's purchase system, per Google's requirements for apps that sell in-app products.

None of these permissions give Awalk, or us, access to your data off-device — they control on-device behavior only (waking the screen, reading the step sensor, scheduling alarms), except Internet/Billing, which is scoped entirely to the Play Store purchase flow described above.

## Data retention and deletion

All Awalk data lives exclusively on your device. Uninstalling the app deletes it completely and immediately. Because nothing is ever transmitted to us, there is no separate deletion request to make — there is nothing on our end to delete.

## Children's privacy

Awalk is not directed at children and is not designed to be used by anyone under 16. Since the app collects no data that ever leaves the device and requires no account, there is no mechanism by which we could knowingly or unknowingly collect data from a child.

## Changes to this policy

If a future version of Awalk changes what data it collects (for example, if analytics or a backup feature is added later), we'll update this page, the "Last updated" date above, and call out the change in that release's Play Store notes.

## Contact

Questions about this policy or the app: **manish.s.ramteke@gmail.com**
