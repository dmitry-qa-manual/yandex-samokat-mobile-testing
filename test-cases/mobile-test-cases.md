# Yandex Samokat — Mobile Test Cases

## Overview

Test cases were created as part of the Yandex Practicum Software Testing diploma project.

The test cases cover push notifications, application states, notification permissions and network error handling.

## Test Cases

| ID | Test Case | Result | Bug |
|---|---|---|---|
| 1 | Получение push-уведомления в 21:58 | Passed | — |
| 2 | Получение push-уведомления в 21:59 | Failed | BUG-35 |
| 3 | Получение push-уведомления в 22:00 | Passed | — |
| 4 | Получение push-уведомления при заблокированном экране | Failed | BUG-56 |
| 5 | Получение push-уведомления при открытом приложении | Failed | BUG-36 |
| 6 | Получение push-уведомления при закрытом приложении | Failed | BUG-36 |
| 7 | Проверка push-уведомлений при запрещённых уведомлениях | Passed | — |
| 8 | Отображение заголовка push-уведомления | Passed | — |
| 9 | Отображение текста push-уведомления | Passed | — |
| 10 | Отображение адреса заказа в push-уведомлении | Passed | — |
| 11 | Отображение номера поддержки в push-уведомлении | Passed | — |
| 12 | Отображение иконки приложения в push-уведомлении | Passed | — |
| 13 | Отображение элементов push-уведомления | Passed | — |
| 14 | Переход в приложение по push-уведомлению | Failed | BUG-37 |
| 15 | Отображение окна об отсутствии интернет-соединения | Passed | — |
| 16 | Отображение заголовка окна отсутствия интернет-соединения | Passed | — |
| 17 | Отображение текста окна отсутствия интернет-соединения | Passed | — |
| 18 | Отображение кнопки «Ок» в окне отсутствия интернет-соединения | Passed | — |
| 19 | Закрытие окна отсутствия интернет-соединения | Passed | — |
| 20 | Повторное отображение окна при отсутствии интернет-соединения | Passed | — |
| 21 | Отображение элементов окна отсутствия интернет-соединения | Passed | — |

## Test Coverage

### Push Notifications

Tested:

- Receiving notifications at different times
- Notification behavior with the application open
- Notification behavior with the application minimized
- Notification behavior with the application closed
- Notification behavior on the device lock screen
- Notification permissions
- Notification title and text
- Notification icon
- Notification visual elements
- Navigation to the application after tapping a notification

### Network Error Handling

Tested:

- Display of the "No internet connection" message
- Error window title and text
- Availability of the "OK" button
- Closing the error window
- Repeated appearance of the error window
- Correct display of window elements

## Test Environment

- Android Studio
- Pixel 7
- Android 13.0 Tiramisu
- 1080×1920 resolution
- Yandex Samokat 2.0

## Results

21 test cases were executed.

Several defects were identified and documented in separate bug reports.
