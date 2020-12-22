# End-to-end Encrypted Chat based on Signal

### Description ###
An end-to-end encrypted chat room application where multiple users can connect to a server, and begin sending encrypted messages to each other.
Only the connected clients will be able to read each others messages, and the server will only see the encrypted message that was sent.

Based on the Signal protocol, however not all aspects of the protocol were implemented. The parts of the protocol that were implemented include
- [x] Triple Elliptic-curve Diffie–Hellman (3-DH)
- [x] Prekeys
- [x] Cryptographic primitives (e.g. Curve25519, AES-256, and HMAC-SHA256)
- [ ] Double Ratchet algorithm


### Dependencies ###
- PyCryptodome 
  - Reference: https://pypi.org/project/pycryptodome/
  - Command: pip install pycryptodome
 
 
 ### Steps to Run ###
 - Run server with command "python3 chatServerDuplex.py"
 - Connect a new client with command "python3 chatClientDuplex.py"
 - You can connect multiple clients and begin messaging.
