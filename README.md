# project-idea
Download windows 2019 server and osi edition
in kali create a new virtual machine
click the file which we have downloaded
then give windows standard core
set password
location-select whch have more space or create new folder if have  D drive also
60.0gb maxi size
keep it in NAT-->FINISH
Select the os
Click 2nd option  -->Next
power off
If you got error go to windows server in kali
go to edit --> floppy disk-->connect at  power on (unclick)-->next
open windows server in vm -->next-->install-->(2 nd option)next-->accept the agreement-->next
new custom install have to be chosen 
click new in the right side corner(size should be changed as 20,000)-->apply
delete all drive except drive 0
click new -->the size automatically decreased-->apply-->next
after installation give new password 
domain controller has been opened
windows-->dashboard-->server manager-->local server
dashboard -->add roles anf features-->next-->rolebased-->ip displayed-->server roles-->active directory domain serices,dns server-->nextconformation(restart checkbox)-->install
click the warning button-->promote-->add a new domain to an existing forest-->enter team name-->-->root domain name(in lowercase).local-->next-->domain controller option-->give password--->next-->path
cmd-->ping


