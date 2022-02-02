# About Turris

Czech company called [CZ.NIC](https://www.nic.cz/), the maintainer of the `.cz` top-level domain name develops open-source series of routers called [Turris](https://www.turris.com/en/), currently these devices run TurrisOS derived from openWRT which is too light-weight, however during late 2022 a new version of the flag ship product, [Turris Omnia](./Turris-Omnia-2022.md) should be released with sufficient horse power become the ultimate home-appliance for Cardano community members.

Combining Turris Omnia 2022 with openSUSE MicroOS will enable Cardano users to have a great Internet gateway that separates their home network from the dangers of the Internet, while also supporting Cardano network and applications running on it. Possible use-cases include:

- Cardano Node Relay
- Distributed Storage

## Turris Omnia 2020 HW Specifications

| Component Type   | HW Component                            | Notes |
|------------------|-----------------------------------------|-------|
| CPU              | 1.6 GHz dual core ARM                   |       |
| Memory           | 2 GB DDR3 RAM                           |       |
| Storage          | 8 GB flash                              |       |
| WAN port         | 1x 10/100/1000 Mbps (RJ-45)             |       |
| LAN switch ports | 5x 10/100/1000 Mbps (RJ-45)             |       |
| USB ports        | 2 x USB3.0 / A connector                |       |
| Wi-Fi (mPCIe)    | 3×3 MIMO 802.11ac, 2×2 MIMO 802.11b/g/n |       |
| Expansion bus    | mSATA / mPCIe                           |       |

## Turris Omnia 2022 HW Specifications

| Component Type   | HW Component                                        | Notes                                                                        |
|------------------|-----------------------------------------------------|------------------------------------------------------------------------------|
| CPU              | Armada 9130, 2.0 GHz 4 core 64bit                   | Future version could be build using RISC-V SoC                               |
| Memory           | 4GB+ RAM                                            | Can be upgraded to 8GB if we make a bulk order                               |
| WAN port         | 1 x WAN 10Gbps ETH RJ-45                            |                                                                              |
| LAN uplink port  | 1 x LAN 10Gbps SFP                                  | If you need more ports, you can just connect a switch with 10GbE SFP+ uplink |
| LAN switch ports | 4 x LAN 2.5Gbps ETH RJ-45                           |                                                                              |
| USB ports        | 2 x USB3.0 / A connector                            |                                                                              |
| Expansion bus    | 1 x miniPCIe used by WiFi6 card                     |                                                                              |
| Expansion bus    | 1 x M.2 B Key slot ready for 5G modem (USB3.0/2.0)  |                                                                              |
| Expansion bus    | 1 x M.2 E Key slot ready for Wi-Fi (PCIe nebo SDIO) |                                                                              |
| Expansion bus    | 1 x M.2 M Key slot ready for HDD or SSD drive       |                                                                              |
