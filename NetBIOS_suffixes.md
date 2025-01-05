# NetBIOS Suffixes - Complete List

NetBIOS (Network Basic Input/Output System) names are 16 characters long. The **16th character**—known as the **NetBIOS suffix**—designates the type of service registered by the device. These suffixes identify roles or services within a network and are used for network configuration, diagnostics, and troubleshooting.

---

## **Unique and Group Names**

### **Unique Names**
Unique names correspond to individual devices or services, each associated with a single IP address.

| Suffix | Description                                                |
|--------|------------------------------------------------------------|
| **00** | Workstation Service (workstation name)                     |
| **03** | Windows Messenger service                                  |
| **06** | Remote Access Service                                      |
| **20** | File Service (Host Record)                                 |
| **21** | Remote Access Service client                               |
| **1B** | Domain Master Browser – Primary Domain Controller          |
| **1D** | Master Browser                                             |
| **22** | Microsoft Exchange Interchange                             |
| **23** | Microsoft Exchange Store                                   |
| **24** | Microsoft Exchange Directory                               |
| **30** | Modem Sharing Server                                       |
| **31** | Modem Sharing Client                                       |
| **42** | McAfee Antivirus                                           |
| **43** | SMS Clients Remote Control                                 |
| **44** | SMS Administrators Remote Control Tool                     |
| **45** | SMS Clients Remote Chat                                    |
| **46** | SMS Clients Remote Transfer                                |
| **87** | Microsoft Exchange MTA                                     |
| **6A** | Microsoft Exchange IMC                                     |
| **BE** | Network Monitor Agent                                      |
| **BF** | Network Monitor Application                                |
| **[2B]** | IBM Lotus Notes Server                                   |

---

### **Group Names**
Group names are shared among multiple devices, each potentially having its own IP address.

| Suffix | Description                                                |
|--------|------------------------------------------------------------|
| **00** | Workstation Service (workgroup/domain name)                |
| **1C** | Domain Controllers for a domain (up to 25 IP addresses)    |
| **1E** | Browser Service Elections                                  |
| **01** | Master Browser (__MSBROWSE__)                              |
| **4C** | DEC Pathworks TCPIP                                        |
| **52** | DEC Pathworks TCPIP                                        |
| **[2F]** | IBM Lotus Notes (IRISMULTICAST)                          |
| **[33]** | IBM Lotus Notes (IRISNAMESERVER)                         |

---

## **Usage and Importance**

- **Network Roles:** Identifies device roles like servers, browsers, and domain controllers.  
- **Diagnostics:** Assists in troubleshooting communication errors between systems.  
- **Security Testing:** Helps in analyzing vulnerabilities during penetration testing.

### **Examples:**
- **1B**: Identifies a Primary Domain Controller, useful during domain enumeration.  
- **1E**: Indicates a browser service election, aiding in understanding network hierarchy.  

---

## **References**

For more information, check:
- [NetBIOS Wikipedia](https://en.wikipedia.org/wiki/NetBIOS)  
- [Microsoft Knowledge Base](https://ftp.zx.net.nz/pub/Patches/ftp.microsoft.com/MISC/KB/en-us/163/409.HTM)
