# BUG-001 — Gift Cards validation message

**Title:** Gift Cards section displays a generic coupon validation message

**Environment:** Google Chrome, Windows 11

**Module:** Shopping Cart → Gift Cards

**Preconditions:**
- A product has been added to the Shopping Cart.

**Steps to Reproduce:**
1. Open the Shopping Cart.
2. Locate the Gift Cards section.
3. Leave the gift card code field empty.
4. Click **Add gift card**.
5. Enter an invalid gift card code, for example `TEST123`.
6. Click **Add gift card** again.

**Actual Result:**

The following message appears below the Gift Cards section in both cases:

`The coupon code you entered couldn't be applied to your order`

The same message is displayed when an invalid code is entered in the Discount Code section.

**Expected Result:**

Not confirmed. The expected validation message for an invalid gift card code is unknown.

**Severity:** Not determined

**Priority:** Not determined

**Status:** Needs verification

**Note:** This is an unconfirmed potential bug, not a confirmed defect.
