# 3D Printing Studio — GST Policy

**Publisher:** NETSTED (Netsted Infotech), Trichy, Tamil Nadu, India
**Contact:** netsted.infotech@gmail.com
**Applies to:** 3D Printing Studio version 3.5.3 and later
**Last updated:** 18 September 2026

---

**This is a short summary, written for the moment you switch GST on.** The full
and binding terms are **section 18 of the
[Privacy Policy & Terms of Use](privacy-policy.md)** — *"GST and tax figures —
you must verify them"*. Where this page and section 18 differ, **section 18
applies**. Nothing here replaces it, narrows it or adds to it.

---

## 1. The figures on your invoice are yours

3D Printing Studio does arithmetic on the values **you** type in. It does not
look anything up, does not connect to any tax portal, and does not check
anything with any tax authority.

You enter, and you are responsible for:

- your **GSTIN**, your business name, address and state
- the **CGST, SGST and IGST percentages**
- whether GST applies to a given order at all
- your customer's GSTIN, the place of supply and the ship-to address
- the HSN / SAC values, the discount, the margin and every charge line

The app compares your state with the place of supply to decide whether tax is
split as **CGST + SGST** or charged as **IGST**. If either value is missing,
wrong or out of date, that split will be wrong, and the app has no way to know.

## 2. What the app checks, and what that check is not

From version 3.5.3 the app will not let you switch GST on until it has a GSTIN
that is **shaped** like a GSTIN, a business name, an address, a state, and at
least one rate above zero. It also checks that the first two digits of your
GSTIN match the state you selected.

⚠️ **This is a completeness check, not a verification.** It confirms the fields
are filled and internally consistent. It does **not** confirm that the GSTIN is
real, that it is yours, that it is active, or that the rate you entered is the
right rate for what you sell. A GSTIN that is well-formed and wrong will pass.

## 3. Invoice numbering

Documents are numbered in two consecutive series per financial year — one for
tax invoices and one for documents that carry no GST — in the format
`GST/2627/00001`, within the sixteen characters Rule 46(b) allows.

**What a non-GST document is called is your choice**, set in
**Settings → Orders**. Under Rule 49 a *Bill of Supply* is a registered
person's document, for exempt, nil-rated or non-taxable supplies, or under the
composition scheme. The app cannot tell which of those applies to you, so it
offers a sensible default and leaves the decision to you and your accountant.

A serial, once issued, never changes. Cancelling an order does not release its
number — gaps in a series are normal, and a cancelled invoice is answered with a
credit note, not by reusing the number.

## 4. Before you send anything

- **Check every invoice** — the taxable value, the tax split, the rate, the
  place of supply, both GSTINs, the round-off and the total.
- Satisfy yourself it meets what the law requires of a tax invoice, including
  its numbering and sequence.
- Keep your rates and details current. The app keeps using what you last
  entered.

## 5. Responsibility

**The publisher is not responsible** for tax charged, collected, omitted,
split, reported or printed by the app; for changes in GST law, rates or filing
requirements; or for any consequence of a wrong figure — including penalties,
interest, demands, notices, assessments, denied or reversed input tax credit,
rejected invoices or disputes with customers. Those values are under your sole
control.

**This app is not tax, legal or accounting advice.** It is not accounting
software, it is not a return-filing tool, and it does not replace a qualified
professional. If you are unsure how tax applies to your business, consult a
chartered accountant or tax adviser.

The full terms are in **section 18** of the
[Privacy Policy & Terms of Use](privacy-policy.md).
