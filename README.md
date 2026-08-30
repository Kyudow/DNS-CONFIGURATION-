Prerequisites: Make sure that apps are installed and ISO are already downloaded. Also make sure that the github repository is already cloned and downloaded in the PC
GITHUB REPOSITORY: https://github.com/Rivanyte/DNS-CONFIG
•	Go to the GitHub link, and download the Repository
•	Click the button “<> Code” and click Download Zip
<img width="1914" height="899" alt="image" src="https://github.com/user-attachments/assets/2d4482a6-a7e1-4d3a-86d4-8379f061480b" />

•	Save it as default name
<img width="936" height="563" alt="image" src="https://github.com/user-attachments/assets/ea8c2992-23ee-4c4f-8b3d-f8e5f8b34719" />

•	verify if the download is finished

<img width="312" height="101" alt="image" src="https://github.com/user-attachments/assets/e9aa5ac6-9f9f-4c5f-baea-040811144e14" />



Step 1: Creating Windows Virtual Machine
•	Click Windows Button and Search for VMware Workstation
•	Open The Application VMware Workstation Pro
<img width="1166" height="548" alt="image" src="https://github.com/user-attachments/assets/52457d9d-a2eb-4447-ac57-1414fa8e52f3" />


Step 1.2: Creating Windows Virtual Machine
•	Click “Ctrl + N” to create New Virtual Machine, and click “Next >”
<img width="1920" height="1013" alt="image" src="https://github.com/user-attachments/assets/9ff1206e-957f-4998-8676-ae57633b9a18" />

•	Click “I will install the operating system later.” and Click Next >
<img width="655" height="645" alt="image" src="https://github.com/user-attachments/assets/f243f6fd-0a9a-4167-b84d-571b109d2d68" />

•	Select “Microsoft Windows”, and under Version, select “Windows Server 2022”
<img width="657" height="657" alt="image" src="https://github.com/user-attachments/assets/68a6a018-6c1d-4f30-9559-2aa06282a936" />

•	Then Click Next >
<img width="654" height="643" alt="image" src="https://github.com/user-attachments/assets/b912adce-c443-4c48-8935-199f36d60f60" />

•	Type your desired Virtual Machine Name:
•	For Instance, WINHACKER-M (”M is your Monitor Number”)
<img width="650" height="637" alt="image" src="https://github.com/user-attachments/assets/43247b5c-5bf4-48bd-8809-b65ce46b03e7" />

•	After typing your desired machine name, click "Next >"
<img width="640" height="633" alt="image" src="https://github.com/user-attachments/assets/8ace3c3e-9034-4500-a17e-1d89355f72c7" />

•	Default Setting for maximum disk size is okay, you don’t have to change anything just click Next
<img width="652" height="645" alt="image" src="https://github.com/user-attachments/assets/f50fa7f3-e64f-4011-9ffa-b3db04f4d4d3" />


Step 1.3: Customizing Virtual Machine Hardware
•	We need to customize the machine for it to run smoothly
<img width="659" height="644" alt="image" src="https://github.com/user-attachments/assets/12712213-fae1-42cc-b9f3-3010ef38c57d" />

•	For Memory (Ram Size), Select your desired memory 
•	If your Memory is below 16GB, Selecting 4gb is enough for the system to run smoothly
•	If your Memory (Ram Size is above 16GB, 8gb is enough for the system to run smoothly
<img width="1090" height="528" alt="image" src="https://github.com/user-attachments/assets/607c84c9-5116-4b86-b446-b38d64551b67" />

•	On processor, select number of cores per processor 2, that is enough for the system to run smoothly
<img width="1115" height="352" alt="image" src="https://github.com/user-attachments/assets/dea5a255-0570-4128-b431-736e911ee707" />

•	Under CD/SATA, select the ISO Image you downloaded
•	Select “Use ISO image file:” and then click “Browse…”
<img width="1114" height="515" alt="image" src="https://github.com/user-attachments/assets/6433cefb-fafd-4445-b181-5099bc86a5e3" />

•	On the pc under Rivan Possession, On HP Products Mini PC they have their own D: Drive, under __RivanAPPS, open that folder
•	On Dell PC, usually on the center Isle, only C Drive is there, under __RivanAPPS, open that folder
•	On your own pc, find the downloaded ISO
<img width="968" height="564" alt="image" src="https://github.com/user-attachments/assets/e170065e-f652-40b8-8f01-1b7f600651fa" />

•	Look for “SERVER_EVAL_x64FRE_en-us”  and then click it, then click Open
<img width="949" height="717" alt="image" src="https://github.com/user-attachments/assets/10622646-7ecb-443a-9e20-b569f6675747" />

•	This is for Rivan Method, we need to add another network adapter to be connected on the switch
•	Click Add, then click Network Adapter, then finish
<img width="1287" height="672" alt="image" src="https://github.com/user-attachments/assets/3eba4916-6e78-456c-a529-0526c4beacb3" />

•	Change the added Network to Bridged and click Replicate, that way it can communicate to the switch with no problems
<img width="646" height="132" alt="image" src="https://github.com/user-attachments/assets/c77ba928-0996-4cbb-a172-57c397ec8e78" />

<img width="594" height="44" alt="image" src="https://github.com/user-attachments/assets/585d8ed2-95fc-487b-8850-be1d26733763" />

•	After all checking, adding, and fixing the hardware machine, if all is correct we can now then close and click Finish
<img width="1503" height="739" alt="image" src="https://github.com/user-attachments/assets/56870374-d6d0-419e-ab6f-fc7bf3daad81" />


Step 2: Powering on Virtual Machine
•	Click Power on this virtual machine
<img width="1225" height="724" alt="image" src="https://github.com/user-attachments/assets/fe2f3648-8b78-4d14-982e-06ac943bba74" />

•	This Part is all about speed, the moment you see this you need to click inside the virtual machine and click enter, if you didn’t do this the next image shown will be the error
<img width="1031" height="838" alt="image" src="https://github.com/user-attachments/assets/20f4f091-3ef6-4f59-a163-6de982277b1c" />


SAMPLE ERROR
•	To avoid this, the moment you see this the line “Press any key to boot from CD or DVD…..” you need to click inside the virtual machine and click enter
<img width="1006" height="664" alt="image" src="https://github.com/user-attachments/assets/7677ad4a-be77-41db-b391-bfb42b1c842d" />


If all procedures are correct, the windows logo will run on the virtual machine
<img width="1027" height="810" alt="image" src="https://github.com/user-attachments/assets/f87a8e3d-a2b3-4af4-b5e3-67c93b4d8abc" />

Step 3: Windows Installation Prerequisites
•	After powering on, you can skip this part, just click Next
<img width="1004" height="721" alt="image" src="https://github.com/user-attachments/assets/7820370d-e634-4d83-bc79-f66ad66ee1f3" />

Then Click “Install now”
<img width="1019" height="733" alt="image" src="https://github.com/user-attachments/assets/d5236a7e-3fd1-4a52-890c-19e3261085ed" />

•	After that, the windows installation will go to setup
<img width="1016" height="799" alt="image" src="https://github.com/user-attachments/assets/7cab220a-9fda-43f0-9e21-a6e427f21713" />

•	Select the type of Operating system you want to install
•	Select the 2nd option, this option has a GUI 
•	Then click Next
<img width="1020" height="737" alt="image" src="https://github.com/user-attachments/assets/72a85881-4fcb-4218-8068-ac0d09cc6e0d" />

•	Click the checkbox icon to accept license terms
•	Then click Next
<img width="1022" height="730" alt="image" src="https://github.com/user-attachments/assets/d5389d48-4061-4c2d-9e1f-91965db1eb32" />

•	Select the 2nd Option to Install Microsoft Server
<img width="1021" height="731" alt="image" src="https://github.com/user-attachments/assets/d1aac8dc-fd7a-4afd-bd1a-9e4be7f22ff1" />


•	After selecting custom, we will now be directed to selected the disk/drive to install the OS
•	Select the only drive to install, then click Next
<img width="1017" height="722" alt="image" src="https://github.com/user-attachments/assets/42bbc357-beb1-4b06-b577-aa77cd534ebb" />

•	After all configuration
<img width="1009" height="811" alt="image" src="https://github.com/user-attachments/assets/9146b732-c14a-4d77-b725-b3b4fb1ac94f" />

•	Wait for the Installation to Finish
<img width="1029" height="829" alt="image" src="https://github.com/user-attachments/assets/6f401961-2e6b-412e-bd3b-f1ab93153118" />

Step 4: Customizing Windows Virtual Machine
•	Type your desired password, for this lab we will use Rivan Password
•	C1sc0123
<img width="1027" height="821" alt="image" src="https://github.com/user-attachments/assets/f81a75cf-5a63-4c03-8758-15a232701e7c" />

•	After re-entering your password and if it is correct, click Finish
<img width="1022" height="729" alt="image" src="https://github.com/user-attachments/assets/e52c73ab-8f96-48aa-87a7-0cb0162be079" />


Step 5: Logging on Windows Virtual Machine
•	To proceed to logging in, Click the keys “Ctrl+Alt+Insert”, that way only the virtual machine shows the input of the password
<img width="1024" height="816" alt="image" src="https://github.com/user-attachments/assets/f4d20336-1d74-480e-af71-3db963cadfd3" />


•	Type in your created password, for this lab it is C1sc0123, then click Enter
<img width="991" height="787" alt="image" src="https://github.com/user-attachments/assets/d501ae41-f96b-4981-904a-a72894a970bd" />

•	wait for the system to boot up
<img width="995" height="791" alt="image" src="https://github.com/user-attachments/assets/699158e2-ad50-4b31-9e68-8609e1e8d6c5" />


Step 6: Changing IP Address
•	On 1st startup the Network notification will show, just click yes
<img width="1020" height="606" alt="image" src="https://github.com/user-attachments/assets/c5a45d2c-7f18-46e1-acd7-27cf114c57d9" />

•	Minimize the Server Manager, we will need it later on
<img width="1027" height="767" alt="image" src="https://github.com/user-attachments/assets/15627381-ad77-4970-a14c-eeee127e6517" />


Step 6.1: Opening Network Connections
•	On your Keyboard click Windows Key ⊞ + R
•	Then type ncpa.cpl this will open the Network Connections Panel
<img width="495" height="287" alt="image" src="https://github.com/user-attachments/assets/3142653a-53f3-46e4-9f61-96d0e2afdac8" />

•	Rename Network Adapter 1 to NAT, this is connected to the internet
•	Rename Network Adapter 1 to Tunay na BRIDGED, this network adapter is connected to the switch
<img width="1022" height="814" alt="image" src="https://github.com/user-attachments/assets/fa89089a-7f48-477f-932b-b16db2f78f53" />


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
<img width="1307" height="557" alt="image" src="https://github.com/user-attachments/assets/d6348a3a-b5e5-4f6c-a107-f91226fe2039" />

•	Then the Network 2 Notification will show, click Yes
<img width="1025" height="482" alt="image" src="https://github.com/user-attachments/assets/850a37d1-a525-40ae-9e04-5ea7b5d7bf9c" />


Step 7: Verifying Changed IP Address
•	On your Keyboard click Windows Key ⊞ + R
•	Then type CMD to open Command Prompt
•	Then click OK
<img width="510" height="795" alt="image" src="https://github.com/user-attachments/assets/93f0fca2-7bf7-4f4f-b2a4-2420a6254ca4" />

•	On CMD, type ipconfig
•	NAT should be getting dhcp from the IP Address 208.8.8.0 each VM may differ on the 4th Octet
•	Ethernet adapter TUNAY na BRIDGED should be getting the static IP Address
<img width="979" height="513" alt="image" src="https://github.com/user-attachments/assets/d890ba40-45a6-4628-b93d-2b04147dc141" />


Step 7.1: Verifying if Changed IP can Communicate to TUNAY na pc and Switch
•	On CMD, Ping the SWITCH
•	type “ping 10.M.1.4” it should be getting a reply
•	type “ping 10.M.1.10” it should be getting a reply
Why the first ping times out for the switch
Because ARP resolution takes time:
•	First ping → ❌ times out (ARP still resolving)
•	Second ping → ✅ success (MAC  already known)
•	Next pings → ✅ fast replies
<img width="720" height="448" alt="image" src="https://github.com/user-attachments/assets/dbae198a-87d1-4fac-9054-f24e725a3936" />


Step 8: Turning off the Firewall using Poweshell
•	Click Windows Key ⊞ and Type Powershell, Select Windows Powershell ISE
<img width="808" height="537" alt="image" src="https://github.com/user-attachments/assets/57d0023c-43c3-4088-bf2b-9386c68a822c" />

•	Wait for it to boot up
<img width="1014" height="767" alt="image" src="https://github.com/user-attachments/assets/12c5e03a-d8a6-4aa9-907a-85c08cad7dd4" />

•	The window will show and, clcik the show script pane thats where we need to type
•	We can type Directly to the CLI
•	But for this practice we need to show how Powershell ISE Works
<img width="1018" height="780" alt="image" src="https://github.com/user-attachments/assets/bc5700f0-c1b8-44cb-968b-104a7f5ea7ae" />


SSStep 8.1: Typing Commands to Powershell ISE
•	type this command:
•	“set-netfirewallprofile -name public,private,domain -enabled false”   
•	Then click the Play button or F5 Key to run script
<img width="1018" height="773" alt="image" src="https://github.com/user-attachments/assets/9fef5015-0185-45ce-a9e4-d5815947bcd5" />

•	After running the script, no red lines should show
•	If red error shows, that means that there is a typo in the command
<img width="707" height="170" alt="image" src="https://github.com/user-attachments/assets/51a6c67c-29ba-4ae7-bcb9-6b3595c1bd65" />



Step 9: Accessing a Virtual Machine’s C$ Drive from Host via Run Command
•	On your host (real PC):
•	Press:
Windows + R
•	Type:
\\<VM-IP>\C$
•	Example:
\\10.29.1.8\C$
•	Then click OK
<img width="700" height="480" alt="image" src="https://github.com/user-attachments/assets/9870f6a3-f08f-498a-89c3-a584d3498682" />


•	This will open the VM C$ Drive
•	Open Your Local Files
1.	Open File Explorer on your host
2.	Navigate to the folder where your files are located 
(e.g., D:\RivanApps)
<img width="1900" height="919" alt="image" src="https://github.com/user-attachments/assets/f1e11781-112d-4d7d-88e6-c7032a771945" />

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
<img width="1787" height="690" alt="image" src="https://github.com/user-attachments/assets/f0562030-7bf2-46cf-820c-f98e769bd799" />

<img width="1856" height="896" alt="image" src="https://github.com/user-attachments/assets/d25bd7c8-458e-41a8-a135-e9bd0a9064cd" />

•	We also need the DNS Folder to be pasted on the VM C$
•	Copy and paste from your host  pc to the VMC$
<img width="1901" height="935" alt="image" src="https://github.com/user-attachments/assets/f07c9d1f-f6c7-4f17-a0bd-a25f51763932" />


Step 9.1: Verify the folder/apps inside the VM
•	Open C Drive in Virtual Machine to check if the copied files are available
<img width="1024" height="775" alt="image" src="https://github.com/user-attachments/assets/c6dedf19-e63e-4eac-9f3a-64f25d0cfc3e" />


Step 10: Extract the DNS-CONFIG.main zip file
•	Right Click the zipped file, then click extract files, then it will open a new tab, then click extract
•	wait for the extraction to finish it will then generate a new folder
<img width="1678" height="685" alt="image" src="https://github.com/user-attachments/assets/c7df4cba-4ae5-4f33-b10a-8504ade531a5" />

•	Close all the folders after verifying if the extraction is completed.
<img width="975" height="555" alt="image" src="https://github.com/user-attachments/assets/02411530-d1f3-464b-a32a-b75b8d2acebb" />



Step 11: Adding/Managing Roles and Features for DNS
•	Re-open the Server manager
<img width="1192" height="642" alt="image" src="https://github.com/user-attachments/assets/b82202bd-72e1-4d24-b249-b34d1adc168e" />

•	Click Manage 
<img width="964" height="610" alt="image" src="https://github.com/user-attachments/assets/34180c0a-fe07-41c8-9502-8b33ec338697" />

•	Then Click Add Roles and Features
<img width="260" height="176" alt="image" src="https://github.com/user-attachments/assets/4f6d9734-e259-4625-83a6-6a227a41e560" />

•	Click Next 2 times
<img width="1598" height="585" alt="image" src="https://github.com/user-attachments/assets/18ad9db4-2200-44a9-b9e2-5412b4d34d2f" />

•	If the IP Address on the virtual machine that we changed is correct, we should see it in the server pool
•	If not, installation of DNS and other features will fail
•	Click next after verifying 
<img width="1022" height="739" alt="image" src="https://github.com/user-attachments/assets/56e30b31-8582-40d2-b01d-9ba70d6ea154" />

•	On the next page we will see the Roles, click the checkbox of DNS Server then a new tab will show click Add Features
<img width="1490" height="662" alt="image" src="https://github.com/user-attachments/assets/03321fac-d642-423f-8b3a-ac360191280e" />

•	After that, the unchecked box will now be checked
•	Click next
<img width="1023" height="774" alt="image" src="https://github.com/user-attachments/assets/50f4da03-6074-433d-821b-87945c124dda" />

•	After that we will now go to Features, we will now proeed on installing .NET Framework 3.5 Features
•	Click the checkbox of .NET Framework 3.5 Features
DNS does not require the .NET Framework to run. However, some management tools, scripts, and future features may depend on it. Installing it now helps avoid errors and saves time later.
<img width="1003" height="736" alt="image" src="https://github.com/user-attachments/assets/d4a2b9cd-5995-4466-9ca5-32b5d161e7dd" />

•	Click next and then Confirm Installation Selections and click Install
<img width="1795" height="734" alt="image" src="https://github.com/user-attachments/assets/a3225fde-8d76-406b-aa0b-7d9a9a4a0956" />

•	Then Wait for the Installation to finish, it may take some time to install kindly wait for it
<img width="1021" height="770" alt="image" src="https://github.com/user-attachments/assets/f36ede0b-904a-46f0-a5d5-8aa7b7aa562c" />

•	After Installation we can now close the Wizard Window
<img width="1025" height="765" alt="image" src="https://github.com/user-attachments/assets/70fed0f9-f9e1-41c6-8cba-fde1ca093492" />



Step 12: Load a PowerShell Script File (.ps1) into PowerShell ISE
•	On Powershell ISE, click File then Open
<img width="717" height="468" alt="image" src="https://github.com/user-attachments/assets/61811aaf-2a58-434d-9630-fd71375974e2" />

•	Under This PC, Local Disk C:
<img width="625" height="498" alt="image" src="https://github.com/user-attachments/assets/c07b7080-e1f5-40c9-943a-cbc9d0d6b413" />

•	Open the Folder DNS-CONFIG until you reach the .ps1 files for Powershell
•	Select the 3 .ps1 Files then click Open
<img width="1889" height="668" alt="image" src="https://github.com/user-attachments/assets/73b5e771-3352-4dfe-8606-148643a82bae" />

•	It will then Open 3 powershell script tabs
<img width="867" height="518" alt="image" src="https://github.com/user-attachments/assets/ecbeaafd-b9d5-4bce-a7cc-26f93c678926" />


Step 13: Editing .ps1 Files
•	Select the “createDNSZONES.ps1”
•	“This script will build an entire DNS environment for us—but right now it’s configured for a different domain.”
<img width="379" height="201" alt="image" src="https://github.com/user-attachments/assets/ca688d31-8812-41b9-885a-421e622151cd" />

•	We’re not just changing text—we’re redefining the entire DNS namespace.
•	We need to change the zone name to match the domain we want to use. In our lab environment, we already have preconfigured HTML and CSS files that simulate a website. Once DNS is configured, those domain names will point to our web server and display those pages.
•	You open Find & Replace (Ctrl + H)
•	Find what:
ngcpm.ph
•	Replace with:
bdo.ph.com
Then click Replace All
<img width="794" height="548" alt="image" src="https://github.com/user-attachments/assets/05be0a0b-7380-4be4-99c7-0a3b365ce4a7" />

•	Find what: (REMEMBER M is your monitor Number)
.m
•	Replace with:
.29
Then click Replace All
<img width="773" height="502" alt="image" src="https://github.com/user-attachments/assets/4c778636-3602-4e5d-8593-a881032fadce" />

•	Make sure that the createDNSZONES.ps1 is correct to avoid errors
<img width="753" height="470" alt="image" src="https://github.com/user-attachments/assets/796af0a8-92e0-40a9-b225-6e068edc3b50" />

•	Click the green play button or F5 key to run the selected script
•	we don’t need to save the .ps1 file, if you want to save 1st click CTRL+S before running the script

[https://discordapp.com/channels/845330743513317376/1543423664303644832/1543423680003051581](https://cdn.discordapp.com/attachments/1543423664303644832/1543423680049184918/a8479498fd971531cc9d4444947b54a42d6f6b09d01a8fdf098e47c3cdaec8a55005cad8219cb2c33d20b0a989eb5e305ebb6276582a9358a8ff369f043b52ec05e3f53e24ca76c7aecec6b2b2021010faf945315b8c3df044558fdd8d011cb875394684.png?ex=6a94d0d0&is=6a937f50&hm=f4e720ca2c2aa78d97bba58a444785617afeff0fd6f6fa33148579e1d4d41d96&)



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

































































