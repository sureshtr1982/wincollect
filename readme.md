This repository contains samples of tools that administrators can use to assist with Windows event collection. All Powershell samples and scripts are for reference or educational use. These samples are provided on an "as is" basis and are without warranties of any kind.  

We encourage administrators to examine these scripts before running them or test these tools in a lab environment before making use of them in the production network.

Any issues discovered using the samples should not be directed to QRadar support, but be reported on the Github issue tracker.


Get Event Log Reports
=====================
This Powershell script allows administrators to create EPS reports for local or remote Windows systems by polling the data from the Windows Event Viewer. The script advises the administrator on the best method of event collection, based on the returned EPS rate. 

WinCollect Agent Reinstall
=====================
The ReInstallWinCollect.ps1 PowerShell utility is intended to assist administrators with upgrades to Wincollect V7.3.0 on Windows hosts. The attached utility automates the install process to copy existing installation values and reinstall agents using the WinCollect V7.3.0 EXE for administrators who have large deployments of WinCollect agents.