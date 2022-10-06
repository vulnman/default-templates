To send encrypted data between clients and servers, TLS brakes the input data into fixed-length chunks, called blocks.
Each block is encrypted separately according to a mode of operation.

An attack, called SWEET32, has been found against ciphers that use 64-bit encryption blocks.

The attack is feasible, but not very practical because it requires gathering a very large amount of traffic, and the attacker needs to listen the HTTPS traffic between the victim and the server.

For more information about this vulnerability read CVE-2016-2183.