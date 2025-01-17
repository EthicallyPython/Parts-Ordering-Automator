# Parts-Ordering-Automator
This project is licensed under the terms of the MIT license. View the license [here](https://github.com/Vomet/Parts-Ordering-Automator/blob/main/LICENSE.txt).

For use in a specific Microsoft Access Database template.

## Prerequisites
1. Download latest version of [AutoHotKey](https://www.autohotkey.com/). Note, the [portable version](https://www.autohotkey.com/download/) is recommended.
2. Download this [repository](https://github.com/Vomet/Parts-Ordering-Automator/) as a ZIP file.
3. Extract ZIP file.
4. Run in AutoHotKey.

## Instructions
1. Ensure AutoHotKey is running. If portable, open the `.ahk` file with `AutoHotKeyU64.exe`.
2. Open `Parts Ordering.ahk`.
3. Ensure coordinates work on your computer. If not, use `WindowSpy.exe` in `AutoHotKey.zip`


### Hotkeys
`F1`: Clicks "New Order" button

`F2`: Clicks "New Product" tab and selects dropdown

`F3`: Clicks "Shipping Info" tab and selects dropdown

`F4`:
  1. Clicks and completes "Payment Info" tab
  2. Completes "Invoice Order", "Ship Order", "Mark as Complete", and (planned) clicks "New Order" button

`F5`: Stops program (by refreshing script)


## Potential Issues
This script moves the mouse and presses keys. It is recommended to press each function key in sequential order (`F1`, `F2`, `F3`, `F4`). Pressing keys out of order may result in errors.
