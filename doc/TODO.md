DPVS TODO list
==============

Short-term
----------

* [+] Merge DPDK-17.11.1
* [x] Basic traffic control
* [x] Neighbour (ARP) refactor
* [x] Tunnel Interface (gre/ipip)
* [x] NAT/Tunnel forwarding mode
* [x] Consistent hashing
* [x] Get real client IP for UDP, like TCP TOA.
* [x] Keepalive.conf support SNAT
* [x] Numa/fdir auto check.
* [ ] SNAT Related
    - [ ] Multi-WIPs for schedule (auto switch to new WIP if one fails).
    - [ ] Fixed group of WIPs for user, share or not share with other user.
    - [ ] White/black list.
    - [ ] Throughput and concurrency monitoring.
    - [ ] Throughput and/or concurrency limiting.
* [ ] Logging
    - [ ] Packet based logging.
    - [ ] Session based logging (creation, expire, statistics)
* [ ] CI, Test Automation setup.
* [ ] Performance optimization for 25G/40G NIC.
* [ ] Documents update.

Long-term
---------

* [ ] VM support
* [ ] IP fragment support, for UDP apps.
* [ ] Session Sharing
* [ ] ALG (ftp, sip, ...)
* [ ] VxLAN Support
* [ ] NIC without Flow-Director (fdir)
  - Packet redirect to workers.
  - RSS pre-calcuating.
* [ ] IPv6 Support.
