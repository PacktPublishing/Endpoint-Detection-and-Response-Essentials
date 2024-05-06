# Endpoint Detection and Response Essentials

<a href="https://www.packtpub.com/product/endpoint-detection-and-response-essentials/9781835463260?utm_source=github&utm_medium=repository&utm_campaign=9781835463260"><img src="https://content.packt.com/_/image/original/B21790/cover_image_large.jpg" alt="Endpoint Detection and Response Essentials" height="256px" align="right"></a>

This is the code repository for [Endpoint Detection and Response Essentials](https://www.packtpub.com/product/endpoint-detection-and-response-essentials/9781835463260?utm_source=github&utm_medium=repository&utm_campaign=9781835463260), published by Packt.

**Explore the landscape of hacking, defense, and deployment in EDR**

## What is this book about?
This book provides invaluable insights into the evolving security landscape, offering practical strategies for implementing and maximizing the effectiveness of EDR tools.

This book covers the following exciting features:
* Gain insight into current cybersecurity threats targeting endpoints
* Understand why antivirus solutions are no longer sufficient for robust security
* Explore popular EDR/XDR tools and their implementation
* Master the integration of EDR tools into your security operations
* Uncover evasion techniques employed by hackers in the EDR/XDR context
* Get hands-on experience utilizing DNS logs for endpoint defense
* Apply effective endpoint hardening techniques within your organization

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1835463266) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
GuvenHackinEdr PROC
mov r10, rcx ; Move the handle to the target process to
r10
mov eax, 0023h ; System call number for NtOpenProcess (may
vary based on version)
syscall
ret
GuvenHackinEdr ENDP
```

**Following is what you need for this book:**
If you're an IT professional seeking to safeguard yourself and your company's digital assets, this book is for you. To make the most of its content, a foundational understanding of GNU/Linux, operating systems, networks, and programming concepts is recommended. Additionally, security professionals eager to delve into advanced endpoint defense techniques will find this book invaluable.

With the following software and hardware list you can run all code files present in the book (Chapter 1-8).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-8 | Singularity XDR by SentinelOne | Windows, Mac OS X, and Linux (Any) |
| 1-8 | Or another EDR tool | Windows, Mac OS X, and Linux (Any) |

### Related products
* Microsoft Unified XDR and SIEM Solution Handbook [[Packt]](https://www.packtpub.com/product/microsoft-unified-xdr-and-siem-solution-handbook/9781835086858?utm_source=github&utm_medium=repository&utm_campaign=9781835086858) [[Amazon]](https://www.amazon.com/dp/1835086853)

* Microsoft Intune Cookbook [[Packt]](https://www.packtpub.com/product/microsoft-intune-cookbook/9781805126546?utm_source=github&utm_medium=repository&utm_campaign=9781805126546) [[Amazon]](https://www.amazon.com/dp/1805126547)

## Get to Know the Author
**Guven Boyraz**
 is a Cybersecurity/Software Engineer and Architect with a wide technical breadth and deep understanding of many systems. He boasts over a decade of experience in the computer science and IT industry. Throughout his career, he has provided cybersecurity consultancy services to a wide range of clients, including both enterprise-level customers and startups, primarily in London, UK. With a BSc in Electrical and Electronics engineering and several certifications in computer science, Boyraz has acquired a strong educational foundation. In addition to his consulting work, he has also made significant contributions as a trainer and speaker at numerous international conferences. He currently resides in London/UK.

