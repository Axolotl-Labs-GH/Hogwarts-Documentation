# Network

## Network Overview

The network consists of 3 main parts, router, switch and then endpoints being 2 planned to expand to 3 Lenovo ThinkCentre Micro PC's acting as Servers.

The network uses the following software and services:

- [OpenWRT](https://openwrt.org/)
- [TechnitiumDNS](https://technitium.com/dns/)

## Network Addressing

The Network uses a complete /24 address divided into individual /28 subnets providing 14 useable hosts per subnet and 16 individual subnets

#### Hogwarts Network Individual Subnets

=== "1 - 192.168.1.0/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}


=== "2 - 192.168.1.16/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}

=== "3 - 192.168.1.32/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}

=== "4 - 192.168.1.48/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}

=== "5 - 192.168.1.64/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}

=== "6 - 192.168.1.80/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}

=== "7 - 192.168.1.96/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}

=== "8 - 192.168.1.112/28"

    - {Subnet Allocated Use}
    - {Network address}
    - {First Usable Address}
    - {Last Usable Address}
   
## Network Topology

``` mermaid
graph LR
  A[ISP Connection] --> |g/e-0| B[rte-1];
  B ---> |g/e-4| C[rte-1 - Axolotl Network];
  B --> |g/e-1| D[sw-1];
  D --> E[srv-lo-1];
  D --> F[srv-lo-2];
  D --> G[srv-pi-1];
  D --> H[srv-pi-2];
```

###### Device Pages

- [Hogwarts Primary Router](./hardware/Networking/rte-1.md)