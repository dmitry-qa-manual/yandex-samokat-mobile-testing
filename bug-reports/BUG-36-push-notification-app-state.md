# BUG-36 — Push notification is not displayed in different application states

## Summary

The push notification reminding the user to complete the order is not displayed when the application is open, minimized or closed.

## Priority

**Standard**

## Status

**Open**

## Preconditions

1. A courier is authorized in the application.
2. There is an active unfinished order in the **My Orders** section.
3. Notifications are allowed for the application.
4. The order has a delivery date corresponding to the current day.

## Steps to Reproduce

1. Set the order delivery time to **21:59**.
2. Leave the Yandex Samokat application open.
3. Wait until 21:59 and check whether the push notification is displayed.
4. Repeat the test with the application minimized.
5. Repeat the test with the application closed.

## Expected Result

The push notification reminding the user to complete the order is displayed regardless of whether the application is open, minimized or closed.

## Actual Result

The push notification is not displayed when the application is open, minimized or closed.

## Environment

- Android Studio
- Google Pixel 7
- Android 13.0 Tiramisu
- Resolution: 1080×1920
- Yandex Samokat 2.0

## Additional Information

The defect was identified while testing push notifications in different application states.
