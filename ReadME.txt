This project is a Command-and-Control (C2) learning framework written in Python.
It demonstrates how distributed agents (bots) can connect to a central controller (C2 server) and receive commands this shows a real working version for defence reasrchers to learn how they work and test in real time safe labs.

⚠️ This project is for educational and research purposes only.
It must not be used for malicious activity. The goal is to help developers, students, and researchers understand:

Socket programming in Python

Client-server communication models

Remote command execution

File system navigation

Sending data to external APIs (e.g., Discord webhooks)

⚙️ Features

Multiple agents connect to the C2 server

Remote command execution(power shell)

File browsing & navigation (/files, /cd, /back)

Screenshot capture (agents send images back to the C2)

Bot information reporting (/info)

Console management (/clear)

Webhook alerts on agent connect/disconnect events
basic ddos attack where bots use random user agents to request a url 

🚀getting started

ensure python3+ is installed 
ensure request is installed (pip install requests)
ensure colour mode is installed (pip install colorama)

next you will need a server of some sort ill walk you though

windows guide:
1- get a cheap vps I used a windows os vps from display vps (5£ a month)

2- since I used windows I connected via rdp if u choose Linux u can connect via putty ssh

3- cause I choose windows for how easy it is I used WinSCP to transfer files via ftp

4- installed python and all dependacys on the vps and 

5- run the c2 script ensureing you have changed the bits in the code where the # are and complie the file on the vps

7- do python (name of c2 file).py in ur cmd panel to open it 

6- once c2 is open on vps/dedi in a vm or old laptop run the worm/bot code ensureing changed to code where # are and it will show the connection

7- have fun

Linux guide:
1- get a cheap vps I used a windows os vps from display vps (5£ a month)

2- choose Linux u can connect via putty ssh

3-Open PuTTY and Connect to Your VPS Enter your VPS IP in the "Host Name" field and click Open Login using your VPS username and password

4-Transfer Files Using PSCP open cmd on ur pc navigate to the folder where the file is and do this command pscp bot_script.py username@your_vps_ip:/home/username/ (replace with ur info)

5-Verify the File on the VPS In PuTTY, navigate to the directory where you uploaded the file You should see your uploaded file listed

6-Ensure Python 3 and dependencies are installed
commands to install:
sudo apt update
sudo apt install python3 python3-pip -y
pip3 install requests pillow colorama

7-Run your script python bot_script.py (replace bot_script with ur name)

how to setup worm/bot script for Linux and windows (recommend doing in vm):
1- load the script in a code editor I use vs22 for simplicity but note pad works

2- check and ensure dependancys are installed but they should be since the c2 is setup now

3- alter the code where # are 

4- complie the file 

5- run it in a vm or old laptop ensure the c2 file is open first this isnt required at all but it makes it easyier to check its working
(side note heres how i ran it this way terminal stays open and you can check it works by sening a message if u just run the file terminal will close so u wont be able to check and since this is for eductional use it doesnt matter if terminal is open since were checking our own work

cd C:\Users\(user)\source\repos\botscript
python botscript.py

they were the cmd commands i ran to open script that way terminal stays open and i can test my message feture to check its working to be fair it works u dont nedd to test it but its good practice to do so)

6- test its working by doing /message testing (or whatever u wanna say) 

7- now u have ran that command on ur c2 pannel go to ur cmd where the file was ran and it will say

[Message from C2]: (whatever u said)

8- now u can test the other fetures and since u knwo the framework/basic template is working u can close it all down and 
customise the code which is the whole point of this its ment to be used as a template people build of thats 
why i choose python my main language is c++/c# but python is a very basic common known language which
most poeple will knwo strongly so please dont say "Oh ThIs COdE iS sHiT ItS So BaSIc" because thats the point 
ur ment to use it for learning testing and working up from this is like the ingrediants and your the chef who needs to cook with it



my contact info is

discord              - 9zvv
telegram             - nevtrapx
twitter              - swipvs
my discord community - https://discord.gg/uq54CHAyXe


just a side note this is the commands i used to run the c2 code on my windows vps incase people struggle

python c2.py

type that in cmd then to remove base words in cmd type /clear



and last thing I promise lol is this is detected the c2 code isn't but the worm is in order for me to run it in vms and test it I had to disable all anti virus including firewall/windows defender because its for testing purposes not to harm people in any way please don't be a wierdo and skid it
to harm others I was gonna include a tool that works as a fud to make code ud but I thought nah people will use it for the wrong reasons
if I do 

the tutorial on how to use is 

https://youtu.be/Lhs7mssxVoQ

