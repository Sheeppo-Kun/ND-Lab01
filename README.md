# NDLab01 - Packet Tracer Introduction

## Description
This project implements a basic network topology using Cisco Packet Tracer.

## Devices
- R1-ISP
- R2-Central
- S1-Central
- Eagle Server
- 11 Pods with 2 hosts per Pod

## Main Configuration
- Serial connection between R1-ISP and R2-Central
- LAN connection from R2-Central to S1-Central
- Eagle Server connected to R1-ISP
- Static routing between the networks
- IP addressing configured according to the lab requirements

## Verification
The network was verified using:
- `show ip interface brief`
- `show ip route`
- `ipconfig`
- `ping`
- `tracert`
- Simulation Mode with ARP/ICMP

## Files
- `NDLab01.pkt` - Cisco Packet Tracer project
