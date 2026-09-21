# \[BUG\] Submit button stays disabled after filling out contact form

**Bug ID:** BUG-2026-101

**Date Reported:** September 21, 2026

**Reporter:** Jeff Wang

**Severity:** Low

**Priority:** P3 - Low

**Component:** UI / Contact Form

## 1. Description

On the Contact Us page, after filling out all required text fields (Name, Email, Message), the "Submit" button remains greyed out and disabled. The user cannot click the button to send the form.

## 2. Environment

* **Browser:** Google Chrome (153.0.8010.53)

* **Device:** MacOS (27.0 Golden Gate)

## 3. Steps to Reproduce

1. Go to the `Contact Us` page.
2. Enter a name in the **Name** field (e.g., "Jane Doe").
3. Enter a valid email address in the **Email** field (e.g., "jane@example.com").
4. Enter text in the **Message** box.
5. Look at the **Submit** button at the bottom of the form.

## 4. Expected Result

The **Submit** button should become clickable (blue and active) as soon as all required fields are filled out.

## 5. Actual Result

The **Submit** button remains disabled (greyed out) and cannot be clicked.

## 6. Workaround

No workarounds found.