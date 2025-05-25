---
title: rte-1 - Router 1
---

# rte-1 - Router 1

=== "Front View"

    <figure markdown="span">
        ![rte-1-front](../../assets/rte-1-front.png){ loading=lazy, width="400" }
        <figcaption></figcaption>
    </figure>

=== "Rear View"

    <figure markdown="span">
        ![rte-1-rear](../../assets/rte-1-rear.png){ loading=lazy, width="400" }
        <figcaption></figcaption>
    </figure>

## Hardware Specs

Device Model: Asus RT-AC85P

##### Network Interfaces

- g/e-0
- g/e-1
- g/e-2
- g/e-3
- g/e-4

##### Power

- AC Input : 110V~240V(50~60Hz)
- DC Output : 12 V with max. 2.5 A current

## Config

Role - Primary Router

## Interfaces

| Interface    |   Description                  |   Speed   |   Addressing     |
| :----------: | :--------------:               | :-------: | :-----------:    |
| g/e-0        | Link from ISP                  | 1 Gigabit | WAN IP           |
| g/e-1        | Uplink to sw-1                 | 1 Gigabit | 192.168.1.1/28   |
| g/e-2        | Disabled                       | 1 Gigabit | N/A              |
| g/e-3        | Disabled                       | 1 Gigabit | N/A              |
| g/e-4        | Uplink to rte-1 (Axolotl Net)  | 1 Gigabit | 192.168.200.1/30 |

## Power

12v DC Cable