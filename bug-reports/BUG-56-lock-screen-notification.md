# BUG-56 — Push notification is not displayed on the lock screen

## Summary

The push notification is not displayed when the device screen is locked.

## Priority

Standard

## Status

Open

## Preconditions

1. A courier is authorized in the application.
2. There is an active unfinished order.
3. Notifications are allowed for the application.
4. The device is connected to the internet.
5. The device screen is locked.

## Steps to Reproduce

1. Lock the device screen.
2. Wait for the push notification related to the active order.
3. Check the lock screen.

## Expected Result

The push notification is displayed on the device lock screen.

## Actual Result

The push notification is not displayed on the lock screen.

## Environment

- Android Studio
- Google Pixel 7
- Android 13.0 Tiramisu
- Resolution: 1080×1920
- Yandex Samokat 2.0

## Additional Information

The defect was identified during testing of push notifications on the device lock screen.
