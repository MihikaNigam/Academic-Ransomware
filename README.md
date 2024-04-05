# Academic-Ransomware

In this we utilised msfconsole to study and analyse how bad actors think and make a ransomware to inject our os-processes.

We kept checking how detectable each malware was by passing it through virustotal. Checkout the "c# malware" folder to look at "virustotal_results.png" for an idea of how the results looked.

A bad actor typically tries to keep his malware as undetectable as possible. Trying to target the simplest os processes, keeping the name as unnoticable as possible, writing malware in languages that Antiviruses aren't built to detect and encrypting the code wherever possible, bypassing the sandbox completely. Our process injection in go was only detected by 2 AVs which is scary.


To prevent these it's important for os and developers to catch on any delays in their usual processes, look for verifications and block unverified content entirely. 




