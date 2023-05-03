<p align="center">
 <img src="https://i.imgur.com/KYCbv8H.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Folder Encryption</h1>


<h2>Description</h2>
Get ready to secure your data with one of the most powerful encryption tools available in Windows operating systems: BitLocker! With BitLocker, you can encrypt your entire hard drive, preventing unauthorized access to your sensitive information, even in the event of theft or hard drive removal.

Now, not every version of Windows comes equipped with BitLocker - for example, the home version of Windows doesn't have it. But if you own Windows Pro or above, you likely have BitLocker preinstalled and just need a TPM module installed in your motherboard to get started.

In today's demo, we're going to show you how to enable BitLocker and take your data security to the next level. But first, we need to make sure our TPM module is enabled in the BIOS. Get ready to lock down your data like a pro!
<br />

<h2>Environments Used </h2>

 <b>Windows Server 2019 </b> <p>


<h2>Program walk-through:</h2>

<p align="center">


<br />
Your first step is to log into your EUFI-BIOS. Check your motherboard documentation or google how to log into yours. Look for TPM security and make sure it's selected for enable. Hit apply and reboot your system.
 <br/>
<img src="https://i.imgur.com/bDlsLhu.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Once you log into Windows, search or locate the control panel. Then select system and security.
 <br/>
<img src="https://i.imgur.com/OBC7u3x.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select BitLocker Drive Encryption.
 <br/>
<img src="https://i.imgur.com/AJKJXvA.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select Turn on Bitlocker.
<br/>
<img src="https://i.imgur.com/1dXsFAl.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select encrypt the entire drive.
 <br/>
<img src="https://i.imgur.com/15y0bK2.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select Start Encrypting.

 <br/>
<img src="https://i.imgur.com/fbmb4PZ.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
That's it! You're done. BitLocker is now enabled and the padlock now shows next to the encrypted drive.
 <br/>
<img src="https://i.imgur.com/F6YDJwp.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
I hope you enjoyed this demonstration.
 <br/>
<img src="https://i.imgur.com/uv6M2Pv.jpg" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
 
 
 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
