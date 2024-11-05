<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1> osTicket: Ticket Resolution and Troubleshooting </h1>


<p>Welcome to "osTicket: Ticket Resolution and Troubleshooting." This project is designed to guide you through osTicket, a powerful open-source help desk solution, focusing on ticket resolution and troubleshooting. We will delve into the ticket lifecycle, from initiation to resolution, and examine troubleshooting strategies to address common issues. This project aims to empower IT professionals, help desk agents, and support teams to navigate challenges seamlessly, ensuring a smooth and effective support experience for end-users.</p>

<h2>Prerequisites</h2>

- <a href="https://github.com/kirkgacias/osticket-prereqs"> osTicket - Prerequisites, Setup, and Installation </a>

<h2>Key Objectives</h2>

<h4>Mastering Ticket Resolution</h4>

- Understand the complete lifecycle of a ticket within osTicket, from the initial intake to its successful resolution.

<h4>Efficient Troubleshooting Techniques</h4>

- Explore and implement troubleshooting strategies for common IT issues, ensuring quick and effective problem-solving.

<h4>Enhancing User Satisfaction</h4>

- Learn how to provide timely and effective support to end-users, fostering a positive experience and minimizing downtime.

<h4>Building a Knowledge Base</h4>

- Develop a comprehensive knowledge base that documents common issues and their resolutions, empowering both support teams and end-users.



<h2>Environments and Technologies Used</h2>

- osTicket
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)



<h1>Tickets</h1>

<h3>Scenario A: Granting Admin Rights</h3>

<p><strong>User:</strong> James Holden</p>

<h4>Background:</h4>



<p>James Holden, a senior software developer, has successfully obtained approval for elevated administrative rights. As the IT administrator, your task is to grant James the necessary permissions while ensuring a secure and controlled activation process.
</p>

<br>

<img width="593" alt="John Jacob first ticket" src="https://i.imgur.com/P2nzRMY.png">

<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Verification</h5>

- Validate John's identity and admin rights approval.

<h5> Access Control Configuration:</h5>

- Once verification is done, modify Johns's user profile and assign the appropriate administrative privileges.
- Ensure that his machine allows him remote access

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Configure specific permissions based on John's approved request, such as adding him to the Remote Desktop Users Group</strong></p>

<img width="300" alt="rdp" src="https://i.imgur.com/5kZlIh6.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h5>Communication:</h5>

- Inform John that his admin rights have been granted successfully.
- Include a summary of the specific permissions he now holds and any relevant guidelines for responsible use.

<h5>Documentation & Closure:</h5>

- Document the completion of the admin rights activation in osTicket.
-Close the ticket, indicating that the task has been completed, and provide documentation for future audits or inquiries.

<img width="592" alt="Done w john " src="https://i.imgur.com/L6dELth.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario B: Addressing Slow System Performance </h3>

<p><strong>User:</strong> Tristan Cannoli </p>

<h4>Background:</h4>


<p>Tristan Cannoli, a marketing manager, submits a ticket through osTicket, reporting a low memory warning and persistent slow performance on her workstation. As the IT helpdesk agent, your objective is to diagnose and resolve the issue to enhance Tristan's overall system responsiveness.

</p>

<br>

<img width="593" alt="Tristan ticket" src="https://i.imgur.com/Mz2ZP8e.png">

<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Engage in a threaded discussion to gather more information about the specific performance issues Tristan is encountering.
- Request details such as recent software installations, background processes, and any error messages he might have encountered

<img width="592" alt="reply" src="https://i.imgur.com/4LYzIEA.png">


<h5> Remote Diagnosis:</h5>

- Utilize a remote desktop connection to conduct a  diagnosis of Tristan's workstation.

<h3> Specific Problem Identified:</h3>

<p>Tristan Cannoli's workstation is experiencing slow performance and low memory warnings mainly due to not having enough RAM for his demanding marketing applications. These include graphic design and video editing software, along with many browser tabs open at once. A lack of regular cleanup, like deleting temporary files and optimizing disk space, has also made the system slower over time.</p>

<h3> Resolution Steps:</h3>

- Go to add or remove programs and delete any unnecessary applications

<img width="400" alt="add or remove" src="https://i.imgur.com/NuxsVI5.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Check Task Manager to identify resource-intensive processes, unnecessary apps at startup, and potential bottlenecks affecting system performance.</strong></p>

- Empty the recycling bin to free up some disk space

<img width="500" alt="recycle" src="https://i.imgur.com/MuPIIjD.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Open the Disk Cleanup application and perform a cleanup.</strong></p>

<img width="500" alt="cleanup" src="https://i.imgur.com/Yo45at0.png">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Go to Windows Features and turn off features not needed by the user</strong></p>

- After performing the tasks, diagnose the performance of the workstation 

<img width="500" alt="on or off" src="https://i.imgur.com/a1D7o19.png">


<h5>Documentation & Closure:</h5>

- Inform Tristan through osTicket of the initial assessment findings.
- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.
- Close the ticket within osTicket when Tristan confirms the satisfactory resolution of the slow system performance issue or when the case is deemed resolved based on the follow-up assessments.

<img width="591" alt="Tristan closed" src="https://i.imgur.com/bodyKm5.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario C: Laptop Camera Not Working on Windows 11</h3>

<p><strong>User:</strong> Taco Sauce </p>

<h4>Background:</h4>


<p>Taco Sauce, a sales representative, submits a ticket through osTicket, reporting that the integrated camera on his laptop is not functioning properly after upgrading to Windows 11. Taco relies on video calls for client meetings and needs a prompt resolution to ensure uninterrupted communication.

</p>

<br>

<img width="593" alt="Screenshot" src="https://i.imgur.com/CpYGJ4p.png">


<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Engage in a threaded discussion within osTicket to gather more information about the issue.

<img width="590" alt="Taco Sauce reply" src="https://i.imgur.com/BvcV6kh.png">


<h5> Remote Diagnosis:</h5>

- Access Taco’s laptop through a remote desktop connection
- Check device manager if the necessary drivers are installed

<br>

<img width="350" alt="devmgmt" src="https://i.imgur.com/YhSmMUz.jpeg">


<h3> Specific Problem Identified:</h3>

<p>Upon conducting a remote diagnostic session with Taco Sauce's laptop, it was discovered that the integrated camera is not recognized by the Windows 11 operating system. This issue seems to stem from outdated camera drivers that are incompatible with Windows 11.
</p>

<h5> Communication:</h5>

- Inform Taco through osTicket that the initial assessment indicates a potential driver-related issue with the camera after the Windows 11 upgrade

<img width="592" alt="llll" src="https://i.imgur.com/dtyBG2u.png">



<h3> Resolution Steps:</h3>

- Download the camera drivers from the manufacturers website and install the drivers manually
- Reboot the system after making the changes to ensure proper implementation.

<img width="592" alt="bigboi" src="https://i.imgur.com/uKcSb7D.png">


<h5>Documentation & Closure:</h5>

- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.
- Close the ticket within osTicket when Taco confirms the satisfactory resolution of the laptop camera issue

<img width="592" alt="closed" src="https://i.imgur.com/iMSe1eD.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario D: Resolving Email Synchronization Issues</h3>

<p><strong>User:</strong> Burt Johnson </p>

<h4>Background:</h4>


<p>Burt Johnson, a sales executive, submits a ticket via osTicket, reporting that his email is not synchronizing properly across his devices. As the IT help desk agent, your goal is to troubleshoot and resolve the synchronization issue to ensure seamless access to his emails across all platforms.

</p>

<br>

<img width="587" alt="Burt" src="https://i.imgur.com/wL3iG42.png">



<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Initiate a detailed conversation with Burt through osTicket, asking for specifics about the devices he uses, the email client or service, and any error messages he has encountered.

<img width="590" alt="amos2" src="https://i.imgur.com/UrblyCt.png">

- Determine if the issue started after a particular update or change in settings.
- Establish a remote desktop connection to further diagnose the problem


<h3> Specific Problem Identified:</h3>

<p>During the remote diagnosis, it's discovered that Burt's smartphone and tablet are not set to use IMAP for his email account, which is essential for synchronizing emails across multiple devices. Instead, they are configured with POP3, leading to emails being downloaded to a single device and not being accessible on others.

</p>


<h3> Resolution Steps:</h3>

- Change the email settings from POP3 to IMAP on both his smartphone and tablet.
- Ensure that Amos's laptop is also configured to use IMAP for his email account, ensuring consistency across all devices.

<img width="590" alt="amos2" src="https://i.imgur.com/2XAeg9o.png">


<p><strong>Test email synchronization by instructing Burt  to send a test email to himself and check if it appears across all his devices.</strong></p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h5>Documentation & Closure:</h5>

- Document all steps taken to resolve Burt's email synchronization issue within osTicket, including the initial problem identification, communication logs, and the resolution process.
- Close the ticket within osTicket once Burt confirms the issue is resolved to his satisfaction, ensuring a record of the solution is available for future reference.

<img width="589" alt="Burt3" src="https://i.imgur.com/2XAeg9o.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario E: Addressing Printer Connectivity Problems </h3>

<p><strong>User:</strong> Jawson Baker </p>

<h4>Background:</h4>


<p>Jawson Baker, an account manager, submits a ticket through osTicket, indicating that he cannot connect to the network printer from his laptop. The printer is essential for his role, as he frequently needs to print contracts and reports for clients. As the IT help desk agent, your task is to diagnose and rectify the connectivity problem to restore Jawson's printing capabilities.

</p>

<br>

<img width="589" alt="Jawson ticket1" src="https://i.imgur.com/33NVpx3.png">




<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Communicate with Jawson and ask further questions about the problem
- Establish a remote desktop connection to Jawson’s workstation to further diagnose the issue.

<img width="588" alt="Jawson 2" src="https://i.imgur.com/njtVdp2.png">


<h3> Specific Problem Identified:</h3>

<p>The primary issue hindering Jawson Baker from connecting to the network printer is an incorrect printer IP address configuration on his laptop. After the recent network upgrade, the IP addresses of several devices, including printers, were changed to accommodate the new networking schema. However, Jawson's laptop retained the old IP address for the printer, leading to failed connection attempts. This misconfiguration is a common oversight following network modifications, especially if devices are manually configured or if the update communication does not reach all users effectively.


</p>


<h3> Resolution Steps:</h3>

- Update Printer IP Address on Jawson's Laptop
- This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address. This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address.

<img width="400" alt="printer" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/4dbe262a-bd46-4b65-aa6f-6ec1c563fec4">


<p><strong>Verify connectivity by attempting to print a test page.</strong></p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h5>Documentation & Closure:</h5>

- Document the steps taken to resolve the issue within osTicket Additionally, update any internal IT documentation to reflect the new network configuration and troubleshooting steps for related issues.
- Close the ticket once Jawson confirms the issue is resolved. 

<img width="590" alt="printer" src="https://i.imgur.com/Uo37wV0.png">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h2>Final Thoughts and Key Insights</h2>

<p>
This project serves as an essential guide for IT help desk agents and support teams, offering in-depth scenarios from granting administrative rights to resolving complex email synchronization issues. It highlights the critical role of a structured approach in IT troubleshooting, emphasizing key insights:</p>

- Structured Problem-Solving: Importance of a step-by-step approach from problem identification to solution documentation.
- User-Centric Communication: Keeping users informed is essential. Keeping users updated is key to trust and a positive experience.
- Adaptability and Continuous Learning: The need for IT professionals to stay adaptable and continuously learn to tackle a wide range of issues.
- Documentation and Knowledge Sharing: Essential for building a knowledge base that facilitates quicker future resolutions.

<p>These points highlight the essentials of effective IT troubleshooting: methodical problem-solving, clear communication, adaptability, and thorough documentation.</p>

<h1>Thank you! &#127881; </h1>
