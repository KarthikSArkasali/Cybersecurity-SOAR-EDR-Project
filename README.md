# ~ Development of Automated Incident Response Playbook with SOAR and EDR Integration

* This project involves designing and implementing an automated incident response playbook utilizing LimaCharlie for advanced detection and response capabilities. The system integrates seamlessly with Slack, email, and Tines to enable robust Security Orchestration, Automation, and Response (SOAR) functionalities. The playbook features user-driven decision-making workflows, facilitating prompt isolation of compromised machines based on real-time security event analysis.

# ~ Step-1: Developed a Logic Diagram using the Draw.io application.
Playbook Workflow.

![EDR Project Block Dgm](https://github.com/user-attachments/assets/9293ea77-5f12-47a9-9ef3-ccce0614c48e)

# ~ Step-2: Install and Configure LimaCharlie EDR on Windows Server 2022.

![Limacharlie](https://github.com/user-attachments/assets/6216ad33-5bb1-484b-b57f-47f3a94e4827)

# Installed the LimaCharlie Agent on Windows Server 2022.

![Limachrlie-Agent](https://github.com/user-attachments/assets/ae6672d9-078e-4ba8-8b7f-8daf7c8ec462)

# Verified LimaCharlie Agent functionality on the Windows endpoint.

![Services](https://github.com/user-attachments/assets/cbf8d524-5cea-4832-8468-d8837b1edc18)

# ~ Step 3: Generate Telemetry and Develop Detection Rules.

# Developed Detection and Response (D&R) Rules in LimaCharlie EDR.

![Created Rule](https://github.com/user-attachments/assets/c98e8c38-16ac-45a9-8384-2549c319f6b6)

# Installed LaZagne, a post-exploitation tool for password recovery, to generate telemetry on Windows Server 2022.

![LaZagne](https://github.com/user-attachments/assets/7e72b451-0e92-483c-90c9-43c08ce34ef7)

# Executed LaZagne to generate telemetry within LimaCharlie EDR.

![LaZagne Executed](https://github.com/user-attachments/assets/79474fd0-d3a8-4f25-a3bd-3389a4deebe7)

# Detected LaZagne events within LimaCharlie EDR.

![LaZagne Events](https://github.com/user-attachments/assets/cc76898e-33d8-43a3-b600-b626fda7329c)

# ~ Step-4: Integrate Tines SOAR and Configure Slack.

![Slack Setup](https://github.com/user-attachments/assets/95be385e-316c-4b78-86c9-2ba8a47b9104)

# Detected LaZagne incidents within Tines.

![Detection of LaZagne in tines](https://github.com/user-attachments/assets/e83c8a6a-fad4-43f2-8adc-85a3abe816e5)

# Integrated LimaCharlie, Slack, and Gmail within Tines.

![Integration of Slack   Gmail](https://github.com/user-attachments/assets/340cf57e-2ae3-4c83-8372-c1fc51b98548)

# ~ Step 5: Complete Playbook Integration According to the Block Diagram.

# Sent a message in Slack. 

![Slack Message](https://github.com/user-attachments/assets/f9811c7f-0713-4236-869c-c93d7e63879e)

# Sent a message via Gmail. 

![Gmail](https://github.com/user-attachments/assets/cf02421c-94dc-4be9-9579-84369fd92134)

# Created a Yes/No prompt.

![Prompted Yes No](https://github.com/user-attachments/assets/fb1ac3b4-59a2-4af5-8e6a-b3f3ae60233c)

# If 'Yes' is selected, the Windows endpoint will be isolated in LimaCharlie.

![Isolated](https://github.com/user-attachments/assets/7527e695-4f98-4b32-9766-de5436c5e9fb)

# Sent a Slack message stating that the endpoint has been isolated.

![Isolated Yes](https://github.com/user-attachments/assets/bbf9499a-4050-428f-895d-fba38aeb94fe)

# If 'No' is selected, the Windows endpoint will not be isolated in LimaCharlie.

# Sent a Slack message requesting investigation of the endpoint that is not isolated.

![If Prompted No](https://github.com/user-attachments/assets/a8cf05da-dfce-4900-a38a-1efc5ce6db6f)


