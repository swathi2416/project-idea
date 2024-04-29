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

 ---------------------------**MULTI COLUD SECURITY ASSESSMENT TOOL**--------------------------------
**Multi-cloud security** is a strategy that aims to provide consistent and comprehensive risk management to protect all apps, APIs, and workloads in an organization's environment, regardless of where they are hosted.
**A cloud security assessment (CSA)** evaluates the cloud infrastructure for vulnerabilities, configuration weaknesses and potential threats. It analyzes the configuration of cloud service provider accounts or subscriptions and reviews the possible threats from the internet and within the cloud infrastructure itself.
**CLOUD SECURITY SCOPES**
1.Data Storage
2.Data Server
3. Computer Virtualization Framework
4.Operating System
5.Middleware
6.JDK Evironment(hardware,software,ram,rom)
7.Data
8.Application
9.End user device
**COLUD SECURITY SERVICE**
1.PLATFORM AS A SERVICE
2.SOFTWARE AS A SERVICE
3.INFRASTUCTURE AS A SERVICE
**CLOUD ENVIRONMENT**
1.Public
2.Private
3.Hybrid
**How it works?**
1.Data Security
2.IAM(Identity and Access Management  -->works based on prievilages
3.Governace and Compliance-->entire management
4.Data Retention and Business Contnuity Planning
5.Legal compliance
**CLOUD RISKS**
1.Cloud Based Infrastructure
2.Internal threats(Human error -Default changes not done)
3.external Threats (like phising)
**MITIGATIONS**
1.Never leave the default setting unchanged
2.Never leave the bucket open 
3.Strong Password 
4.Use Password managers
5.Protect all devices likes connected devices
6.Regular Backup
7.Permissions modification
8.Protect system from antivirus
9.Avoid public wifi
