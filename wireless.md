# Wireless

Short to medium range

| Name | Organization | PHY / MAC Standard | Frequency | Power profile | Range | Data rate | Topology
| --- | --- | --- | --- | --- | --- | --- | ---
| NFC | ISO / IEC | ISO 13157 | `13.56 MHz` | months / years | `~10cm` |
| Bluetooth | Bluetooth SIG | 802.15.1 | `2.4 - 2.5 GHz` | days | `~10m` |
| BLE | Bluetooth SIG | 802.15.1 | `2.4 - 2.5 GHz` | days | `~10m` | `1 Mbit/s` | Scatternet
| WiFi | IEEE | [802.11](https://en.wikipedia.org/wiki/IEEE_802.11) | `2.4 - 2.5 GHz` | hours | `~30m` | `54 Mbit/s` | Star
| ZigBee | ZigBee Alliance | 802.15.4 | `868 - 868.8 MHz`, <br> `902 - 928 MHz`,<br>`2.4GHz` | months / years | `~100m` | `250 kbit/s` | Mesh
| Z-wave | Z-Wave Alliance | 802.15.4 | `900MHz` | | `~100m` | `40 - 100 kbit/s` | Mesh
| Thread | Thread Group | 802.15.4 | `2.4GHz` | | `~100m` | `250 kbit/s` | Mesh

Long range / cellular

| Name  | Standard | Data Rate
| --- | --- | ---
| 1G |  | `2 kbps`
| 2G | GSM, GPRS |`14.4 - 64 kpbs`
| 2.5G | EDGE | |
| 3G | UMTS |`2 Mbps`
| 4G | LTE |`200 Mbps - 1 Gbps`
| 5G | |`< 1 Gbps`
| WiMax | 802.16 |

## Wired

| Name | Organization | Standard
| --- | --- | --- |
| Ethernet | IEEE | 802.3|

## Low power industrial network for wide area (WAN)

Most LP WAN technologies are physical layer implementations only

| OSI | Physical | LoRaWAN | SigFox
| --- | --- | --- | ---
| Application | Application | undefined | undefined
| Presentation | Application | undefined | undefined
| Session |  Application | undefined | undefined
| Transport | Transport | undefined | undefined
| Network | Internet | undefined | undefined
| Data Link | Internet | undefined| partial definition
| Physical | Link | LoRa `169 - 960 MHz` | SigFox `900MHz`, `868MHz`

## Low power home networks for home / office (LAN)

WiFi is indicated as a comparison

| | WiFi | Z-Wave | ZigBee | Thread | BLE
| --- | --- | --- | --- | --- | ---
| PHY / MAC | IEEE 802.11.1 | ITU-T G.9959 | IEEE 802.15.4 | IEEE 802.15.4 | IEEE 802.15.1
| Frequency band | `2.4GHz` | `900MHz` | `2.4GHz` | `2.4GHz` | `2.4GHz`
| Topology | Star | Mesh | Mesh | Mesh | Scatternet
| Power usage | high | low | low | low | low

## TCP / IP vs 6LoWPAN

| OSI | Physical | TCP/IP | 6LoWPAN
| --- | --- | --- | ---
| Application | Application | HTTP, RTP | application
| Presentation | Application |
| Session |  Application |
| Transport | Transport | TCP, UDP, ICMP | UDP, ICMP
| Network | Internet | IP | IPv6 with LoWPAN
| Data Link | Internet | Ethernet MAC | 802.15.4 MAC
| Physical | Link | Ethernet PHY | 802.15.4 PHY

## References

1. [11 Internet of Things (IoT) Protocols You Need to Know About](http://www.rs-online.com/designspark/electronics/knowledge-item/eleven-internet-of-things-iot-protocols-you-need-to-know-about)
- [Smart home protocol war](http://www.iot-now.com/2015/08/10/35653-the-smart-home-radio-protocols-war/)
