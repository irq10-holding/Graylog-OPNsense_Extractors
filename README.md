# Graylog-OPNsense_Extractors
Extractors for Graylog to parse OPNsense firewall logs. Should be able to parse most all IPv4/IPv6, ICMP, UDP, & TCP messages.
6/21/18 Update to IPv6 ICMP. OPNsense sends "ICMPv6", remove case insensitive regex for better processing when under heavy load.
6/26/21 Update - Removed some ICMP extractors. Updated to new OPNsense log message format.
