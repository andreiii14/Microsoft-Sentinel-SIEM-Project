# Real-Time Geolocation Tracking of Failed RDP Attempts on an Azure Virtual Machine Using SIEM

## Description

This repository features an advanced PowerShell script designed to analyze Windows Event Log data for failed Remote Desktop Protocol (RDP) intrusion attempts. Using a robust third-party API, the script accurately identifies the geographic locations of potential threat actors.

In this project, I implemented Azure Sentinel (SIEM) as a top-tier Security Information and Event Management (SIEM) system. By setting up a live virtual machine with intentional vulnerabilities, I monitored real-time RDP brute force attacks from global sources. With a customized PowerShell script, I visualized the precise geolocation data of these potential threats on an Azure Sentinel Map.
<img width="1477" alt="Screenshot 2023-11-08 at 1 18 32 pm 2" src="https://github.com/andreiii14/Microsoft-Sentinel-SIEM-Project/assets/128039153/96d24e61-2f08-49ff-b589-76cd58f5ccb5">

### Skills Highlighted

- Leveraging Azure Sentinel as a comprehensive Security Information and Event Management (SIEM) solution for threat monitoring and analysis
- Creating a deliberately vulnerable virtual machine on Azure to simulate and capture failed RDP attacks for enhanced security analysis
- Implementing PowerShell scripts on Azure for in-depth analysis of Windows Event Log data and seamless integration with third-party geolocation APIs
- Utilizing Azure's robust infrastructure and security features to fortify the monitoring and defense capabilities of the virtual environment
- Leveraging Azure's cloud-based services and tools to facilitate real-time threat detection, response, and visualization for comprehensive security management

### Languages Used
- PowerShell: Extract RDP failed logon logs from Windows Event Viewer

### Utilities Used
- ipgeolocation.io: IP Address to Geolocation API

### Attacks from Brazil coming in; Custom logs being output with geodata
<img width="1512" alt="Screenshot 2023-11-08 at 1 09 45 pm 2" src="https://github.com/andreiii14/Microsoft-Sentinel-SIEM-Project/assets/128039153/7ba3ce06-41cc-4fae-b70c-cb770a572938">


### Highlights
- Observing RDP attacks from various global locations, providing insights into emerging threat patterns
- Generating custom logs embedded with geodata for enhanced analysis

### Visualization of global attack origins over a 24-hour period on a world map, generated from customized logs enriched with precise geolocation data.
<img width="671" alt="Screenshot 2023-11-08 at 2 00 00 pm 2" src="https://github.com/andreiii14/Microsoft-Sentinel-SIEM-Project/assets/128039153/0cb0e366-8643-44f1-9ed6-ac660c742ec9">

