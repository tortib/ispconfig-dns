# ispconfig-dns
This modification to ISPConfig3 will allow only the server IPv4 & IPv6 addresses to be displayed in the AJAX popup window that appears when you click on the "IP Address" field for the new DNS Record in ISPConfig3.  The data is pulled from the server_ip table so you will have to have the IP addresses added to the "Server IP addresses" under the "System" section in ISPConfig3.

# Installation
Copy the ispconfig-dns/interface/web/dns/ajax_get_json.php file to your /usr/local/ispconfig/interface/web/dns/ directory to apply the new changes.  I recommend creating a copy of the origional ajax_get_json.php file prior to moving the file over.

```cp /usr/local/ispconfig/interface/web/dns/ajax_get_json.php /usr/local/ispconfig/interface/web/dns/ajax_get_json.php.bak```

# Happy Hosting!
