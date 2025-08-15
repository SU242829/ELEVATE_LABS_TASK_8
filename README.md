Cyber Security Internship – Task 8
VPN Setup and Privacy Testing



Objective
Configure and test a free VPN to understand its role in securing online communications and protecting privacy.


Tools Used

ProtonVPN (Free Tier)

WireGuard protocol

Kali Linux terminal

ipinfo.io for IP verification


 
 Steps

Signed up for a free ProtonVPN account.

Downloaded and saved the WireGuard .conf file from ProtonVPN.

Moved it to /etc/wireguard/proton.conf and set correct permissions.

Connected using: sudo wg-quick up proton

Verified new IP and location via curl ipinfo.io.

Disconnected using: sudo wg-quick down proton

 
 Screenshots

VPN connection output (wg-quick up proton)

IP change verification (curl ipinfo.io)

Disconnection output (wg-quick down proton)

 
 Key Learning

VPNs encrypt internet traffic and mask real IP addresses.

WireGuard offers lightweight, fast, and secure tunneling.

Privacy benefits depend on VPN provider policies.
