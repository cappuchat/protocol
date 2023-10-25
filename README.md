# Cappuccino Protocol
*Cappuccino* is free and open-source protocol for self-hosted federated chatting network.

> [notice]
> this is an alpha version of *Cappuccino*!
> There can be drastic changes.

## Structure.
*Cappuccino* protocol currently contains following components:

* Server (aka. Chino)
* Client (aka. Cappuchat)
* User
* Server database provider (aka. Cafe)
* Chatting structure (aka. message)
* Server-Server communications
* Client-Server communications
* Server authentication
* Server authorization
* Client authentication
* Client authorization
* History vault
* User vault

## Components.
### Server
Server MUST have ECDSA key pair. (aka. `SERVER_KEYPAIR`)

### Client
Client MAY contain many users.

### User
User MUST have ECDSA key pair. (aka. `USER_KEYPAIR`)

User MUST use only one Server.
