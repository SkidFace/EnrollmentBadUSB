# EnrollmentBadUSB
A simple BadUSB script that can save the valuable time and sanity of K-12 sysadmins and beyond when it comes to enrolling Chromebooks! Initially made on ChromeOS 114.0.5735.177, and verified working on 108 (Theoretically should work on 85 and above). 

## Why use this?
Are you tired of manually enrolling hundreds of Chromebooks, typing the same keystrokes and passwords over and over again? Look no further than this simple BadUSB script! 

## What is a "BadUSB"?
Typically, a BadUSB is plugged into a device, and then appears as a human input device (HID). This then is able to type things faster than humanly possible, and is usually used for malicous purposes. In this case, it is used to input the needed keystrokes to enroll a device. 

## How do I use this?
The text file, "Enrollment.txt" is in DuckyScript 1.0. This contains the keystrokes and delays to send to the computer. However, **this will not work out of the box.** You must edit a few things in the file first. Please read over each line beginning with "REM", as they are important comments documenting what to edit. For a TL;DR, edit the four lines ending in "!!!" with the wifi SSID/password and email/password that you use for enrollment. Make sure to increase the numbers after every "DELAY" if the Chromebook is a little slow. These are in milliseconds, not seconds. 

After you are satisied with the contents of the script, it is time to upload it to a BadUSB device! There are a few devices that are good for this, such as the classic [USB Rubberducky](https://shop.hak5.org/products/usb-rubber-ducky), Flipper Zero, or [Raspbery Pi Pico](https://github.com/dbisu/pico-ducky).

Plug your device in, sigh in relief, and watch the magic happen! (Or, cry and watch it mess up if there is tweaking that must be done)

If you have any problems or questions, don't hesitate to open an issue!

[![Video]](https://www.youtube.com/watch?v=Pasua64j3GA)
