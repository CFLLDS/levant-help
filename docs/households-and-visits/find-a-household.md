# Find a household and read its case

**Tab: Cases**

## Find the household

1. Select the **Cases** tab.
2. Type a name, a postcode or a case reference (for example `EW-CASE-000123`) in the **Search** box and select **Search**.
3. Use the filter buttons under the search box to narrow the list. Each button shows a count.
   - **All**: every open case.
   - **Live**: the home is on board and readings are arriving.
   - **Consent given**: the resident has signed, but the home is not live yet.
4. Select the household in the list. Its case opens on the right.

Closed cases (withdrawn, cancelled or consent refused) do not appear in the list. The list shows the first 100 matches, so narrow your search if you cannot see the one you want.

## What the case shows

| Field | Meaning |
|---|---|
| Status | Where the case is in its journey, for example consent given or live |
| Phone and Preferred contact | How the resident asked to be contacted. Always use their preferred route first |
| Next visit | Date, time, visit type, adviser and outcome of the most recent or next visit |
| Appointment letter | Whether the letter has been delivered |
| Adviser visits | How many visits have been made |
| Consent | One row per meter. Shows the state (given or withdrawn), how it was signed, the date signed, the date it runs to, and whether the data service has confirmed it |
| Visits | Every visit for this household with its date, type and outcome |

### How consent was signed

| Shown as | Meaning |
|---|---|
| qr_code | The resident scanned the QR code on their appointment letter |
| unique_code | The resident typed in the code from their letter |
| assisted_ihd | An adviser helped the resident in the home, using the in-home display |

### Data service column

| Shown as | Meaning |
|---|---|
| succeeded | Registered. Readings will arrive |
| not confirmed | Signed, but not yet confirmed by the data service. No readings yet |
| failed | The registration was rejected. Contact support |
| withdrawn | Consent has ended. Readings have stopped |
