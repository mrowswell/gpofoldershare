<h1>GPO Folder Share</h1>



<h2>Description</h2>
Step by step demonstration how to set up a Group Policy Object to access a shared folder.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
<br />
Start > group policy management:  <br/>
<img src="https://imagur.org/i/Mk8VSKoY" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
In group management, select desired organisational unit > right click > create a GPO in this domain: <br/>
<img src="https://imagur.org/i/OxFpQIPe" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name it map share drive: <br/>
<img src="https://imagur.org/i/Efi79cpM" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click > edit GPO:  <br/>
<img src="https://imagur.org/i/ImfeL7uq" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
User configuration > preferences > windows settings > drive maps:  <br/>
<img src="https://imagur.org/i/Am8Py3bK" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click > new mapped drive:  <br/>
<img src="https://imagur.org/i/YWag3zuo" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure: update > location > drive letter > check Reconnect:  <br/>
<img src="https://imagur.org/i/e9v73Opa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On the common tab, check run in logged-on user's security context > click ok:  <br/>
<img src="https://imagur.org/i/DowAGnTH" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirmation of new mapped drive:  <br/>
<img src="https://imagur.org/i/SPcDNadO" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
