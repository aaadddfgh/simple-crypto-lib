# simple-crypto-lib
One simple lib for web security, protect your data in transmission from leaking.  
Addtionally, **this lib can not prevent a man in the middle attack**.
# concepts
this lib has 2 key concepts.
## 1. handshake
Before encrypting/decrypting data, you need to init the crypto lib. 
This process will exchange the rsa public keys of both communication parties and securely deliver the transmission key from the client to the server
## 2. encrypt/decrypt
After a successful handshake, you can encrypt and decrypt the data. For confidential data, you should encrypt it when transmitting it to the other party and decrypt it on the receiving party.
# useage
## init 
## encrypt/decrypt
