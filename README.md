## SecOTA: Universal Secure Flash-Over-The-Air for Embedded and IoT Systems

This thesis addresses the lack of secure, easy-to-deploy on-premise flash over the air 
(FOTA) frameworks that consider physical security, providing companies with an 
efficient way to stop the financial losses caused by recalls, due to software failures, 
emerging security threats, or rapid development bugs, and save time developing in
house FOTA solutions. Our project develops a universal and secure FOTA 
comprehensive framework for embedded and IoT systems, implementing the Uptane 
standard, which is based on The Update Framework (TUF). TUF is primarily used for 
software updates by companies like Microsoft, Google, and Amazon, while Uptane 
adapts it to the environment and capabilities of embedded and IoT devices. The 
development was conducted based on the ISO 21434 standard, ensuring adherence to 
automotive cybersecurity guidelines. Our work introduces a specialized Threat 
Analysis and Risk Assessment (TARA) focusing on client-side attacks, often 
overlooked in favor of backend attacks. Using both the STRIDE methodology and the 
MITRE ATT&CK framework for identifying threats and tactics, techniques, and 
procedures (TTPs), we identified and mitigated risks related to physical and client app 
attacks on the Electronic Control Unit (ECU). Mitigations include updating deprecated 
cryptographic algorithms to the latest standards, network Intrusion Prevention Systems 
(IPS), and process manipulation countermeasures. Our framework, SecOTA, is 
designed with security by design principles and employs a microservice architecture 
for compromise resilience. It is ready to deploy universally across a wide range of 
boards, ensuring a robust and adaptable solution for secure FOTA in embedded and 
IoT systems.