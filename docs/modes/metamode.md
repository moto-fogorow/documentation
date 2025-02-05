---
title: Meta
---

## Boot to META mode
### Using buttons
- Power off phone
- **Hold down the POWER & VOL- & VOL+ buttons** and connect the phone to the PC
### Using testpoint GPIO_META_DET
- Power off phone
- Short the [testpoint GPIO_META_DET](../dev/testpoints.mdx) to GND
- Connect the phone to the PC

## Phone management in META mode
Use the ```Android Utility``` program to control your phone in META mode. (See [Tools](../dev/tools.md))

You can restore nvram/nvdata partitions, etc.