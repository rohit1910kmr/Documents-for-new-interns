# **Install Ubuntu desktop**<a id="docs-internal-guid-f5cc38ee-7fff-e6ae-c3ed-d742ccba4064"></a>

\



## **1. Overview**

### **What you’ll learn**

In this tutorial, we will guide you through the steps required to install Ubuntu Desktop on your laptop or PC.


### **What you’ll need**

- A laptop or PC with at least 25GB of storage space.

- A flash drive (12GB or above recommended).

If you are installing Ubuntu on a PC or laptop you have used previously, it is always recommended to back up your data before installation.

\
\
\
\
\
\
\
\
\
\



## **2. Download an Ubuntu Image**

You can download an Ubuntu image[ here](https://ubuntu.com/download/desktop). Make sure to save it to a memorable location on your PC! For this tutorial, we will use the Ubuntu 23.04 release which uses the new Ubuntu Desktop installer that will be included in all future Ubuntu releases.

If you are installing an older version of Ubuntu, such as Ubuntu 22.04 LTS, you will find that the visual presentation of the installer is different, but the overall flow should remain the same.

\


![](https://lh7-us.googleusercontent.com/q4wb3d9gGXnNc62kQQMzpeoxaoYJHSY_2fllIVfUDO2UV7o2xvT9YAg2OhWCV09DKvMmLy2qhIcUd760eJsri9UPCxZW6bKC7KRIkABLoyc2DmMltbx8o9l8nzOVzEnRlR7cASfma2Je8nY2P1UKkYI)

\
\
\
\
\
\
\
\
\
\



## **3. Create a Bootable USB stick**

To install Ubuntu Desktop, write your downloaded ISO to a USB stick to create the installation media. This is not the same as copying the ISO and requires some bespoke software.

For this tutorial, we’ll use[ balenaEtcher](https://etcher.balena.io/), as it runs on Linux, Windows and Mac OS. Choose the version that corresponds to your current operating system, and download and install the tool.

![](https://lh7-us.googleusercontent.com/-RK9sjjiaaK7W5JD87YTEoW5MGs1XBXS7fBrLSfdt3l4xC1tJnrbMw5Av72_4XGPR121lO9h_poQPz5_NTI9MDwCCqDqdgnH7WKxvhJgTJKc9B4_gJXi8M5xDpoLkZBFDGIzbbyrAqttYDyuf6MfOJA)

Select your downloaded ISO, choose your USB flash drive, and then click **Flash!** to install your image.

![](https://lh7-us.googleusercontent.com/nt_KX6U25um2hLHtsu0UTszZxNyZBEde-AnekkQ1y-T7Ag-L0kEFc2I5Zw9sZgrTsz7KiIrUYkcjfYZGN6-mmifmNIAwg5sefasXaLGBIovAmdkkiMMkW-_fjLb1A1HXEBrVu_F2T77kU1ykl4z2KCg)

\



## **4. Boot from a USB flash drive**

Insert the USB flash drive into the laptop or PC you want to use to install Ubuntu and boot or restart the device. It should recognise the installation media automatically. If not, try holding F12 during startup and selecting the USB device from the system-specific boot menu.

F12 is the most common key for bringing up your system’s boot menu, but Escape, F2 and F10 are common alternatives. If you’re unsure, look for a brief message when your system starts – this will often inform you of which key to press to bring up the boot menu.

Once the installer has initialized you will be invited to choose your language

![image](https://lh7-us.googleusercontent.com/EmMuz1HypAk0fW2t2wqHIU6RdItF7BpQ_XgEHa2htXmbeppSRESxJDu1BsH7lVu8dy36nxFI7xji6rAygD7R8yQfPfQ6VV_j36JSfzW0uz1QoBdqTN0XJWjmuGeygrtU8BKENOUra55E_MlQ0OB9o4U)

And then presented with the option to try or install Ubuntu.

![image](https://lh7-us.googleusercontent.com/tyqciWl8Fnm4ndLWKWOgLq8JBxkSoNErr2XSlmYImHAPfQm0o0B7THKTb8pg22TM2M39A6TMwFxlM4QZnmNY6daQyD7i8kN_VGowKGfY3Rfvoaty1fWehxcCTI-HATrSooX-p01m9htUBWs6ImMAlQQ)

If you click **Try Ubuntu**, you can preview Ubuntu without making any changes to your PC. You can return to the installer menu at any time by clicking the **Install Ubuntu** shortcut on the desktop.

To proceed, click **Install Ubuntu**.

You will be asked to select your keyboard layout. Once you’ve chosen one, click **Continue**.

![image](https://lh7-us.googleusercontent.com/ZDK8Taiy4oYtqlQFAxNeASsU2erfUwznGUC0bdGwGKxIF-dmu9m0X0TtdUftn4UTJF5_jnJTb91Zz3Yh_wXbbPJiWmXknGssr1wyMReTeTyjdw5AYm6aH1_N8aWLHwclcqUhJygQkqUb7vALspPGYa8)

Next, you will be asked to connect to wi-fi, this will allow Ubuntu to download updates and third-party drivers (such as NVIDIA graphics drivers) during installation. Once you have connected to wi-fi (or chosen to proceed offline) then we can continue to the installation setup.


### **(Alert) RST is enabled**

Some PCs use Intel RST (Rapid Storage Technology) which is not supported by Ubuntu. If this is the case then you will not be able to proceed beyond this point without disabling RST in the bios menu of your machine. If you encounter this pop-up please visit[ help.ubuntu.com/rst](https://help.ubuntu.com/rst/) for more information.

![image](https://lh7-us.googleusercontent.com/OHvr6ixsHGM21_8Ny2JZZfG93rVueOI_w10SS1Xb_MeXtI7qIwIR2Q-6y3EAsKMjOaPsyNdhKtmZyGyvqABV0yJFJq0PFQIVTaHJfjIAxtb4MV8b952fEBzkYsycN4yrJcBGayDFozsnw5ZhkpJt0yo)

***


## **5. Installation Setup**

You will be prompted to choose between the **Normal installation** and **Minimal installation** options. The minimal installation is useful for those with smaller hard drives or who don’t require as many pre-installed applications.

In **Other options**, you will be prompted to download updates as well as third-party software that may improve device support and performance (for example, Nvidia graphics drivers) during the installation. It is recommended to check both of these boxes.

![image](https://lh7-us.googleusercontent.com/N8joP05GApooJctBB0Uezj23-m1i94ULRdfQ_JEyT0npahMjIdl8URtedYXu16VhVL7HvpqBBA0fmuGaTFrnmVod__XRAvhN4MbWP3kQOHD3NpU51YrimE86X58IZD4zLcHb5cLQ6VqSrrqlZbcswp4)

\



## **6. Type of installation**

This screen allows you to configure your installation. If you would like Ubuntu to be the only operating system on your hard drive, select **Erase disk and install Ubuntu**.

If your device currently has another operating system installed, you will receive additional options to install Ubuntu alongside that OS rather than replacing it.

![image](https://lh7-us.googleusercontent.com/RudAwqmhesM7bBZVySKsYpPhMjiwdQViF6RQZYE4lI1VYXMGt7-Lz6Gp8N8zS7Z3ZnZ_fU3UibsgOgrmF9IdorV85QrYr--MNAJ8N21GqlFHKxWtdztYA1m7ct2rtrOLUK3A57p-PFygicypmxhBpQA)

Let’s take a moment to review all of the above options in detail.


### **Installing Ubuntu alongside another operating system**

If you select this option you will be given a simple interface that allows you to select the drive you want to install Ubuntu on and a slider to determine the amount of disk space you would like Ubuntu to use. The available space is limited by the existing contents of the disk and is designed to avoid overwriting existing files.

This view automatically selects the largest partition on the drive. For more fine-grained control you can switch to the _Manual partitioning_ option that is detailed further down.

![image](https://lh7-us.googleusercontent.com/EScZjuOXo7g_wyzbeGoMzvb_YqOnRbYazf0yvNb19GgN22ri4WCtyTGnL28X-H01L0MCDSeGY9f9-eiBdzawmPlnOckEdpMN-TaoAcPXC2cYiO6a7ILUJPhDHaCakooaytsqhu-NYqgvF_Ctx-ncZIA)


### **Erase the disk and install Ubuntu**

If you select this option Ubuntu will take up the entire disk space on the selected drive.

![image](https://lh7-us.googleusercontent.com/yi8yph37ra8UErJsaJfWMcj47JoWcUusHrP8cAVvDB1QQ7ZkzwwDVErFmaqGPjoK8UtXX8K3QSDi2seETFUMnqUsF_bJBCIUXH3-UHB3l87RAh6iw_NJIRfr5wFEGwhmdRGaZ209P_jGUGcEyVSGKps)

If your PC has multiple hard drives then this option allows you to install Ubuntu alongside an existing OS as long as they each have their drive. Take care to ensure that you are selecting the right drive in this instance!

This option also allows you to encrypt your entire drive using LVM. To do this open the Advanced features option before proceeding to the above screen and select ‘Encrypt the new Ubuntu installation for security’

![image](https://lh7-us.googleusercontent.com/Yvcj4lPmBsxT40MoWWL00cPE0m4-IP0TwQ301GaIWv4S0LV70tn4091cmkwNByDAns3xhccoMGPNwaINz_BF_xKpNIvl5MvFdMATTusHgk6ksotfDONawxCNy_Xx35wenaNZqyc2j5ryMp3tnp53ur0)

LVM stands for Logical Volume Management. By using LVM during the setup, it makes it easier to create and manage partitions post-installation.

In the following step, you will be prompted to create a Security key that you will need to enter on boot before logging in with your user credentials.

![image](https://lh7-us.googleusercontent.com/ZK5khEbJQ64LO4mm6VbGVJJtb3c-ADZUroJdMPxaX3MR8P0vC7u7hIYbvETn6CAkwMEyxjkGeipILjrJK_Daag-ji1s5asAQSzMkuVLGeq0DkLu5mn6AKtTcFblzQW59Vkzqdfq7aFiNHDDN_QBo18I)

If you select encryption, you mustn't lose your security key! Write it down and store it in a safe place outside of your local system. **You will not be able to recover your data without it!**


### **Manual partitioning**

Manual partitioning is designed for advanced users who want to create specific configurations for their use cases. As such we assume that these users will be comfortable with this interface and will not go into detail during this tutorial on specific setups.

Here users can see all existing drives and partitions and create and manage new partition tables and configurations.

![image](https://lh7-us.googleusercontent.com/9uz-2ZLoyr5zmtKoVlMX0p26QePt-5eZUBzU8zvJo9BmDxpt3pbPztpEWKq1ySL3GkLIh19fQS5bJEIheNoH0LB63UcmHsunYZw5rzRwyc71uVEQ1jzOExo7U9WRngisNwt3oGsCvN807Fxh8EI6Bcc)


### **(Alert) Windows BitLocker is enabled**

If your device has Windows BitLocker Drive Encryption enabled then Ubuntu will not be able to gather the drive information it needs to install Ubuntu safely alongside Windows.

If this is the case you will get a prompt to disable BitLocker in Windows before restarting the Ubuntu installer.

![image](https://lh7-us.googleusercontent.com/15UM-IO1ghQCji0wPCbCvgkB66Wd7gG_eJh-Syay9nqj6ZynZRZp6ZBoToWGv3AKM53jVxVaOXrf6ITfn1bFn2rOJ1CL7O4PvNdYtDABgLhkW0VfdQdulTErXK4hRpzVJt9Remth-hMfiq6VOyTwMSQ)

Disabling Windows BitLocker is not required when fully erasing Windows or when there is a separate, unencrypted drive available for Ubuntu. For more information see the final section at the end of this tutorial.

\
\



## **7. Ready to install**

Regardless of the option you select, clicking **Next** will take you to a summary of your installation configuration to give you a chance to confirm your setup before clicking **Install**

****![image](https://lh7-us.googleusercontent.com/hkRXWr3j-JPshGbALGmkGw8od5AmDOS-BT_mR_hdgfnrG2Sk40uJgRNF2cVTvmw8Z6unZsS52Jt_oR3T_CGV3-CMTo1FNaamiYB1w8f5-SsWlTw9OeGxzbnmh2MXsfd_u4RIeSUw9v23tN_QcOK6LW4)****

Once you proceed, Ubuntu will begin the installation process in the background and you will not be able to return to this point.

\
\



## **8. Choose your Location**

Select your location and timezone from the map screen and click **Continue**. This information will be detected automatically if you are connected to the internet.

![image](https://lh7-us.googleusercontent.com/pW6IA6MhPVvAD16Hf8kVMgxX0bgP_FdVnrg9qWJeQ5DQlAYWQkBxDj3Rv6GhQadcpP5bNxAlRHwqprlNDBCiTS5kplfsitoF5thaEXERcUDzuFgRwQhjgm4Bd1xpEF9ezXDPNtqlvy1qszXHoGtAvF0)

***

 \



## **9. Create Your Login Details**

On this screen, you will be prompted to enter your name and the name of your computer as it will appear on the network. Finally, you will create a username and a strong password.

You can choose to log in automatically or require a password. If you are using your device whilst travelling, it’s recommended to keep “Require my password to log in” enabled.

![image](https://lh7-us.googleusercontent.com/zfljFv1Z6meUeJLVSO9r0Hr2886T4bKc56aVo1jMtKyhGxp-G1dOCXxnBsuEURNfcATKd849vLlEDqyrDC6_k58My5A1k9qrvFg4uO3HT5ainAN6SP8KoqKq9nY_5vEOLLPJcclAeC5dbk00cc1uiRg)

\



## **10. Complete the Installation**

Finally, you can choose to switch your desktop from Light to Dark theme.

![image](https://lh7-us.googleusercontent.com/qeSMYSrrwkXq_sD4XUVJzK0cGy0mwALANn-veO5iQBbKP5-aSwEpCohvMJH3m79Mq-mq43uYuuYK-1LNWKxKYvupDwzAEmOdXQFcAHdD_MRYUBE48MzrwL0KvyA-fJ_0HyU3c_V-UOaw2kL_5_X6KhI)

And then sit back and enjoy the slideshow as Ubuntu installs in the background! ![:slight\_smile:](https://lh7-us.googleusercontent.com/lpr8AYZAoX6VP5a5pHHyQ5xAVgVj3xHahdy9Z5hUkeXfY3P7fTTSdT6h0V1WfndND4L5pLUh6xlq50_CaiLFY-XhB5X5WBxVpmbUfG4NCOyzPvvSTUmXGWtjPDwtfjCuH17GhDo_wKATZIHUXBSEnAk ":slight_smile:")

![image](https://lh7-us.googleusercontent.com/HGFsiZ6bYy_fMDzdbReIsdz8Mjq6I3DXBNgyjsyKfo8FQbRWCBiGm5Wv9EzJn9kkGeVbMVWywDJ6fcLyilbxHONwkdmYRvyYzbfYCQEf-p-XoYHLkzCaFjWmioPljxgm6LlJHMB25Dx_2m9myPYmtMM)

Once the installation has been completed, you will be prompted to restart your machine.

Click **Restart Now**.

![image](https://lh7-us.googleusercontent.com/eZzhm7bjTN5lN_uHWlbdHOh90Uu95pvFZ9qXxzMM_sQB7BaJOHfXUdNZ5qwRxJM674haA7QSbC6B-NogXVK1EsOpiXQiq1GKtAnzz7YsfWMMH6PJrVKtyLWV9ITC3ujXRM9kIaRbwdX4pzZYv3Eo26s)

When you restart, you will be prompted to remove your USB flash drive from the device. Once you’ve done this, press **ENTER**.

Enter your encryption password if you created one, followed by your user password on the login screen.

And that’s it, welcome to your new Ubuntu Desktop!

![Desktop Dark](https://lh7-us.googleusercontent.com/tSFPwjcuv4qyyHhr4qb_9y1WmKEvqRlXbTWF2mhJT2LI_RZ836n4jd8scQk-xwUruCIZiViCZxmNhm-Api7Eezk4MDk0jNIE_qjVMfh1G7MAsYy7s_izwQhLySj4ieaDOsx12hFNazfOf98dc9xdig8)

The welcome widget will help you with some additional setup options, including:

- Connecting your profile to various online accounts.

- Attach an[ Ubuntu Pro](https://ubuntu.com/pro) free personal or paid subscription to apply additional security patches to your device (this option is only available when using a long-term support \[LTS] version of Ubuntu).

- Opting into sending device information to Canonical to help improve Ubuntu (by default, Canonical doesn’t collect device information).

- Activating location services.

- Downloading additional apps from Ubuntu Software.

***

 \
\



## **11. Don’t forget to Update!**

It’s always good practice to ensure your system is up to date, especially after a fresh install.

The easiest way to do this is via the **Software Updater** app. Search for Software Updater via the app menu (the icon with 9 squares in the bottom corner of your window) and it will check for updates and apply them.

![](https://lh7-us.googleusercontent.com/S3JSkkf4zOcYV2lGTJm2g1LYUe6TOSFc_H586IglBFjdfqGuZFPF5vDdi4YmNEKB-D7s_T-pHDuySpBrtnmvAe3S2xTsDiofHnnWP7YiWvHaojle-67rqKwMrzUkiw-1Td9jTzx-U7uH4rY_EouqEII)

You can also update Ubuntu using the terminal.

Press **CTRL+ALT+T** to bring up a Terminal window (or click the terminal icon in the sidebar).

Type in:

    sudo apt update

You will be prompted to enter your login password.

This will check for updates and tell you if any need to apply. To apply any updates, type:

    sudo apt upgrade

Type **Y**, then press **ENTER** to confirm to finish the update process.

***

 


## **12. You’ve installed Ubuntu!**

Thank you for completing this tutorial. We hope you enjoy your new desktop.

Check out our picks for[ the Top 10 apps for a fresh Linux install in 2021](https://ubuntu.com/blog/top-10-apps-for-a-fresh-linux-install-in-2021).

If you have any issues, please contact us via the[ Ubuntu Discourse](https://discourse.ubuntu.com/), or visit[ Ask Ubuntu](https://askubuntu.com/).

You can also read the latest news about Ubuntu Desktop on the[ Ubuntu Blog](https://ubuntu.com/blog/desktop).

As a next step, why not try:

- [Installing Ubuntu Desktop on a Raspberry Pi 4](https://ubuntu.com/tutorials/how-to-install-ubuntu-desktop-on-raspberry-pi-4#1-overview)

- [Using VirtualBox to try out different Ubuntu flavours](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview)

For users who need to run both Ubuntu and Windows, you can also install Ubuntu via Windows Subsystem for Linux (WSL).

- [Install Ubuntu on Windows Subsystem for Linux (WSL)](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support#1-overview)

\
\



## **13. (Additional) Installing Ubuntu alongside Windows with BitLocker**

During the installation type step, you may find that you are unable to proceed with the installation without first deactivating Windows Bitlocker.

![image](https://lh7-us.googleusercontent.com/787EJShdTVGOrNlrFQgGwHmtSEbaeamV8nNJyjuIqyYo5Y_iYocBy-9nnSMATQQO-Cd-a2GHJ6QF7P6vMNVhK8kdMiLu46kvltoZgUFIOPSdx91p0we1SZZUlnpEzYXOYzccRNAY9vWpg1y1CjQ9KVo)

[BitLocker Drive Encryption](https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-overview) is a data protection feature that integrates with the Windows operating system. When activated, it will encrypt the contents of the hard drives in Windows, making the data inaccessible without the correct decryption key. It is designed to minimise the risk of data theft or exposure from lost or stolen computers.

When a user starts their computer and properly authenticates with the correct credentials, BitLocker will decrypt the data and allow seamless usage of the hard drive and the data it contains. Without the correct credentials, the encrypted hard drive data will look like random noise.


### **BitLocker & Ubuntu installation**

If you plan to install Ubuntu side by side with Windows, you need to take into consideration the operational setup on your computer.

- If you are not using BitLocker, Ubuntu will be able to see the correct hard drive structure, including any partitions and data stored on it. This allows the guided wizard to correctly map the data, and safely make adjustments to accommodate the additional installation of Ubuntu alongside Windows.

- If you are using BitLocker, the hard drive contents will not be accessible, and they will appear as random noise. This means that the Ubuntu installer cannot correctly map data, and the additional installation cannot be safely performed without data loss… Additionally, some manufacturers ship systems with BitLocker enabled but the hard drive contents are not yet encrypted. In this case, the Ubuntu installer will also not be able to correctly map data.

You can:

- Cancel the installation of Ubuntu and continue using Windows only.

- Decide that the data stored in Windows is not important and that you are willing to overwrite the data contents. The Ubuntu installer can then erase the entire contents of the hard drive and create its structure (partitions and data). This is a destructive operation, with no option to recover any Windows data.

- Decide to turn BitLocker off. This will turn off the encryption feature, and the hard drive and its data will be visible and accessible from the Ubuntu installer, allowing it to correctly and safely set up a side-by-side configuration. For systems with BitLocker enabled but not yet encrypted you will need to first turn BitLocker on and then turn it off.

- **Note:** Not all versions of Windows will allow you to re-enable BitLocker after disabling it. If you wish to re-encrypt your Windows partition after installing Ubuntu alongside it, please check that your version of Windows supports this.


### **Turn BitLocker off**

If you decide to proceed with the third option, you will need to do the following:

- Back your data up - any encryption procedure, hard drive structure change or installation of new operating systems on a hard drive that already contains data can potentially lead to a data loss. You need to make sure your data is safe. Even simply copying the important files to an external drive can minimize the risk of data loss.

- Quit the Ubuntu installer and reboot the computer into Windows.

- In Windows, open Settings > type Manage BitLocker in the search box. Alternatively, open Control Panel > System and Security > BitLocker Drive Encryption.

![bitlocker-turn-off](https://lh7-us.googleusercontent.com/D8LhiOWxmME9T7gUCdbzhGqmJhLkixqCu7gnP5JB6RUZztCEL8HJa7ImGvQpx6xc5O2GJbp5HJRxR9WBkJlGwa5K4SnipwaY3kk0Dub-6mHFUGsGx1z2h2fJmewyjUVBuMYdYt-Ef2vkLMZPiMMHRlY)

Windows will now inform you that it is going to decrypt the data.

![bitlocker-decryption-warning](https://lh7-us.googleusercontent.com/yaGyvkiHg9PNQkjTCi7UbU0k18ov_ymi617kWilY2OkmnAdjXujPCfo2hDM2l5PnXrTtgIGKrlaQ6i1uhmheAyvW9rPoQsaWrfx0opOAaIij99ryBd7EPiw2m7K43nnthf2tu0jj1CHeoGjfGDNZNPM)

This process can take a little bit of time:

![bitlocker-decrypting](https://lh7-us.googleusercontent.com/6O6sEgQBlOBhzPd202A_t5SSthM0vYEWwXlGYmaSctx1mw6URu6wbbLRTMgzOxiLLotpn0XxSbsiDMFdj5ic36y_rdND3Yme-h4hvVSmDt-YBOIeDvUaN5MhT2ShcIMb2GmPFERgZ_Omipn649FCnY8)

![bitlocker-decryption-complete](https://lh7-us.googleusercontent.com/OwcZ8V1JYLPuobofS-cfA4cJDUPUADv1DQhtwpmj4CAhup2hF_Ey8qVFgQRkrKlDoeKgDlvC20sR5YZAeNa5HKGPCLo3ZTn4w5e7BtRTEyYps61J4SSwvdFUX0c3iAtsxRPX26Am5Wi7xSL25V2GH-U)

- Once this step is complete, reboot the computer, and log into Windows, to make sure everything works correctly, and that all your data is intact.

- Reboot your computer again, and launch the Ubuntu installer. At this point, you will be able to proceed with the hard disk configuration step.
