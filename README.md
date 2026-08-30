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
https://cdn.discordapp.com/attachments/1543423664303644832/1543424480855064646/3bb393e900937923b3c9ed005b4342a22d3f6790c20e435fe0832a3b60dbd933653a77b93b9eecb8eccc9822888fd5b0eb964c7e81e429dc431954e359a251fddc514d16b6459b46d4ff869a60db3cb376155fddb0ec0b927342aa98d1cf29afa59a3649.png?ex=6a94d18f&is=6a93800f&hm=97058bef03ee91af6502ff33796336e0a77f191795a8f71b077dce46c33722ca&


Step 14: Verifying DNS connectivity
🧪 Test
ping bdo.ph.com
❌ Fails
ping www.bdo.ph.com
[[83.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543424566737506405/2167b6a9782058c92b2e6af6825feff5dfd0f0e913b98c01eb669bd76df1a0ccac00e0274d8d213b02b2798e68f6af713f26168a6732a7ad5b85dcd6f13d5cdac22069435608f45666c9f0f349e03c4ef74dc26b81fc122567d506275cad2b202876c347.png?ex=6a94d1a4&is=6a938024&hm=08996c15d182ae7e9781172756668671a7df03c3d9db1168b77b943559fc8ac3&)

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
https://cdn.discordapp.com/attachments/1543423664303644832/1543424766155821236/a569cb3b58682d35553295923873e725509fbd84cdb71f6b82ffb0724676e7b06a5619dbf5559e41477eb4767e6a73d83dda088e0b02bfb4dc6c93a7cc0b8d408a0ee4661f0beab2f6864efd7b873d246cc017d1537cff0dbb3a897e16c0a9cc2399320d.png?ex=6a94d1d3&is=6a938053&hm=59007cdff849c8fbc1056e06c10678c73a5ef2f46efd88ae8acb44ae062e0d1e&

•	Click Add Host
https://cdn.discordapp.com/attachments/1543423664303644832/1543424870761762866/453d091bd90cde29200b908d3da3b9ece9a23281c0947697b73fb1f1ea414813104d350b29ce568b7b0ddf47318c446d3a3ed83fa4680d314b5932f9853bfdb2abf4365c6d92ff7e01ede154516f80ef2a0379b5b5d98adb13f6921a2545db1e8662c5b3.png?ex=6a94d1ec&is=6a93806c&hm=b5f1d302b3da1b57643c7268cbf80e4dce87613583712f6b4e7a8c3b247c0a12&

•	After that re-ping bdo.ph.com it should have a reply back 
[[86.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425094527746148/ce9ca5da55cb882bdf9e92c9d339e502d2ad3255b384ef62f1275b633064bad7fb5c1c4fd82a1936c80c69a074cae22f34207dfdf3b266e8b5b0718a5dc9305bca9458907b9dae8920fe18af592a18c340fb8c4296bb314b04cf2c1357cdf88bfed3e027.png?ex=6a94d221&is=6a9380a1&hm=b94989b45afa8a95851368de620c2a1bca479441f2488a92c7a952c17bc97a30&)

Step 14.1: Opening Cameras Using DNS Hostnames
•	Within configured DNS we can already see the end devices 
•	For instance we can see the name c1 and c2 
•	c1 and c2 is the name for our Tunay na CAMERA which is connected on the switch
[[87.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425204070391870/f8112e3a335ea07362b0f28ca5fd0e8b2521f55e3764857cb4affbf831d9d84228450ecc9c843474cffc778336f58245a32142ab4d9c332fc6d5118b46dd1be848e0f7f852a9fe87093fcf6c8911a28c6eb20853725941c6024453a9b5704762f781c5f0.png?ex=6a94d23c&is=6a9380bc&hm=bca63bdf5f7ffe7c74afc2c651bb2b269967ca2371aa827995813c10822da553&)

•	Ping the DNS of our cameras
•	If the pings are getting a reply, we can now then access the CAMERAS using the dns on the browser of our choice
https://cdn.discordapp.com/attachments/1543423664303644832/1543425351089131570/319aa25812dd1c7f4d953ff53187dd9f71e8db5f1896e86e4cd35b1586fe08ccdf56e8dd7d7a4a61c9758d5a8b0f5002319585f404f9c1aab7e647e176934d4fa9342dc6713b5b5785ee661cf84cd68a2dff3121f7fc4e0a1971c1e6753bdc0f59e78fee.png?ex=6a94d25f&is=6a9380df&hm=714de758ccca35152c7273ba3243576992ae07b2add0676f62070272fed17359&

•	go to your browser of your choice in vmware, (edge)
•	then type the link of the following:
•	c1.bdo.ph.com
•	c2.bdo.ph.com
https://cdn.discordapp.com/attachments/1543423664303644832/1543425428222386258/2e1408dccb9b3912e109be8cd6a56573f73783c7318169cba0f604f2aeae14c0fc4c40fa178e217a9576385b46065c5ecfc62c9ba11e079640d317c422db6d0699855f2249b94b83fdafc5cf192633b1635c648357770529a3f3bfb54d1c9f05d21921c8.png?ex=6a94d271&is=6a9380f1&hm=962f3bde49c1d5822dbe505a8ec33f8642c39030b6b57d7e6be3c6556bea94bd&

[[90.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425569880940614/5ae2795130314cdd3609bedc3ac2e380497c1109ff83ba3b499d535921877c4eaa5734a7e9c6647a780772765cd7380c3e41ba457b7a63abb81ddb9cc693decaa14637385d3b92192e00821174d92c20d0888bedbf42b63f6be944459b20512011e6d1aa.png?ex=6a94d293&is=6a938113&hm=9b7e7314f3c116e3c1c6c094ecde6c7780a6edc4a118704f0ab5f92d865de0bd&)


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
[[91.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425672565760121/da287b821e664d5d99515d029f3fc5cdc8c35416efc3efe8106232b9bd85da77d7a7820ac2f4fefc3fb40bae3fa79a7b73b6384a32cfe446cb4c46dddaca483d2917b50b958d3ad73292f0e20b6466c2099310f09e58e523a8975e10e98298a67041fd11.png?ex=6a94d2ab&is=6a93812b&hm=7f2a7e47b9b880fa6839f5a7ab1675bab539e2203f2b228138a99b56be75030f&)

•	Configuration:
•	Fully Qualified Domain Name (FQDN) of mail server:
bdo.ph.com
•	Leave other settings as default (unless you are configuring priority)
•	Click OK to create the record
[[92.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425784864182322/9fab4124339c8d73e4b3b4e2a7f31fa1e3e7009abc1810949a429c4e1307c3ce510c83addbc1341fd38359fca8693f364ce93c6a71f757aeb77db98f11f7e394799c68edf8340a0752f581ded4cbd105c27358cfe7803a41e90aab5b6d7f1b307872954c.png?ex=6a94d2c6&is=6a938146&hm=365b1086469c49745dd0d108b498d961508fd8ad89d904f1210518935261408b&)

•	Verify if the Mail Exchanger (MX) is added
[[93.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425798910779463/f999825ee7bc5133c554e76015b008a1f041dd23308177ee2dd3f631062f101af4cd35f7de55ae4ca4094e295f8270d27810fe56549d3dc89b1f04defa6e2c62ed3aa4ef69096ee1be6573ecb2feba831e45f5524e2caf4c19236df37a450d9789cf18c4.png?ex=6a94d2c9&is=6a938149&hm=221d844daaf64c6a034db3a85117e43db75037e4b0b5dcad2d2918017ae4f9c6&)

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
[[94.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425904636600340/573f8f3bb88ef10f3cac3ef4838a7860d8d0e61a304ba56f07af2e07ff7dbfeade233b598c60566630b97ab06a15ab0b94ad7a79cf108d243d0f3131349c95d40749206ba4114a13fcd22ed733a338a62808ae155427bed1d84ada714c48161bb3954748.png?ex=6a94d2e3&is=6a938163&hm=d007249b68de4d3c880ea95a2ebea643ad06b066038fbfd54f87ac298d0df37d&)

•	highlight “ngcpM.ph” replace with what we added on to our dns which is “bdo.ph.com”
[[95.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543425925620965496/d50861b55a06dacb5ace0fcb1adcd08bafc007c85ad200597bd31ab7f53e165d9c9e35753b409b36064ff16e25aa01758f17faa53a4cdaae24652936419d3b2bc06c51a308ad1de3c0cf7f93a0aaaad4984f83811d160d2b6265c2f35188e9749a7db12b.png?ex=6a94d2e8&is=6a938168&hm=ccd197a95ca2f9acb2ab0b39a2a6b00c6c46d8aff7fca1e76d36ee3f0b36df8d&)

•	verify after changing
•	we need then to change the physical path on where we extracted the folder for our DNS configurations
•	If you extracted your DNS/website files to a different location, update "d:\webs\datingbiz" to the correct path.

[[96.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426068256399440/0e5d7f72e2ddbe10661ee2d70dc22c2f898bdddb1abc636a5b135de4faafad758ac32ddace29b908467989fee6ba39f6032148270e9f3f9acd65e6b2b67377b910c642408afef4ca67c3137d382b14ba2cee69d99d6aac6b7effc5ff386302361c7e4ff7.png?ex=6a94d30a&is=6a93818a&hm=7128f577b3a39b53eb9e6ee415f57be04b16c626903c6031c3769343a7a70b11&)

•	Navigate to the extracted files directory:
•	Open File Explorer
•	Go to:
C:\DNS-CONFIG-main\DNS-CONFIG-main\bank-phishing-sites
•	Highlight or click the link, then copy it
[[97.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426171679547422/ada6bf3a1d1f127ab19bb7db8e27d2b89d930903eba4acf014706e6e1a281498487327208d5fcfab15f374b293ca64da9fc867168446b558aad63b7076ec1798b4e90ba80e92487e008203930df0e7cfec04d9faf51b7cfc01bd4d5a8370f372723e3083.png?ex=6a94d322&is=6a9381a2&hm=ad3d4cbc24c14ab21cf57ce7a7f891a4d7ec15117a278269d0cee50272a7318f&)

•	Replace the old link on the ps1 script to the new copied link
[[98.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426188285054999/cea7eaf8b09827e43617ad15429f1baf110ed4c12205a899e29aae0ce3f7f5def5fa61df8a5ec54cdd7f8c0ffab76c87f7a327f508e2caf225efd775be1db8389c437d333e6b184e916001571060a0de32247c3f4e5e1e215da2bb09ba9948ae5db14025.png?ex=6a94d326&is=6a9381a6&hm=ee03782c59cf4e628d4655efef983ec0c8b42fb6f1956f233d000c82a1c3cb00&)

•	After all is correct we are then good to proceed running the script
•	press F5 or click the Green Play button to run script
[[99.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426201379536896/c912e99f968fb01aa6ceda5219635e8fcd506d17e4d0a189747c94b0797ba0adab8e307734f52e62db9b996f4b8cfd074ec92c3582e779639d6ad7c73dcf5496fd962e07859a713879b2b021f65aee7eb6095f4cb678f152f838c026807f5175907d5ad4.png?ex=6a94d329&is=6a9381a9&hm=56d5beb1c4648085a7855679d1cb7249fbeca1be13e5643caf58f9edce2d58ff&)

•	It will then proceed to install IIS Web-Serer and add a New-Website
•	wait for the installation to finish, and the website to be added
[[100.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426427754381393/c7d1a9866887ae1ce7b41f0de5a2a06d745347c1b8088124d085ce0f59f38cb05042da78257de0e3a774efd54cb59616f443ef8547cc962ebc57bc7d541c91508fc029ea0a70e04a2b12eada7d29816d15c4afdbefdd3cf905cb9468d57ca3eeb6ac57e2.png?ex=6a94d35f&is=6a9381df&hm=df31f2cac919c9b6fc31b3e972ee926261afdee3be6bd94876b57be47ca3d9c7&)

•	It should have no errors, if it has errors, typo has been done
[[101.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426448436764682/5a537f99335ba99087885f6d96fe648be1d3bc8fda5366a4a86c17e0140e7ce60cd6b57f8ac8f2789cf23df266b916763e6903462685f5ba473012d015505f7026da665cc1fe847c4342a457ffb385646bd797020a3bcc90310a91fab4131b992824098c.png?ex=6a94d364&is=6a9381e4&hm=d86e5b49ae0e0d5cb45417bf62f6b3a4b842eeb14a7e959af212f74dfb1c70b8&)

Step 17: Opening Fake Website
•	Since it is a virtual machine, we don’t need to install another Tool for opening the fake website
•	Microsoft Edge is enough for running it
•	Open Microsoft Edge on the Virtual Microsoft Server
•	Click Start Without your data
[[102.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426617362096128/ee792cfcf86a991b108e44bb4d46691aeeb9915fcdf792b9d4424db797cb11e32ce700e8f5011ea8a05d2f5792c46f1bcbac4e134a4f660d50df9b23faf4feb470234394022e04bdfa2bf454d9f60adddc99f527e9b559ab0da43ec5d1ddb03ed1012b47.png?ex=6a94d38d&is=6a93820d&hm=dc55575f45867cf36693121f329592a92f3f974aa9de4596b55e28b8d6906b42&)

•	click Confirm and Continue
[[103.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426648190222336/d0507c5e5095daddbfe8737f133fc249824ffa63fc4ff56f3251db309c3d6c29d317db83ef57d1a46b4a7dd4380b7c754954221eab7eed75b73c10aafd5b710def343280b9029370b2b0e25ab01e8dc578c5c1a86b9f68c33a502e2f462153420dd72044.png?ex=6a94d394&is=6a938214&hm=b9fd12bb636e34ef5524eb2b5bb2da111f056c92e0e022d9687f4bea02d78a6f&)

•	Click Continue without google data
[[104.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426724337815582/688811ea35a7c7d832df8bfa9583b51724ef9de014c092afd332777f3dde83d03cef662848e32e508f13b58c96bd9869cbf8e466ac9b651e3da6c1193ba1f11cb621d9616c3b42d451a1bef4f7a61c4f775526e92d8e9886e91d61faa909bbd47d39cf16.png?ex=6a94d3a6&is=6a938226&hm=2b3289a765aacbbbf06b8d182f57739a073d4868ad80459fec5e27413e940abc&)

•	Click confirm and start browsing
[[105.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426738208374925/3c545306a633f7035f9f043922af8a920f4b8f52e04125ab9bbbe17067464edde9cc15aa43ee04a590f3b60307907e91642f34fd43d651f3f761e8a963ca9ae4a9dafcf9a1256c888aa3bbba2fd44c014a817df862e96a72dd81095ca6ac85a33a1c5759.png?ex=6a94d3a9&is=6a938229&hm=2e4133780a6b714126fbf1efe0bab897b9e12c2dbd7305e3d0ca65d7cd2c63a6&)

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
[[106.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426840717299722/ac320202a08701b54d02831c90d2f8052c699da02c8e32712f3b1859b32ab59eb5de16f7d18634f360a9608f0ae0ae38b861bd4b7c107d6bfc5d91f0f7ff19f58ab22b6add0fbf035f0eaaa895187d3a9ba8309d947b79174cb2acab51bf1ea386a5f3a5.png?ex=6a94d3c2&is=6a938242&hm=b45ec6e894460ad0c60a3073617ef6e3ada393d80e06fd75c3bf9d59909d0db5&)

•	Recommended IIS Configuration
To properly support both domains:
o	Add both hostnames in IIS bindings:
o	click Tools on Server manager and under Tools click Internet Information Services (IIS) Manager
[[107.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426932077502586/ae6370eafabe920ec5a770c4d1c53233a620992ebc460a211b55564750f3d38ade3b2f9b3078a80f4fbd92abdd056fbd78d1f9d322dd5e6387e05a0e19ea54e2edb0df48cd44011be7f8bca7d1c4deba46069514bda2ff8f3bbcbfcaf4a1fd1b458a4b61.png?ex=6a94d3d8&is=6a938258&hm=40885be2f18fa7ca8f533ca14588986c3d09f1898d0655aed3daa1113505d011&)

•	It will open a new tab, click the dropwdown on the connections on the left up to sites and click the site bdo.ph.com
[[108.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426950067134587/47ce36be23c771b9192e1ff9a62b75377d1a8c22cd9c7020fd2e759dcb648e6ca64e9659c3443a4671de8beb52d76e7733d1391ae681547090b9a0f5cf0f48b5c55fa6013aca1b2e59a53b5a6ebd985b1f09302357edaee5d353aa7e29f2818e6b434ec8.png?ex=6a94d3dc&is=6a93825c&hm=56376fd60f946f1e02090bf6b55df823098674ab6d24cb39dabbb011f3575f46&)

•	On the actions panel on the right side click, under Edit Site click Bindings
[[109.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543426963002228856/61299c7a5c9b9372332c10045d069d147fe8e386b15189fc280afc4635f428d0e6a09269587babbd063ae6d17c0132c628dbd43f4eafe4e5fdecf2f2012358b216699e4e4fe1eef41114b5e4d616624bb711b655bd5c57ee32d96304e12cef659965e374.png?ex=6a94d3df&is=6a93825f&hm=09a73732cbb4ed7ced5858ea96c1fc1c1ac09c00123fb2da516b8e76066c1c20&)

•	From here we will see that only 1 address is shown and binded to our dns
•	we need to add another one
•	click Add button
[[110.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427165826060328/adab3e4689e37175ad5ef7304dfbb473e39ad862624160f44347dc800da22bb3f52e24f60d9cc48f7344d21ae987337b3e4420603c17d93c08514e85121f3861edc5bf115b9abfa95e76513f5d2e4e5addf12bbe9d28f1686c05b28eda9574b4d97b8f8f.png?ex=6a94d40f&is=6a93828f&hm=83f71060ea2a88c4eb58301c7ac95f75de11edf885ab87491d17f0385fcadab4&)

•	Under host name:
•	add this: (bdo.ph.com), then click OK
[[111.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427182108483594/e4b7022352397f602a63dbda4d268b819b5f8ccfe30581ec0943b7dc06760f4e7ed76908ab6689b6ed6e18cd2c19572660f524c03ef4c4c3bbdbd2ed67cd77f86a9e4b07153e8c4c33b054af3aec372eb509473a555fdf5cf6ddfa020e73840667325e6b.png?ex=6a94d413&is=6a938293&hm=8e1bccc9065dd750e70ad2b416f32a6c6fc17440bf1f6829feee5350f340f470&)

•	from there another hostname is added
•	click Close
[[112.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427210218578050/b41fbf5b59b0568850b93f72282834a0640dd7ebd838f09a0792b8d4425e3adadf0bb4b73769e0b13dfad5b2ea0d4d8f68bad770a790b96520cf8aea8abff05ce650476c8c8fe0dfa8df92910029d5a7df810a80580e0387d3a3b48231a2ea09cc666ab4.png?ex=6a94d41a&is=6a93829a&hm=73becda4f198bdf107314c621b701f9823ebea0941b205166a04b46fb3c843e6&)

•	Open CMD in Virtual Machine
•	Flush dns configuration in CMD using this command:
•	then click enter
ipconfig /flushdns
[[113.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427515991728169/97b4851a9fe74f847e52355f29f908b05db337762f6d0a5eebe531478b5b41e8405cf7162886dd3de59f9cf9f93782de274b19afcad9cb030e576d3c12574bc579180e4087dfdcb1737960192f830c268e9e691e31badbc75ec80a5aebd36df8e1429350.png?ex=6a94d463&is=6a9382e3&hm=215f70076100f5a90b00e066a7a08c6bf4e2fd1fdf494385868f3cc58c6da733&)

•	On the browser, refresh or reload the site bdo.ph.com
•	it should now work 
[[114.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427583863951473/8485f610740db083bffb7c6e8d45d19ee25ead98c0676ee990a2b6a4c2b8dd207be71929ecac17af7a42df79e3f2681cd514cd06fac8395184fe121d5d89bbf0c6b51aebec2e10283054e3740a2f536df976d96eb941847296a66d6679a3eeaf4cd6b6e4.png?ex=6a94d473&is=6a9382f3&hm=8122d0f2c2aa797c8a4b7ef0b61a0ed1ac9dc162a1743248aa4fe16f41019237&)

•	Also navigate www.bdo.ph.com
[[115.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427603107545189/1d0bb3a105ba8e02b980dfc4f3adf71fbc9f5e35636cbd2e6e669be5be1554c9c125e781c231c946103ff586c22e36cae87b534ba554002897fb469611e69ca43346f5c97d8d43da739e8a3a4c724de5a1bd32452a5d1e26ec7dcc5fe2c95b20fd4cbe89.png?ex=6a94d478&is=6a9382f8&hm=a4f8f2b73f9e7a38381c550fb56526c0aa4311b3fd6e0204f1ccea7a14c5dcaa&)


Step 18: Creating a self trusted certificate
Create a Self-Signed SSL Certificate
This step creates a local trusted certificate for both domain variants:
Crucial Step: Add the code below to line 2 beside the DnsName
Edit the PowerShell script (VERY important)
•	Find this line in your script:
$cert = New-SelfSignedCertificate -DnsName "www.bdo.ph.com" -CertStoreLocation "Cert:\LocalMachine\My"
•	Modify it to include both domain variants:
$cert = New-SelfSignedCertificate -DnsName "www.bdo.ph.com","bdo.ph.com" -CertStoreLocation "Cert:\LocalMachine\My"
[[116.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427684833431682/36d307e94b5b164da4abcf5ad4302279280e53c139b0feb2e585d9eef2eff137d2157b9d4759f3686e03494121a0ee73b848fe895530fc8ce433fcf7a9ab4acb86bdb234553b60d4ddbf40a16e7d34e9b21b69657c1d57bfffa794e2f6491d25159e3df1.png?ex=6a94d48b&is=6a93830b&hm=613097cb90b4115e191809cdd1f00a33a635ad7b85e94a8b6412d1a691feadca&)

•	Then click F5 or Play button to run script, then click OK
[[117.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427696867016835/10fd7469f45eabe280e2ba7c0f38caec1dba0a83f35b02a0b887c3208fda81e66bc60d46316b70e6dbe0f55a490a215fe2cbe6c378b35cdf77d749ed576aa13212ff1560d616cd9cf7967b4d405bb650671a7a447d8d205ae11338322dcf74a6dbd5c39c.png?ex=6a94d48e&is=6a93830e&hm=cd6aac7363ade956296ed2b40511af930eea533238d2224aee63ea8452fe302f&)

•	If there are no errors the output should display like below:
[[118.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427812927607007/f933c29ef3f0863088532e534dbdad40870455cff09b7f8920aa5b4e9ee674a9e88ddf6265d8bd86cc2e98c4155b0888bd455c10c872abdfa9c85ab1d4fe42ac284dbe499c6900223aaff0238fa12626daa05d454bc8bfd0e48cbcb6213c822db231f6ba.png?ex=6a94d4aa&is=6a93832a&hm=280880d0fc9744995de5286819cdc3c59deaef15f6eb4b5ea44f247d1ef839df&)


•	Navigating https://www.bdo.ph.com will work and show that the website is secured, while https://bdo.ph.com will return an HTTP Error 404 or not found
[[119.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543427897778380830/b90db29a32f5eb8a79e538866b0499a6c39c5984f95a6a11d33fc6ddc1b31f6392bed7b8cc65d17c8962e817158c4ecb9a019a6703403f707a51eb50e27b619c3e5fd39fd6d4a1fccd39bdd067aa4b51e91f0a4e8b81c0c56336de8f3a462176d8a07f72.png?ex=6a94d4be&is=6a93833e&hm=8e9dcd85bfd92262f53ea0d9ee14e14071b7054d9130c12c5b3053a82db28549&)

•	Why does www work but not the root domain?
•	https://www.bdo.ph.com →  Works
•	https://bdo.ph.com →  404 Error
Reason
The certificate includes both domains, but IIS is only configured (bound) for:
www.bdo.ph.com
So:
•	IIS recognizes www.bdo.ph.com 
•	IIS does NOT recognize bdo.ph.com 
[[121.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428012941516841/ce3883f10bbdcd646298a1cac03302d3b34410943b00a6cfe4cd511e9fb5b749133aed3b0d3432d4d207bd04712d7de0a185b14601db038aab9b435306d0c6253c68e45bff89be3ee2645c6823e473f6830f10e9fe6c32ee87416cf0c212921d8322dbce.png?ex=6a94d4d9&is=6a938359&hm=51b224fceeb66a88b6a5baf6bd17593c16c2d81ad5309a38fd61ac4e53739e81&)

https://cdn.discordapp.com/attachments/1543423664303644832/1543428044675354716/c6fecff1894f8c656c4599ad1d120c0363baeff5f27197059d7ce036fc4e29289d77aa40b0b2b3cfb5bdd46245a6bc8155745cebf78ac044ffb07073d2f87c32064dcf3f95397fbec37174662df009a5d093a430f41b4cc48dda06f7122fc26cadeaa867.png?ex=6a94d4e1&is=6a938361&hm=815ff129d6092054fda7e99fd16f972ed1ef7e06087536c63b76f49f2c6d1264&

•	Click Add…
[[122.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428156445298748/40e7417b23f910fcc8a9a12ad049bf459653868c9551edb0d529eb639e7d5add10bc7bb087068efabf4bfac6da365ffc8c56b4ab48d418d4396f48cd7923c4cddea997216045ead0011d4d107d64decc42bfb9060da4e3ef4d4223bea113ca1965f3dac5.png?ex=6a94d4fc&is=6a93837c&hm=072f292254c74b4d40ea9b8433e71d3d623bf8a5b394b7a095f6c9809a2fd575&)

Set:
•	Type: https
[[123.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428276779880530/c2448c05f7153dcf5715f08b3945fd95784799114737fd9eb948aa732ab25897c99e4fd056c8208c7eb34d6512cf7cc2ca9bbf1508a398cf0848d69851b0013613ad4a73781c04dc2f3c188e0bbaae88b19cf7d9ff807db9b5ce4301396e677576359da3.png?ex=6a94d518&is=6a938398&hm=34550b20df8caa1a2696b6c2f9f1a05a72c9b604ae188d11fb15469080e8dd94&)

•	Host name: bdo.ph.com
•	SSL certificate: select your created certificate
•	Click view to view generated certificate, and then click OK to close it
[[124.1]<Image placeholder>[125.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428298149728338/03e62cdb28d38aa4bf69e1c84826ee5a087123b3734d4d38f6c640ea7d3199abd43c19cd7a694b370b004f61bf3904b8c2b4ed1944574d7c970f1dec5c3439ebdbb4b287e84dc1a5cc591ae9b7d499c34a30b8bea7043085eaeea4d5ae3882941fad45db.png?ex=6a94d51d&is=6a93839d&hm=19c534cc9ed527ff39eafb754c1a08ae67a36d9fc1031066e7a13bf439a40129&)

https://cdn.discordapp.com/attachments/1543423664303644832/1543428318693560330/a830f67fde123280ffd4a4c2567f60fb8bb31e0fc8864ace9d7aecbbd695fd5c4b4a3a8bf0a85ef7695372bf9d9041d9301dc47a770755117b45e98156c5401315cdbb97e8bf0d5e9d40d65f56affcd147924cbcd8875afd4728a50276571ef698b2a71b.png?ex=6a94d522&is=6a9383a2&hm=5f60f1ff75d976ca4d1cfb04db1a1b313432573f7c2f6f0c680fa7e9ebb4131c&


[[126.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428334577385472/11b6a7ab32b43186e200272169fa2375a0122702fefbc821dc1cac7345c3ed4b6970da4e8cc6798589d008b464fda673963d6b7baa33451504360f3f3046eeaac63999341bbaabbe9035274e00d4b16b61ed5e8c86baf72bc699786fd867244c77ced876.png?ex=6a94d526&is=6a9383a6&hm=cc0e1504c56a72875958e73fbb282be689b7286bffb80d56ee8784535a37eb3d&)


•	Click OK
[[127.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428751402999818/726e53b023bd4203794d0a2aa365b1be941e6c08b682cedf71f0647d6362d66a329ab0fcb5057d9373e5c3363362f5c552f851e21adba088f1cfd9a89f5a22e90a0b1f7781c11e2e350c98a2ec25f4041fdade541a4d2523d6cd5f981c66cd3d848810a1.png?ex=6a94d589&is=6a938409&hm=e4e30259db63c483a3e8e0d7103181a3121ef77b4ab8ecd93497b77b18be9c03&)

•	Then Close
[[128.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428774018682931/01a4a922d9472c3a810e943113ff158a9125bd1c65ab524d9493e0accb2e7da303d9d9dddb629a62c1a9cb065747b5f30f830fec3660007ddda660a84bfc2fc4942b09cb666bdfc53002a269c4d7cb31efb2df84bc5ffe0fdcb03c1b7b9fbb68521c1003.png?ex=6a94d58f&is=6a93840f&hm=b4e77a3f5eaf4ee4dd2f516285e184baabc49e7945d82d3f805bab9639e964ad&)

•	Now when we browse https://bdo.ph.com we will now see the secured version of the website
•	and also for https://www.bdo.ph.com 
[[129.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428867098677318/3ac449847f980d4bd66d9d0030bf6f1a24e2046a375434b69e21b1b778abd62a4d36bfb51fd94040aac68ccd6688095d2ac825b507471b644b9d0084dd8c0a15370f3d0bc5f483b92d9878f7ec1f9421aab65539c170b25206966200e2d52bc52445ee63.png?ex=6a94d5a5&is=6a938425&hm=3c10a1d749653c42de173cba47c451b1b6ede7d79e45732781a6e003b0745000&)

[[130.1]<Image placeholder>](https://cdn.discordapp.com/attachments/1543423664303644832/1543428890259619930/405cee3a75507d3ab8c6660910eb464e5c6fe7db97ce35eed67dab03632f917c68ca744e5399edaea00299dd68a1459d23b0b396ec54c254c7e440cde583757748b88e968a2da9f75c36591c4284ae63b67f5558b90f55c6af798d81ca6276532faa4084.png?ex=6a94d5aa&is=6a93842a&hm=1c0643272fc9a3d544db7eadb5d26025e91d9c6f128b020e3c692daf3c951e1a&)

Now create a DNS and a fake website with certifcate for bpi and gcash

Next Step: Continuation of DNS, Configuring MailServer and ThunderBird
•	Click the Button Bellow to proceed on Mail Configuration, this is continuation for DNS along with mail configs
Mail Configuration Tutorial Step-By-Step

































































