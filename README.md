<p align="center">
<img src="https://i.imgur.com/r7UlOH2.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This guide provides instructions for configuring and setting up an osticket system post-installation. It covers essential steps such as role configuration, department setup, team creation, enabling ticket creation for anyone, agent and user management, SLA implementation, and help topic customization. By following these instructions, users can effectively organize their ticketing system and streamline the support process.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Objectives for guide:</h2>


1. Configure Roles <br>

2. Configure Departments <br>

3. Configure Teams <br>
 
4. Allow anyone to create tickets <br>

5. Configure Agents <br>

6. Configure Users <br>

7. Configure SLA (Service Level Agreement) <br>

8. Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 1: Configure Roles</h2>
<p>Navigate to the Admin Panel and go to Agents -&gt; Roles.</p>
<p>Click on "Add New Role" and create a role called "Supreme Admin."</p>
<p>In the permissions section, ensure that all checkboxes related to tickets, tasks, and knowledge are selected.</p>
<p>Save the changes.</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 2: Configure Departments</h2>
<p>In the Admin Panel, go to Agents -&gt; Departments.</p>
<p>Click on "Add New Department" and name it "System Administrators."</p>
<p>Create the department.</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 3: Configure Teams</h2>
<p>Go to the Admin Panel and select Agents -&gt; Teams.</p>
<p>Create a new team by providing a name and adding members from different departments.</p>
<p>Create the team.</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 4: Allow anyone to create tickets</h2>
<p>Access the Admin Panel and go to Settings -&gt; User.</p>
<p>Uncheck the "Registration Required" option under "Require registration and login to create tickets."</p>
<p>Save the changes.</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 5: Configure Agents</h2>
<p>In the Admin Panel, navigate to Agents -&gt; Add New Agent.</p>
<p>Fill in the agent's name, email, and username.</p>
<p>Set a password for the agent.</p>
<p>Assign the agent to a department, specify their roles and access permissions, and add them to any relevant teams.</p>
<p>Create the agent.</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 6: Configure Users</h2>
<p>Access the Agent Panel and go to Users -&gt; Add New User.</p>
<p>Enter the user's email, name, and contact number.</p>
<p>Add the user.</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 7: Configure SLA (Service Level Agreement)</h2>
<p>In the Admin Panel, go to Manage -&gt; SLA.</p>
<p>Create a new SLA plan by providing a name.</p>
<p>Set the time limit for ticket resolution.</p>
<p>Choose the schedule (weekends/weekdays) and define the grace period (the hour within which the ticket needs to be resolved).</p>
<p>Save the SLA plan.</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Step 8: Configure Help Topics</h2>
<p>Access the Admin Panel and go to Manage -&gt; Help Topics.</p>
<p>Add new help topics based on the categories you want to offer, such as "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."</p>
<p>Save the help topics.</p>

</body>
</html>
