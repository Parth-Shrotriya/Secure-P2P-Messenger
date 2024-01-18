![logo]([https://github.com/Parth-Shrotriya/MentHealth/blob/main/Turing_hacks(Hack%20Chambers).jpg](https://github.com/Parth-Shrotriya/Secure-P2P-Messenger/blob/main/Screenshot%202024-01-19%20013609.png))
# Secure P2P Messenger
Version: 1.0
Platform: Windows, Mac OSX, and Linux
Language: Go 1.16
License: MIT

## Overview
Secure P2P Messenger is a terminal-based P2P chat application developed in Golang, utilizing libp2p and the IPFS network for peer discovery and routing. Inspired by chat examples from libp2p's pubsub library, Secure P2P Messenger represents an evolved and fully featured version. It employs a Kademlia DHT from libp2p for peer discovery and routing, integrating essential libp2p components like TLS encryption, peer active discovery, and YAMUX stream multiplexing.

## Key Features:
Seamless switching between different chat rooms without restarting the application.
Dynamic username changes at any point.
Cross-network communication for nodes behind NATs through automatic router configuration using UPnP and AutoRelay (TURN).
Note: Communication between nodes on different private networks is supported starting from version 1.1.0.

## Dependencies
libp2p: A modular network stack library born out of The IPFS Project. Secure P2P Messenger's P2P and GossipSub layers are built using the Go implementation of libp2p.
tview: A terminal UI library in Golang with rich, interactive widgets. Secure P2P Messenger's UI layer is built using tview and tcell.

## Future Development
1. Support for QUIC and WebSocket transports.
2. Migration to Protocol Buffers for message encoding.
3. Chat room notification when users change names.
4. Support for other PubSub routers (RandomSub, FloodSub, and EpiSub).
5. Support for password-protected chat rooms.
