<h1>JWipe - Disk Sanitization</h1>


<h2>Description</h2>
This project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
First, launch Powershell as an administrator via the start menu: <br/>
<img src="https://i.imgur.com/zD6FSTO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Second, type the command get-disk then press enter : <br/>
<img src="https://i.imgur.com/BZ7dimm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Thirdly, select the disk:  <br/>
<img src="https://i.imgur.com/hNGt41h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, To format the drive type in Clear-Disk -Number X -RemoveData replacing X with your drive number.
: <br/>
<img src="https://i.imgur.com/ZMkRKnO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Then type Y to confirm and press enter:  <br/>
<img src="https://i.imgur.com/gqM6LJH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now sanitization is complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Finally, observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
