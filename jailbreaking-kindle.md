# Jailbreaking Kindle based on Generation

Note: Before you start, identify your device by following the instructions in [Identifying Kindle](identifying-kindle.md).

## Introduction

Jailbreaking is the process of removing the restrictions imposed by Amazon on your Kindle device. By jailbreaking your Kindle, you can install custom fonts, screensavers, applications, and other modifications that are not officially supported by Amazon. Jailbreaking also allows you to access the root file system of your Kindle, which gives you more control and flexibility over your device.

However, jailbreaking also has some drawbacks and risks. Jailbreaking may void your warranty and expose your device to security threats. Jailbreaking may also cause instability, errors, or bricking of your device if done incorrectly or if you install incompatible or malicious software. Therefore, you should only jailbreak your Kindle if you are confident and comfortable with the process and the consequences.

## Table of Contents

- [Kindle 1 (1st Generation)](#kindle-1st-generation)
- [Kindle 2 (2nd Generation)](#kindle-2-2nd-generation)
- [Kindle DX (2nd Generation)](#kindle-dx-2nd-generation)
- [Kindle DX Graphite (2nd Generation)](#kindle-dx-graphite-2nd-generation)
- [Kindle Keyboard (3rd Generation)](#kindle-keyboard-3rd-generation)
- [Kindle 4 (4th Generation)](#kindle-4-4th-generation)
- [Kindle Touch (4th Generation)](#kindle-touch-4th-generation)
- [Kindle 5 (5th Generation)](#kindle-5-5th-generation)
- [Kindle Paperwhite 1 (5th Generation)](#kindle-paperwhite-1-5th-generation)
- [Kindle Paperwhite 2 (6th Generation)](#kindle-paperwhite-2-6th-generation)
- [Kindle 7 (7th Generation)](#kindle-7-7th-generation)
- [Kindle Voyage (7th Generation)](#kindle-voyage-7th-generation)
- [Kindle Paperwhite 3 (7th Generation)](#kindle-paperwhite-3-7th-generation)
- [Kindle Oasis 1 (8th Generation)](#kindle-oasis-1-8th-generation)
- [Kindle Basic 2 (8th Generation)](#kindle-basic-2-8th-generation)
- [Kindle Oasis 2 (9th Generation)](#kindle-oasis-2-9th-generation)
- [Kindle Paperwhite 4 (10th Generation)](#kindle-paperwhite-4-10th-generation)
- [Kindle Basic 3 (10th Generation)](#kindle-basic-3-10th-generation)
- [Kindle Oasis 3 (10th Generation)](#kindle-oasis-3-10th-generation)
- [Kindle Paperwhite 5 (11th Generation)](#kindle-paperwhite-5-11th-generation)
- [Kindle Paperwhite 5 Signature Edition (11th Generation)](#kindle-paperwhite-5-signature-edition-11th-generation)
- [Kindle Basic 4 (11th Generation)](#kindle-basic-4-11th-generation)
- [Kindle Scribe (11th Generation)](#kindle-scribe-11th-generation)

## Kindle 1 (1st Generation)

## Kindle 2 (2nd Generation)

## Kindle DX (2nd Generation)

## Kindle DX Graphite (2nd Generation)

## Kindle Keyboard (3rd Generation)

## Kindle 4 (4th Generation)

### [Firmware Version](https://wiki.mobileread.com/wiki/Kindle4NTHacking) 4.0.0 - 4.1.4

1. [Download](https://www.mobileread.com/forums/attachment.php?attachmentid=141180&d=1439936080) and unzip the jailbreak.
2. Plug in the Kindle and copy the `data.tar.gz` & `ENABLE_DIAGS` files plus the `diagnostic_logs` folders to the Kindle's USB drive's root
3. Safely remove the USB cable and restart the Kindle (Menu -> Settings -> Menu -> Restart)
4. Once the device restarts into diagnostics mode, select "D) Exit, Reboot or Disable Diags" (using the 5-way keypad)
5. Select "R) Reboot System" and "Q) To continue" (following on-screen instructions, when it tells you to use 'FW Left' to select an option, it means left on the 5-way keypad)
6. Wait about 20 seconds: you should see the Jailbreak screen for a while, and the device should then restart normally
7. After the Kindle restarts, you should see a new book titled "You are Jailbroken", if you see this, the jailbreak has been successful.

## Kindle Touch (4th Generation)

## Kindle 5 (5th Generation)

## Kindle Paperwhite 1 (5th Generation)

## Kindle Paperwhite 2 (6th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.12.2.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Paperwhite 2 (6th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Basic 1 (7th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.12.2.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Basic 1 (7th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Voyage (7th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Voyage (7th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Paperwhite 3 (7th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Paperwhite 3 (7th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Oasis 1 (8th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Oasis 1 (8th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Basic 2 (8th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Basic 2 (8th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Oasis 2 (9th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Oasis 2 (9th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Paperwhite 4 (10th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Paperwhite 4 (10th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Basic 3 (10th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Basic 3 (10th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Oasis 3 (10th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Oasis 3 (10th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Paperwhite 5 (11th Generation)

### [Firmware Version](https://www.mobileread.com/forums/showthread.php?t=346037) 5.13.4, 5.13.5, 5.13.6, 5.13.7, 5.14.1.1, 5.14.2

#### Requirements

Before you start jailbreaking your Kindle, you will need the following:

- A Kindle Paperwhite 5 (11th Generation) with firmware version
- A computer with a USB port
- A USB cable compatible with your Kindle
- The Kindle Paperwhite 2 jailbreak [file](https://mega.nz/file/2ahlQKZS#jXyYLEp9rvRQCOzv7LNYBF-9fOfPhpigaLZMHZkN7fg)

#### Setup

1. Factory reset the device. **Make sure to use the "en_GB" or "English (United Kingdom)" locale when setting the language.**
2. Type ;enter_demo in the Kindle search bar after performing a factory reset. This will enable the "Demo" menu.
3. Reboot the device.
4. Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted.
5. Skip searching for a demo payload
6. Select the "standard" demo type
7. Press "Done" at the prompt to sideload content. **Do not sideload the jailbreak at this stage.**
8. Once the demo is setup, skip the misconfiguration lockout using the "secret gesture" (double finger tap on bottom right of screen then swipe left)
9. Enter the demo configuration menu by typing ;demo into the search bar
10. Select the "Sideload Content" option

#### Jailbreak

1. Connect the device to a PC and:
2. Create the directory `.demo` at the root of the Kindle storage
3. Copy `${YOUR_DEVICE}-${YOUR_FW_VERSION}.zip` to `.demo/`
4. Copy `demo.json` to `.demo/`
5. Create an empty folder at `.demo/goodreads`. Do not put any files in this folder.
6. Press "Done" at the prompt to install the jailbreak script
7. Exit the demo menu and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
8. If an application error occurs, hard reboot the device by holding the power button, enter the demo menu again and select Sideload Content -> Done once more without connecting to USB
9. Select "Help & User Guides" then "Get started"
10. If jailbreaking KT2 or PW2, select the store button instead
11. The device will reboot
12. The jailbreak script will run during the next boot

#### Post Jailbreak

1. After the device has rebooted, type `;uzb` into the search bar
2. Connect the device to a PC and copy `Update_hotfix_watchthis_custom.bin` to the root of the Kindle storage
3. Eject the device and either enter `;dsts` or swipe down and select the settings icon to enter the device settings menu
4. Select Update Your Kindle to install the custom hotfix
5. This will take your device out of demo mode, rebuild the application registry and clean up unneeded jailbreak files.

#### Troubleshooting

If you encounter any problems during or after the jailbreaking process, here are some possible solutions:

1. Alternative Demo Mode entry method:
   - Create an empty file named `DONT_CHECK_BATTERY` at the root of the Kindle USB storage
   - Activate demo mode by typing `;demo` into the search bar
   - Once in demo mode, skip setting up wifi and enter dummy values for store registration when prompted
2. If you need to reset your device whilst in Demo Mode, enter `;uzb` in the search bar to enable USB storage mode then create an empty file named `DO_FACTORY_RESTORE` at the root of the Kindle storage. Once this has been created, reboot the device.
3. [Video demonstration of secret gesture](https://www.youtube.com/shorts/JzuIGbGPpig)

## Kindle Paperwhite 5 Signature Edition (11th Generation)

## Kindle Basic 4 (11th Generation)

## Kindle Scribe (11th Generation)
