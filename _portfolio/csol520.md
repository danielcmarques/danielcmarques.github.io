---
title: "Security Architecture"
excerpt: "In my experience, most security architectures fail due to a misalignment with business requirements. Multiple issues can jeopardize the architecture due to failing to support the company’s goals and provide security as a business enabler, such as lack of leadership support, insufficient funding, and inadequate understanding of assets supporting critical business goals. Using a layered model generating artifacts that allows leadership to trace security decisions back to the original business drivers and reinforce security services as business enablers are paramount for a successful cybersecurity strategy. This section covers an approach to security architecture using the SABSA model."
collection: portfolio
---

In my experience, most security architectures fail due to a misalignment with business requirements. Multiple issues can jeopardize the architecture due to failing to support the company’s goals and provide security as a business enabler, such as lack of leadership support, insufficient funding, and inadequate understanding of assets supporting critical business goals. Using a layered model generating artifacts that allows leadership to trace security decisions back to the original business drivers and reinforce security services as business enablers are paramount for a successful cybersecurity strategy.

The complexity derived from defending a corporate environment while supporting business goals calls for a systematic approach. The Sherwood Applied Business Security Architecture (SABSA) methodology provides a model to approach the problem by breaking it into smaller parts and addressing security concerns from different stakeholders and viewpoints by using a layered strategy. Each layer of the SABSA architecture builds from information obtained from the other, starting with the business view provided by the contextual layer. Therefore, the model offers a framework that allows security architects to define controls focused on critical assets and aligned with business goals. The layered model lets leadership trace security decisions back to the original business drivers, reinforcing the security services as business enablers.

## The SABSA Architecture Model
The SABSA architecture model consists of six layers, each approaching security from a different perspective (figure 1).

**Figure 1.**

_The SABSA® Model for Security Architecture Development (Sherwood et al., 2005)._

<img src='/images/sabsa_model.png' width="60%" height="60%">

### Contextual Security Architecture: The Business View
The contextual layer’s primary function is to help the architect to understand business requirements that will drive the effective design that aligns with the business goals. This layer considers what assets are essential to the business and must be protected; why the company should cover these assets, and the objectives that will drive the security strategy; how the business operates, and which process will require security considerations; who is involved in the business operation, such as organizational structures and third parties; where is the business operating, and associated security aspects such as geographically dispersed offices and local laws; and the time requirements for security, including deadlines and time-to-market. Once the architects enumerate and understand the business requirements and context of security controls, they can create the overall security philosophy.

Business drivers are a vital part of this layer: they serve as initial input to establish Business Attributes and, consequently, the Business Risk Model. Leveraging the Business Risk Model, the security practitioner can, for instance, establish control objectives aligned to the business goals. To illustrate this concept, I wrote a paper that uses the methodology described by Sherwood et al. (2005) to create an example Business Risk Model for Target leveraging publicly available information to derive business drivers, requirements and impact, and potential vulnerabilities.

* _[Target Corporation: A business risk model based on the 2013 data breach](http://danielcmarques.github.io/files/coursework/csol520/Assignment.CSOL520.Business_Risk_Model.Daniel_Cordeiro_Marques.pdf)_

**Note:** This paper was developed for educational purposes only, based exclusively on publicly available information. It does not reflect the company's opinions, needs, or objectives.
{: .notice}

### Conceptual Security Architecture: The Architect's View
The architect leverages the contextual layer requirements in the conceptual layer to develop the security architecture’s directions and attributes. This layer defines what the architecture is trying to protect, and the associated risks; the control objectives, and why is it essential to preserve those attributes; how the security approach translates to strategies aligned with business requirements; who will be involved in protecting the assets; the conceptual boundaries and relationships, and where security will be applied; and the time-related performance targets for security attributes, such as lifetimes and deadlines.  With the security strategy established, designers can define security architecture’s logical abstraction and identify the elements that support the plan.

In the conceptual security architecture proposed by Sherwood et al. (2005), security practitioners can derive an overall security strategy using the contextual layer’s business information. Leveraging the business attribute profiles as a starting point, one can define control objectives to mitigate the business risks. To demonstrate this concept, I applied the SABSA conceptual security architecture to develop a mock security strategy that addresses the risks outlined in my previous paper.

* _[Target Corporation: Control objectives and mock security strategy](http://danielcmarques.github.io/files/coursework/csol520/Assignment.CSOL520.Control_Objectives_And_Mock_Security_Strategy.Daniel_Cordeiro_Marques.pdf)_

**Note:** This paper was developed for educational purposes only, based exclusively on publicly available information. It does not reflect the company's opinions, needs, or objectives.
{: .notice}

### Logical Security Architecture: The Designer's View
The logical layer uses the conceptual layer’s principles to identify security components and their relationship, representing the previous layer’s strategies. This layer defines what business information the security controls will protect; the security policy requirements; the security services, and how they combine to become a system that supports the business goals; the entities that participate in the security process, their roles and relationships; the security domains and their boundaries; and the security processing cycle (Sherwood et al., 2005, p. 38). Next, the architect must translate the abstractions into a model that realizes the security concept.

To illustrate my understanding of the Logical Security Architecture, I developed a paper that describes a mock logical architecture for Equifax, based on the SABSA framework and publicly available information. Specifically, the work leverages Equifax’s 2019 annual report to establish risks and business drivers and the U. S. Government Accountability Office (GAO)’s report to derive a gap analysis.

* _[Logical Security Architecture (Designer’s view): Equifax case study](http://danielcmarques.github.io/files/coursework/csol520/Assignment.CSOL520.FinalProject.Daniel_Cordeiro_Marques.pdf)_

**Note:** This paper was developed for educational purposes only, based exclusively on publicly available information. It does not reflect the company's opinions, needs, or objectives.
{: .notice}

### Physical Security Architecture: The Builder's View
The physical layer takes the logical layer’s abstractions and transforms them into a technological model that physically expresses the security requirements. As a business enabler, a robust security strategy plays a critical role in offering mechanisms that allow essential business services to continue operating if an incident occurs. Businesses continue to rely heavily on technology to achieve their goals; therefore, as Sherwood et al. (2005) propose, “physical network and platform infrastructure should be built in resilient configurations to incorporate a degree of fault tolerance” (p. 364). A resilient design must focus on the criticality of assets while considering cost-effectively strategies to withstand a security event.

Architects should consider three design principles to create a resilient strategy: avoidance of single points of failure, redundancy of hard physical components, and recovery procedures. Yet, these can quickly become costly initiatives; an architect can address this potential risk by considering two factors while prioritizing solutions: focus on critical assets and manageability of the process.

The network and platform resilience approaches can cover different aspects of a robust design. However, two elements are common to all strategies: diversity of resources supporting mission-critical functionality and testing and monitoring supporting features. The architect must not rely solely on the plan; the security team must regularly test and improve processes and procedures to ensure they work as expected and align with the latest threats.  

This layer deals with security data model and structures; procedures to security guide decision-making; security mechanisms and the servers that support them; who is responsible for security functions and what they use to perform them; the physical technology supporting security functions; and processing schedule. With a complex environment likely using multiple technologies to address different needs, the security architect must address how components interact with one another.

### Component Security Architecture: The Tradesman's View
The component layer covers integrating the products defined in the physical layer, assuring they work cohesively and as intended. Many different functions must operate together to fulfill business requirements and achieve the company’s goals; consequently, business functions and their needs call for various security components to support their objectives. To address that, Sherwood et al. (2005, p. 281) propose that standards provide the mechanisms to integrate the different components into a system. Due to the high cost and complexity of implementation, companies may choose to move away from using such standards. However, reducing the scope to controls and assets focused on business requirements can mitigate these risks and allow organizations to reap the benefits that positively impact business operations and brand awareness.  

This layer is concerned with detailed data structures, security standards, delivery tools and processes, users’ identities, privileges, roles and responsibilities, computer addresses, and process execution order and timing. Security must consider day-to-day operations and ensure that all functions are performed as expected and according to the plan.

### Operational Security Architecture: The Facilities Manager’s View
This layer is concerned with ensuring operational continuity, minimizing failures and disruptions, providing security services, user support and access provisioning, managing the environment, and scheduling and executing security functions according to the timetable. The operational layer runs across all other layers, and its focus is to keep the security functions in working order.

## Reflection
Having provided advisory services for Fortune 500 companies for the past ten years, I could observe firsthand how the lack of alignment between the cyber security strategy and business needs can impact the efficacy of controls. A framework like the SABSA model is instrumental in addressing this issue. It provides mechanisms to establish a security architecture based on decisions that can be traced back to business goals. The key takeaways from this course are that the primary drivers for a security strategy should be the business drivers, and decision traceability is vital to obtain senior leadership support to security initiatives. I am already incorporating the knowledge obtained from this course into my daily job by bringing insights from senior management to elaborate recommendations to my clients.

To illustrate the benefits from this learning experience, I selected the papers covering the first three layers of the SABSA model. They clearly outline the understanding of business requirements, definition of a security strategy and selection of control objectives based on these requirements, and the layout of components and security services that will support the business goals. While developing these papers, I concluded that having leadership and stakeholders involved in the earlier stages of developing a cyber security strategy can be beneficial for its efficacy in the long term.

As cyber security professionals, our professional and ethical duty is to protect organizations from threats impacting their business; therefore, we should make decisions that sustain and not hinder their growth. Establishing a security architecture that starts with the involvement of relevant stakeholders and builds on top of business drivers enables us to fulfill our duties to the best of our ability.  


## References  
Bacik, S. (2008). _Building an effective information security policy architecture_. CRC Press.

Bodeau, D., & Graubart, R. (2017). _Cyber resiliency design principles_. The MITRE Corporation. [https://www.mitre.org/publications/technical-papers/cyber-resiliency-design-principles](https://www.mitre.org/publications/technical-papers/cyber-resiliency-design-principles)

National Institute of Standards and Technology. (2003). _Guide to Information Technology Security Services_ [Special Publication 800-35]. U. S. Department of Commerce. [https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-35.pdf](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-35.pdf)

Rose, S., Borchert, O., Mitchell, S., & Connelly, S. (2020). _Zero Trust Architecture_ [Special Publication 800-207]. National Institute of Standards and Technology.[https://doi.org/10.6028/NIST.SP.800-207](https://doi.org/10.6028/NIST.SP.800-207)

Ross, R., Pillitteri, V., Graubart, R., Bodeau, D., & Mcquaid, R. (2019). _Developing cyber resilient systems: A systems security engineering approach_ [NIST SP 800-160] (Vol. 2). National Institute of Standards and Technology. [https://doi.org/10.6028/NIST.SP.800-160v2](https://doi.org/10.6028/NIST.SP.800-160v2)

Sherwood, J., Clark, A., & Lynas, D. (2005). _Enterprise security architecture: A Business-driven approach_. CRC Press.
