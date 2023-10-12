# WAF20 - Threat Analysis

**NOTE:** 
This content below is supposed to be part of the WAF 20 document, to be embedded in the chapter "WAF>Security>Design>Applications and Services>Threat Analysis".

https://review.learn.microsoft.com/en-us/azure/well-architected/security/threat-model?branch=collab-waf-2-0-1

## Introduction / Use case

**NOTE**:
This chapter is not about the security solutions that Microsoft has available to protect your environment against Threats, such as M365 Defender solutions.

**Threat analysis** will present you with some best practices that will help you identify threats, attacks, vulnerabilities, and countermeasures during the design phase.

In this use case, we are considering an IT environment, the reference presented in the chapter "Baseline" (add a link here) with some workloads, components, and personas that will help you understand all the recommendations in this chapter, regarding **Threat Analysis**.

As we may consider any type of solution development into the **threat analysis** model, such as applications, databases, and other services available in the cloud, we may consider different components and workloads as examples, that is the reason we have below a common IT environment with some components explained below.

![image](https://github.com/rudneir2/WAF20-Threat-Analysis/assets/97529152/361fe17d-81d2-457a-8939-6c418129795a)

**NOTE:**
If you'd like to understand more about any solution described in the diagram, including acronyms, please refer to this table of contents, from the Baseline chapter.
(table to be built)

Let's consider the following:

1. There are many personas involved in a development life cycle, including developers, testers, final users, and administrators. All of them may be compromised and put your environment at risk through vulnerabilities or threats created intentionally.
2. Attackers consider a wide range of tools available easily to be used at any time to explore your vulnerabilities and start an attack.
3. one of the exercises based on the threat modeling proposed in this chapter is to make you try to anticipate any vulnerability that you may have in your solution. One of the best practices you may consider is adding some Azure security services to be used to protect your solution, so you may evaluate how effective those solutions could be, like DDOS, TLS, and Entra ID security services. (highlighted in the diagram)
4. Logs from Azure resources and some on-premises components may be sent to Azure Log Analytics so you may understand the behavior of your solution developed and try to capture initial vulnerabilities. Logs may also be collected from Security services, like Azure Firewall, DDOS, and many others.
5. Microsoft Sentinel may be added even in an early stage of the solution (during the test phase, for example), so you may build some analytics queries to mitigate threats and vulnerabilities, anticipating your Security environment when you are in production.
6. Finally, Microsoft Defender for Cloud may add to your environment important security recommendations so you may improve your solution being developed.

All the services mentioned above may be used with the **Threat Modeling** to reduce the risks in your environment.

See more details about **Threat Analysis** and **Threat modeling** below.

**here we would add the current draft content**
