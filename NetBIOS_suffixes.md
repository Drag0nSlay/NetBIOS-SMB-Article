# NetBIOS Suffixes - Unique and Group Names

NetBIOS (Network Basic Input/Output System) names are 16 characters long, with the 16th character—known as the **NetBIOS suffix**—designating the service type associated with the registered name. These suffixes help identify specific services or roles a device offers within a network.

---

## **Unique Names**

Unique names correspond to individual devices or services, each associated with a single IP address.

| Suffix | Description                                        |
|--------|----------------------------------------------------|
| **00** | Workstation Service (workstation name)             |
| **03** | Windows Messenger service                          |
| **06** | Remote Access Service                              |
| **20** | File Service (also called Host Record)             |
| **21** | Remote Access Service client                       |
| **1B** | Domain Master Browser – Primary Domain Controller  |
| **1D** | Master Browser                                     |

---

## **Group Names**

Group names are shared among multiple devices, each potentially having its own IP address.

| Suffix | Description                                                |
|--------|------------------------------------------------------------|
| **00** | Workstation Service (workgroup/domain name)                |
| **1C** | Domain Controllers for a domain (group record, max 25 IPs) |
| **1E** | Browser Service Elections                                  |

---

## **Importance**

Understanding these suffixes is essential for:
- Configuring network services.
- Diagnosing network communication issues.
- Recognizing device roles in Windows-based networks.

For more information, refer to the [NetBIOS Wikipedia page](https://en.wikipedia.org/wiki/NetBIOS).
