PANA (Protocol for Carrying Authentication for Network Access) is an IP-based protocol that allows a device to authenticate itself with a network to be granted access. PANA will not define any new authentication protocol, key distribution, key agreement or key derivation protocols. For these purposes, the Extensible Authentication Protocol (EAP) will be used, and PANA will carry the EAP payload. PANA allows dynamic service provider selection, supports various authentication methods, is suitable for roaming users, and is independent from the link layer mechanisms.

This project implements a PANA library.
There are also a PAC and a NAS test apps.

http://en.wikipedia.org/wiki/Protocol_for_carrying_Authentication_for_Network_Access