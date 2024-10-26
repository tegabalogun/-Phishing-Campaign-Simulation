<h1>Phishing-Campaign-Simulation</h1>

 

<h2>Description</h2>
Created a phishing site hosted on an Azure Virtual Machine to simulate real-world phishing attacks. The project demonstrates how attackers can use phishing tactics to steal credentials and underscores the importance of Multi-Factor Authentication (MFA) in mitigating phishing threats. Phishing links were sent via email to simulate a realistic scenario, allowing for a comprehensive view of how credentials could be captured by attackers and emphasizing the need for additional security layers.

<h2>Languages and Utilities Used</h2>

- <b>PHP</b>
- <b>HTML/CSS</b>
- <b>Azure Virtual Machines</b>
- <b>Apache Web Server</b>

<h2>Environments Used</h2>

- <b>Azure Cloud</b> - Hosted on an Ubuntu 20.04 LTS VM

<h2>Program Walk-through:</h2>


<p align="center">
Create an Azure Virtual Machine for hosting the phishing site: <br/>
<img src="https://example.com/vm-setup.png" height="80%" width="80%" alt="Setting up Azure VM"/>
<br />
<br />
Configure necessary ports (HTTP, HTTPS, SSH) for remote access:  <br/>
<img src="https://example.com/configure-ports.png" height="80%" width="80%" alt="Configuring VM Ports"/>
<br />
<br />
Install Apache Web Server and upload phishing page code: <br/>
<img src="https://example.com/apache-install.png" height="80%" width="80%" alt="Installing Apache"/>
<br />
<br />
Set up a storage account for hosting the logo image used on the phishing page: <br/>
<img src="https://example.com/storage-setup.png" height="80%" width="80%" alt="Azure Storage Account Setup"/>
<br />
<br />
Enable blob anonymous access in the storage account for public visibility of images: <br/>
<img src="https://example.com/enable-blob-access.png" height="80%" width="80%" alt="Enabling Blob Access"/>
<br />
<br />
Add the logo URL to the phishing page and test the display: <br/>
<img src="https://example.com/add-logo.png" height="80%" width="80%" alt="Adding Logo to Phishing Page"/>
<br />
<br />
Create the `process.php` file to handle credential capture: <br/>
<img src="https://example.com/process-php.png" height="80%" width="80%" alt="Credential Capture Script"/>
<br />
<br />
Send phishing email containing the phishing link and interact with the page: <br/>
<img src="https://example.com/phishing-email.png" height="80%" width="80%" alt="Phishing Email"/>
<br />
<br />
Review captured credentials on the virtual machine to observe results: <br/>
<img src="https://example.com/captured-credentials.png" height="80%" width="80%" alt="Captured Credentials"/>
</p>
