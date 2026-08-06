# Enterprise Network Design Using VLSM and Static Routing

## Overview

This project demonstrates the design and implementation of a multi-site enterprise network using Cisco Packet Tracer.

The network connects multiple branch offices through WAN links and implements VLSM addressing, static routing, and essential network services to provide full connectivity between all locations.

---

## Branches

- Sana'a 1
- Sana'a 2
- Taiz
- Aden
- Hodyda
- Mukalla
- ISP
- Gateway Router (R-GW)

---

## Network Services

- DHCP
- DNS
- HTTP
- TFTP

---

## Routing

- Static Routing

---

## Addressing

- IPv4
- VLSM (Variable Length Subnet Masking)

Assigned Network:

```
111.52.0.0/16
```

---

## Software

- Cisco Packet Tracer 8.x

---

## Repository Structure

```
Enterprise-Network-Design-Using-VLSM-and-Static-Routing/
│
├── README.md
├── Enterprise-Network-Design-Using-VLSM-and-Static-Routing.pkt
│
├── Configurations/
│   ├── R-GW.txt
│   ├── ISP.txt
│   ├── SANA1.txt
│   ├── SANA2.txt
│   ├── TAIZ.txt
│   ├── ADEN.txt
│   ├── HODYDA.txt
│   └── MUKALLA.txt
│
└── Screenshots/
```

---

## Configuration Files

Router configuration files are available in the `Configurations` directory.

| Router | Configuration File |
|---------|--------------------|
| R-GW | `R-GW.txt` |
| ISP | `ISP.txt` |
| SANA'A1 | `SANA1.txt` |
| SANA'A2 | `SANA2.txt` |
| TAIZ | `TAIZ.txt` |
| ADEN | `ADEN.txt` |
| HODYDA | `HODYDA.txt` |
| MUKALLA | `MUKALLA.txt` |

---

## Verification

The following tasks were successfully completed:

- VLSM addressing implemented
- Static routes configured
- DHCP service configured
- DNS service configured
- HTTP server accessible
- TFTP server configured
- End-to-end connectivity verified

---

## Author

Saleem Al-Rhimi

Cybersecurity Student

University of Sana'a

---

## License

This project is licensed under the MIT License.
