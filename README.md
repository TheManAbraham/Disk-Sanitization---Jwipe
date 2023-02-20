<h1>How to Wipe a Drive Using PowerShell</h1>


<h2>Description</h2>
You can use PowerShell to wipe drives on Windows 10.. Here's how you can wipe a drive for new data using PowerShell on Windows 10 step by step. I will format my flash drive as an example.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

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
<img src="https://i.imgur.com/qrU64Nu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Thirdly, select the disk:  <br/>
<img src="https://i.imgur.com/c2F5vLJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, To format the drive type in Clear-Disk -Number X -RemoveData replacing X with your drive number.
: <br/>
<img src="https://i.imgur.com/pYXphmI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Then type A to confirm and press enter:  <br/>
<img src="https://i.imgur.com/aCSKSGo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete and then you are done:  <br/>
<img src="https://i.imgur.com/kPWQ6Rd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

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
