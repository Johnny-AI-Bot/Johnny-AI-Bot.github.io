# Network Address Translation (NAT)

This project demonstrates configuring Network Address Translation (NAT) to allow private internal hosts to securely access external networks while conserving public IP space.

The lab focuses on translating internal RFC1918 addressing to a public-facing address, validating connectivity, and verifying NAT behavior through troubleshooting outputs.

## Key Concepts Demonstrated
- Private vs public IP addressing
- Static NAT vs Dynamic NAT vs PAT (NAT Overload)
- NAT inside / NAT outside interfaces
- Default routing for internet access
- Verifying translations and troubleshooting

## Lab Overview
- Internal LAN uses private addressing
- Edge router performs NAT to allow outbound access
- Translations verified using show commands and connectivity tests

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS routing and NAT configuration
- Basic troubleshooting (translations, routing, interface roles)

## Skills Demonstrated
- Enterprise edge routing fundamentals
- NAT configuration and validation
- Connectivity troubleshooting and verification
