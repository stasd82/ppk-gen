# ppk-gen
Private and public keys generator

To generate a private/public key PEM file:
> openssl genpkey -algorithm RSA -out private.pem -pkeyopt rsa_keygen_bits:2048
> openssl rsa -pubout -in private.pem -out public.pem