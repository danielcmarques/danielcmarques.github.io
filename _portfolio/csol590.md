---
title: "Incident Response and Computer Network Forensics"
excerpt: "Incident response (IR) is one of the primary responsibilities of the modern CISO. Notably, it is crucial for the CISO to effectively communicate the operational and business impact of the incident, legal aspects, and the steps the organization is taking to address the incident. This section reflects my efforts to study the topic and gain exposure to typical IR deliverables."
collection: portfolio
---

As Fruhlinger (2021) notes, incident response is one of the primary responsibilities of the modern CISO. Notably, it is crucial for the CISO to effectively communicate the operational and business impact of the incident, legal aspects, and the steps the organization is taking to address it. As such, transparency is paramount (Mahon, 2021).

To successfully communicate with stakeholders during an ongoing incident,  I would request a briefing with the following details (Ellis, n.d.):

* **The fundamental aspects of the incident.** These details will provide context around the event, informing the CISO what went wrong. Information should cover how the incident was identified, the gap between the event and its notification,  
* **The Impact of the incident.** The CISO must understand what was affected by the incident and its impact on the business operations. Details should include impacted areas, what was compromised, and the result of the malicious actions. Potentially, the CISO should also consult with other departments to understand the legal implications of the incident. Understanding the impact will help the CISO prioritize the incident response actions.       
* **The plan to contain, remediate, eradicate, and recover from the incident.** Presenting a plan to address the incident helps give the stakeholders the comfort that the incident is under control. The CISO should be informed of how the incident response team approaches the event, particularly, which actions were taken to contain the incident at its early stages, what is planned for the near future, and how long it will take to recover to a production state fully.

These details would help the CISO communicate with the many stakeholders involved in the process, including a board of directors or others in the C-level suite and the technical teams responsible for treating the incident.

## Sample Forensic Examination Report
This sample forensic examination report illustrates the steps to perform the analysis and presents recommendations and the examiner's conclusion based on existing evidence.

* _[Final Project: Forensic Examination Report](http://danielcmarques.github.io/files/coursework/csol590/Assignment.CSOL590.Final_Project_Sample_Forensic_Examination_Report.Daniel_Cordeiro_Marques.pdf)_

**Note:** Out of respect for the exercise’s creator, I modified the report to reflect a possible answer, although not the correct one. The contents still illustrate the proper process to identify the perpetrator in the expected format; therefore, the integrity of the assignment remains intact.
{: .notice}

## Reflection
With the increased number of incidents, the incident response function is one of the main attributions of any cyber security professional. Therefore, trust is the cornerstone of this attribution, as it requires transparency and clear communication of identified issues.

When performing network forensics, cyber security practitioners have the professional responsibility to respect the chain of custody. As Kent et al. (2006) noted, the chain of custody is essential “to avoid allegations of mishandling or tampering of evidence”; therefore, failing to reasonably demonstrate to the court that the evidence is legitimate and was not modified might jeopardize the case. Most jurisdictions will require a process that can display the integrity of the evidence throughout the investigation. The chain of custody is critical to building a case that can withstand the court's scrutiny. Ethically, we must also ensure the lawful collection of evidence, respecting the user’s privacy and relevant regulation. The Fourth Amendment and the Electronic Communication Privacy Act (ECPA) deal with specific aspects of the user’s rights associated with evidence collection. As Wright (2008) argues, the first “only applies to government searches” while the second “applies to everyone (whether government or private) and prohibits the unlawful interception or access to electronic Communications.”

Once the forensics professional has collected the evidence, they should perform an unbiased analysis and develop a package to present their findings. The final project exemplifies this process, demonstrating observations based on the evidence collected for a mock-up case and organized into a report. The report illustrates the many aspects of the process, including a chain of custody description, and demonstrates what one could expect from a forensic report.

As a red team leader, my digital forensics peers frequently request my feedback on attack vectors that could generate the evidence they collect or the feasibility of a technique on the targeted environment. The knowledge I obtained during this course helped me to better understand the forensic process and be prepared to collaborate with my colleagues in similar situations efficiently.  


## References
Ellis, D. (n.d.). _6 Phases in the Incident Response Plan_. SecurityMetrics. [https://www.securitymetrics.com/blog/6-phases-incident-response-plan](https://www.securitymetrics.com/blog/6-phases-incident-response-plan)

Fruhlinger, J. (2021, April 21). _How the CISO role is evolving_. CSO. [https://www.csoonline.com/article/3332026/what-is-a-ciso-responsibilities-and-requirements-for-this-vital-leadership-role.html](https://www.csoonline.com/article/3332026/what-is-a-ciso-responsibilities-and-requirements-for-this-vital-leadership-role.html)

Kent, K., Chevalier, S., Grance, T., & Dang, H. (2006). _Guide to Integrating Forensic Techniques into Incident Response_ (Special Publication 800-86 ed.). National Institute of Standards and Technology. [https://doi.org/10.6028/NIST.SP.800-86](https://doi.org/10.6028/NIST.SP.800-86)

Mahon, D. (2021, March 16). _For Today’s CISO, It’s All About Incident Response and Resilience_. International Security Management Association. [https://www.isma.com/index.php?option=com_dailyplanetblog&view=entry&year=2021&month=03&day=16&id=6:for-today-s-ciso-it-s-all-about-incident-response-and-resilience](https://www.isma.com/index.php?option=com_dailyplanetblog&view=entry&year=2021&month=03&day=16&id=6:for-today-s-ciso-it-s-all-about-incident-response-and-resilience)

Stephenson, P. (2014). _Cyber Investigation_. In Computer Security Handbook (Sixth ed., Vol. 2, 55.1-55.26). Wiley.

Wright, C. (2008, December 22). Searches and the US 4th Amendment. SANS Institute. [https://www.sans.org/blog/searches-and-the-us-4th-amendment/](https://www.sans.org/blog/searches-and-the-us-4th-amendment/)
