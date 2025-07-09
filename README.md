# SIM-Jacker
SIMJacker is a SIM card vulnerability discovered in 2019 that allows attackers to remotely execute commands on a victim’s mobile device by sending specially formatted OTA (over-the-air) SMS messages to the SIM card.

🧠 How It Works:
It exploits the [SIM Toolkit (STK)] and S@T Browser (SIMalliance Toolbox Browser).

Attackers send a binary SMS containing S@T commands (like SETUP CALL, SEND USSD, SEND SMS, etc.).

These commands are processed silently by the SIM without notifying the user.

📡 Typical Payload Commands:
SETUP CALL – Forces the phone to call a number.

SEND USSD – Executes a USSD request (e.g., balance check).

SEND SMS – Sends silent SMS messages.

PROVIDE LOCAL INFO – Gets location or device info.

⚠️ Simjacker allows remote tracking, surveillance, and SIM-based control, often without user interaction or visible symptoms.

POC https://www.youtube.com/watch?v=IpgypEw1bkw&t=2s

for more info TG Mini0com 

Email mini0com.x@gmail.com
![image alt](https://github.com/Mini0com/SIM-Jacker/blob/a5df308ab0473d8e132b1db537c09dc425a22d91/Screenshot%20from%202025-07-09%2022-18-54.png)
![image alt](https://github.com/Mini0com/SIM-Jacker/blob/a5df308ab0473d8e132b1db537c09dc425a22d91/Screenshot%20from%202025-07-09%2022-19-42.png)
