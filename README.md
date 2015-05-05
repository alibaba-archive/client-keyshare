# Client Keyshare Extention for TLS

We define an extension that allows a TLS client to carry
Diffie-Hellman (DH) keyshare in ClientHello message, replacing
ClientKeyExchange message in the 2nd round-trip, so as to reduce the
full handshake latency of one network round-trip time (RTT).

See rfc-draft/ for details.

See patch/ for code (not available yet).
