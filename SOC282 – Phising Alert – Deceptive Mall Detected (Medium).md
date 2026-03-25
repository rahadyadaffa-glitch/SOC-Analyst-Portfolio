##SOC282 – Phising Alert – Deceptive Mall Detected (Medium)
<img width="1340" height="102" alt="image" src="https://github.com/user-attachments/assets/8967ba85-3d16-4a16-8fdd-c23267fdd472" />
<img width="1449" height="414" alt="image" src="https://github.com/user-attachments/assets/a567aff2-064e-4da7-868f-7181b5394770" />

TimeLine:

May 13, 2024, 09:20 AM An email was sent from IP 103.80.134.64 using the address free@coffeeshooop.com to Felix@letsdefend.io.

<img width="1449" height="414" alt="image" src="https://github.com/user-attachments/assets/5cf06ab9-95e8-48e8-bc95-2c5082dc3753" />


May 13, 2024, 12:59 PM On the same day, Felix opened the email and clicked the URL provided. The URL contained a ZIP file.

<img width="623" height="337" alt="image" src="https://github.com/user-attachments/assets/a894a0a0-3942-4b88-80d7-ab933fa5115c" />


May 13, 2024, 01:00 PM Felix installed an application from the ZIP file named coffee.exe. The destination IP associated with coffee.exe is suspicious, with a VirusTotal score of 11/94.

<img width="1339" height="73" alt="image" src="https://github.com/user-attachments/assets/a3ab4f7b-71f8-408e-8e67-9192041c2864" />

<img width="628" height="331" alt="image" src="https://github.com/user-attachments/assets/b6ca84e3-7455-498a-a939-7874af37be86" />


May 13, 2024, 01:00 PM (Continuation) Immediately after coffee.exe was successfully installed on Felix's device, a process was initiated that generated an image hash. After verifying this hash on VirusTotal, it was found to be highly suspicious with a score of 57/71. VirusTotal flagged this hash as a Backdoor and Spyware.

<img width="1011" height="458" alt="image" src="https://github.com/user-attachments/assets/4891569e-f4c7-4f31-980b-1d08bb77bf43" />

<img width="679" height="665" alt="image" src="https://github.com/user-attachments/assets/4762f8f8-f0be-4d0f-8ab1-8803f5cb230a" />


Result : 
In conclusion, the alert is a True Positive, confirming a Phishing Email attack that led to a malware infection. 



<img width="1308" height="304" alt="image" src="https://github.com/user-attachments/assets/f81ce7e7-90c8-41f4-9579-3c2d1bd833a4" />


