# Protocols

Common examples of protocols used in micro-controllers and embedded systems:

| Standard | Transmission | Signal wires | Data rate | Distance | Protocol | Invented
| --- | --- | --- | --- | --- | --- | ---
| RS-232 | | | `20 kpbs` | `15 m`| simplex / full duplex
| UART | Async | 2 | `20 kbps` | `15 m`
| SPI | Sync | > 4 | `20 Mbps` | `0.1 m` | full duplex, single master | Motorola
| I2C | Sync | 2 | `1 Mbps` | `0.5 m` | half duplex, multi-master | Philips
| CAN | Sync | 2 | | | full duplex, multi-master | Bosch
| USB | | 4 | `480 Mbps` (USB2) <br> `5 Gbps` (USB3)



## references

1. [USART, UART, RS232, USB, SPI, I2C, TTL, etc. what are all of these and how do they relate to each other?](https://electronics.stackexchange.com/questions/37814/usart-uart-rs232-usb-spi-i2c-ttl-etc-what-are-all-of-these-and-how-do-th)
- [USB vs Serial](http://www.brouhaha.com/~eric/editorials/usb_vs_serial.html)
