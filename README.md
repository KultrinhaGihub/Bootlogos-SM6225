# Bootlogos-SM6225
For some reason, this has become a hobby. This is the Bootlogos repository for the **Devon, Hawao, and Rhode**, better known as **Moto G32, G42, and G52** phones. That's all I can describe for a README. Now, let's move on to the bootlogo previews of the ROMs.

| LineageOS | Evolution X | CrDroid |
| --- | --- | --- |
|  ![logo](https://github.com/user-attachments/assets/9f4c6ac2-562a-435f-8dad-41ddcbad5326) | ![logo](https://github.com/user-attachments/assets/9bd757ff-f504-4423-9ebf-458ab2c33fb8) | ![logo](https://github.com/user-attachments/assets/ddaa3e07-ea1b-4232-a885-414879973634)

| Murena OS (/e/OS) | LMODroid | CalyxOS |
| --- | --- | --- |
| ![logo](https://image2url.com/images/1762801076703-71cb05fa-4f1f-4438-9f1c-b987b7c4623a.png) | ![logo](https://image2url.com/images/1762801136407-19c9f135-e1c3-4a47-a009-1d1d31de323f.png) | ![logo](https://image2url.com/images/1762801375603-9a297cac-3355-46cf-a57e-7082a3dcdb9c.png) |

| HyperOS (Style 1) | HyperOS (Style 2) |
| --- | --- |
| ![logo](https://image2url.com/images/1762823896187-05584179-21e9-4e11-9ca2-dd3cddf2038e.png) | ![logo](https://image2url.com/images/1762823888045-0de6fcd0-2e87-4d73-a4f9-37fcb1a5879c.png) |

# Requirements
- Unlocked Bootloader
- PC or OTG with other phone (Use Bugjaeger)
- Android Platform Tools (with installed Motorola USB driver on Windows)

# How to flash?
1. Reboot the phone to fastboot/bootloader mode
2. Insert command to flash bootlogo
```bash
fastboot flash logo <path/to/logo.bin>
```
3. Reboot the phone