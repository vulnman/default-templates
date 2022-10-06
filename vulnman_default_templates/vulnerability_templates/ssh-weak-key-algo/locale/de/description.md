Der SSH-Server verwendet einen Host-Schlüssel, der als schwach angesehen wird.

Seit *OpenSSH 8.8* wird das weit verbreitete `ssh-rsa` Signaturschema deaktiviert.
Dieses Schema verwendet *SHA-1* und ist empfindlich gegenüber chosen-prefix-Angriffen.