# cPanel
cPanel &amp; WHM Administrator (CWA) - Core Curriculum  &amp; cPanel &amp; WHM Systems Administrator I (CWSA-1) - Core Curriculum

Correct Answer of cpanel certification:-
----------------------------------------
- Within which of the following WHM interfaces would you be able to add SPF and DKIM records to an account? <br>
=> WHM Home >> Account Functions >> Modify Account

- Diego is a web designer who operates his own cPanel & WHM server. He wants to create a test subdomain for one of his clients and upload some web content to it so that he can share a "beta" (non-production) version of the site to his client. <br>
Which of the following interfaces should he start with, in order to accomplish this? <br>
--- cPanel » Domains » Subdomains

- By default, cPanel creates SPF records in which of the following modes? <br>
--- Testing mode (non-production)

- To add a PTR record that points the IP address 192.168.0.4 to mail.example.com, which zone would you modify? <br>
--- 0.168.192.in-addr.arpa

- Which of the following options indicates what the abbreviation TTL stands for, in the context of DNS? <br>
--- Time To Live; indicating how long a resource record should be cached.

- Within which of the following WHM interfaces can you globally enable DKIM and SPF for all accounts? <br>
--- DNS Functions >> Enable DKIM/SPF Globally

- Nameserver address record setup in modern installations of cPanel & WHM, both within the Basic WHM Setup and Edit Reseller Nameservers and Privileges interfaces, provide support for certain DNS records associated which of the following types of hostnames? <br>
--- Hostnames that resolve to AAAA records.

- Which of the following options best describes the term recursive, in the context of DNS? <br>
--- A recursive nameserver can resolve non-local domains.

- Within which of the following WHM interfaces would you enter the default nameservers for accounts that a reseller creates? <br>
--- WHM Home >> Resellers >> Edit Reseller Nameservers and Privileges

- Which of the following statements best describes the term resolver? <br>
--- A nameserver that can resolve non-local domains.

- By default, cPanel creates SPF records in which of the following modes? <br>
--- Testing mode (non-production)

- Diego is a web designer who operates his own cPanel & WHM server. He wants to create a test subdomain for one of his clients and upload some web content to it so that he can share a "beta" (non-production) version of the site to his client.
Which of the following interfaces should he start with, in order to accomplish this? <br>
--- cPanel » Domains » Subdomains

- Of the following nameserver software options available in a cPanel & WHM environment, which is described as having the following major strengths? <br>
Very high performance.
Low memory footprint.
PowerDNS

- Within which of the following WHM interfaces would you be able to add SPF and DKIM records to an account? <br>
WHM Home >> Account Functions >> Modify Account

- Given the following options, which indicates the ideal source from which you should obtain your server's resolver IP addresses? <br>
Your hosting provider or data center.

- cPanel offers a DNSOnly installation specifically for the purpose of using with a standard cPanel & WHM environment in a DNS cluster configuration. Which of the following is the standard license cost associated with DNSOnly? <br>
Free.

- Which of the following DNS clustering synchronization types, found in the WHM interface, can be best described as the copying of all updated versions of local zone files to all servers in the cluster? <br>
Synchronize all zones to all servers.

- Which of the following statements best describes the term resolver? <br>
A nameserver that can resolve non-local domains.

- Which of the following best describes one of the primary, intended purposes of a DNSOnly server? <br>
Providing a means of establishing DNS redundancy in a cluster configuration.

- Which of the following statements most accurately describes the term clustering, in the context of a server hosting environment? <br>
Two or more servers that all serve the same purpose configured in a distributed, connected environment.

- If you have one DNSONLY server and three full cPanel & WHM servers, which of the following is recommended as the optimal cluster configuration, given this scenario? <br>
The cPanel & WHM servers should be set to push to the DNS Only server, which should not send updates back to the cPanel & WHM Servers.

- After performing an installation of cPanel & WHM on a fresh environment, what is the initial, default state of DNS clustering? <br>
DNS clustering is initially disabled, and must be manually enabled.

- The system's administrator receives an email alert from WHM when which of the following conditions occur? <br>
The hostname does not point to the main IP address on the server.

- Which of the following query returns the IP addresses of the nameservers for the IP address 10.9.8.7? <br>
dig +nssearch 8.9.10.in-addr.arpa

- Which of the following options most accurately describes the interface or interfaces that you would utilize to create reverse DNS zones from within WHM? <br>
WHM Home » DNS Functions » Add a DNS Zone, and then WHM Home » DNS Functions » Edit DNS Zone.

- Which of the following options accurately indicate a task that can be performed from within the WHM interface? <br>
Change an MX record.

- Given the selection of nameserver software options available in a cPanel & WHM interface, which of the choices below have a major weakness that can be described as having a considerably extended initial zone loading time, if the server contains a very large quantity of zones? <br>
BIND/named

- Which of the following MySQL/MariaDB-related terms can be accurately described as a data structure that improves the speed of operations in a table? <br>
Index

- Which of the following types of tables can you repair using the Repair a MySQL Database interface, found in WHM? <br>
MyISAM

- Given the following options, which accurately describe a feature specific to the MyISAM storage engine? <br>
MyISAM has repair capabilities that allow you to perform the REPAIR query, either directly or from the WHM interface, on tables that may have corrupted data or indexes.

- By default, what kind of remote MySQL access is allowed, given the correct user and password? <br>
No remote access is provided by default.

- Which of the following best describes the role of the MySQL root password in a cPanel & WHM environment? <br>
A password that is primarily handled via automated means by cPanel & WHM back-end services, and can be reset as needed.

- Which of the following definitions best describes InnoDB's data dictionary component? <br>
A part of the InnoDB storage engine that uses metadata to map structural information to the file it’s stored in.

- Which of the following terms can be described as the way that permissions are handled inside a MySQL or MariaDB database? <br>
Grants

- In modern versions of cPanel & WHM, what benefits can database prefixing, enabled from the SQL tab of the Tweak Settings interface in WHM, provide? <br>
Primarily cosmetic; helps server administrators identify database ownership, as well as providing auto-grouping in the phpMyAdmin interface.

- Which of the following terms can be described as the way that permissions are handled inside a MySQL or MariaDB database? <br>
Grants

- The WHM Home >> SQL Services >> Manage Databases interface allows you to do which of the following operations? <br>
Automated renaming of a MySQL/MariaDB database.

- Which of the following details about the remote server would you need to know, if you wanted to set up a new remote MySQL profile in WHM? <br>
Remote SSH port

- Which of the following types of tables can you repair using the Repair a MySQL Database interface, found in WHM? <br>
MyISAM

- WHM contains an interface feature that allows you to attempt an automatic repair on which of the following types of tables? <br>
MyISAM

- The WHM Home >> SQL Services >> Additional Access Hosts interface creates server-level grants that are similar to the grants that can be created in which of the following cPanel account-level Interfaces? <br>
cPanel Home >> Databases >> Remote MySQL

- Which of the following describes a term that indicates a trait of the object described by the table, or can be otherwise referenced as a table column? <br>
Field

- Which of the following options describes the best way to import a SQL dump into a PostgreSQL databases via the WHM interface? <br>
There are no features in WHM that provide this capability; it must be performed from the command-line.

- Which of the following best describes the role of the MySQL root password in a cPanel & WHM environment? <br>
A password that is primarily handled via automated means by cPanel & WHM back-end services, and can be reset as needed.

- Which of the following WHM interfaces would you use to configure a cPanel & WHM server to utilize a remote MySQL® server environment to handle its database operations? <br>
Manage MySQL® Profiles

- As of cPanel & WHM 60, what is the minimum version of MySQL that can be running on a remote server, in order for it to be used in a Remote MySQL Profile? <br>
5.5

- MySQL Profiles can be used to set up what kind of relationship between servers? <br>
1-to-1 (1:1) only

- When using a cPanel & WHM environment, remote MySQL capabilities should be set up via the MySQL Profiles interface in WHM at which of the following stages of a server's operations? <br>
After installation, but before beginning to create production accounts on the server.

- Given the following options, which of these indicate the correct amount of characters that a MySQL 4.1 password hash is composed of, before being updated to the current standard of 41 character-hashes? <br>
16 characters.

- Given the following options, which accurately describe a feature specific to the MyISAM storage engine? <br>
MyISAM has repair capabilities that allow you to perform the REPAIR query, either directly or from the WHM interface, on tables that may have corrupted data or indexes.

- Which of the following MySQL/MariaDB-related terms can be accurately described as the language used to add, remove, and view data in a database? <br>
SQL

- Which of the following describes a term that indicates a trait of the object described by the table, or can be otherwise referenced as a table column? <br>
Field

- Which of the following is one of the most common causes of MySQL upgrade failures? <br>
Aborting the upgrade, intentionally or otherwise, part-way through the procedure.

- In modern versions of cPanel & WHM, what benefits can database prefixing, enabled from the SQL tab of the Tweak Settings interface in WHM, provide? <br>
Primarily cosmetic; helps server administrators identify database ownership, as well as providing auto-grouping in the phpMyAdmin interface.

- When using a cPanel & WHM environment, remote MySQL capabilities should be set up via the MySQL Profiles interface in WHM at which of the following stages of a server's operations? <br>
After installation, but before beginning to create production accounts on the server.

- Which of the following options describes the best way to import a SQL dump into a PostgreSQL databases via the WHM interface? <br>
There are no features in WHM that provide this capability; it must be performed from the command-line.

- Which of the following WHM interfaces would you use to configure a cPanel & WHM server to utilize a remote MySQL® server environment to handle its database operations? <br>
Manage MySQL® Profiles

- Which of the following MySQL storage engines is the native default (native to MySQL - not necessarily in cPanel & WHM) engine used by MySQL versions 5.5.5 and above? <br>
InnoDB

- Which of the following types of tables can you repair using the Repair a MySQL Database interface, found in WHM? <br>
MyISAM

- Which of the following is one of the most common causes of MySQL upgrade failures? <br>
The my.cnf file contains a number of non-default customizations that have not been verified prior to upgrading.

- Using the Manage MySQL Profiles interface in WHM, what is the recommended maximum number of cPanel & WHM servers should be connected to each configured remote MySQL server? <br>
1

- The WHM Home >> SQL Services >> Manage Database Users interface in WHM can be used for which of the following purposes? <br>
Rename existing database users.

- Which of the following actions can you perform directly from within the WHM interface, without using phpMyAdmin? <br>
Change a database user's password.

- Which of the following database-related term can be defined as the marking of a table or row so that only one process can access it a time? <br>
Locking

- Which of the following options accurately describe an action that can be performed from within WHM's EasyApache 4 interface? <br>
Change the MPM that is used in your Apache installation.

- When operating in a cPanel & WHM environment running EasyApache 4, within which of the following WHM interfaces can you adjust the server's default PHP version? <br>
This can be adjusted from within WHM's MultiPHP Manager interface.

- Which of the following options best describes the method you would use to install the PHP-FPM software, within a cPanel & WHM environment? <br>
PHP-FPM appears under the PHP Extensions stage of the EasyApache 4 profile customization walkthrough.

- In modern installations of cPanel & WHM, EasyApache 4 will allow you to install which of the following versions of Apache? <br>
Apache 2.4

- In modern installations of cPanel & WHM, how is the PHP version determined for newly created accounts, when System PHP-FPM status is set to ON? <br>
It is set to the same value as the system default.

- Which of the following EasyApache 4 profile actions can you perform from WHM's EasyApache 4 interface, in modern installations of cPanel & WHM? <br>
Upload a profile file from your file system or via a URL.

- Which of the following options best describes one of the most notable behaviors that separate the DSO handler from other PHP handlers available in a cPanel & WHM environment? <br>
DSO does not create new "php" processes to handle requests, but instead works internally with Apache, spawning from the parent httpd process.

- In addition to increasing the speed of the build process, which of the following options describes another reason that EasyApache 4 provides an improvement over EasyApache 3? <br>
Reduced chances of critical Apache failures.

- Which of the following options describes the appropriate method needed to enable PHP-FPM from within the WHM interface? <br>
PHP-FPM is enabled via WHM's MultiPHP Manager interface.

- When operating in a cPanel & WHM environment running EasyApache 4, within which of the following WHM interfaces can you adjust the server's default PHP version? <br>
This can be adjusted from within WHM's MultiPHP Manager interface.

- In modern installations of cPanel & WHM, when selecting DSO from the EasyApache 4 interface without mod_ruid2 or mpm_itk, what recommendation will be displayed to you automatically, directly from within the EasyApache 4 interface? <br>
PHP DSO runs as the nobody user by default. In a shared hosting environment, this is a security issue.

- Which of the following PHP handlers can only be used on one PHP version at a time? <br>
DSO

- Which of the following accurately indicates the user that processes created for the DSO handler are owned by? <br>
nobody user

- Which of the following options best describes the procedure needed to enable the BlueHost SymLink Protection Patch? <br>
Toggle the corresponding option found in WHM's Apache Configuration's Global Configuration interface.

- In a cPanel & WHM environment, which of the following options accurately describe what the system default PHP version setting defined in WHM's MultiPHP Manager interface represents? <br>
The version that is used if a domain does not already have a specific version selected for it.

- When operating in a cPanel & WHM environment, which of the following files are used by the system to define the PHP configuration? <br>
/etc/apache2/conf.d/php.conf

- You're operating in a PHP 5.6 environment and using DSO as your PHP handler. You've created a .user.ini file in your website's public_html folder, but are not seeing your changes reflected. <br>
Of the following choices, which of these most accurately describes the issue that is occurring here? <br>
An .htaccess file stored in public_html should be used instead, containing the appropriate syntax for declaring PHP values.

- If a user wants to utilize the system default version of PHP, which of the following selections would they enable for their account? <br>
inherit

- In a cPanel & WHM environment, which of the following options accurately describe what the system default PHP version setting defined in WHM's MultiPHP Manager interface represents? <br>
The version that is used if a domain does not already have a specific version selected for it.

- When operating in a cPanel & WHM environment, which of the following files are used by the system to define the PHP configuration? <br>
/etc/apache2/conf.d/php.conf

- Of the following options, which of these handlers operate in a non-persistent state, requiring the creation of new PHP processes each time something is executed? <br>
suPHP

- In modern installations of cPanel & WHM, when selecting DSO from the EasyApache 4 interface without mod_ruid2 or mpm_itk, what recommendation will be displayed to you automatically, directly from within the EasyApache 4 interface? <br>
PHP DSO runs as the nobody user by default. In a shared hosting environment, this is a security issue.

- In modern installations of cPanel & WHM, which of the following PHP configuration values are set automatically during the Initial Setup Assistant steps? <br>
memory_limit

- Which type of user can select the version of PHP that can be used within a particular cPanel account, using the cPanel & WHM interfaces? <br>
Both the cPanel account user and the WHM root user.

- Given the following options, select the components or component combinations that would provide standard per-user process ownership for handling PHP content. <br>
suPHP (mod_suphp) OR Ruid2 (mod_ruid2) OR PHP-FPM

- Which of the following Apache modules are core to Apache and can be disabled, but cannot be removed using the EasyApache 4 interface? <br>
mod_userdir

- Which of the following options is NOT a real Multi-Processing Module (MPM) available for installation within WHM's EasyApache 4 interface? <br>
Postfork

- Which of the following options accurately describes an action that can be performed from within WHM's EasyApache 4 interface? <br>
Install new PHP extensions for use in your active Apache/PHP environment.

- Which of the following options accurately indicates the file syntax that can be seen within downloaded EasyApache 4 profiles? <br>
JSON

- As a first step in DNS resolution, what does a resolver query to determine the address of the TLD nameserver? <br>
The root nameserver

- To ensure that the internet sees the changes you've made to a DNS zone file manually, what should be updated? <br>
The serial number

- To retrieve the IPv6 record of a domain, I would query for the domain's __________ record. <br>
AAAA

- To force my local system to resolve a domain to a specific IP address, I would modify the __________ file. <br>
/etc/hosts

- DNS zone files will only be found in /var/named when BIND/named is in use. <br>
False

- True/False: BIND/named's DNS zone files are stored in /etc/named. <br>
False

- The rndc utility can be used to administer a BIND/named server either locally or remotely. <br>
True

- To reload NSD, I would execute the __________ script. <br>
rndc reload

- Which of the following would be the best way to restart the DNS server from the command-line? <br>
/scripts/restartsrv_named

- Resetting a DNS zone using a zone template is one method that can be used to address a malformed DNS zone. <br>
True

- Zone templates can be used to ensure that changes to zones are saved when the DNS server is restarted. <br>
False

- Which of these looks like a BIND/named zone file name? <br>
domain.net.db

- What does the Error logging severity imply, when referring to BIND/named logs? <br>
A problem has been encountered during BIND/named operations.

- Which of these logging categories encompasses all categories that have not already been explicitly configured to use another specific channel? <br>
default

- True/False: On a server that does not need to facilitate zone transfers, set "allow-recursion" to "none" in the named.conf file to disable them. <br>
False

- What does the acronym ACL represent? <br>
Access Control List

- True/False: To define a range or subnet of IP addresses for the system to re-use within other areas of the named.conf, create a named ACL. <br>
True

- Which of the following command-line tools can be used to list running processes in a Linux environment? <br>
ps

- When you see a "rndc reload: connection refused" error, which of the following commands should you run first? <br>
/scripts/fixrndc

- By default, which of these logging categories are routed into the default_log channel, in a BIND/named DNS server configuration? <br>
general

- To force the local system to resolve a domain to a specific IP address, which of the following files would you modify to accomplish this? <br>
/etc/hosts

- Which of the following is the first nameserver that the resolver queries to determine the address of the TLD nameserver? <br>
The root nameserver.

- On a server that does not need to facilitate zone transfers, which of the following configuration variables found in the named.conf file should be set to none to disable them? <br>
allow-transfer

- Which of the following utilities included with BIND/named can be used to troubleshoot malformed zone files? <br>
named-checkzone

- In a cPanel & WHM environment, you will find zone files stored in /var/named when using which of the following namesever software? <br>
All of these.

- Which of the following DNS-related command-line utilities would provide you with similar results to those given by the dig utility, and is used for essentially the same purposes? <br>
nslookup

- When a remote mail exchanger handles a domain's mail, which of the following files must include the domain? <br>
/etc/remotedomains

- A banking website wants to prevent inappropriate certificate authorities from issuing certificates for their domain. Which of the following record types would best be used to assist in accomplishing this? <br>
CAA

- To ensure that the internet sees the changes that you make DNS zone file manually, which of the following components of a DNS zone should you update? <br>
The serial number.

- In a cPanel & WHM environment, DNS zone files can be found in which of the following folders? <br>
/var/named

- What does the acronym TLD represent, as in for a "TLD nameserver"? <br>
Top-level Domain

- If you create a customized DNS zone template from the command-line, which of the following would be a correctly-named custom template file name? <br>
root_templatename

- To retrieve the IPv6 record of a domain, you would query for which of the following records in a domain? <br>
AAAA

- Which of the following options best describes the role of DNSSEC? <br>
Provides cryptographic authentication of DNS zones.

- Which of the following is the default path for the BIND/named configuration file? <br>
/etc/named.conf

- Which of the following nameserver applications does not load all of its DNS zones upon startup? <br>
MyDNS

- What does the Error logging severity imply, when referring to BIND/named logs? <br>
A problem has been encountered during BIND/named operations that may allow further operations to continue.

- When operating within a cPanel & WHM server, which of the following indicates the best method to restart the DNS server from the command line? <br>
/scripts/restartsrv_named

- Registrant information associated with domain names is maintained in an online database accessible with what service? <br>
WHOIS

- By default in a cPanel & WHM environment, the system logs cluster-related messages into which of the following log files? <br>
/usr/local/cpanel/logs/dnsadmin_log

- Which of the following is one method that you can use, within the WHM interface, to repair a malformed DNS zone using a zone template? <br>
Reset a DNS Zone

- In a BIND/named configuration, you can modify the level of detail that is provided to remote servers regarding which of the following types of information? <br>
Host application details indicating version and server data regarding your BIND/named installation.

- Which of the following options best indicate the typical delivery failure rate that a spamming email account will report, if examining from the Mail Delivery Reports interface found in WHM? <br>
The account will have a high failure rate.

- If you suspect that mail has not been delivered because the user is over their quota, in which of the following WHM interfaces might you look to confirm why the message was not delivered? <br>
WHM Home » Email » Mail Delivery Reports

- All mail from a specific user is neither delivered to the inbox nor bounced. <br>
When you check the WHM Home » Email » Mail Delivery Reports interface, you see a green checkmark icon next to the message. Which of the following options best describes what this indicates? <br>
That the message was delivered successfully to a folder other than the inbox.

- Given the following options, which describe an actual reason that the system may place a message into the Exim queue? <br>
There are DNS issues preventing Exim from finding the remote mail server.

- Given the following options, which best describes something about an email address that can be determined by using the WHM Home » Email » Mail Troubleshooter interface, found in WHM? <br>
It will indicate whether the destination address forwards mail to a remote server.

- You can use the Exim Configuration Manager - Basic Editor to configure Exim to deliver mail without scanning messages based on which of the following criteria? <br>
When the message is over a certain size.

- Given the following options, which of these accurately describe the behavior of the Mail Troubleshooter interface, found in WHM? <br>
It can report the remote or local server that Exim uses to hand off messages for a specific email address.

- Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as enabling the checking of DNS resolution to see if the sender's domain exists? <br>
Sender Verification

- Which of the following tools may help you to resolve issues indicated by the time moved backwards warning? <br>
The "ntp" tool.

- In which WHM interface can you configure the forwarders for the root, cpanel, and nobody mail accounts? <br>
WHM Home » Server Contacts » Edit System Mail Preferences

- Which of the following methods best indicate the recommended approach for backing up, restoring or resetting the system's Exim configuration? <br>
Use the corresponding functions found within the Exim Configuration Manager interface, in WHM.
