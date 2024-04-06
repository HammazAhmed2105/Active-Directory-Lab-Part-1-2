# Active-Directory-Lab
**Note:** I have utilized DFIR's Active Directory Walkthrough to complete this project. (https://www.youtube.com/@MyDFIR)
## What to expect - 
Welcome to the Active Directory and Splunk Integration Lab! In this comprehensive project series, we will embark on a journey to build a home lab environment that not only serves as a practical playground for blue team activities but also provides invaluable insights into the workings of Active Directory, Splunk, and cybersecurity as a whole.

Over the course of five parts, we will meticulously construct our lab environment, starting with the setup of Active Directory, followed by the integration of Splunk for event monitoring and analysis. Through hands-on exercises, we will explore various scenarios ranging from administrative tasks within Active Directory to simulated attack and detection exercises using Kali Linux.

Here's a brief overview of what we'll be covering:

Part 1 - Setting Up the Lab Environment: We'll begin by setting up our virtual lab environment using VirtualBox, deploying Windows Server 2022, Windows 10, Kali Linux, and Splunk instances.

PArt 2 -Exploring Active Directory and Splunk: We'll delve into the fundamentals of Active Directory, learning how to configure and manage resources such as users, computers, and groups. Concurrently, we'll set up Splunk for ingesting events from our Windows Server and target Windows machine.

Part 3 -Configuring Logging and Telemetry: This phase focuses on configuring Sysmon for logging purposes and ensuring proper integration with Splunk, laying the foundation for effective monitoring and analysis.

Part 4 -Implementing Active Directory: We'll configure Active Directory on our Windows Server, promote it to a domain controller, create domain users, and join a target PC to our domain.

Part 5 -Simulated Attack and Detection: In the final part, we'll simulate a brute force attack using Kali Linux against one of our domain users, analyzing the telemetry generated in Splunk. Additionally, we'll explore the capabilities of Atomic Red Team to further enhance our understanding of attack detection.

<h2>In our Virtual Machine we will have 2 Computers, 1 attacker machine, and 1 Target Machine. This will all be installed using Virtual Box. </h2>
<h3>Part 1</h3>
- Creating a Logical Diagram 
<img src="https://i.imgur.com/F57jfvR.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
- Hardware Requirements:
  - Windows with at least 16 gigs of RAM and 250 GB of Disk Space.


## Part 2
**Note:** I will not be explaining the basics, such as installing virtual machines and Windows Server, but I will be providing helpful links with timestamps.

- Installing Virtual Box 
  - Timestamp: 2:33 - 5:18 
  - [Tutorial Link](https://www.youtube.com/watch?v=2cEj3bS5C0Q&t=30s)

- Installing Windows Machine 
  - Timestamp: 5:21 - 8:30 
  - [Tutorial Link](https://www.youtube.com/watch?v=2cEj3bS5C0Q&t=30s)

- Installing Kali 
  - Timestamp: 9:00 - 12:00 
  - [Tutorial Link](https://www.youtube.com/watch?v=2cEj3bS5C0Q&t=30s)

- Installing Windows Server 
  - Timestamp: 12:30 - 16:08 
  - [Tutorial Link](https://www.youtube.com/watch?v=2cEj3bS5C0Q&t=30s)

- Installing Splunk 
  - Timestamp: 16:20 - 20:00 
  - [Tutorial Link](https://www.youtube.com/watch?v=2cEj3bS5C0Q&t=30s)





