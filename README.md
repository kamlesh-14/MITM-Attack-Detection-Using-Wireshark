# MITM-Attack-Detection-Using-Wireshark

## Project Objective
Detect MITM attacks by analyzing live network traffic using Wireshark.

## Tools Used
- Wireshark
- Kali Linux (Attacker)
- Metasploitable 2 (Victim)
- aprspoof

## Steps Performed
1. Set up Kali Linux and Metasploitable 2 in VirtualBox.
2. Configured both machines on the same NAT network.
3. Use ARPSpoof to carry out an ARP spoofing attack, redirecting traffic between two machines.
4. Captured traffic on Wireshark.
5. Applied filter: `arp`

## Observations
1. Observed Duplicate IP detected warning
2. shows attacker sending fake ARP replies to victim.
3. Duplicate use detected" messages
   
## Conclusion
Using Wireshark, it's possible to detect MITM attacks by filtering specific ports and analyzing the misbehaviour of packets
This method can help SOC analysts spot suspicious behavior early.
