# ~ Cybersecurity-SOAR-EDR-Project

This project focuses on developing an automated incident response playbook using LimaCharlie for detection and response. It integrates with Slack, email, and Tines for seamless SOAR capabilities and includes user-driven decision-making steps to isolate compromised machines based on security events.

# ~ Step-1: Logic Diagram (Using draw.io app)
Created Playbook Workflow  

![EDR Project Block Dgm](https://github.com/user-attachments/assets/9293ea77-5f12-47a9-9ef3-ccce0614c48e)

# ~ Step-2: Install and Setup LimaCharlie EDR on Windows Server 2022

![Limacharlie](https://github.com/user-attachments/assets/6216ad33-5bb1-484b-b57f-47f3a94e4827)

# ~ Installed LimaCharlie Agent on Windows Server 2022

![Limachrlie-Agent](https://github.com/user-attachments/assets/ae6672d9-078e-4ba8-8b7f-8daf7c8ec462)

# ~ Verified whether LimaCharlie is Runnging in Windows Endpoint 

![Services](https://github.com/user-attachments/assets/cbf8d524-5cea-4832-8468-d8837b1edc18)

# ~ Step-3: Generate Telemetry & Create Detection Rule

# ~ Created D&R Rules in LmaCharlie EDR

![Created Rule](https://github.com/user-attachments/assets/c98e8c38-16ac-45a9-8384-2549c319f6b6)

# ~ Installed LaZagne (Post-Exploitation tool used to recover passwords) to generate telemetry on Windows Server 2022

![LaZagne](https://github.com/user-attachments/assets/7e72b451-0e92-483c-90c9-43c08ce34ef7)

# ~ Executed LaZagne to Generate Telemetry on LimaCharlie EDR

![LaZagne Executed](https://github.com/user-attachments/assets/79474fd0-d3a8-4f25-a3bd-3389a4deebe7)

# ~ Detected LaZagne Events in LimaCharlie EDR 

![LaZagne Events](https://github.com/user-attachments/assets/cc76898e-33d8-43a3-b600-b626fda7329c)

# ~ Step-4: Tines SOAR Integration & Slack setup

![Slack Setup](https://github.com/user-attachments/assets/95be385e-316c-4b78-86c9-2ba8a47b9104)

# ~ Detection of LaZagne in Tines

![Detection of LaZagne in tines](https://github.com/user-attachments/assets/e83c8a6a-fad4-43f2-8adc-85a3abe816e5)

# ~ Integrated LimaCharlie, Slack & Gmail in Tines

![Integration of Slack   Gmail](https://github.com/user-attachments/assets/340cf57e-2ae3-4c83-8372-c1fc51b98548)

# ~ Step-5: Complete Playbook integration According to Block Diagram

# ~ Send a Slack message 

![Slack Message](https://github.com/user-attachments/assets/f9811c7f-0713-4236-869c-c93d7e63879e)

# ~ Send a Gmail 

![Gmail](https://github.com/user-attachments/assets/cf02421c-94dc-4be9-9579-84369fd92134)

# ~ Created Prompt Yes/No

![Prompted Yes No](https://github.com/user-attachments/assets/fb1ac3b4-59a2-4af5-8e6a-b3f3ae60233c)

# ~ If we prompted Yes Windows Endpoint will be isolated in LimaCharlie 

![Isolated](https://github.com/user-attachments/assets/7527e695-4f98-4b32-9766-de5436c5e9fb)

# ~ send message in slack

![If Yes ](https://github.com/user-attachments/assets/50a6e5af-8484-4eec-8655-35a9cd65afd2)

# ~ If we prompted No Windows Endpoint will not isolated in LimaCharlie 

# ~ Send a message in slack

![If Prompted No](https://github.com/user-attachments/assets/a8cf05da-dfce-4900-a38a-1efc5ce6db6f)


