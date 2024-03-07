The link to an external resource file. The file should be a plain text file with one IP/IP range/Subnet each line. IPv6 address will be ignored in DNS filter profile. For example,

192.168.2.100
172.200.1.4/16
172.16.1.2/24
172.16.8.1-172.16.8.100
2001:0db8::eade:27ff:fe04:9a01/120
2001:0db8::eade:27ff:fe04:aa01-2001:0db8::eade:27ff:fe04:ab01

--

The link to an external resource file. The file should be a plain text file with one domain each line and supports simple wildcard. For example,

mail.*.example.com
*-special.example.com
www.*example.com
example.com
