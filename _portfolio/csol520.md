---
title: "Security Architecture"
excerpt: "Coming Soon"
collection: portfolio
---

WIP.

The complexity derived from defending a corporate environment while supporting business goals calls for a systematic approach. The Sherwood Applied Business Security Architecture (SABSA) methodology provides a model to approach the problem by breaking it into smaller parts and addressing security concerns from different stakeholders and viewpoints by using a layered strategy. Each layer of the SABSA architecture builds from information obtained from the other, starting with the business view provided by the contextual layer. Therefore, the model offers a framework that allows security architects to define controls focused on critical assets and aligned with business goals. Finally, the layered model lets leadership trace security decisions back to the original business drivers, reinforcing the security services as business enablers.

## The SABSA Architecture Model
The SABSA architecture model consists of six layers, each approaching security from a different perspective (figure 1).

**Figure 1.**
_The SABSA® Model for Security Architecture Development (Sherwood et al., 2005)._
<img src='/images/sabsa_model.png'>

### Contextual Security Architecture: The Business View
The contextual layer’s primary function is to help the architect to understand business requirements that will drive the effective design that aligns with the business goals. This layer considers what assets are essential to the business and must be protected; why the company should cover these assets, and the objectives that will drive the security strategy; how the business operates, and which process will require security considerations; who is involved in the business operation, such as organizational structures and third parties; where is the business operating, and associated security aspects such as geographically dispersed offices and local laws; and the time requirements for security, including deadlines and time-to-market. Once the architects enumerate and understand the business requirements and context of security controls, they can create the overall security philosophy.

Business drivers are a vital part of this layer: they serve as initial input to establish Business Attributes and, consequently, the Business Risk Model. Leveraging the Business Risk Model, the security practitioner can, for instance, establish control objectives aligned to the business goals. To illustrate this concept, I wrote a paper that uses the methodology described by Sherwood et al. (2005) to create an example Business Risk Model for Target leveraging publicly available information to derive business drivers, requirements and impact, and potential vulnerabilities.

**Paper:** [Target Corporation: A business risk model based on the 2013 data breach](http://danielcmarques.github.io/files/coursework/csol520/Assignment.CSOL520.Business_Risk_Model.Daniel_Cordeiro_Marques.pdf)
_Note: This paper was developed for educational purposes only, based exclusively on publicly available information. It does not reflect the company's opinions, needs, or objectives._

### Conceptual Security Architecture: The Architect's View
The architect leverages the contextual layer requirements in the conceptual layer to develop the security architecture’s directions and attributes. This layer defines what the architecture is trying to protect, and the associated risks; the control objectives, and why is it essential to preserve those attributes; how the security approach translates to strategies aligned with business requirements; who will be involved in protecting the assets; the conceptual boundaries and relationships, and where security will be applied; and the time-related performance targets for security attributes, such as lifetimes and deadlines.  With the security strategy established, designers can define security architecture’s logical abstraction and identify the elements that support the plan.

In the conceptual security architecture proposed by Sherwood et al. (2005), security practitioners can derive an overall security strategy using the contextual layer’s business information. Leveraging the business attribute profiles as a starting point, the security practitioner can define control objectives to mitigate the business risks. TO demonstrate this concept, I applied the SABSA conceptual security architecture to develop a mock security strategy that addresses the risks outlined in my previous paper.

**Paper:** [Target Corporation: Control objectives and mock security strategy](http://danielcmarques.github.io/files/coursework/csol520/Assignment.CSOL520.Control_Objectives_And_Mock_Security_Strategy.Daniel_Cordeiro_Marques.pdf)
_Note: This paper was developed for educational purposes only, based exclusively on publicly available information. It does not reflect the company's opinions, needs, or objectives._

### Logical Security Architecture: The Designer's View
The logical layer uses the conceptual layer’s principles to identify security components and their relationship, representing the previous layer’s strategies. This layer defines what business information the security controls will protect; the security policy requirements; the security services, and how they combine to become a system that supports the business goals; the entities that participate in the security process, their roles and relationships; the security domains and their boundaries; and the security processing cycle (Sherwood et al., 2005, p. 38). Next, the architect must translate the abstractions into a model that realizes the security concept.

To illustrate my understanding of the Logical Security Architecture, I developed a paper that describes a mock logical architecture for Equifax, based on the SABSA framework and publicly available information. Specifically, the work leverages Equifax’s 2019 annual report to establish risks and business drivers and the U. S. Government Accountability Office (GAO)’s report to derive a gap analysis.

**Paper:** [Logical Security Architecture (Designer’s view): Equifax case study](http://danielcmarques.github.io/files/coursework/csol520/Assignment.CSOL520.FinalProject.Daniel_Cordeiro_Marques.pdf)
_Note: This paper was developed for educational purposes only, based exclusively on publicly available information. It does not reflect the company's opinions, needs, or objectives._

### Physical Security Architecture: The Builder's View
The physical layer takes the logical layer’s abstractions and transforms them into a technological model that physically expresses the security requirements. This layer deals with security data model and structures; procedures to security guide decision-making; security mechanisms and the servers that support them; who is responsible for security functions and what they use to perform them; the physical technology supporting security functions; and processing schedule. With a complex environment likely using multiple technologies to address different needs, the security architect must address how components interact with one another.

### Component Security Architecture: The Tradesman's View
The component layer covers integrating the products defined in the physical layer, assuring they work cohesively and as intended. This layer is concerned with detailed data structures, security standards, delivery tools and processes, users’ identities, privileges, roles and responsibilities, computer addresses, and process execution order and timing. Finally, security must consider day-to-day operations and ensure that all functions are performed as expected and according to the plan.

### Operational Security Architecture: The Facilities Manager’s View
This layer is concerned with ensuring operational continuity, minimizing failures and disruptions, providing security services, user support and access provisioning, managing the environment, and scheduling and executing security functions according to the timetable. The operational layer runs across all other layers, and its focus is to keep the security functions in working order.

## Reflection
WIP.


## References  
The National Institute of Standards and Technology. (2003). _Guide to Information Technology Security Services_ [Special Publication 800-35]. U. S. Department of Commerce. [https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-35.pdf](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-35.pdf)

Sherwood, J., Clark, A., & Lynas, D. (2005). _Enterprise security architecture: A Business-driven approach_. CRC Press.
