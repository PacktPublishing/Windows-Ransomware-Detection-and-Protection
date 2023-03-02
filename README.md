# Windows Ransomware Detection and Protection

<a href="https://www.packtpub.com/product/windows-ransomware-detection-and-protection/9781803246345"><img src="https://static.packt-cdn.com/products/9781803246345/cover/smaller" alt="Windows Ransomware Detection and Protection" height="256px" align="right"></a>

This is the code repository for [Windows Ransomware Detection and Protection](https://www.packtpub.com/product/windows-ransomware-detection-and-protection/9781803246345), published by Packt.

**Securing Windows endpoints, the cloud, and infrastructure using Microsoft Intune, Sentinel, and Defender**

## What is this book about?
If you’re looking for an effective way to secure your environment against ransomware attacks, this is the book for you. From teaching you how to monitor security threats to establishing countermeasures to protect against ransomware attacks, Windows Ransomware Detection and Protection has it all covered. 

This book covers the following exciting features:
* Understand how ransomware has evolved into a larger threat
* Secure identity-based access using services like multifactor authentication
* Enrich data with threat intelligence and other external data sources
* Protect devices with Microsoft Defender and Network Protection
* Find out how to secure users in Active Directory and Azure Active Directory
* Secure your Windows endpoints using Endpoint Manager
* Design network architecture in Azure to reduce the risk of lateral movement

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1803246340) today!

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter05.

The code will look like the following:
```
"policyRule": {
 "if": {
 "allOf": [
 {
 "field": "location",
 "notIn": "norwayeast
 },
 {
 "field": "location",
 "notEquals": "global"
 },
 ]
 },
 "then": {
 "effect": "deny"
```

**Following is what you need for this book:**
This book is for Windows administrators, cloud administrators, CISOs, and blue team members looking to understand the ransomware problem, how attackers execute intrusions, and how you can use the techniques to counteract attacks. Security administrators who want more insights into how they can secure their environment will also find this book useful. Basic Windows and cloud experience is needed to understand the concepts in this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-10).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-10 | Microsoft Sentinel | Windows, Mac OS X, and Linux (Any) |
| 1-10 | Microsoft Defender | Windows, Mac OS X, and Linux (Any) |
| 1-10 | Virtual Machine | Windows, Mac OS X, and Linux (Any) |
| 1-10 | Microsoft Intune | Windows, Mac OS X, and Linux (Any) |
| 1-10 | Microsoft Sentinel | Windows, Mac OS X, and Linux (Any) |
| 1-10 | Microsoft 365 | Windows, Mac OS X, and Linux (Any) |
| 1-10 | Microsoft Azure Services | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781803246345_ColorImages.pdf)

### Related products
* Mastering Windows Security and Hardening - Second Edition [[Packt]](https://www.packtpub.com/product/mastering-windows-security-and-hardening-second-edition/9781803236544) [[Amazon]](https://www.amazon.com/dp/180323654X)

* Operationalizing Threat Intelligence [[Packt]](https://www.packtpub.com/product/operationalizing-threat-intelligence/9781801814683) [[Amazon]](https://www.amazon.in//dp/1801814686)

## Get to Know the Author
**Marius Sandbu**
is a Cloud Evangelist and architect working at Sopra Steria in Norway with over 17 years in the IT industry. Marius has a wide range of technical experience across different technologies such as identity, networking, virtualization, endpoint management, infrastructure, and with a special focus on the public cloud. He is an avid blogger, co-hosts the CloudFirst Podcast, and is also an international speaker at events such as Microsoft Ignite and Citrix Synergy.
He has previously worked at TietoEVRY where he was the technical lead for the Public Cloud unit and has also worked at the University of Oslo as a system administrator and at Microsoft as a Technical Advisor.
