---
title: "Secure Software Design and Development"
excerpt: "Safety and security are not typically considered functional requisites for most software projects, resulting in development teams allocating resources to prioritize usability and performance over security to fit constrained budgets and aggressive timelines. In my experience, being able to deploy code quickly is the primary focus of most tech giants. As such, they favor development processes that allow changes in the software to move from the requirement stages to production with minimal delay. This section discusses some of the aspects associated with the Secure Software Design and Development Process."
collection: portfolio
---

Safety and security are not typically considered functional requisites for most software projects, resulting in development teams allocating resources to prioritize usability and performance over security to fit constrained budgets and aggressive timelines. In my experience, being able to deploy code quickly is the primary focus of most tech giants. As such, they favor development processes that allow changes in the software to move from the requirement stages to production with minimal delay. For example, Facebook applies a continuous deployment strategy that encourages developers to deploy small pieces of code frequently, rather than making significant changes to the codebase at once (Feitelson et al., 2016).

However, Dawson et al. (2010) argue that the cost to fix issues in earlier stages of the development process is lower than after its release. Google, for instance, adopts the “shifting left” model: it embeds security early in the development process by considering security requirements during the design phase, testing if the code complies with them during each stage, and employing Static Application Security Testing (SAST) to address automating as much as possible into the deployment pipeline (_DevOps Tech: Shifting Left on Security_, 2021 & Smith et al., 2021). This model allows development teams to spend less time fixing security issues, reducing the time to deploy systems to production.

Another aspect of the process is testing those design assumptions after the application deployment. Performing Dynamic Application Security Testing (DAST) allows security practitioners to identify vulnerabilities that external attackers might exploit. Unlike SAST, the practitioner does not have access to the source code during this approach, but it is vital to highlight security issues that are only apparent during runtime. Organizations should consider SAST and DAST as complementary and not mutually exclusive. They provide different points of view and context, improving the application coverage from a security perspective.

## Sample Dynamic Application Security Testing (DAST) Report
The following report illustrates a Dynamic Application Security Testing (DAST) on deliberately vulnerable web applications. The work outlines the methodology used to perform the test, selected vulnerabilities identified during the exercise, and recommendations for remediation.

* _[WebGoat Dynamic Application Security Testing Report](http://danielcmarques.github.io/files/coursework/csol560/Assignment.CSOL560.WebGoat_DAST.Daniel_Cordeiro_Marques.pdf)_

## Reflection
Modern organizations rely heavily on software to achieve their business goals; some base their entire business model on complex applications that are publicly available and accessible to environments with varying levels of security. These applications are clear targets to threats: they handle sensitive data from a large userbase and are readily available anywhere. At the same time, software security is still overlooked for development speed and often lower costs, exposing the applications to a multitude of attacks that might lead to a security incident.

As cyber security practitioners, we are responsible for recommending efficient and cost-effective solutions to safeguard applications and user data. Automation plays a vital role in addressing this issue, adding security into the early stages of the Software Development Lifecycle (SDLC) and reducing the cost of security defects happening later in the process. For instance, developers can employ Static Application Security Testing (SAST) tools to analyze the source code against pre-defined rulesets. Generally, these solutions can easily detect typical security flaws so developers can address them before application deployment.

Although SAST tools can efficiently detect “low hanging fruit” vulnerabilities, they rarely identify business logic flaws that could lead to the compromise of sensitive data. To overcome that limitation, security professionals can perform Dynamic Application Security Testing (DAST) on an application after it is deployed, observing how it behaves when interacting with a real user. As DAST is usually performed in the production environment with actual data, ethical considerations are paramount when testing. The secure practitioner ensures that testing activities stay within scope, respect the user’s privacy, and promptly report all vulnerabilities.

As a red team manager, the knowledge obtained during this course helps me develop better recommendations for my clients. Organizations frequently struggle to manage risk effectively, so providing cost-effective guidance to improve security during the application design and development while addressing relevant threats is a significant competitive advantage.

## References
Axelrod, C. W. (2013). _Engineering safe and secure software systems (1st ed.)_. Artech House.

Dawson, M., Burrell, D. N., Rahim, E., & Brewster, S. (2010, January). _Integrating Software Assurance into the Software Development Life Cycle (SDLC)_. Journal Of Information Systems Technology & Planning, 3(6), pp. 49-53. [https://www.researchgate.net/publication/255965523_Integrating_Software_Assurance_into_the_Software_Development_Life_Cycle_SDLC](https://www.researchgate.net/publication/255965523_Integrating_Software_Assurance_into_the_Software_Development_Life_Cycle_SDLC)

_DevOps tech: Shifting left on security_. (2021, September 22). Google Cloud Architecture Center. [https://cloud.google.com/architecture/devops/devops-tech-shifting-left-on-security#how_to_implement_improved_security_quality](https://cloud.google.com/architecture/devops/devops-tech-shifting-left-on-security#how_to_implement_improved_security_quality)

Feitelson, D., Frachtenberg, E., & Beck, K. (2016, November). _Development and Deployment at Facebook_. Facebook Research. [https://research.fb.com/wp-content/uploads/2016/11/development-and-deployment-at-facebook.pdf](https://research.fb.com/wp-content/uploads/2016/11/development-and-deployment-at-facebook.pdf)
