<h1>Adding a computer to an existing domain</h1>



<h2>Description</h2>
Using JobSkillShare's virtual lab, I will be providing step-by-step instructions of how to take an unjoined local computer (PLABWIN101) and add it to an exisitng domain(PRACTICELABS.COM).If a computer is a part of domain, a domain will be listed.If not, you may see Window's default option: WORKGROUP. Unlike a domain, a WORKGROUP is a collection of unmanaged computers on a local network. It is important that we join PLABWIN101 on the domain so that it can use the services provided by our server (Windows Server 2019 Domain Controller).
<br />


<h2>Tools</h2>

- <b>Windows 10 standalone client workstation, PLABWIN101</b> 
- <b>Windows Server 2019 Domain Controller, PLABDC01</b>
- <b>Powershell

<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Program walk-through:</h2>

<p align="center">
Run Windows 10's command prompt on PLABWIN101 and type systeminfo: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Computer.  :  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
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
