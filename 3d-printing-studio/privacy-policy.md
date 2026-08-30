# 3D Printing Studio — Privacy Policy & Terms of Use

**Publisher:** NETSTED (Netsted Infotech), Trichy, Tamil Nadu, India
**Contact:** netsted.infotech@gmail.com
**Applies to:** 3D Printing Studio version 3.3.0 and later
**Last updated:** 30 August 2026

---

**Local first.** 3D Printing Studio stores your business data on your own
device. We operate no servers, run no analytics, and never receive a copy of
your data. The only time anything leaves your device is when *you* choose to
back up to your own Google Drive, share an invoice, or activate your account.

**This document has two parts.** Part A is the privacy policy — what the app
stores, what leaves your device and what does not. Part B is the terms of use,
disclaimers and legal notes — including who is responsible for the GST and
other figures on your invoices (you are — see section 18), how account
activation works, and why you must keep your own backups. By installing or
using the app you accept both parts.

---

# PART A — PRIVACY POLICY

## 1. Who we are

3D Printing Studio ("the app") is developed and published by **NETSTED**
(Netsted Infotech), Trichy, Tamil Nadu, India. In this document, "we", "us" and
"the publisher" refer to NETSTED, and "you" refers to the person or business
using the app.

## 2. Information stored on your device

The app is a business tool for 3D-printing makers. It stores the following in a
database in the app's private storage on your device:

- **Customer records you enter:** name, phone number (with country code), email
  address, postal address, notes, and — if you use tax invoicing — the
  customer's GSTIN, state and PIN code.
- **Order records:** order numbers, customer name and contact, line items,
  prices, discounts, advances, balances, payment mode, payment and refund
  status, printer / packing / post-processing / delivery charges, profit
  margin, the GST recorded on the order (CGST, SGST or IGST and the place of
  supply), any separate ship-to address, and the order's history log.
- **Invoice snapshots:** when an order is created, the business details its
  invoice will print are frozen onto that order, so a document you have already
  issued cannot be rewritten later by changing a setting.
- **Filament inventory:** brands, types, colours, weights, spool counts, cost
  and sell rates, stock purchases and stock movements.
- **Products:** your catalogue of finished goods.
- **Printers, packing types, post-processing steps and delivery options:** the
  names, descriptions and costs or hourly rates you set.
- **Investment ledger:** money you record spending — item name, item type,
  vendor, date, amount and notes — together with your vendor and item-type
  lists. Filament stock purchases also create a matching ledger entry.
- **Business and invoice details:** store name, operator name, business address,
  state, PIN code, country, your GSTIN, your CGST / SGST / IGST percentages,
  your invoice labels and terms-and-conditions lines, your profit-margin
  setting, and — if you add them — your **bank account name, account number,
  account type, bank name and IFSC**.
- **Images you choose:** your business logo and your signature image. These are
  copied into the app's private storage and printed on invoices.
- **Reminders:** the title, body and scheduled time of reminders you create.
- **Preferences:** currency symbol, order-number prefix, dark-mode setting,
  backup schedule and feature choices.

**We do NOT collect, and the app does not contain:**

- Any analytics, telemetry, crash-reporting or tracking SDK.
- Advertising, advertising IDs or advertising SDKs.
- Location data.
- Any server operated by us that receives your business data — **we have none**.

The only identifier the app ever sends anywhere is the activation device
identifier described in **section 8**, and only if you choose to activate your
account. If you never activate, no identifier leaves your device.

The app has an "Analytics" screen. This shows *your own business figures*
(revenue, profit, top customers, order trends) calculated on your device from
your own records. It is not usage tracking, and nothing from it is transmitted
anywhere.

## 3. Your business, tax and bank details

To print a proper invoice, the app lets you store your own business identity —
address, GSTIN, logo, signature, and optionally your bank account details for
payment.

- **All of it stays on your device.** It is held in the same private database
  and the same private image folder as everything else. It is never sent to us,
  and we never see it.
- **Bank details are optional and off until you add them.** A separate switch
  decides whether they are printed on invoices at all.
- **Anything printed on an invoice goes wherever you send that invoice.** If you
  enable bank details, every invoice you share carries your account number and
  IFSC to whoever receives it. That is the point of the feature — but it is your
  decision, and only you can make it. Review what is on the page before sharing
  it.

## 4. Data about your customers — your responsibility

This app is designed for you to record details of **other people** — your
customers' names, phone numbers, email addresses, postal addresses and, where
you use tax invoicing, their GSTIN.

Because that information is entered by you, held on your device, and never sent
to us, **you are the controller of that data and are responsible for it.** This
includes:

- Having a lawful basis to collect and keep your customers' details.
- Telling your customers how you use their information, if the law where you
  operate requires it.
- Honouring their requests to see, correct or delete their data — you can edit
  or delete any customer record in the app at any time.
- Keeping your device, and any backups or exports you create, physically and
  digitally secure.

Depending on where you operate, laws such as India's Digital Personal Data
Protection Act or the EU/UK GDPR may place obligations on you as a business. We
provide the tool; complying with those obligations is your responsibility.

## 5. Phone contacts — copied, never linked

The customer form can build a customer from your phone's address book. One rule
governs the whole feature: **the app copies, it never links.**

- **Read-only.** The app asks for permission to *read* contacts and nothing
  else. It cannot add, change or delete anything in your address book — that
  permission is deliberately not requested.
- **Only the name and one mobile number** are taken, and only from the contact
  you pick and can see before saving. Emails, addresses, photos, notes,
  organisations and every other contact field are never read.
- **One-shot.** The address book is read only while the picker is open, and
  never again. There is no background sync, no observer and no periodic refresh.
- **Nothing points back.** No contact ID or lookup key is stored. A customer
  created this way is an ordinary customer record. Editing or deleting the
  contact afterwards does not change it, and the app never writes back.
- **The permission is asked at first use, never at start-up**, and declining is
  harmless — you can always type the details in instead.
- **Nothing is transmitted.** The copied name and number live in your on-device
  database and travel only in your own backups.

## 6. How your data is stored

- **Local database:** all records are stored in a SQLite database in the app's
  private storage on your device. On Android, this area is not readable by other
  apps.
- **Images:** your logo and signature are copied into the app's private storage.
  Large logos are automatically reduced in size so that invoices stay small.
- **Backup files:** the app can export your data as a backup bundle (`.abb`), a
  JSON file, a raw SQLite file, or CSV files. The `.abb` bundle also carries
  your logo and signature images, so a restore puts your invoices back exactly
  as they were.
- **Optional backup encryption:** in Settings → Backup & restore you can set a
  **backup password**. When set, every new `.abb` backup bundle — local exports
  *and* Google Drive backups — is encrypted with **AES-256-GCM**, using a key
  derived from your password (PBKDF2, 150,000 iterations). The password itself
  stays in the app's private storage on your device, is never included in any
  backup, and is never sent to us.

Please note:

- Backup encryption is **off until you set a password**. Without one, `.abb`
  backups are unencrypted, and anyone who obtains the file can read everything
  in it, including your customers' contact details and your bank details.
- **JSON, raw SQLite and CSV exports are always unencrypted** — they exist to be
  readable and portable. Treat them as confidential.
- **If you forget your backup password, encrypted backups cannot be opened — by
  you, by us, or by anyone.** There is no recovery or reset. Keep the password
  somewhere safe.

## 7. Google Drive backup (optional)

Cloud backup is entirely optional and is off until you connect an account. If
you enable it:

- **You sign in with your own Google account.** Backups are uploaded to *your*
  Google Drive, into a visible folder named `3DPrintingStudioBackups`. They are
  not uploaded to us, and we cannot see them.
- **We request only the `drive.file` permission.** This is the narrowest Drive
  permission available: it lets the app see and manage *only the files the app
  itself creates*. The app cannot see, read or touch any other file in your
  Google Drive.
- **Account information we handle:** your Google account email address and an
  access token, used solely to sign you in and upload to your Drive. These stay
  on your device.
- **Scheduled automatic backups:** if you turn on automatic backup and stay
  signed in, the app uploads a backup to your Drive on the schedule you choose
  (daily, weekly or monthly) without asking each time. The app keeps the newest
  five automatic backups in your Drive and deletes older automatic ones; backups
  you made manually are never auto-deleted. You can turn the schedule off at any
  time in Settings.
- **Your control:** you can back up, restore, list and delete backups from
  within the app, disconnect the account at any time, or delete the folder
  directly in Google Drive.
- **Backup contents are encrypted only if you have set a backup password** (see
  section 6). With a password set, the file uploaded to Drive is AES-256
  encrypted and Google cannot read its contents; without one, it is an
  unencrypted archive protected only by your Google account. Either way it is
  stored under Google's terms.
- Google's handling of your Drive data is governed by Google's Privacy Policy
  (https://policies.google.com/privacy).

**Limited Use disclosure:** 3D Printing Studio's use and transfer of information
received from Google APIs adheres to the Google API Services User Data Policy
(https://developers.google.com/terms/api-services-user-data-policy), including
its Limited Use requirements. We do not transfer, sell, or use Google user data
for advertising, and we do not allow humans to read it.

## 8. Account activation (optional)

Some features of the app are unlocked by activating your account. Activation is
optional — the app is fully usable without it, and until you choose to activate,
this section does not apply to you and no activation data leaves your device.

If you do activate:

- **You sign in with your own Google account.** We use your Google account
  **email address only**, for two purposes: to identify which account an
  activation belongs to (registration), and to send you a reminder when an
  activation is coming to an end. It is not used for anything else.
- **We do not use it for marketing.** We do not send newsletters, offers or
  promotions, we do not sell or rent it, we do not share it with advertisers,
  and we do not add it to any mailing list.
- **What is stored:** your email address, the activation's start and end dates,
  what the activation includes, and a **device identifier** for the device the
  activation is used on.
- **About the device identifier:** it is the identifier Android itself provides
  to an app for the device it is installed on. It is specific to this app on
  this device — other apps receive a different value, so it cannot be used to
  follow you across apps. It is **not** your phone number, IMEI, advertising ID
  or hardware serial number, and it carries no personal information. On a device
  that does not provide one, the app generates a random value instead.
- **Why it exists:** an activation is valid for one device at a time. The
  identifier is the only way to tell "the same phone checking again" from "a
  second phone", and it is used for nothing else.
- **What is not sent:** none of your business data — orders, customers,
  filament, prices, bank details or invoices — is ever transmitted during an
  activation check. Only the items listed above are.
- **Where it is stored:** in Google Firebase (Firestore), operated by Google.
  Google's handling of it is governed by Google's Privacy Policy
  (https://policies.google.com/privacy).
- **The narrowest sign-in available:** activation asks for your basic profile
  and email address, and no other permission. It does not request access to your
  Google Drive, Gmail, contacts or any other Google service.
- **How long it is kept:** for as long as the account is activated, plus a short
  period afterwards for support and renewal. You can ask us to delete your
  activation record at any time by emailing netsted.infotech@gmail.com; deletion
  ends the activation.
- **Your control:** you can disconnect the account at any time in Settings. The
  app keeps working, with the features that do not require activation.

**Limited Use disclosure:** our use and transfer of information received from
Google APIs adheres to the Google API Services User Data Policy, including its
Limited Use requirements.

## 9. Sharing invoices and exports

The app can generate a PDF invoice for an order and let you share it. Sharing
only ever happens when you tap to do it. When you do:

- The file is handed to the app you choose — for example WhatsApp, your email
  client, or the Android share sheet.
- An invoice contains the order details, the customer's name and contact
  information, your business details, and — if you have enabled them — your
  GSTIN and bank account details.
- CSV, JSON and SQLite exports contain your records in readable form, including
  customer contact details.
- Once handed over, the receiving app and service handle that file under *their*
  privacy policies, not ours. Please make sure you are comfortable with the app
  you send it through, and with the person receiving it.

## 10. Permissions the app requests

- **Contacts (read only):** used only for "Import from contacts" on the customer
  form, asked the first time you use that button and never at start-up.
  Read-only — the app cannot modify your contacts. See section 5. Declining is
  harmless.
- **Internet / network state:** used only for Google Drive backup and, if you
  activate your account, for the activation check. With neither in use, the app
  makes no network calls of its own.
- **Notifications:** to show the reminders you schedule.
- **Exact alarms:** so a reminder fires at the time you set rather than being
  delayed, and so a scheduled automatic backup runs at its set time (12:00 AM).
- **Run at startup:** so scheduled reminders and automatic backups survive a
  device restart.
- **Ignore battery optimizations (optional):** asked only when you turn on
  automatic backup. Battery savers can silently stop the scheduled midnight
  backup; granting this exemption keeps it running. You can decline — backups
  will then also run when you next open the app.

The app does not request access to your camera, microphone, location, photos,
SMS or call logs, and it never asks for permission to write to your contacts.

## 11. Data retention and deletion

- **Records in the app:** kept until you delete them. Deleted customers and
  filaments go to a recycle bin and can be restored from the Recover screen, or
  removed permanently.
- **Uninstalling the app** removes its local database, its stored logo and
  signature images, and its local backup files from your device.
- **Google Drive backups are NOT removed by uninstalling.** They remain in your
  Google Drive until you delete them — from the app, or from Drive directly. If
  you want them gone, delete them.
- **Files you exported or shared** (invoices, CSV or backup files sent to other
  apps or saved elsewhere) are outside the app's control and must be deleted by
  you wherever you put them.
- **On our side:** none of your business data — we never receive it. The only
  record we hold is the activation record described in section 8, and you can
  ask for that to be deleted at any time.

## 12. Data security

- **No transmission to us:** your business data never reaches a server we
  operate, because we operate none.
- **App-private storage:** the database and your logo and signature images live
  in the app's private directory, which other apps on the device cannot read.
- **Minimal cloud permission:** only `drive.file` — the app can never see the
  rest of your Drive.
- **No third-party analytics or trackers** are embedded in the app.
- **Optional AES-256 backup encryption:** setting a backup password encrypts all
  new `.abb` backups (section 6). JSON/SQLite/CSV exports remain unencrypted by
  design.
- **Android's own app-data backup is switched off** (`allowBackup=false`): the
  operating system is not allowed to copy the app's private database into its
  own cloud backup. The only copies of your data that leave the device are the
  ones this app makes under the rules above.
- The app has no screen lock or biometric lock. Your device's own lock screen is
  what protects the data on it. We recommend you use one.

No method of storage or transmission is completely secure, and we cannot
guarantee absolute security.

## 13. Third-party services

The app uses these third-party services, and only when you choose to use the
corresponding feature:

- **Google Sign-In** and the **Google Drive API** — for optional cloud backup
  (subject to Google's Privacy Policy).
- **Google Sign-In** and **Google Firebase (Firestore)** — for optional account
  activation, storing only your email address, the activation dates and what it
  includes, and a device identifier (section 8).
- **Your phone's address book** — read only, and only while you are using the
  contact picker (section 5).
- **Apps you share invoices or exports through** — e.g. WhatsApp or your email
  client (subject to their own privacy policies).

We do not sell, rent or share your data with anyone, and we do not use it for
advertising.

## 14. Children's privacy

3D Printing Studio is a business tool intended for adults running a 3D-printing
operation. It is not directed at children under 13, and we do not knowingly
collect data from children.

## 15. International users

The app runs entirely on your device, and none of your business data is
transferred internationally by us. If you enable Google Drive backup, or
activate your account, the data described in sections 7 and 8 is stored in
Google's infrastructure and Google's data-handling practices apply. Google
operates globally, so that data may be processed outside your country.

The app's tax features are built around Indian GST. If you operate elsewhere,
see section 18 — the figures are yours to verify in any case.

## 16. Changes to this document

We may update this document from time to time — for example when the app gains a
feature that handles data differently. Changes are reflected in the "Last
updated" date above, at the same address. Continued use of the app after a
change constitutes acceptance of the updated document.

---

# PART B — TERMS OF USE, DISCLAIMERS AND LEGAL NOTES

## 17. Your licence to use the app, and acceptable use

- You are granted a personal, non-exclusive, non-transferable, revocable licence
  to install and use the app for your own business. The app is licensed, not
  sold, and all intellectual property in it remains with the publisher.
- **The app is single-user and local.** It is designed for one operator on one
  device, and it does not synchronise between devices. Moving to a new device is
  done by taking a backup and restoring it (section 24).
- You may not resell, rent, sub-licence or redistribute the app; modify,
  reverse-engineer or decompile it except where the law expressly allows; or
  attempt to bypass, tamper with or defeat account activation, its device limit
  or its date checks.
- You may not use the app to create false, misleading or fraudulent documents,
  or for any unlawful purpose. What you enter, print and issue is your act, not
  ours.
- You are responsible for the accuracy of everything you enter, and for keeping
  your device, your Google account and your backup password secure.

## 18. GST and tax figures — you must verify them

**Please read this section carefully. It is the most important term in this
document.**

The app can put GST on an order and print a tax invoice. Every part of that is
**controlled solely by you**:

- **Whether GST applies at all.** GST is off until you switch it on, and each
  order carries its own on/off decision.
- **The rates.** The CGST, SGST and IGST percentages are values *you type into
  Settings*. The app does not know, look up, or update the rate that the law
  requires for what you sell.
- **Whether the tax is split as CGST + SGST or charged as IGST.** The app
  decides this by comparing two pieces of information *you* entered — your own
  state and the place of supply for that order. If either is missing, wrong or
  out of date, the split will be wrong, and the app has no way to know that.
- **Your GSTIN, your customer's GSTIN, the place of supply, the ship-to address,
  the HSN/SAC values, the invoice number series and prefix, the round-off, the
  discount, the margin and every charge line** — all entered and controlled by
  you.
- **What is taxed.** The app applies your rate to the pre-tax total, packing and
  delivery charges included. Whether that is the correct treatment for your
  business is a question for you and your tax adviser, not for the app.

**What the app does is arithmetic on the values you supply.** It does not know
your registration status, your turnover, your place of business, your customer's
status, which rate or exemption applies to what you sell, or how the law has
changed since the version you are running was released.

**Your responsibility, before you issue anything:**

- **Check every invoice before you send it** — the taxable value, the tax split,
  the rate, the place of supply, both GSTINs, the round-off and the final total.
- Satisfy yourself that the invoice meets whatever your law requires of a tax
  invoice, including its numbering and its sequence.
- Keep your rates and details current when the law changes. The app will keep
  using the numbers you last entered.

**The publisher is not responsible** for the GST or other tax charged,
collected, omitted, split, reported or printed by the app; for any change in GST
law, rates, classifications or filing requirements, or for the app not
reflecting such a change; or for any consequence of a wrong figure — including
penalties, interest, demands, notices, assessments, denied or reversed input tax
credit, rejected invoices, disputes with customers, or loss of any kind. **Those
options and values are under your sole control, and the responsibility for them
is yours.**

**This app is not tax, legal or accounting advice.** It is not accounting
software, it is not a GST return-filing tool, it does not connect to, file with
or upload anything to any tax portal, and it does not replace a qualified
professional. If you are unsure how tax applies to your business, consult a
chartered accountant or tax adviser.

## 19. Other figures the app calculates

The same principle applies to everything else the app works out for you —
pricing, printer running cost, packing, post-processing and delivery charges,
discounts, profit and margin, filament consumption and stock levels, the
investment ledger, and the analytics screen.

- Every one of those is derived from rates, weights, hours, costs and options
  **you** entered. A wrong input produces a wrong result, quietly and
  confidently.
- They are provided for your own convenience and internal use. **Verify anything
  you rely on for a commercial decision, a quotation, a bill or a filing.**
- The publisher gives no assurance that any calculated figure is fit for
  accounting, statutory, audit or reporting purposes, and accepts no
  responsibility for decisions taken on the basis of them.

## 20. Invoices are documents you issue

An invoice produced by the app is **your** commercial document. The publisher is
not a party to it, does not see it, does not store it, and has no involvement in
the transaction it records. Payment, delivery, refunds, warranties and disputes
with your customer are entirely between you and them.

Bank details printed on an invoice are the ones you entered, exactly as you
entered them. Check them: an incorrect account number or IFSC will send your
customer's payment to the wrong place, and that cannot be undone by us.

## 21. Account activation — how it works

This section covers the commercial side of activation. The privacy side is in
section 8.

- **The app is free to install and use.** Activation unlocks additional
  capabilities. There is no purchase inside the app.
- **Periods run on the calendar, not on usage.** An activation covers a fixed
  period and runs to the **end of its final day** — not to the clock time it was
  activated at. It continues to run whether or not you open the app, and unused
  time does not roll over or extend.
- **One device at a time.** An activation is tied to the first device that
  claims it. A second device is refused and falls back to the capabilities
  available without activation. Moving your activation to a new device — after a
  replacement, repair or reset — is a support request: email us and we will
  release it.
- **All payments are final and non-refundable.** Once an activation period
  has started it cannot be cancelled, paused, transferred or refunded in
  whole or in part — including for unused time, a period you forgot
  to use, a device you no longer own, or a change to what activation
  includes. Nothing here affects any refund right you have under applicable
  law, or under the terms of any store you obtained a period through.
- **We record when your activation began and when it ends**, so that both of us
  can see the same thing.
- **What we provide is activation, and only activation.** We do not host, store,
  process or have access to your business records at any point.
- **An activation ending takes nothing away from you.** Your records stay on
  your device, remain readable and remain editable; local backup, export,
  restore and invoice sharing keep working. Only the capabilities that require
  activation stop.

## 22. What activation includes may change

- **The publisher decides what activation includes.** The set of capabilities it
  unlocks, the limits that apply without it, the length and price of a period,
  and whether activation is offered at all may be introduced, changed, reduced
  or withdrawn at the publisher's sole discretion, with or without prior notice.
- **An activation already in force keeps what it was granted.** A change to what
  is offered does not reduce a period you have already paid for; your activation
  continues with the capabilities it was granted until its end date. Any change
  takes effect for you on your next renewal.
- **Features of the app itself may also change.** The publisher may add, alter
  or remove features, change how a calculation is presented, or stop supporting
  older versions or older Android releases, in the ordinary course of developing
  the app.
- **The app may be discontinued.** If the app or the activation service is
  withdrawn, no new activations will be issued and activations in force will not
  be renewed. Your data remains on your device and can be exported at any time —
  which is precisely why the app keeps export and local backup free in every
  state.

## 23. Availability, internet and device time

- The app runs offline and does not need a connection for day-to-day work. An
  activated account checks in periodically; if it cannot reach the network for an
  extended period, the activated capabilities pause until it can. Your records
  are never affected.
- **The device's own date and time must be correct.** Because activation runs on
  the calendar, the app detects a device clock that has been set backwards and
  blocks use until the date is corrected. Setting the date back to the correct
  value clears it immediately and nothing is lost. Keep automatic date and time
  switched on.
- We do not guarantee uninterrupted or error-free operation. Sign-in, Google
  Drive and Firebase are Google services and are outside our control.

## 24. Backups and data loss — read this before you update

**Your data lives on your device and nowhere else.** We operate no storage of
your business records and hold no copy. If your device is lost, stolen, reset,
damaged or replaced, **we cannot recover anything for you — we have nothing to
recover from.** Keeping backups is entirely your responsibility.

**Take a backup before:**

- **every app update**, including automatic ones from the store;
- an Android system update, a factory reset, or a device transfer;
- restoring an older backup over your current data;
- any bulk change or clean-up you are not certain about.

**How to keep yourself safe:**

- **Keep two copies:** a local `.abb` file saved somewhere off the device, and a
  Google Drive backup. One copy in one place is not a backup.
- **Test a restore occasionally.** A backup you have never restored is an
  assumption, not a safety net.
- **Store your backup password safely.** Without it, an encrypted backup cannot
  be opened by you, by us, by Google, or by anyone.
- **Do not rely on Android's own cloud backup.** It is deliberately switched off
  for this app (section 12), so the only backups that exist are the ones you
  make.
- Uninstalling removes the local database and local backups. Drive backups
  survive; files you exported elsewhere survive.

To the fullest extent permitted by law, **the publisher is not liable for any
loss, corruption or unavailability of your data**, however caused — device
failure or loss, uninstall, a system or app update, a restore, a forgotten
backup password, a Google account problem, or your own deletion.

## 25. No warranty

The app is provided **"as is" and "as available"**, without warranty of any
kind, express or implied, including any implied warranty of merchantability,
fitness for a particular purpose, accuracy, or non-infringement. We do not
warrant that the app will be error-free or uninterrupted, that defects will be
corrected, or that any figure it produces — tax, price, profit, stock or
otherwise — is accurate, complete or suitable for your purposes.

We do not commit to any timeframe for responding to, investigating or
resolving a bug, defect or support request, and we may decide not to fix a
given issue at all. Support is provided on a best-effort basis by email, and
whether, when and how an issue is addressed is at the publisher's sole
discretion.

Some jurisdictions do not allow the exclusion of certain warranties, so parts
of this section may not apply to you.

## 26. Limitation of liability

To the fullest extent permitted by law, the publisher shall not be liable for
any indirect, incidental, special, consequential, punitive or exemplary damages,
or for any loss of profit, revenue, business, goodwill, contracts, savings or
data, arising out of or in connection with the app or this document — whether in
contract, tort (including negligence), statute or otherwise, and whether or not
the publisher was advised of the possibility.

This includes, without limitation, any liability for: tax charged, collected,
omitted, mis-split or mis-reported (section 18); penalties, interest, notices or
denied input credit; incorrect prices, profits, margins or stock figures
(section 19); a mistaken invoice, bank detail or customer record; loss of or
inability to access your data (section 24); or any act or omission of Google or
any other third-party service.

Where liability cannot lawfully be excluded, the publisher's total aggregate
liability for all claims arising in any twelve-month period is limited to the
amount you actually paid for account activation in that period, or, if you have
paid nothing, to **INR 1,000**.

Nothing in this document excludes or limits liability for fraud, fraudulent
misrepresentation, death or personal injury caused by negligence, or any other
liability that cannot lawfully be excluded.

## 27. Your indemnity

You agree to indemnify and hold harmless the publisher against any claim,
demand, penalty, loss or expense (including reasonable legal costs) arising from
your use of the app, from the documents and figures you issue with it, from the
personal data of your customers that you record in it, or from your breach of
this document or of any law applicable to your business.

## 28. Governing law and jurisdiction

This document, and any dispute arising out of it or out of your use of the app,
is governed by the laws of **India**. The courts at **Trichy (Tiruchirappalli),
Tamil Nadu, India** shall have exclusive jurisdiction, save that nothing here
prevents a consumer from relying on any mandatory protection available to them
under the law of their place of residence.

## 29. General

- **Severability:** if any provision is found unenforceable, the rest remains in
  force and that provision is applied to the maximum extent permitted.
- **No waiver:** a delay in enforcing any right is not a waiver of it.
- **Entire agreement:** this document is the whole agreement between you and the
  publisher about the app, and replaces any earlier version of it.
- **Store terms also apply:** if you obtained the app through Google Play, that
  store's terms apply to your download and to any purchase made through it.
- **Changes:** this document may be updated as described in section 16. The
  current version always lives at the address below.

---

## Contact

For questions about this document, your data, account activation, or to request
deletion of an activation record or a device release:

**Developer:** NETSTED (Netsted Infotech)
**Email:** netsted.infotech@gmail.com
**Location:** Trichy, Tamil Nadu, India
**Online version:** https://gunapathi.github.io/policies/3d-printing-studio/privacy-policy.html

---

## Summary

- Your business data stays on your device — orders, customers, filament, prices,
  bank details and invoices are never sent to us.
- No analytics, no tracking, no ads.
- Contacts are read only when you use the importer, copied not linked, and never
  written to.
- Cloud backup is optional, goes to *your* Google Drive, and uses the narrowest
  possible permission.
- Account activation is optional and sends only your email address, the
  activation dates and a device identifier — used for registration and
  activation reminders, never for marketing.
- You can export, restore and delete everything yourself, activated or not.
- **GST is yours to verify.** The rates, the CGST/SGST/IGST choice, the states,
  the GSTINs and every option are entered and controlled by you — check every
  invoice before you issue it. The publisher is not responsible for tax figures,
  or for changes in tax law (section 18).
- Prices, profit, margin and stock figures are calculated from what you entered —
  verify anything you rely on (section 19).
- **Back up before every update**, keep a local copy and a Drive copy, and test a
  restore now and then — we hold no copy and cannot recover your data for you
  (section 24).
- A forgotten backup password cannot be recovered; CSV/JSON exports are always
  readable — keep them safe.
- You are responsible for the customer details you choose to store.
- Activation periods run to the end of their final day, cover one device at a
  time, and are not refundable once started except where the law or the store
  requires it (section 21).
- What activation includes is the publisher's decision and may change — an
  activation already running keeps what it was granted until it ends
  (section 22).

---

*3D Printing Studio — Privacy Policy & Terms of Use. Last updated 30 August
2026. © NETSTED (Netsted Infotech), Trichy, Tamil Nadu, India.*
