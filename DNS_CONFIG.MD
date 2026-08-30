Prerequisites: Make sure that apps are installed and ISO are already downloaded. Also make sure that the github repository is already cloned and downloaded in the PC
GITHUB REPOSITORY: https://github.com/Rivanyte/DNS-CONFIG
•	Go to the GitHub link, and download the Repository
•	Click the button “<> Code” and click Download Zip

•	Save it as default name

•	verify if the download is finished
[3.1]<Image placeholder>

Step 1: Creating Windows Virtual Machine
•	Click Windows Button and Search for VMware Workstation
•	Open The Application VMware Workstation Pro
[4.1]<Image placeholder>

Step 1.2: Creating Windows Virtual Machine
•	Click “Ctrl + N” to create New Virtual Machine, and click “Next >”
[5.1]<Image placeholder>
•	Click “I will install the operating system later.” and Click Next >
[6.1]<Image placeholder>
•	Select “Microsoft Windows”, and under Version, select “Windows Server 2022”
[7.1]<Image placeholder>
•	Then Click Next >
[8.1]<Image placeholder>
•	Type your desired Virtual Machine Name:
•	For Instance, WINHACKER-M (”M is your Monitor Number”)
[9.1]<Image placeholder>
•	After typing your desired machine name, click "Next >"
[10.1]<Image placeholder>
•	Default Setting for maximum disk size is okay, you don’t have to change anything just click Next
[11.1]<Image placeholder>

Step 1.3: Customizing Virtual Machine Hardware
•	We need to customize the machine for it to run smoothly
[12.1]<Image placeholder>
•	For Memory (Ram Size), Select your desired memory 
•	If your Memory is below 16GB, Selecting 4gb is enough for the system to run smoothly
•	If your Memory (Ram Size is above 16GB, 8gb is enough for the system to run smoothly
[13.1]<Image placeholder>
•	On processor, select number of cores per processor 2, that is enough for the system to run smoothly
[14.1]<Image placeholder>
•	Under CD/SATA, select the ISO Image you downloaded
•	Select “Use ISO image file:” and then click “Browse…”
[15.1]<Image placeholder>
•	On the pc under Rivan Possession, On HP Products Mini PC they have their own D: Drive, under __RivanAPPS, open that folder
•	On Dell PC, usually on the center Isle, only C Drive is there, under __RivanAPPS, open that folder
•	On your own pc, find the downloaded ISO
[16.1]<Image placeholder>
•	Look for “SERVER_EVAL_x64FRE_en-us”  and then click it, then click Open
[17.1]<Image placeholder>
•	This is for Rivan Method, we need to add another network adapter to be connected on the switch
•	Click Add, then click Network Adapter, then finish
[18.1]<Image placeholder>
•	Change the added Network to Bridged and click Replicate, that way it can communicate to the switch with no problems
[19.1]<Image placeholder>
[20.1]<Image placeholder>
•	After all checking, adding, and fixing the hardware machine, if all is correct we can now then close and click Finish
[21.1]<Image placeholder>

Step 2: Powering on Virtual Machine
•	Click Power on this virtual machine
[22.1]<Image placeholder>
•	This Part is all about speed, the moment you see this you need to click inside the virtual machine and click enter, if you didn’t do this the next image shown will be the error
[23.1]<Image placeholder>

SAMPLE ERROR
•	To avoid this, the moment you see this the line “Press any key to boot from CD or DVD…..” you need to click inside the virtual machine and click enter
[24.1]<Image placeholder>

If all procedures are correct, the windows logo will run on the virtual machine
[25.1]<Image placeholder>

Step 3: Windows Installation Prerequisites
•	After powering on, you can skip this part, just click Next
[26.1]<Image placeholder> 
Then Click “Install now”
[27.1]<Image placeholder>
•	After that, the windows installation will go to setup
[28.1]<Image placeholder>
•	Select the type of Operating system you want to install
•	Select the 2nd option, this option has a GUI 
•	Then click Next
[29.1]<Image placeholder>
•	Click the checkbox icon to accept license terms
•	Then click Next
[30.1]<Image placeholder>


•	Select the 2nd Option to Install Microsoft Server
[31.1]<Image placeholder>

•	After selecting custom, we will now be directed to selected the disk/drive to install the OS
•	Select the only drive to install, then click Next
[32.1]<Image placeholder>

•	After all configuration
[33.1]<Image placeholder>
•	Wait for the Installation to Finish
[34.1]<Image placeholder>


Step 4: Customizing Windows Virtual Machine
•	Type your desired password, for this lab we will use Rivan Password
•	C1sc0123
[35.1]<Image placeholder>
•	After re-entering your password and if it is correct, click Finish
[36.1]<Image placeholder>

Step 5: Logging on Windows Virtual Machine
•	To proceed to logging in, Click the keys “Ctrl+Alt+Insert”, that way only the virtual machine shows the input of the password
[37.1]<Image placeholder>

•	Type in your created password, for this lab it is C1sc0123, then click Enter
[38.1]<Image placeholder>
•	wait for the system to boot up
[39.1]<Image placeholder>

Step 6: Changing IP Address
•	On 1st startup the Network notification will show, just click yes
[40.1]<Image placeholder>
•	Minimize the Server Manager, we will need it later on
[41.1]<Image placeholder>

Step 6.1: Opening Network Connections
•	On your Keyboard click Windows Key ⊞ + R
•	Then type ncpa.cpl this will open the Network Connections Panel
[42.1]<Image placeholder>
•	Rename Network Adapter 1 to NAT, this is connected to the internet
•	Rename Network Adapter 1 to Tunay na BRIDGED, this network adapter is connected to the switch
[43.1]<Image placeholder>

•	Change the IP Address of TUNAY na BRIDGED to the same Subnet of the vlan 1 of the switch, that way the virtual server can communicate to the switch
•	Right Click the Network Adaptor TUNAY na BRIDGED
•	Click Properties
•	Double Click Internet Protocol Version 4 (TCP/IPv4)
•	then change obtain to Use the Following IP Address:
IP Address: 10.M.1.8
Subnet Mask: 255.255.255.0
Default Gateway: 10.29.1.4  /no default gateway

Preferred DNS Server: 127.0.0.1
•	After configuring the IP Address, click “OK” 2 Times
[44.1]<Image placeholder>
•	Then the Network 2 Notification will show, click Yes
[45.1]<Image placeholder>

Step 7: Verifying Changed IP Address
•	On your Keyboard click Windows Key ⊞ + R
•	Then type CMD to open Command Prompt
•	Then click OK
[46.1]<Image placeholder>
•	On CMD, type ipconfig
•	NAT should be getting dhcp from the IP Address 208.8.8.0 each VM may differ on the 4th Octet
•	Ethernet adapter TUNAY na BRIDGED should be getting the static IP Address
[47.1]<Image placeholder>

Step 7.1: Verifying if Changed IP can Communicate to TUNAY na pc and Switch
•	On CMD, Ping the SWITCH
•	type “ping 10.M.1.4” it should be getting a reply
•	type “ping 10.M.1.10” it should be getting a reply
Why the first ping times out for the switch
Because ARP resolution takes time:
•	First ping → ❌ times out (ARP still resolving)
•	Second ping → ✅ success (MAC  already known)
•	Next pings → ✅ fast replies
[48.1]<Image placeholder>

Step 8: Turning off the Firewall using Poweshell
•	Click Windows Key ⊞ and Type Powershell, Select Windows Powershell ISE
[49.1]<Image placeholder>
•	Wait for it to boot up
[50.1]<Image placeholder>
•	The window will show and, clcik the show script pane thats where we need to type
•	We can type Directly to the CLI
•	But for this practice we need to show how Powershell ISE Works
[51.1]<Image placeholder>

SSStep 8.1: Typing Commands to Powershell ISE
•	type this command:
•	“set-netfirewallprofile -name public,private,domain -enabled false”   
•	Then click the Play button or F5 Key to run script
[52.1]<Image placeholder>
•	After running the script, no red lines should show
•	If red error shows, that means that there is a typo in the command
[53.1]<Image placeholder>


Step 9: Accessing a Virtual Machine’s C$ Drive from Host via Run Command
•	On your host (real PC):
•	Press:
Windows + R
•	Type:
\\<VM-IP>\C$
•	Example:
\\10.29.1.8\C$
•	Then click OK
[54.1]<Image placeholder>

•	This will open the VM C$ Drive
•	Open Your Local Files
1.	Open File Explorer on your host
2.	Navigate to the folder where your files are located 
(e.g., D:\RivanApps)
[55.1]<Image placeholder>
•	Select the Files to Transfer
1.	Click the files you want (e.g., installers)
2.	Use:
o	Ctrl + Click to select multiple files 
or
o	Drag your mouse to highlight them
o	On this lab we need the:
o	hMailServer and Thunderbird
•	Drag and Drop to the VM
a.	Click and hold the selected files
b.	Drag them to the C$ window (VM drive)
c.	Release the mouse to drop them

•	Wait for Transfer
o	Windows will begin copying the files
o	A progress bar will appear
o	Wait until it completes

•	Verify the Files
a.	In the VM C$ window, confirm the files are visible
b.	You can now use them inside the VM
[56.1]<Image placeholder>
[57.1]<Image placeholder>
•	We also need the DNS Folder to be pasted on the VM C$
•	Copy and paste from your host  pc to the VMC$
[58.1]<Image placeholder>

Step 9.1: Verify the folder/apps inside the VM
•	Open C Drive in Virtual Machine to check if the copied files are available
[59.1]<Image placeholder>

Step 10: Extract the DNS-CONFIG.main zip file
•	Right Click the zipped file, then click extract files, then it will open a new tab, then click extract
•	wait for the extraction to finish it will then generate a new folder
[60.1]<Image placeholder>
•	Close all the folders after verifying if the extraction is completed.
[61.1]<Image placeholder>


Step 11: Adding/Managing Roles and Features for DNS
•	Re-open the Server manager
[62.1]<Image placeholder>
•	Click Manage 
[63.1]<Image placeholder>
•	Then Click Add Roles and Features
[64.1]<Image placeholder>
•	Click Next 2 times
[65.1]<Image placeholder>
•	If the IP Address on the virtual machine that we changed is correct, we should see it in the server pool
•	If not, installation of DNS and other features will fail
•	Click next after verifying 
[66.1]<Image placeholder>
•	On the next page we will see the Roles, click the checkbox of DNS Server then a new tab will show click Add Features
[67.1]<Image placeholder>
•	After that, the unchecked box will now be checked
•	Click next
[68.1]<Image placeholder>
•	After that we will now go to Features, we will now proeed on installing .NET Framework 3.5 Features
•	Click the checkbox of .NET Framework 3.5 Features
DNS does not require the .NET Framework to run. However, some management tools, scripts, and future features may depend on it. Installing it now helps avoid errors and saves time later.
[69.1]<Image placeholder>
•	Click next and then Confirm Installation Selections and click Install
[70.1]<Image placeholder>
•	Then Wait for the Installation to finish, it may take some time to install kindly wait for it
[71.1]<Image placeholder>
•	After Installation we can now close the Wizard Window
[72.1]<Image placeholder>


Step 12: Load a PowerShell Script File (.ps1) into PowerShell ISE
•	On Powershell ISE, click File then Open
[73.1]<Image placeholder>
•	Under This PC, Local Disk C:
[74.1]<Image placeholder>
•	Open the Folder DNS-CONFIG until you reach the .ps1 files for Powershell
•	Select the 3 .ps1 Files then click Open
[75.1]<Image placeholder>
•	It will then Open 3 powershell script tabs
[76.1]<Image placeholder>

Step 13: Editing .ps1 Files
•	Select the “createDNSZONES.ps1”
•	“This script will build an entire DNS environment for us—but right now it’s configured for a different domain.”
[77.1]<Image placeholder>
•	We’re not just changing text—we’re redefining the entire DNS namespace.
•	We need to change the zone name to match the domain we want to use. In our lab environment, we already have preconfigured HTML and CSS files that simulate a website. Once DNS is configured, those domain names will point to our web server and display those pages.
•	You open Find & Replace (Ctrl + H)
•	Find what:
ngcpm.ph
•	Replace with:
bdo.ph.com
Then click Replace All
[78.1]<Image placeholder>
•	Find what: (REMEMBER M is your monitor Number)
.m
•	Replace with:
.29
Then click Replace All
[79.1]<Image placeholder>
•	Make sure that the createDNSZONES.ps1 is correct to avoid errors
[80.1]<Image placeholder>
•	Click the green play button or F5 key to run the selected script
•	we don’t need to save the .ps1 file, if you want to save 1st click CTRL+S before running the script
[81.1]<Image placeholder>
•	After Running the script make sure that there are no error red lines or red texts
[82.1]<Image placeholder>

Step 14: Verifying DNS connectivity
🧪 Test
ping bdo.ph.com
❌ Fails
ping www.bdo.ph.com
[83.1]<Image placeholder>
✅ Works
🧠 Why?
“www.bdo.ph.com works because it has an A record in DNS. 
bdo.ph.com fails because no record exists for the root domain.”
👉 DNS only resolves what is explicitly created 
👉 www and the root domain are separate records
•	To fix this (Add root domain record)
1.	Click Tools on Server Manager
2.	Open DNS Manager
3.	Go to Forward Lookup Zones → bdo.ph.com
4.	Right-click → New Host (A or AAAA)
5.	Set:
o	Name: (leave blank)
o	IP: 10.M.1.8
6.	Click Add Host
[84.1]<Image placeholder>
•	Click Add Host
[85.1]<Image placeholder>
•	After that re-ping bdo.ph.com it should have a reply back 
[86.1]<Image placeholder>

Step 14.1: Opening Cameras Using DNS Hostnames
•	Within configured DNS we can already see the end devices 
•	For instance we can see the name c1 and c2 
•	c1 and c2 is the name for our Tunay na CAMERA which is connected on the switch
[87.1]<Image placeholder>

•	Ping the DNS of our cameras
•	If the pings are getting a reply, we can now then access the CAMERAS using the dns on the browser of our choice
[88.1]<Image placeholder>

•	go to your browser of your choice in vmware, (edge)
•	then type the link of the following:
•	c1.bdo.ph.com
•	c2.bdo.ph.com
[89.1]<Image placeholder>
[90.1]<Image placeholder>


Step 15:  Adding MX (Mail Exchanger)
•	Creating an MX Record (Mail Server Simulation)
Purpose
We need to simulate how mail delivery works in DNS. This will be used later for:
•	Account creation scenarios
•	Testing email-based attacks (e.g., phishing simulations in a controlled lab)

Steps to Create an MX Record
1.	Open DNS Manager
2.	Navigate to your domain:
o	Forward Lookup Zones → bdo.ph.com
3.	Right-click the zone → Select New Mail Exchanger (MX)
[91.1]<Image placeholder>
•	Configuration:
•	Fully Qualified Domain Name (FQDN) of mail server:
bdo.ph.com
•	Leave other settings as default (unless you are configuring priority)
•	Click OK to create the record
[92.1]<Image placeholder>
•	Verify if the Mail Exchanger (MX) is added
[93.1]<Image placeholder>

What This Does
•	The MX (Mail Exchanger) record tells systems:
•	“Where should emails for this domain be delivered?”
•	In this lab:
o	Emails sent to @bdo.ph.com will resolve to your configured mail server
o	This enables realistic simulation of:
	Email flow
	Phishing scenarios
	DNS-based mail routing

⚠️ Note
•	This is a simulation only (no real external email delivery)
•	Ensure your mail server (or fake service) matches the DNS record if you plan deeper testing

Step 16: Creating Fake Website 
•	Go back to PowerShell ISE, then open createWEBSITE.ps1 powershell file
[94.1]<Image placeholder>
•	highlight “ngcpM.ph” replace with what we added on to our dns which is “bdo.ph.com”
[95.1]<Image placeholder>
•	verify after changing
•	we need then to change the physical path on where we extracted the folder for our DNS configurations
•	If you extracted your DNS/website files to a different location, update "d:\webs\datingbiz" to the correct path.

[96.1]<Image placeholder>

•	Navigate to the extracted files directory:
•	Open File Explorer
•	Go to:
C:\DNS-CONFIG-main\DNS-CONFIG-main\bank-phishing-sites
•	Highlight or click the link, then copy it
[97.1]<Image placeholder>
•	Replace the old link on the ps1 script to the new copied link
[98.1]<Image placeholder>
•	After all is correct we are then good to proceed running the script
•	press F5 or click the Green Play button to run script
[99.1]<Image placeholder>
•	It will then proceed to install IIS Web-Serer and add a New-Website
•	wait for the installation to finish, and the website to be added
[100.1]<Image placeholder>
•	It should have no errors, if it has errors, typo has been done
[101.1]<Image placeholder>

Step 17: Opening Fake Website
•	Since it is a virtual machine, we don’t need to install another Tool for opening the fake website
•	Microsoft Edge is enough for running it
•	Open Microsoft Edge on the Virtual Microsoft Server
•	Click Start Without your data
[102.1]<Image placeholder>
•	click Confirm and Continue
[103.1]<Image placeholder>
•	Click Continue without google data
[104.1]<Image placeholder>
•	Click confirm and start browsing
[105.1]<Image placeholder>
•	Navigate to “ bdo.ph.com ” and “ www.bdo.ph.com “
•	Website Access Configuration (www vs non-www)
When configuring IIS for the website, two domain variants must be considered:
•	www.bdo.ph.com
•	bdo.ph.com
By default, IIS only serves traffic for domains that are explicitly added in site bindings.
If only www.bdo.ph.com is configured, then:
•	✅ https://www.bdo.ph.com → works
•	❌ https://bdo.ph.com → will not load

⚙️ Why Both Domains Matter
Users do not always type www when accessing websites. For usability and consistency, both versions should be supported.
Supporting both ensures:
•	Better user experience
•	Avoids broken access depending on how the domain is type
•	Prevents confusion in DNS resolution testing
[106.1]<Image placeholder>
•	Recommended IIS Configuration
To properly support both domains:
o	Add both hostnames in IIS bindings:
o	click Tools on Server manager and under Tools click Internet Information Services (IIS) Manager
[107.1]<Image placeholder>
•	It will open a new tab, click the dropwdown on the connections on the left up to sites and click the site bdo.ph.com
[108.1]<Image placeholder>
•	On the actions panel on the right side click, under Edit Site click Bindings
[109.1]<Image placeholder>
•	From here we will see that only 1 address is shown and binded to our dns
•	we need to add another one
•	click Add button
[110.1]<Image placeholder>
•	Under host name:
•	add this: (bdo.ph.com), then click OK
[111.1]<Image placeholder>
•	from there another hostname is added
•	click Close
[112.1]<Image placeholder>
•	Open CMD in Virtual Machine
•	Flush dns configuration in CMD using this command:
•	then click enter
ipconfig /flushdns
[113.1]<Image placeholder>

•	On the browser, refresh or reload the site bdo.ph.com
•	it should now work 
[114.1]<Image placeholder>
•	Also navigate www.bdo.ph.com
[115.1]<Image placeholder>


Step 18: Creating a self trusted certificate
Create a Self-Signed SSL Certificate
This step creates a local trusted certificate for both domain variants:
Crucial Step: Add the code below to line 2 beside the DnsName
Edit the PowerShell script (VERY important)
•	Find this line in your script:
$cert = New-SelfSignedCertificate -DnsName "www.bdo.ph.com" -CertStoreLocation "Cert:\LocalMachine\My"
•	Modify it to include both domain variants:
$cert = New-SelfSignedCertificate -DnsName "www.bdo.ph.com","bdo.ph.com" -CertStoreLocation "Cert:\LocalMachine\My"
[116.1]<Image placeholder>
•	Then click F5 or Play button to run script, then click OK
[117.1]<Image placeholder>
•	If there are no errors the output should display like below:
[118.1]<Image placeholder>

•	Navigating https://www.bdo.ph.com will work and show that the website is secured, while https://bdo.ph.com will return an HTTP Error 404 or not found
[119.1]<Image placeholder>
•	Why does www work but not the root domain?
•	https://www.bdo.ph.com →  Works
•	https://bdo.ph.com →  404 Error
Reason
The certificate includes both domains, but IIS is only configured (bound) for:
www.bdo.ph.com
So:
•	IIS recognizes www.bdo.ph.com 
•	IIS does NOT recognize bdo.ph.com 
[120.1]<Image placeholder>
[121.1]<Image placeholder>
•	Click Add…
[122.1]<Image placeholder>
Set:
•	Type: https
[123.1]<Image placeholder>
•	Host name: bdo.ph.com
•	SSL certificate: select your created certificate
•	Click view to view generated certificate, and then click OK to close it
[124.1]<Image placeholder>[125.1]<Image placeholder>
[126.1]<Image placeholder>
•	Click OK
[127.1]<Image placeholder>
•	Then Close
[128.1]<Image placeholder>
•	Now when we browse https://bdo.ph.com we will now see the secured version of the website
•	and also for https://www.bdo.ph.com 
[129.1]<Image placeholder>
[130.1]<Image placeholder>

Now create a DNS and a fake website with certifcate for bpi and gcash

Next Step: Continuation of DNS, Configuring MailServer and ThunderBird
•	Click the Button Bellow to proceed on Mail Configuration, this is continuation for DNS along with mail configs
Mail Configuration Tutorial Step-By-Step

































































