<img width="1919" height="1079" alt="Screenshot 2026-02-08 002224" src="https://github.com/user-attachments/assets/701d1d4a-58a8-4aea-8348-c35943f57c77" />Basic Router & Switch Configuration Lab.
Project Status: Complete.

Project Overview:
I built a simple network by applying the knowledge I acquired while trying to understand networking fundementals, which is a neccesity for my Cybersecurity journey. I used Cisco Packet Tracer to build it from scratch. The main objective was to configure  the router and switch to manage the securuty of this simple network.

Tech stacks:
Tools: Cisco Packet Tracer and Github
Technologies: SSH, IPv4, IOS security and VTY management.

What I managed to build with my basic knowledge:
1. Identity & Security:
   Configured Hostnames (`R1`) to identify devices.
   Secured Privileged Mode with MD5 hashing (`enable secret`).
   Locked the physical console port.
   Added a legal banner (`MOTD`) to warn unauthorized users.

2. Connectivity:
   Assigned IPv4 Address `192.168.1.1/24` to the Gateway.
   Enabled interfaces and added description labels for troubleshooting.
3. Remote Management (SSH):
    * Replaced insecure Telnet with SSH (Secure Shell).
    * Generated 1024-bit RSA Encryption Keys.
    * Created local user authentication (`username admin`).





<img width="1919" height="1079" alt="Screenshot 2026-02-08 002224" src="https://github.com/user-attachments/assets/68a0b0df-2e06-4606-9d8b-f77b15a7d96e" />

<img width="960" height="449" alt="Screenshot 2026-02-05 020737" src="https://github.com/user-attachments/assets/5dfa5e33-6762-4a63-b7c4-af6fd72feb61" />

<img width="518" height="991" alt="Screenshot 2026-02-05 020539" src="https://github.com/user-attachments/assets/ff992f5f-8775-49ee-ac0d-e1e14f617c77" />

<img width="745" height="753" alt="Screenshot 2026-02-05 015837" src="https://github.com/user-attachments/assets/084b73f1-cf1b-4ec1-8c2e-9cee50b0efdd" />

<img width="725" height="771" alt="Screenshot 2026-02-05 015015" src="https://github.com/user-attachments/assets/b46dd28e-186e-4542-9010-5e4f9f9f484a" />

<img width="747" height="747" alt="Screenshot 2026-02-05 012916" src="https://github.com/user-attachments/assets/d29fd7ee-3385-454d-8709-bf591dc69eda" />

<img width="749" height="753" alt="Screenshot 2026-02-05 011946" src="https://github.com/user-attachments/assets/2af17807-4c2c-4494-9d09-6c3523338a8d" />

<img width="712" height="390" alt="Screenshot 2026-02-04 233150" src="https://github.com/user-attachments/assets/5c4c402c-9db3-4daa-8270-6b7e9b00524b" />

<img width="741" height="758" alt="Screenshot 2026-02-04 232123" src="https://github.com/user-attachments/assets/a161e8bb-28c7-4357-b5ce-56f344a590dc" />

<img width="1295" height="793" alt="Screenshot 2026-02-04 231708" src="https://github.com/user-attachments/assets/3c5eb924-e18f-420b-ab2b-36939d193b66" />

<img width="1168" height="773" alt="Screenshot 2026-02-04 231334" src="https://github.com/user-attachments/assets/d150ea1b-705c-4c46-90eb-0c6bb16eceac" />

<img width="741" height="748" alt="Screenshot 2026-02-04 224643" src="https://github.com/user-attachments/assets/a790e55e-eab8-475a-a0f4-c7e394cc6251" />

<img width="737" height="750" alt="Screenshot 2026-02-04 222959" src="https://github.com/user-attachments/assets/6230fdab-5320-46be-bd3f-6806be889315" />

<img width="745" height="749" alt="Screenshot 2026-02-04 215829" src="https://github.com/user-attachments/assets/5c0a5744-008f-4819-a555-8f56a8546f99" />

<img width="745" height="751" alt="Screenshot 2026-02-04 215749" src="https://github.com/user-attachments/assets/17481d95-71d2-4639-9e8e-fc6fb9212956" />

<img width="744" height="751" alt="Screenshot 2026-02-04 214445" src="https://github.com/user-attachments/assets/16caf9c7-e5ae-4ab1-9d9f-939d9e898c78" />

<img width="749" height="748" alt="Screenshot 2026-02-04 213617" src="https://github.com/user-attachments/assets/caad79d5-f51a-466e-b243-0fe2061d311d" />


Lessons learnt:
1. I learned that `login local` is critical for SSH because it forces the router to check the username database instead of just a line password.
2. Navigating between User Exec (`>`), Privileged Exec (`#`), and Global Config (`(config)#`) modes is now second nature.



