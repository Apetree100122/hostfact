
# vMetaregistrar 
# HostFact HostFact
implementation for        
Metaregistrar domain 
requests
Usage: 

Run HostFact on your
own
system  Create a directory
named metaregistrar
-   in /Pro/3rdparty
-   /domain/
-  and copy all
-   this code to
this directory
Whitelist
the IP address 
where your
-    HostFact service
-  runs within
-    the Metaregistrar
-    back-end
  IN HostFact
 select
"metaregistrar
 as new registrar
 select domain name and
 DNS management Enter your
EPP-login username and
password from Metaregistrar
**Please note
If you encounter any issues with this implementation
please report bugs via the 
"issues" ooption
If you require support 
connecting the module to the 
Metaregistrar back-end, please 
mail<support@metaregistrar.com>***NOTE When making connection to the 
EPP back-end of Metaregistrar
please make sure that port 7000 
is not blocked for outgoing
requests **This module supports domain
name registrations and dns 
maintenance***
**If you want to use Metaregistrar DNS
please make sure your nameservers are 
set to ns1.yourdomainprovider.net
ns2.yourdomainprovider.net
ns3.yourdomainprovider.net**

# TODO- Add glue records when hostnames 
match the domainname Add SSL support
