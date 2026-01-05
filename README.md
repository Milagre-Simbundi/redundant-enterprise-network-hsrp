# Redundant Enterprise Network with HSRP

## Overview
This project demonstrates a highly available enterprise network using
Hot Standby Router Protocol (HSRP) to provide default gateway redundancy.

## Technologies Used
- Cisco Packet Tracer
- HSRP
- Layer 2 Switching
- Layer 3 Routing

## Network Design
- Two routers configured in an HSRP group
- One active and one standby router
- Virtual IP used as the default gateway
- Switch connecting end devices

## Key Features
- Automatic failover with minimal packet loss
- No gateway reconfiguration required on hosts
- Improved network availability

## Verification
- `show standby` used to verify HSRP roles
- Continuous ping test performed during router failure
