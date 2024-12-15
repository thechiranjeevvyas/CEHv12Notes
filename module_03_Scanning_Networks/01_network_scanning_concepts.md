# Section 01: Network Scanning Concepts

## Transmission Control Protocol (TCP)

The Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite.
It originated in the initial network implementation in which it complemented the Internet Protocol (IP).

TCP segment flags

- SYN: Synchronize sequence numbers. Only the first packet sent from each end should have this flag set. Some other flags and fields change meaning based on this flag, and some are only valid when it is set, and others when it is clear.
- ACK: Indicates that the Acknowledgment field is significant. All packets after the initial SYN packet sent by the client should have this flag set.
- FIN: Last packet from sender
- RST: Reset the connection

TCP is connection-oriented, and a connection between client and server is established before data can be sent.
The server must be listening (passive open) for connection requests from clients before a connection is established.
Three-way handshake (active open), retransmission, and error detection adds to reliability but lengthens latency.

Links

- [https://en.wikipedia.org/wiki/Transmission_Control_Protocol](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)

[Definition](../../definitions/definitions_T.md#transmission-control-protocol)

## nmap

Nmap is a network scanner created by Gordon Lyon.
Nmap is used to discover hosts and services on a computer network by sending packets and analyzing the responses.
Nmap provides a number of features for probing computer networks, including host discovery and service and operating system detection.

Links

- [https://nmap.org](https://nmap.org)
- [https://en.wikipedia.org/wiki/Nmap](https://en.wikipedia.org/wiki/Nmap)

[Definition](../../definitions/definitions_N.md#nmap)

## hping3

hping3 is a network tool able to send custom ICMP/UDP/TCP packets and to display target replies like ping does with ICMP replies.
It handles fragmentation and arbitrary packet body and size, and can be used to transfer files under supported protocols.

Links

- [https://www.kali.org/tools/hping3](https://www.kali.org/tools/hping3)

[Definition](../../definitions/definitions_H.md#hping3)

## Metasploit

Knowledge is power, especially when it’s shared.
A collaboration between the open source community and Rapid7, Metasploit helps security teams do more than just verify vulnerabilities, manage security assessments, and improve security awareness; it empowers and arms defenders to always stay one step (or two) ahead of the game.

Links

- [https://www.metasploit.com](https://www.metasploit.com)

- [Definition](../../definitions/definitions_M.md#metasploit)
