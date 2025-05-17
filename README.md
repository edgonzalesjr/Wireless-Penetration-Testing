## Objective
To develop and apply hands-on skills in wireless network security by conducting ethical attacks, analyzing network behavior, and implementing strategies to harden defenses.

### Skills Learned
- Wireless reconnaissance and environment setup using Kali Linux.
- Packet capture and analysis (WPA2 handshake identification).
- Password cracking with wordlists.
- Execution of deauthentication attacks.
- Monitoring real-world wireless traffic and diagnosing connectivity/authentication issues.
- Applying legal and ethical standards in penetration testing.

### Tools Used
- Kali Linux: Penetration testing tool to perform attacks on a vulnerable machine.

## Practical Exercises

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/01_CheckWirelessAdapter.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>First, check if your wireless adapter is recognized by the system.</b>
<br/>

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/02_ChangeWirelessAdapterMonitorMode.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Set the wireless adapter to monitor mode.</b>
<br/>

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/03_RunMonitorModeFindTargetAccessPoint.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Enable monitor mode and identify the target Wi-Fi access point.</b>
<br/>

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/04_CaptureWPAHandshake.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Capture the WPA handshake and save it to a file.</b>
<br/>

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/05_DeauthenticateConnectedDevices.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Deauthenticate connected devices to force reauthentication.</b>
<br/>

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/06_CapturedWPAHandshake.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Confirm the WPA handshake has been captured.</b>
<br/>

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/07_StopCapture.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Stop the capture process.</b>
<br/>

<p align="center">
<img src="https://github.com/edgonzalesjr/Wireless-Penetration-Testing/blob/main/images/08_TryPass.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Try to crack the captured .cap file. We've successfully cracked the weak password.</b>
<br/>

## Outcome
- Gained practical, real-world experience simulating wireless attacks and analyzing Wi-Fi traffic.
- Understood the limitations of legacy encryption (WPA2) and the benefits of modern protocols (WPA3).
- Demonstrated the ability to identify wireless vulnerabilities and recommend secure configurations.
- Prepared to assist organizations with Wi-Fi threat detection, incident response, and proactive security configurations in line with best practices.

## Acknowledgements
This project combines ideas and methods from various sources, such as the wireless security tutorials by David Bombal and my IT experience. These resources provided the fundamental information and techniques, which were then modified in light of practical uses. 
 - [David Bombal](https://www.youtube.com/playlist?list=PLhfrWIlLOoKPbqR5Ttl1HGbiDhaxiUv9l)
 - [Kali Linux](https://www.kali.org/) 

## Disclaimer
The sole goals of the projects and activities here are for education and ethical cybersecurity research. All work was conducted in controlled environments, such as paid cloud spaces, private labs, and online cybersecurity education platforms. Online learning and cloud tasks adhered closely to all usage guidelines. Never use these projects for improper or unlawful purposes. It is always prohibited to break into any computer system or network. Any misuse of the provided information or code is not the responsibility of the author or authors.
