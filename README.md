# Automating-Information-RECON


<h2>Description</h2>
<p>
A passive reconnaissance scan will be conducted within the Kali Linux VM using Recon-NG. The procedure will involve establishing a controlled workspace, incorporating modules, and executing the scan. This automated scan serves the purpose of validating and complementing the manual scan conducted in the previous "passive reconnaissance" lab.
</p>

<h2>Environments Used</h2>
<ul>
  <li>
    <p><b>Kali Linux VM</b></p>
  </li>
</ul>

<h2>Tools Used</h2>
<ul>
  <li>
    <p><b>Recon-NG</h2>
      
<h2>IMPORTANT NOTE!</h2>
<p>For security reasons, IP addresses and other sensitive information in screenshots have been blurred out.</p>

<h2>Lab walk-through:</h2>

<h2>Screenshot 1:</h2>
<p align="center">
Utilizing Kali Linux, access the terminal window and execute the command 'recon-ng'. Subsequently, press the 'Enter' key.
</p>
<img src="https://i.imgur.com/zId9XIC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h2>Screenshot 2:</h2>
<p align="center">
 Now, input the command 'modules load hackertarget' and press the 'Enter' key. Then, proceed to enter the command 'options set SOURCE Uber.com' and press 'Enter' once again.
</p>
<img src="https://i.imgur.com/cihxYbz.png" height="80%" width="80%" alt="Disk Sanitization Steps" />


<h2>Screenshot 3:</h2>
<p align="center">
Enter the command 'info' and press the 'Enter' key. Subsequently, input the command 'run' and press 'Enter' once more. Evaluate the displayed IP results and take note of the number of hosts identified.
</p>
<img src="https://i.imgur.com/Y7LSo2z.png" height="80%" width="80%" alt="Disk Sanitization Steps" />


<h2>Screenshot 4:</h2>
<p align="center">
Enter the command 'show hosts' and press the 'Enter' key. This will present host information, including IP details, for your examination.
</p>
<img src="https://i.imgur.com/gVrEF7Z.png" height="80%" width="80%" alt="Disk Sanitization Steps" />


<h2>Screenshot 5:</h2>
<p align="center">
  Using your web browser, access the website 'who.is'. Proceed to enter 'uber.com' into the designated search box, and then press the 'Enter' key to initiate the search.
</p>
<img src="https://i.imgur.com/DHwmAUi.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
  
  
<h2>Screenshot 6:</h2>
<p align="center">
From the search results, make a note of the DNS servers obtained. Additionally, pay attention to any other significant information presented in the subsequent sections below.
</p>
<img src="https://i.imgur.com/0jEfZYE.png" height="80%" width="80%" alt="Disk Sanitization Steps" />

    
<h2>Screenshot 7:</h2>
<p align="center">
Within the same web browser, enter "dnsqueries.com" into the search bar and press the 'Enter' key.
</p>
<img src="https://i.imgur.com/mb2fHgY.png" height="80%" width="80%" alt="Disk Sanitization Steps" />

  
 <h2>Screenshot 8:</h2>
<p align="center">
Proceed to scroll down and locate the hostname box on the webpage. Within this box, enter the first DNS server obtained in step 2. Afterward, select the 'run tool' option to initiate the process.
</p>
<img src="https://i.imgur.com/AmcX3vF.png" height="80%" width="80%" alt="Disk Sanitization Steps" />


<h2>Screenshot 9:</h2>
<p align="center">

Take note of the IP address obtained from the results. Repeat the aforementioned steps (step 4) using the second DNS server provided.
</p>
<img src="https://i.imgur.com/pC336aa.png" height="80%" width="80%" alt="Disk Sanitization Steps" />

      
      
 <h2>Screenshot 10:</h2>
<p align="center">

Now, input "whois.arin.net" into the search bar above and press the 'Enter' key. Next, locate the upper right-hand corner and enter the first IP address obtained in the previous step. Press 'Enter' to initiate the search. Analyze the IP address range to confirm the association with the first two DNS servers. Additionally, observe that this information is linked to NSONE, a technology company presently collaborating with UBER.
</p>
<img src="https://i.imgur.com/WGNjoAC.png" height="80%" width="80%" alt="Disk Sanitization Steps" />

 <h2>Screenshot 11:</h2>
<p align="center">
Proceed to scroll down and examine the available point of contact information, carefully analyzing the obtained results.
</p>
<img src="https://i.imgur.com/0QutxLn.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
  
 <h2>Screenshot 12:</h2>
<p align="center">
Enter the following URL 'elliot.org/company-contacts/uber/' into the search bar and press the 'Enter' key.
</p>
<img src="https://i.imgur.com/Khv38x7.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<ul>
  <li>
    <p>
      <b>Notice the Executive Contacts. Using these names and emails found, the data can be used as an attack vector.  </b>
    </p>
  </li>
</ul>  

