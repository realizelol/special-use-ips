# IPv4
https://www.iana.org/assignments/iana-ipv4-special-registry/iana-ipv4-special-registry.xhtml

https://en.wikipedia.org/wiki/Multicast_address#IPv4

https://en.wikipedia.org/wiki/Reserved_IP_addresses#IPv4

| Network                   | RFC       | Specification                                    |
|:--------------------------|:---------:|:-------------------------------------------------|
| 0.0.0.0/8                 | 791       | "This" Network                                   |
| 0.0.0.0/32                | 1122      | "This host on this network"                      |
| 10.0.0.0/8                | 1918      | Private Network                                  |
| 100.64.0.0/10             | 6598      | Shared Address Space (e.g. CG-NAT)               |
| 127.0.0.0/8               | 1122      | Loopback                                         |
| 169.254.0.0/16            | 3927      | Link Local                                       |
| 172.16.0.0/12             | 1918      | Private Network                                  |
| 192.0.0.0/24              | 5736      | IETF Protocol Assignments                        |
| 192.0.0.0/29              | 7335      | IPv4 Service Continuity Prefix                   |
| 192.0.0.8/32              | 7600      | IPv4 dummy address                               |
| 192.0.0.9/32              | 7723      | Port Control Protocol Anycast                    |
| 192.0.0.10/32             | 8155      | Traversal Using Relays around NAT Anycast        |
| 192.0.0.170 __+__ 171/32  | 8880+7050 | NAT64/DNS64 Discovery                            |
| 192.0.2.0/24              | 5737      | TEST-NET-1                                       |
| ~~192.88.99.0/24~~        | ~~3068~~  | ~~6to4 Relay Anycast~~ (terminated: 2015-03)     |
| 192.168.0.0/16            | 1918      | Private Network                                  |
| 192.175.48.0/24           | 7534      | Direct Delegation AS112 Service                  |
| 198.18.0.0/15             | 2544      | Network Interconnect - Device Benchmark Testing  |
| 198.51.100.0/24           | 5737      | TEST-NET-2                                       |
| 203.0.113.0/24            | 5737      | TEST-NET-3                                       |
| 224.0.0.0/4               | 3171      | Multicast                                        |
| 240.0.0.0/4               | 1112      | Reserved for Future-Use                          |
| 255.255.255.255/32        | 919+922   | Limited Broadcast                                |


# IPv6
https://www.iana.org/assignments/iana-ipv6-special-registry/iana-ipv6-special-registry.xhtml

https://en.wikipedia.org/wiki/Multicast_address#IPv6

https://en.wikipedia.org/wiki/Reserved_IP_addresses#IPv6

| Network               | RFC         | Specification                                    |
|:----------------------|:-----------:|:-------------------------------------------------|
| ::/128                | 4291        | Unspecified Address                              |
| ::1/128               | 4291        | Loopback Address                                 |
| ::ffff:0:0/96         | 4291        | IPv6-to-IPv4-mapped Address Network              |
| 64:ff9b::/96          | 6052        | IPv4-IPv6 Translation                            |
| 64:ff9b:1::/48        | 8125        | IPv4-IPv6 Translation                            |
| 100::/64              | 6666        | IPv6 Discard-Prefix Network                      |
| 2001::/23             | 2928        | Special Network (check downwards)                |
| _2001::/32_           | _438+8190_  | _TEREDO_ Tunnel                                  |
| _2001:1::1/128_       | _7723_      | _Port Control Protocol Anycast_                  |
| _2001:1::2/128_       | _8155_      | _Traversal Using Relays around NAT Anycast_      |
| _2001:2::/48_         | _5180_      | _Benchmarking_                                   |
| _2001:3::/32_         | _7450_      | _AMT_                                            |
| _2001:4:112::/48_     | _7335_      | _AS112-v6_                                       |
| ~~_2001:10::/28_~~    | ~~_4843_~~  | ~~_ORCHID_~~ (terminated: 2014-03)               |
| _2001:20::/28_        | _7343_      | _ORCHIDv2_                                       |
| _2001:30::/28_        | _9374_      | _Unmanned Aircraft System Remote ID_             |
| _2001:db8::/32_       | _3849_      | _Documentation_                                  |
| 2002::/16             | 3056        | 6to4-Tunnel                                      |
| 2620:4f:8000::/48     | 7543        | Direct Delegation AS112 Service                  |
| fc00::/7              | 4193        | Unique-Local - Private Network                   |
| fe80::/10             | 4291+8190   | Link-Local Unicast Network                       |
| ff00::/8              | 4291        | Multicast Network                                |
