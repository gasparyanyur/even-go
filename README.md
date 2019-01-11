# EVEN Node Reference Go Implementation

The EVEN Node repository is the EVEN Platform Go Implementation and the embodiment of the EVEN network specification. 

This is a full-featured [[EVEN]](https://evenfound.org/) node with a convenient JSON-REST HTTP interface.
It allows users to become part of the [[EVEN]](https://evenfound.org/) network as both a transaction relay
and network information provider through the easy-to-use [[API]](https://evenfound.org/reference).

It is specially designed for users seeking a fast, efficient and fully-compatible network setup.

Running an EVEN node also allows light wallet users a node to directly connect to for their own wallet transactions.

<!-- *-* **License:** GPLv3 -->

## How to get started

The EVEN network is an independent peer-to-peer network with a first-user, friend-to-friend, network structure based on IPFS feature:

- As a 'first-user' network, to access the data streams and APIs that other users provide, you must first exchange your IP and port configuration with a current user.

- As a 'friend-to-friend' network, you have the privilege of joining new users into the network through your node
by adding them to your approved neighbors list — ensuring that you both broadcast to them and also receive their broadcasts.
 
Everyone will be welcoming and very happy to help you get connected.
If you want to get tokens for your testcase, please just ask in one of the communication channels.

## How it work
> Simple EVEN Network architecture illustration

<p align="center">
  <img src="https://github.com/evenfound/even-network/blob/develop/doc/even-node.png">
</p>

## Folders Structure

> Structure EVEN Node project and short introduction all its subrpojects

<!-- ### A typical top-level directory layout -->

    .
    ├── build                   # Compiled files
    ├── node                    # Source code files
    │   ├── app                 # Node main files 
    │   ├── hdgen               # HD generator
    │   ├── iipfs               # IPFS intarface
    │   └── ...
    └── README.md

> Use short lowercase names at least for the top-level files and folders except  `README.md`



