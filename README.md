<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install and Enable Internet Information Services(IIS)
- Install Necessary Software
- Register PHP Manager within IIS
- Install osTicket
- Install and Configure HeidiSQL

<h2>Installation Steps</h2>

<p>
  
![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/c5d8d25e-cf9f-4c88-b4ed-7f6baa99843b)
![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/8996dae9-730e-4456-b987-aa27c448f930)
</p>
<p>
To install Internet Information Services (IIS) on a Windows computer, open the Control Panel, click on "Programs," then "Turn Windows features on or off." In the dialog box that appears, scroll down to find "Internet Information Services" and check the box next to it. Click "OK" to initiate the installation. Once installed, open the IIS Manager, select the desired website or application, and click "Start" to enable IIS and make it accessible via the internet.
</p>
<br />

<p>
  
![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/0db99c32-ff74-4c0c-8d9f-9ff04004cd35)
![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/123b3b62-09e7-4b69-82a3-652d5a3f63f7)
![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/9379e4ea-edf9-45dc-8ce0-316aacfd5740)
![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/bbc705da-1911-4264-b5cf-a2a8ee4ee322)

</p>
<p>
To run Internet Information Services (IIS) on a Windows computer, you don't need to install any additional software as IIS comes pre-installed on most versions of Windows. However, if you're using an older version of Windows or a specific edition that doesn't include IIS, you'll need to install it by going to the Control Panel, clicking on "Programs," then "Turn Windows features on or off," and selecting "Internet Information Services" to install it. Some of those installs include PHP Manager and Rewrite module.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/27391a78-8c5c-43a2-b490-381afe8bdff4)

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/4be11cdf-acc6-4884-bf59-e417992bed73)

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/0e316ae9-54c3-4233-a598-3e832cf01675)
</p>
<p>
To register PHP Manager and enable certain settings, open IIS Manager, select the server node in the Connections pane, and double-click on "PHP Manager" in the Features View. From there, you can enable or disable various PHP settings, such as adjusting PHP version, configuring extensions, and modifying PHP directives to suit your requirements.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/4e81c107-6547-4743-87ca-49c5e2b2737b)

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/9aab97ff-2577-418f-b978-84ddcfdab7dc)
</p>
<p>
If you have successfully registered PHP Manager and enabled the desired settings, you should see the PHP Manager interface within the IIS Manager window. It typically appears as a separate module with options to manage PHP configurations, extensions, and settings. Additionally, you may notice that your PHP-based websites or applications are functioning correctly, indicating that the configurations have been applied successfully. As seen above.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/129f3c20-4376-483a-b981-01bc5349ef0f)
![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/f23e5f03-7201-4c82-8caa-d0aadc677ab5)
</p>
<p>
To start HeidiSQL and connect to a database, you need to first download and install HeidiSQL from the official website. Once installed, open the HeidiSQL application and click on "New" to create a new session. Enter the necessary details, such as the database host, username, password, and port, and click "Open" to establish a connection to the database.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/e4848fde-9aa2-43f5-9a0b-93900f2edb82)

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/ca58826b-c9b9-4ce6-bcea-e115207a734f)
</p>
<p>
To start osTicket, you need to fill in all the necessary information during the setup process. This includes providing details such as the database host, username, password, and database name. By accurately providing this information, you can successfully set up osTicket and have it ready for use as a ticketing system.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/11ea13e8-3c0a-4817-b526-8579943b0d93)

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/f3dc65b8-8815-444f-b759-6320ea3baa43)

![image](https://github.com/ijoshua932/osticket-prereqs/assets/139269375/718049a8-3384-40b6-9b29-3be0828fa0c8)
</p>
<p>
If you have successfully filled in all the necessary information during the setup process of osTicket, you should see the osTicket interface or dashboard. This interface typically displays options to manage tickets, configure settings, and interact with your support system. Additionally, you may notice various features like ticket queues, ticket search, and customer interactions, indicating that osTicket has been set up correctly, and that the websites for submitting tickets and admin login are up and running.
</p>
<br />
