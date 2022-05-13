+++
title = "Verify my Digital Signature"
aliases = ["verify", "signed-message", "check"]
  name = "Sandipan"
+++

If you receive a digitally signed message from me, or from someone who claims to be me, this page will guide you to check whether the signature is valid or not.

Need to send me an encrypted message instead? visit the [Encrypt Page](../encrypt/).

## Sample Message:

The following is how a digitally signed message looks like. You can use it to test the signature verification systems described below.


```
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA512

hello, I am Sandipan Roy, trust whatever I say in this message
only if this signature is either valid and generated with my key.

also make sure this message was originally intended for you
and it has not been re-used on a different context to fool you.

consider my signatures valid only if applied on messages
containing explicit reference to their context to prevent
signature-reuse of short and generic messages.

this specific message is a sample that i made for my personal website
and, unless i change it, you should find the original content here
https://bytehackr.tech/verify

every other use of this message should be considered invalid and suspicious.



-----BEGIN PGP SIGNATURE-----

iQIzBAEBCgAdFiEE6ZZh22aD6jBXBO06S1x0cAUbszIFAmJ9+60ACgkQS1x0cAUb
szLolA//YXMb0DrG9PhxUfV6qrv64tCmhE4DWrK9HppA4vdaRhQUcTttMDkDxL5q
8qpF3C7qiIzDIwEZVyfZ+oMuLvF5v0FURcZDv9JlXySqK64K9gKm+6GNld17nUVs
9ijwW4Sa1rvalQtLg1VJhcC2eZCNyqn/nfnTfY/x2SZytndeZklrFQec41fpg/zs
VkxNuqoa8P8fXLi6gj2f1QyV+8DgNZel3IJJoPUfpYhBoXHyyY9gH97lfg0G5A7T
fu12mCBz6QniQa4wZElTFCRsmF9wsfuJuiWURqMbilhnQSvt09+G8gB4u1lwjPSX
6odx781G56ckkK0XTcxdYQ4WHcMmpttVHix8+eA3JIPLUn1vz5k8XO0n62qIK2I5
MF7Ke3hS53gDjuNEFjb3s+XpvUJBDnubPcNlQFbYofRKcfqQtAuSBWI5KJZjwkEU
5e/ecDBsaWWj0ZafYTExN2eFcMHmKwGWCoq+wxlabBRVpI/rENK5NED4m/hnlFFr
smbzyjGa2ZxhmjQuxa8u0cIwahyuWBDLHkqIRQ7UCi3H+mZfK7JpKa72FnBbZ/M3
im7NFzjmNJTGsxMX3eTzzoZE5M74PuikPylzq6ReJlTu99mbfEKtJbxa+GL0XPhN
rAkTwSCNmeWEe4iXEqzUhniy8BZ3qLSL6D49qRnKU6oRgUn/8hs=
=zZx6
-----END PGP SIGNATURE-----

```

# Method 1: Keybase
Keybase is the easiest platform to make cryptography accessible to everyone.
With keybase you can encrypt and decrypt messages using open protocols.

You can use the keybase website to check whether my digital signature is valid or not.

DOWNSIDES (for those who care): The website is hosted on Amazon AWS and the backend is not open source.

![Keybase encryption](../img/keybase-signature.jpg)

[Open Keybase verification page](https://keybase.io/verify#bytehackr)


# Method 2: GPG
GNU Privacy Guard is the most advanced secure communication and signature software available, and uses the PGP standard, which is what i personally trust the most.

DOWNSIDES: It is very hard to use if your are not a techie

![GPG encryption](../img/gpg-signature.jpg)

STEPS

1. Get my GPG public key from [https://keybase.io/bytehackr/pgp_keys.asc](https://keybase.io/bytehackr/pgp_keys.asc)
2. Install the [official GPG client](https://gnupg.org/), or [another PGP client](https://www.openpgp.org/software/)
3. Import my key
4. Verify if the signature on my messages is valid
