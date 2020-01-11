# An rc.firewall script for Slackware

This script can define router, firewall or both on your machine. It can
be used in your BSD type system initialization. It supports four interfaces:
WAN, LAN, LO and Internet. The forwarding is done between the Internet and
the LAN interfaces. The user can define which ports to be available from the
WAN and Internet interfaces. The traffic from LAN and LO interfaces is
considered 'secure'.

_Note_: The project is no longer actively developed, because I now use a
firewall before my server.

