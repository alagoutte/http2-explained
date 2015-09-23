# 15. http2 in Wireshark

A major change of http2 is binary framing ! and the better tool for analyse binary framing is Wireshark.

Wireshark support TLS (ALPN, NPN) and Clear (Upgrade)

## 15.1. What Wireshark support ?

Wireshark decode http2 from draft-04 (Thanks to Stephen, Alexis...). 
With Wireshark 1.12.x, it is possible to decode draft-12 protocol (but don't compatible with final draft).
It is recommanded to use the last developement release (1.99.x)

## 15.2. TLS

https://developer.mozilla.org/en-US/docs/Mozilla/Projects/NSS/Key_Log_Format

## 15.3. Stats!

