# Kali-Nethunter-Redmi5A-Kernel
Optimized kernel for running Kali Nethunter on Redmi 5A. High performance, enhanced security features.

## Steps to Install Nethunter-Kernel on Redmi 5A

### Prerequisites:

1. Ensure that your Redmi 5A bootloader is unlocked.

2. If you have Oreo Redmi 5A (MIUI 11+), you must downgrade to Nougat (V10.1.1.0). Download the Nougat image from [xiaomirom.com](https://xiaomirom.com/en/download/redmi-5a-riva-stable-V10.1.1.0.NCKMIFI/) (Choose the fastboot version).
   don't forget to rename the downloaded file to .tgz

4. Install ADB tools from [forum.xda-developers.com](https://forum.xda-developers.com/attachments/adb-setup-1-4-3-zip.4623157/).

5. Download the official Xiaomi Flash Tool from [xiaomiflashtool.com](https://xiaomiflashtool.com/).

### Installation Steps:

1. Enter Fastboot mode on your Redmi 5A by pressing the Volume Down and Power buttons simultaneously for a few seconds.

2. Connect your Redmi 5A to your computer and open the official Xiaomi Flash Tool.

3. Click on "Refresh" in the flash tool to detect your phone. A random number will appear on the screen.

4. Select the downloaded "redmi-5a-riva-stable-V10.1.1.0.NCKMIFI" folder in the flash tool (choose the image, not the location).

5. Important: Click "CLEAN ALL" at the bottom right of the tool (ensure you don't select "CLEAN ALL AND LOCK").

6. Let the older Nougat version flash onto your Redmi 5A.

7. Your phone will restart automatically. Enter Fastboot mode again.

8. Install TWRP recovery for Nougat on your phone. Download "TWRP-3.2.3-1-Nougat-Riva.img" from my repository or from [androidfilehost.com](https://androidfilehost.com/?fid=1322778262904016475).

9. Copy "TWRP-3.2.3-1-Nougat-Riva.img" to a folder on your PC, open PowerShell in that folder (Shift + Right-click > Open PowerShell window here).

10. Ensure you have ADB tools installed. Type `fastboot devices` in the PowerShell window, and your phone should be listed (connected in Fastboot mode).

11. Flash TWRP: Type `fastboot flash recovery .\TWRP-3.2.3-1-Nougat-Riva.img`.

12. Reboot your phone into TWRP recovery by pressing Volume Up + Power buttons and releasing the Power button when the Fastboot screen disappears.

13. You should now see several options in TWRP. You can access your phone's storage from your PC.

14. Copy "Nethunter-Kernel-by-AkshatSingh.zip" to your phone.

15. In TWRP, click on "Install," select the "Nethunter-Kernel-by-AkshatSingh.zip" file, and flash it.

16. Congratulations! You have successfully installed Nethunter on your Redmi 5A!



# ⚠️ THIS KERNEL IS BROKEN  
**Please do NOT use this version.**  

✅ The latest working kernel is here:  
👉 [Nethunter-Kernel-Redmi5A-Riva](https://github.com/ShorterKing/Nethunter-Kernel-Redmi5A-Riva)
