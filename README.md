<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1> osTicket: Ticket Lifecycle Examples </h1>


<p>This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. We will cover the ticket lifecycle from initiation to resolution and develop effective troubleshooting strategies for common issues. This project equips IT professionals, help desk agents, and support teams to handle challenges smoothly, ensuring a seamless support experience for end-users.</p>

<h2>Prerequisites</h2>

- <a href="https://github.com/ncgriffin/osticket-prereqs"> osTicket: Prerequisites and Installation </a>

<h2>Environments and Technologies Used</h2>

- osTicket
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution



<h1>Tickets</h1>

<h3>Scenario 1: Password Reset</h3>

<p><strong>User:</strong> Karen Jones</p>

<h4>Background:</h4>



<p>Karen Jones, a marketing department employee, forgot her recently changed password and failed to reset it using the 'Forgot Password' function due to unrecognized security answers. She then noticed she's been using an outdated email address. As the IT administrator, your responsibility is to verify identity, reset the password, and guide the user to prevent future issues. 
</p>

<br>

<img width="593" alt="Karen Jones first ticket" src="https://imgur.com/TDKwdK4.png">

<br>
<br>
<p><strong>.</strong></p>

<h3>Assignment and Communication:</h3>

Here we are able to see the ticket has been issued to IT Support Technician, Nick Griffin, and exchange between him and Karen. 

<img width="650" alt="rdp" src="https://imgur.com/JeSc0iO.png">

<p><strong>.</strong></p>

<p><strong>Resolution & Closure:</strong></p>

- Document the completion of the task in osTicket, close the ticket

<img width="700" alt="3" src="https://imgur.com/1w25bOR.png">


<h3>Scenario 2: System Outage Issue </h3>

<p><strong>User:</strong> Cliff Tucker</p>

<h4>Background:</h4>


<p>An unexpected outage of the ERP software occurred, disrupting manufacturing and sales operations. Cliff Tucker, an Account Executive, submits a ticket through osTicket, eporting a system error affecting users; indicating potential server overload or network issues. The IT technician must quickly diagnose the root cause of the outage, and coordinate with the relevant IT teams to resolve it.

</p>

<br>

<img width="593" alt="Cliff ticket" src="https://imgur.com/dQX0lFx.png">

<br>
<br>

<h3>Assignment & Communication:</h3>


- Engage in a threaded discussion to gather more information about the specific issues Cliff and other users are encountering.

<img width="615" alt="reply" src="https://imgur.com/Y5muqYN.png">

<p><strong>.</strong></p>

<h5>Documentation & Closure:</h5>

- Document the troubleshooting steps taken within osTicket, detailing the problem and resolution.
- Close the ticket within osTicket when the case is deemed resolved based on the corrected network error.

<h3>Scenario C: Laptop Camera Not Working on Windows 11</h3>

<p><strong>User:</strong> Alex Kamal</p>

<h4>Background:</h4>


<p>Alex Kamal, a sales representative, submits a ticket through osTicket, reporting that the integrated camera on his laptop is not functioning properly after upgrading to Windows 11. Alex relies on video calls for client meetings and needs a prompt resolution to ensure uninterrupted communication.

</p>

<br>

<img width="593" alt="Screenshot 2024-02-16 094853" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/55359757-dda2-4507-9ed7-ee0aed93258a">


<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Engage in a threaded discussion within osTicket to gather more information about the issue.

<img width="590" alt="alex k reply" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/cd96aaee-84c5-4b0f-a963-8e9275cc6944">


<h5> Remote Diagnosis:</h5>

- Access Alex’s laptop through a remote desktop connection
- Check device manager if the necessary drivers are installed

<br>

<img width="350" alt="devmgmt" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/02b38f22-3489-44cd-a912-4d1728676ce6">


<h3> Specific Problem Identified:</h3>

<p>Upon conducting a remote diagnostic session with Alex Kamal's laptop, it was discovered that the integrated camera is not recognized by the Windows 11 operating system. This issue seems to stem from outdated camera drivers that are incompatible with Windows 11.
</p>

<h5> Communication:</h5>

- Inform Alex through osTicket that the initial assessment indicates a potential driver-related issue with the camera after the Windows 11 upgrade

<img width="592" alt="llll" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/00926f92-e76d-43c2-ace9-1ca45090e7a6">



<h3> Resolution Steps:</h3>

- Download the camera drivers from the manufacturers website and install the drivers manually
- Reboot the system after making the changes to ensure proper implementation.

<img width="592" alt="bigboi" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/fe5a3910-a379-4ea5-9c23-93f661e18789">


<h5>Documentation & Closure:</h5>

- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.

- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.
- Close the ticket within osTicket when Alex confirms the satisfactory resolution of the laptop camera issue

<img width="592" alt="closed" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/36db4069-fbed-4628-988a-066745fc7115">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario D: Resolving Email Synchronization Issues</h3>




<h2>Final Thoughts and Key Insights</h2>

<p>
This project serves as an essential guide for IT help desk agents and support teams, offering in-depth scenarios from granting administrative rights to resolving complex email synchronization issues. It highlights the critical role of a structured approach in IT troubleshooting, emphasizing key insights:</p>

- Structured Problem-Solving: Importance of a step-by-step approach from problem identification to solution documentation.
- User-Centric Communication: Keeping users informed is essential. Keeping users updated is key to trust and a positive experience.
- Adaptability and Continuous Learning: The need for IT professionals to stay adaptable and continuously learn to tackle a wide range of issues.
- Documentation and Knowledge Sharing: Essential for building a knowledge base that facilitates quicker future resolutions.

<p>These points highlight the essentials of effective IT troubleshooting: methodical problem-solving, clear communication, adaptability, and thorough documentation.</p>

<h1>Thank you! &#127881; </h1>








