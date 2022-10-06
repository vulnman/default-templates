The SSH server uses a host key that is considered weak.

Since *OpenSSH 8.8* the widely used `ssh-rsa` signature scheme will be disabled.
This scheme is using *SHA-1* and is sensible to chosen-prefix attacks.