# BUG-37 — Application crashes when opening from a push notification

## Summary

The Yandex Samokat application crashes when the user opens the application by tapping a push notification.

## Priority

**Critical**

## Status

**Open**

## Preconditions

1. A courier is authorized in the application.
2. There is an active unfinished order.
3. Notifications are allowed for the application.
4. A push notification related to the order has been received.

## Steps to Reproduce

1. Receive a push notification about the active order.
2. Tap the push notification.
3. Observe the application behavior.

## Expected Result

The Yandex Samokat application opens successfully and displays the relevant order information.

## Actual Result

The application crashes after tapping the push notification.

## Environment

- Android Studio
- Google Pixel 7
- Android 13.0 Tiramisu
- Resolution: 1080×1920
- Yandex Samokat 2.0

## Additional Information

The defect was identified during testing of navigation from a push notification.
