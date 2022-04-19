---
title: "Cryptography"
excerpt: "Cryptography is the cornerstone of many modern systems, including cybersecurity and finance applications. Although practitioners frequently mistake cybersecurity and encryption due to the increasing concerns around privacy, these terms are not the same. Practitioner should understand the security concerns and business needs and establish the best mechanism to address them without relying solely on encryption. This section demonstrates my efforts to study cryptography applications."
collection: portfolio
---

Cryptography is the cornerstone of many modern systems, including cybersecurity and finance applications. Although practitioners frequently mistake cybersecurity and encryption due to the increasing concerns around privacy, these terms are not the same. Encryption should not be considered a standalone solution but rather a part of a much larger system that believes how threats will attempt to compromise the information’s security attributes. Focusing solely on encryption and not recognizing its role within the cyber security strategy may result in a false sense of security (Ferguson et al., 2010), resulting in insufficient controls that fail to address other environmental issues.

## Developing Cryptographic Controls To Protect A Company
The final project illustrates our efforts to recommend cryptographic controls for a hypothetical health insurance company. Companies in the health insurance industry are regulated by the Health Insurance Portability and Accountability Act of 1996 (HIPAA), which requires organizations to encrypt patient information at rest and in transit.

* _[Final Project](http://danielcmarques.github.io/files/coursework/csol510/Assignment.CS510.Final_Project.pdf)_

## Reflection
With privacy laws and regulations becoming more widespread, executives turned to cryptography as the primary solution for security concerns. This typical misconception limits organizations’ ability to deploy efficient cybersecurity controls.  

Cybersecurity aims to protect data and assets handling it (including people and systems) from threat actors. As practitioners, we have the professional responsibility of using encryption as part of a more extensive security system that limits the attacker’s ability to compromise data instead of a stand-alone solution. That includes educating executives on the many uses of cryptography and how they fit into the overall cyber security architecture. The final project illustrates that point by demonstrating how cryptography can support security objectives, but it is insufficient to address all threats.

From an ethics perspective, cryptography can also lead to discussions about the balance between privacy and upholding the law. Encryption does make the work of law enforcement agencies and governments more difficult. For instance, after a terrorist attack in San Bernardino, CA, two iPhones were taken as evidence (Botelho & Ellis, 2015). The FBI could not recover data from the devices as the culprits set them up to “permanently destroy encrypted data after ten unsuccessful login attempts” (Tanfani, 2018). However, socially, it is reasonable that we expect organizations and government agencies to respect our privacy, a concept introduced by Katz v. the United States (1967) and known as “expectation of privacy.” Governments typically suggest backdooring cryptographic systems as a compromise, which is not viable. If a threat identifies tactics and techniques that allow them to utilize the backdoor, they could get access to unlimited users’ data. As cybersecurity leaders, we are responsible for considering the exposure to similar risk, as a backdoored cryptographic system could impact the organization’s ability to safeguard business-critical information.

As a red team leader, part of my role is providing recommendations to my clients. Educating the executive teams on the many cryptography applications and when to use them to address security gaps plays a central part in that process. Similarly, Cybersecurity professionals could benefit from looking at cryptography as a strategic enabler rather them a catch-all solution.

## References
Barker, E. (2020). _Guideline for Using Cryptographic Standards in the Federal Government: Cryptographic Mechanisms (SP 800-175B Rev. 1)_. National Institute of Standards and Technology. [https://doi.org/10.6028/NIST.SP.800-175Br1](https://doi.org/10.6028/NIST.SP.800-175Br1)

Barker, E., Dang, Q., Frankel, S., Scarfone, K., & Wouters, P. (2020). _Guide to IPsec VPNs (SP 800-77 Rev. 1)_. National Institute of Standards and Technology. [https://doi.org/10.6028/NIST.SP.800-77r1](https://doi.org/10.6028/NIST.SP.800-77r1)

Botelho, G., & Ellis, R. (2015, December 5). _San Bernardino shooting investigated as 'act of terrorism'_. CNN. [https://www.cnn.com/2015/12/04/us/san-bernardino-shooting/index.html](https://www.cnn.com/2015/12/04/us/san-bernardino-shooting/index.html)

Ferguson, N., Kohno, T., & Schneier, B. (2010). _Cryptography Engineering: Design Principles and Practical Applications_. Wiley. [https://doi.org/10.1002/9781118722367](https://doi.org/10.1002/9781118722367)

Katz v. United States, 389 U.S. 347. (1967). [https://www.law.cornell.edu/supremecourt/text/389/347](https://www.law.cornell.edu/supremecourt/text/389/347)

Tanfani, J. (2018, March 27). _Race to unlock San Bernardino shooter's iPhone was delayed by poor FBI communication, report finds_. Los Angeles Times. [https://www.latimes.com/politics/la-na-pol-fbi-iphone-san-bernardino-20180327-story.html](https://www.latimes.com/politics/la-na-pol-fbi-iphone-san-bernardino-20180327-story.html)

McKay, K., & Cooper, D. (2019). _Guidelines for the Selection, Configuration, and Use of Transport Layer Security (TLS) Implementations (SP 800-52 Rev. 2)_. National Institute of Standards and Technology. [https://doi.org/10.6028/NIST.SP.800-52r2](https://doi.org/10.6028/NIST.SP.800-52r2)
