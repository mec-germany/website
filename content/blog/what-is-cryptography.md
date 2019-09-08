+++
author = "Alang"
categories = ["Security"]
tags = ["cryptography"]
date = "2018-11-25"
description = "What is cryptography?"
featured = ""
featuredalt = ""
featuredpath = ""
linktitle = ""
title = "Introduction to Cryptography"
type = "post"

+++

Cryptography is the algorithmic method of providing security of information.

| Cryptographic Goal         | Description                                                  | Algorithm                                                    |
| -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| privacy or confidentiality | keeping information secret from unauthorized parties to see it | encryption and keys (AES, RSA/ECC)                           |
| integrity                  | guarding against improper information modification           | hash (SHA-2, SHA-3)                                          |
| authenticity               | the property of being genuine and being able to be verified  | digital signature and message authentication (CMAC, HMAC, ECDSA) |
| non-repudiation            | preventing the denial of previous commitments                | digital signature (ECDSA)                                    |



##### History of modern cryptography

`1976`
:    Diffie and Hellman published concept public-key cryptography and provided an ingenious method for key exchange based on the intractability of the discrete logarithm problem

`1977`
:    DES adopted as a US FIPS for encrypting unclassified information

`1978`
:    Rivest, Shamir, and Adleman discovered the first practical public-key encryption and signature scheme (now referred as RSA) based on the intractability of factoring large integers

`1985`
:    another practical public-key schemes was found by ElGamal

`1991`
:    1st international standard for digital signatures based on RSA public-key scheme was adopted

`1994`
:    US gov. adopted Digital Signature Standard based on ElGamal public-key scheme
