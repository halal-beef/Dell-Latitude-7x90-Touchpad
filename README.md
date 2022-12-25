# Windows 7/8/8.1 Drivers For The ALPS Touchpads In The Dell Latitude 7x90, x = 2, 3 or 4

## Why did i do this?

For people who installed a windows version Dell says are "unsupported" they'll soon quickly realise the touchpad wont work at all in windows 7 or will work in windows 8.1 albiet very buggy if lucky

I wanted to help such people out


## What would i lose over the actual windows precision drivers if they were on windows 8/8.1?

Nothing really, at most probably like that cool zoom feature if you get what i mean

## Prerequisites

Make sure "Disable Driver Signature Enforcement" is enabled
Make sure you have the Intel Serial IO driver installed

## Tutorial

Download the repo, find the folder suitable to your windows version and then run "DPInst.exe"

Allow any unsigned driver installs

Finished :D

## If touchpad still doesnt work

Launch device manager

Press view tab and select "Devices by connection"

<img width="300" alt="path" src="https://user-images.githubusercontent.com/78730004/209479888-8ab27c6f-2a38-4ff3-a86d-f7e2d20be775.PNG">

Follow the path above

Click on a device and press details and press "Hardware IDs" under the dropdown menu

When you find a device that matches the id "HID\VEN_DELL&DEV_081B&Col03" go back to the "Driver" tab

Press update driver

Press "Let me pick from a list of device drivers on my computer"

If "Dell Touchpad" is there install it, if not follow on

Press "Have Disk..."

Change the path to the appropiate path for your operating system

Press next when you see the dell touchpad

Allow any unsigned driver installs

And now you're finished :D
