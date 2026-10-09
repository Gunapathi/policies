# Machi — Privacy Policy

**Last Updated: October 9, 2026**

> **Privacy first:** Machi talks to your own Machi desk buddy over Bluetooth, straight from your
> phone. There is no account, no ads and no analytics, and nothing is sent to our servers: we
> don't run any. The only thing that goes to the internet is an approximate location for the
> weather, and only if you switch the weather on.

This policy covers the Machi Android app (package `com.netstedinfotech.machi`), published by
NETSTED. It is kept in the same place as the HTML version of this page; the two are always
updated together.

## 1. What Machi is

Machi is the companion app for the Machi desk buddy, a small device with a screen that you own
and pair with your phone. The app sends things from your phone to the buddy so it can show
them, and controls what the buddy does.

## 2. Notifications and calls

With your permission (Android's **Notification access**), the app reads the notifications your
phone receives:

- Only notifications from the apps you switch on in the app reach the buddy. You choose them,
  and you can switch them all off.
- What goes to the buddy: the app's name, the sender or title, and the message text, cut to a
  short length. With **Hide message text** on, the buddy gets "New message" instead of the
  text.
- An incoming call's notification sends the caller's name, so the buddy can show the call.
- The app's **Recent** list shows the last 30 notifications it saw, with the app, the title and
  what happened. It never keeps the message text. The list lives in the app's memory and is
  gone when the app stops.
- Notifications are never sent anywhere except to your own buddy.

## 3. The Bluetooth link to your buddy

- The app pairs with your buddy through Android's companion device pairing (you pick it on a
  system screen, or scan the QR code on its display).
- Over this link the app sends:
  - your notifications and calls (as above);
  - the time and time zone, and your phone's battery level;
  - the weather (if on);
  - your alarms, notes, stopwatch and timer commands;
  - the buddy's settings.
- The buddy sends back:
  - its status and settings;
  - when you choose to see it, a live copy of its screen, which the app shows and never stores.
- The link is direct between your phone and your buddy; no server is involved. It is not
  encrypted yet (encrypted pairing is planned), so a nearby device with special tools could in
  principle read it. Use **Hide message text** if that matters to you.
- The app keeps your buddy's Bluetooth address on your phone, to reconnect to it.

## 4. Location and weather (optional, off by default)

- Only if you switch **Weather** on, the app asks for your **approximate** location (never
  precise), and only reads it while the app is open.
- The approximate coordinates are sent to **Open-Meteo** (`api.open-meteo.com`) to get the local
  forecast, roughly every 30 minutes. Open-Meteo is a free weather service; its privacy policy
  is at [open-meteo.com](https://open-meteo.com/en/terms).
- Android's built-in Geocoder turns the coordinates into a city name to show on the buddy.
- The last coordinates, city and forecast are kept on your phone so the weather keeps updating.
  Switching Weather off stops all of this.

## 5. What is stored on your phone

Only on your phone, in the app's private storage:

- your settings (buddy settings, theme, which apps may reach the buddy, notification options);
- your alarms (time, days and label);
- the paired buddy's address and when it was last seen;
- the last weather (if on).

We have no copy of any of it.

## 6. Backups (your choice)

**Backup** writes your settings and alarms to a file you choose with Android's file picker
(for example your Downloads or your own cloud drive). **Restore** reads such a file back. We
never see these files.

## 7. The debug log (only if you share it)

For troubleshooting, the app keeps the last 200 link events in memory. They include the
messages sent to the buddy, so they can include notification text. The log is gone when the
app stops, and it leaves your phone only if you tap **Share debug log** and pick where to send
it.

## 8. Pairing QR scanner

Scanning the buddy's QR code uses **Google Code Scanner**, which runs inside Google Play
services. The app gets only the scanned link, needs no camera permission, and never sees the
camera image. Google's privacy policy applies to Play services:
[policies.google.com/privacy](https://policies.google.com/privacy).

## 9. Permissions the app asks for

| Permission | Why |
|---|---|
| Nearby devices (Bluetooth) | To connect to your buddy |
| Notifications | To show the app's own status notification and the alarm |
| Notification access | To forward the notifications you choose to your buddy |
| Companion device, run in the background, connected-device service | To keep the link to your buddy while the app is closed |
| Ignore battery optimisation | So Android doesn't cut the link to save power |
| Run at startup | To reconnect to your buddy after the phone restarts |
| Alarms and reminders (exact alarms) | So your phone rings at the exact time an alarm is set for |
| Approximate location | Only for the weather, only if you switch it on |
| Internet | Only for the weather |

## 10. What we don't do

- No account and no sign-in
- No ads, no analytics, no crash reporting, no tracking
- No servers of ours: none of your data reaches us
- We never sell, rent or share your data

## 11. Keeping and deleting your data

- **On your phone:** everything stays until you change it, use **Forget buddy** (removes the
  pairing), clear the app's data, or uninstall the app, which deletes it all.
- **On your buddy:** the buddy keeps its own settings, alarms and current note in its memory
  until they are changed or the device is reset.
- **With us:** nothing to delete; we don't hold any of your data.

## 12. Children

Machi is not intended for children under 13, and we do not knowingly collect any data from
children.

## 13. Changes to this policy

When a new feature changes what the app uses or sends, this page is updated, with a new
"Last Updated" date, before that version of the app is released. For example, a planned
feature for sending a partner's emoji to your buddy over the internet will need accounts, and
this policy will describe it first.

## Contact

Questions about this policy or your data:

- **Developer:** NETSTED
- **Email:** [netsted.infotech@gmail.com](mailto:netsted.infotech@gmail.com)
- **Location:** Trichy, Tamil Nadu, India

## Summary

- ✅ Talks only to your own buddy, over Bluetooth
- ✅ Only the notifications from apps you choose; message text can be hidden
- ✅ Approximate location only for the optional weather, sent to Open-Meteo
- ✅ No account, no ads, no analytics, no servers of ours
- ✅ Uninstalling deletes everything the app stored
