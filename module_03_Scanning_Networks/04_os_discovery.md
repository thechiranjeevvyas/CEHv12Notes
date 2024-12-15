# Section 04: OS Discovery

## Banner Grabbing

Banner grabbing is a technique used to gain information about a computer system on a network and the services running on its open ports. Administrators can use this to take inventory of the systems and services on their network. However, an intruder can use banner grabbing in order to find network hosts that are running versions of applications and operating systems with known exploits.

Links

- [https://en.wikipedia.org/wiki/Banner_grabbing](https://en.wikipedia.org/wiki/Banner_grabbing)

[Definition](../../definitions/definitions_B.md#banner-grabbing)

## Identifying Target OS

Wireshark

[Definition](../../definitions/definitions_W.md#wireshark)

Discovery using `nmap`

```shell
nmap -O 10.10.10.10
```

### nmap script engine

> The Nmap Scripting Engine (NSE) is one of Nmap's most powerful and flexible features.
> It allows users to write (and share) simple scripts to automate a wide variety of networking tasks.
> Those scripts are then executed in parallel with the speed and efficiency you expect from Nmap.
> Users can rely on the growing and diverse set of scripts distributed with Nmap, or write their own to meet custom needs.

nmap IPv6

```shell
nmap -6 -O 10.10.10.10
```

- [https://nmap.org/book/nse.html](https://nmap.org/book/nse.html)
