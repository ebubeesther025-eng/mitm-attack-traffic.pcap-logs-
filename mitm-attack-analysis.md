# MITM Attack Analysis

## Objective
Simulate a Man-in-the-Middle (MITM) attack and analyze captured traffic.

## Setup
- Tools: Wireshark, Ettercap
- Environment: Virtual machines (Victim, Server, Attacker)
- Method: ARP spoofing to redirect traffic

## Observations
- Normal traffic: Direct communication between Victim and Server
- During attack: ARP packets show spoofed MAC addresses
- Wireshark logs reveal intercepted HTTP requests

## Analysis
- MITM allowed attacker to view unencrypted credentials
- Demonstrates confidentiality and integrity risks

## Mitigation
- Use HTTPS/TLS encryption
- Deploy intrusion detection systems
- Implement anti-spoofing measures

## Conclusion
The simulation highlights
