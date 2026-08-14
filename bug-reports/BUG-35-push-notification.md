# BUG-35 — Push notification is not displayed at 21:59

## Summary

The push notification reminding the user to complete the order is not displayed at the expected time.

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

1. Set the device time so that the order delivery time is **21:59**.
2. Wait until 21:59.
3. Wait for the push notification to be received.

## Expected Result

A push notification reminding the user to complete the order is displayed.

## Actual Result

When 21:59 is reached, the push notification is not displayed.

## Environment

- Android Studio
- Google Pixel 7
- Android 13.0 Tiramisu
- Resolution: 1080×1920
- Yandex Samokat 2.0

## Additional Information

The defect was identified during testing of push notifications at different times.
