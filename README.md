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
