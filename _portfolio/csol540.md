---
title: "Operational Policy"
excerpt: "Policies play a vital role in the cyber security strategy, as they represent the organization’s efforts to address threats to the business. This set of documents communicates principles the organization must follow to manage security risks, using simple language to determine the expected behaviors, responsibilities, and the consequences of failure. This section covers the many aspects and challenges of developing security policies."
collection: portfolio
---

Policies play a vital role in the cyber security strategy, as they represent the organization’s efforts to address threats to the business. This set of documents communicates principles the organization must follow to manage security risks, using simple language to determine the expected behaviors, responsibilities, and consequences of failure. The alignment between policies and business requirements is paramount for a cybers security strategy that serves as an enabler, as they “describe how to conduct business functions and transactions with the desired outcome” (Johnson, 2014). Therefore, the cyber security practitioner's professional responsibility is to review the impact of laws and regulations while developing policies and potential privacy concerns associated with the increased amount of data companies collect from their clients. The policies must also consider the ethical implications of security decisions, specially associated with private data.  

This section covers the many aspects and challenges of developing security policies.

## Laws, Regulations, and Standards
Companies continue to collect increasing amounts of data, potentially increasing user exposure to threats and jeopardizing their privacy. This scenario pressures the industry to develop mechanisms that ensure organizations take appropriate measures to safeguard sensitive information. As noted by Johnson (2014, p.65), security and privacy laws and regulations play three essential roles in that direction: establishing the grounds to protect personal privacy, limiting how companies can use and collect the user’s private data and holding accountable organizations when breaches occur.

Users primarily drive the surge in privacy laws and regulations. For instance, Boyon & Wallard (2019) noted that “citizens do not trust companies or governments to use their data in the right way” and that “2/3 of consumers would be more comfortable sharing personal information with a company if it were clear about how it will use the data.” As users are entitled to their privacy, they can understand how their information is used and chose to use the service. Therefore, the industry will naturally adapt to this aspect and create mechanisms to support the customer requirements. The primary benefit from the creation and widespread adoption of these regulations is precisely the increased user trust: the comfort provided by a set of requirements establishing what to expect from the organization might lead to additional business (Oracle, 2018).

A drawback, however, can be the cost. The compliance process for larger organizations that did not prioritize the privacy of their customer data might be resource and time-consuming, requiring additional personnel and the creation of new positions within the organizational structure. Finally, the failure to comply with applicable law and regulation can result in penalties such as fines.

### Healthcare Industry Examples
In the healthcare industry, protecting the patient’s privacy should be one of the organization’s primary goals; therefore, they should follow industry security standards that guide success. Healthcare providers, for instance, are subject to federal and state laws regarding safeguarding and handling patients’ private information. Healthcare companies should comply primarily with the HIPAA regulation, and as they may offer access to patient information online, they should also consider COPPA and its coverage of children’s data:

* **[Health Insurance Portability and Accountability Act of 1996 (HIPAA)](https://aspe.hhs.gov/report/health-insurance-portability-and-accountability-act-1996).** Presents a set of standards that health insurance and health care providers must adopt when to safeguard patient information, including health conditions, treatments, and payment. According to [HIPPA’s Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html), organizations must define administrative, physical, and technical controls to ensure the data’s security. These controls include establishing a managed security process, a breach notification process, access control to patient information based on the least privilege principle, periodic assessments, physical access control to facilities and devices, audit controls, and data security while at rest and in transit.

* **[Children’s Online Privacy Protection Act (COPPA)](https://www.ftc.gov/enforcement/rules/rulemaking-regulatory-reform-proceedings/childrens-online-privacy-protection-rule).** Focuses on safeguarding under 13-year-old children’s online information, mainly how it is collected and used. To comply with COPPA, HCI must provide parents with a comprehensive privacy policy, obtain their verifiable consent to handle their children’s data, and provide parents with the ability to review the information stored.

When operating nationwide, the healthcare provider may collect and store information from patients residing in many states; as such, the organization must consider the relevant state and law privacy regulations. Although many HIPAA requirements overlap with state laws, the [HIPAA Privacy Rule](https://www.hhs.gov/hipaa/for-professionals/privacy/laws-regulations/index.html) notes that more stringent regulations can overrule HIPAA directives. The Chief Privacy Officer (CPO) and the organization’s general counsel must review the policies to align with local privacy laws.

## Data Classification and Security Policy Models
### Formal Security Models
Developers and system administrators are already concerned with keeping the systems stable and readily accessible, leaving minimal time to worry about security. Also, as Dykstra (2015) noted, “Cybersecurity is complex because it is constantly changing. As soon as you think you’ve addressed a problem, the problem or the environment changes.” This situation typically results in a security team often focused on solving crises (such as incidents) or blindly relying on industry practices developed by security professionals that also came from a similar context.

Given that scenario, the scientific method might look overwhelming for an already busy team, which usually does not have a science background. Additionally, the “best practices” that continue to fail in protecting the system pass a false sense that the proponents conducted systematic research before publishing the guidance, creating recommendations disconnected from the practice. I believe both conditions (overwhelmed teams and the lack of confidence in the scientific method) contribute to the belief that scientific rigor does not allow for practical cybersecurity applications.     

To convince coworkers and supervisors of the benefits of using a scientific approach to cybersecurity, I would argue that a methodological approach can support the learning process to improve the organization’s security continuously. Based on the scientific method proposed by Andersen & Hepburn (2020), we can consider a company attempting to verify its resilience against a ransomware attack: the security team can leverage systematic experimentation (developing and executing attack scenarios), along with inductive and deductive reasoning (analyzes of tactics, techniques, and procedures cross-referenced with logs and defenses), to test and analyze the safeguards in place (the hypotheses). This perspective can help the team increase coverage while creating documentation for future reference. Such knowledge can be reused to formally improve policies, providing traceability and a rationale behind control decisions.

### Data Classification
Organizations must understand how to allocate security resources according to specific needs. For instance, information available to the public has very different security requirements than data intended only for the executive leadership. Data and asset classification are vital for security policy framework, as it provides cyber security practitioners with the foundational knowledge to select and apply controls efficiently.

The following paper illustrates a formalized classification policy by outlining the classification scheme and the requirements to safeguard assets and information according to their classification. The classification layers are based on the “Legal Classification Scheme” proposed by Johnson (2014).

* _[Asset and Information Classification Policy Summary](http://danielcmarques.github.io/files/coursework/csol540/CSOL540.Assignment.Classification_Policy.Daniel_Cordeiro_Marques.pdf)_

## Privacy Policies
In general, people want their privacy to make their decisions, take actions, and speak freely. It is also their fundamental right; the Universal Declaration of Human Rights (The United Nations, 1948, art. 12) states that “no one shall be subjected to arbitrary interference with his privacy (...). Everyone has the right to the protection of the law against such interference or attacks.” Therefore, users must have the ability to decide how their information is collected, stored, and used.

Organizations, on the other hand, wish to acquire more data associated with their customer. As Redman & Waitman (2020) point out, not leveraging the customer data to improve business offers can result in a significant competitive advantage. Therefore, the company’s challenge is to address privacy concerns and regulations while collecting sufficient data to fuel innovation and offer an outstanding customer experience.

Finally, governments have two primary concerns: creating mechanisms that enforce the user’s rights by balancing out the relationship between those collecting data and the individuals (Goldstein & Abrams, 2021) and national security.

From the user’s perspective, the best way to protect online information to protect their private information is to exercise caution: think before clicking on links, maintain a limited online presence, and understand how data is collected and how used. To protect online data, companies may map out systems and people handling customer data and implement micro-segmentation to separate these assets from the rest of the network. However, the strategy to safeguard offline private data must be different. Threat agents can carry away physical media, such as printed forms, without drawing attention. Companies and users must develop procedures to store, handle, and discard information safely during its lifecycle.

The following paper illustrates a privacy policy summary delineates a Healthcare organization's privacy domains, relevant laws and standards, and the responsibilities of revoking and granting access to information.

* _[Privacy Policy Summary](http://danielcmarques.github.io/files/coursework/csol540/CSOL540.Assignment.Privacy_Policy.Daniel_Cordeiro_Marques.pdf)_

## Policy Implementation, Enforcement, and Compliance
Threat actors see an opportunity to compromise valuable data and profit from cyberattacks, naturally driving the number of security events every year. This poses as a challenge as threats continue to adapt and evolve. Ultimately, most organizations are unable to follow this evolution and adapt their policies, procedures, and overall security architecture, causing the damage we have been following all over the news.

As security professionals, we can start by bridging the gap between business, technology, and compliance, and build security controls around assets and people that support business objectives. In general, the organization could start looking at process, people, and technologies handling sensitive data and the controls associated with them. These include user awareness initiatives, processes to review policies and procedures when technologies and the business risk landscape change, and training people to adequately implement controls. Although not an easy task, focusing on the business will help creating traction and improve compliance with the security strategy.

Organizations develop policies to safeguard sensitive data to align with relevant regulations and support business needs. Therefore, failing to comply with such policies can lead to severe consequences for the organization, including regulatory fines and damage to its reputation. The implementation, enforcement, and compliance plan establishes guiding principles to ensure that the organization appropriately implements and enforces controls and their compliance with the organizational policies. The following paper serves as an example of this plan.

* _[Implementation, Enforcement, and Compliance Summary Plan](http://danielcmarques.github.io/files/coursework/csol540/CSOL540.Assignment.Implementation_Enforcement_and_Compliance_Plan.Daniel_Cordeiro_Marques.pdf)_

## Reflection
Security policies play a vital role in the organization’s operating model, as they represent the core principles driving its approach to managing cybersecurity risks. Our professional responsibility is to act according to these principles and ensure they align with business requirements and relevant laws and regulations. Understanding their impact on operations is paramount for a successful cybersecurity strategy with the increased demand associated with privacy legislation.

Ethical considerations are also a critical part of security policies. For instance, an Incident Response Policy should outline the organization’s obligations towards their clients’ data if a breach occurs. Furthermore, looking at privacy from an ethics lens is also critical. Organizations’ must ensure they collect data only as needed to perform their activities and secure it according to relevant requirements.

Assets and data must be safeguarded according to their impact on the organization’s operations, starting with formally classifying and labeling them. I selected the “Asset and Information Classification Policy Summary” assignment as it illustrates the core part of this process and is a crucial document to educate users on the organization’s expectations regarding handling information. Next, to illustrate privacy considerations, I selected the “Privacy Policy Summary” paper as it builds on top of the classification policy and applicable laws to outline the requirements while handling sensitive customer data.

Particularly in heavily regulated industries, the impact of non-compliance with policies can be devastating. Once the organization establishes a comprehensive policy framework, it faces the challenge of operationalizing its principles and ensuring its expected performance. The “Implementation, Enforcement, and Compliance Summary Plan” assignment allowed me to round up the knowledge obtained while building a policy framework and practice a strategic thought process of implementing my approach.

My current role covers primarily technical aspects of cybersecurity, so studying the process of building a policy framework helped solidify my skills from a strategic and tactic perspective. As I develop myself as a cybersecurity leader, I will immediately put this experience to use.    

## References  
Andersen, H., & Hepburn, B. (2020). _Scientific Method_ (E. N. Zalta, Ed.; Winter 2020 Edition ed.). The Stanford Encyclopedia of Philosophy. [https://plato.stanford.edu/archives/win2020/entries/scientific-method/](https://plato.stanford.edu/archives/win2020/entries/scientific-method/)

Boyon, N., & Wallard, H. (2019, January 25). _Ignorance and distrust prevail about what companies and governments do with personal data_. Ipsos. [https://www.ipsos.com/en/ignorance-and-distrust-prevail-about-what-companies-and-governments-do-personal-data](https://www.ipsos.com/en/ignorance-and-distrust-prevail-about-what-companies-and-governments-do-personal-data)

Dykstra, J. (2015). _Essential Cybersecurity Science_. O'Reilly. [https://www.oreilly.com/library/view/essential-cybersecurity-science/9781491921050/ch01.html](https://www.oreilly.com/library/view/essential-cybersecurity-science/9781491921050/ch01.html).

Goldstein, L., & Abrams, M. (2021, March 25). _Will expectations for US privacy legislation overwhelm the process? International Association of Privacy Professionals_. [https://iapp.org/news/a/will-expectations-for-federal-privacy-legislation-overwhelm-the-process/](https://iapp.org/news/a/will-expectations-for-federal-privacy-legislation-overwhelm-the-process/)

Johnson, R. (2014). _Security Policies and Implementation Issues (2nd ed.)_. Jones & Bartlett Learning.

Oracle. (2018, July 24). _5 Surprising Side Benefits of GDPR Compliance. Channel Futures_. [https://www.channelfutures.com/from-the-industry/5-surprising-side-benefits-of-gdpr-compliance](https://www.channelfutures.com/from-the-industry/5-surprising-side-benefits-of-gdpr-compliance)

Redman, T. C., & Waitman, R. M. (2020, January 28). _Do You Care About Privacy as Much as Your Customers Do? Harvard Business Review_. [https://hbr.org/2020/01/do-you-care-about-privacy-as-much-as-your-customers-do](https://hbr.org/2020/01/do-you-care-about-privacy-as-much-as-your-customers-do)

The United Nations. (1948). _Universal Declaration of Human Rights_. [https://www.un.org/en/about-us/universal-declaration-of-human-rights](https://www.un.org/en/about-us/universal-declaration-of-human-rights)
