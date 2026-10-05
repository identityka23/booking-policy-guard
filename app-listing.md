# App Market listing — copy draft (V1a)

**Name:** Booking Policy Guard
**Tagline (≤ 80 chars):** See what your cancellation and no-show policy really brings in.
**Category:** Booking tools / Analytics (confirm in Dev Center)

## Short description
Booking Policy Guard reads your Wix Bookings history and shows, in plain numbers, how much of your booking revenue is actually recorded, how often clients no-show or cancel, and which bookings can be analysed at all. Read-only: it never changes your site.

## What you get
- **Data health scan:** how many bookings carry a policy snapshot, how many have attendance marked.
- **Payment check:** attended bookings with no recorded payment in Wix.
- **Policy history:** how many different policy versions your bookings were made under.
- **Honest labels:** every observation is marked Measured or Unverified. Amounts are shown only when measured.

## Who it is for
Businesses that take one-on-one appointments in Wix Bookings and accept online payments (salons, spas, barbers, coaches).

## What it does not do (yet)
It does not change your policies, charge fees or refund anything. Recommendations for new policy values are planned for a later version, after enough data exists.

## Permissions explained
| Permission | Why |
|---|---|
| Read Bookings – Public Data | Read booking policies. |
| Read Bookings – Including Participants | Read bookings and attendance (names and contact details are not stored). |
| Read Orders | Read order totals, payments and refunds. |
| Manage Bookings Services and Settings | **Not needed for V1a.** Remove before publishing; it is reserved for a later, approval-based policy update feature. |

## FAQ
- **Does it send my data anywhere?** No. Records stay in your own site. [CONFIRM]
- **Can I delete what it stored?** Yes: Support and data → Delete stored data.
- **Why do some bookings not appear in the analysis?** Bookings created without an online order have no policy snapshot in Wix.
- **Is it free?** [CURRENT: free during the initial launch.]

## Support
[SUPPORT_EMAIL] — response within [X] business days.

## Pre-submission checklist (from the App Market review list)
- [ ] Only minimum permissions (remove `Manage Bookings Services and Settings` for V1a).
- [ ] Privacy Policy and Terms hosted on public HTTPS pages; URLs added to the listing.
- [ ] Support email and short user documentation.
- [ ] Missing-Bookings handling (done: friendly message).
- [ ] No `alert()`/`confirm()` (done: inline confirmation).
- [ ] Realistic first-run screen (done: Welcome card) — add screenshots to the listing.
- [ ] Install/Remove lifecycle tested; uninstall data behaviour confirmed.
