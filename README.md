
8/4/2017 21:15 Start *************************

Successfully connected to AWS Server via RDP. 
Installing OO 10.50
(Link didn't seem to work from IE: https://s3-eu-west-1.amazonaws.com/ooinstaller/1050/Software_HP_OO_Product_SW_and_Doc_10.50_MLU_T9030-15015.zip )
Link works from Home PC. 
Tried to download Firefox. 
No Space. 
Check C: 0Bytes Free of 29.6GB

21:20 ...this a trick question?

Firing up a new VM. (Using Azure, as Ive got MSDN Credit, and an auto build script based on this I wrote: https://github.com/r3adm3/playingInAzure/blob/master/azureCreate5VMs.ps1)
Connection details:

altestbox-af.westeurope.cloudapp.azure.com
ALAdmin
xytFgwJc6pWtt6T9GjP2V3nP

BaseVM up 21:29

Used this BoxStarter script to install dependencies for OO (I've had problems installing OO Studio on Vanilla Windows in the past and put this together. Running the below in a Runas Admin cmd.exe, installs everything with no user interaction :D )
START http://boxstarter.org/package/nr/url?https://gist.githubusercontent.com/r3adm3/bca907b9adc8309ed2c0/raw/dc5d3ff9ab7b3e66ba43b390ec3680a16b868d96/gistfile1.txt

...turn off IE Security Configuration first tho in Server Manager > Local Server 

More boxstarter scripts hosted on my gist github here: https://gist.github.com/r3adm3
(most should still work)

21:55 Boxstarter Dependencies finished. OO Studio Downloaded.

22:25 Install OO completed.
Hooked up to github: https://github.com/r3adm3/challenges2

22:35 Simple Primary and subordinate flows setup

22:40 Stop.

...turn on IE Security Configuration again in Server Manager > Local Server, make IE secure again


