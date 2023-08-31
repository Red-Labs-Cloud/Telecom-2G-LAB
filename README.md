# Osmocom Cellular Network Infrastructure
Configure a Osmocom Cellular Network Infrastructure

## RAN

1 - OsmoBTS - A BTS implementation
2 - OsmoBSC - GSM Base Station Controller with support for many different BTS vendors and models attached via Abis (over E1 and IP).
3 - OsmoTRX - A transceiver for OsmoBTS to use with SDR hardware
4 - OsmoPCU - A packet control unit for GPRS/EDGE enabling the BTS.


## Core
1 - OsmoMSC - GSM/UMTS Mobile Switching Center with support for AoIP as well as IuCS. SCCPlite support is work in progress.
2 - OsmoHLR - minimal implementation of a Home Location Register
3 - OsmoSTP - SS7 Transfer Point to connect MSC and BSC
4 - OsmoMGW - Media GateWay to relay RTP streams


## GPRS

1 - OsmoSGSN - A Serving GPRS Support Node
2 - OsmoGGSN - A Gateway GPRS Support Node