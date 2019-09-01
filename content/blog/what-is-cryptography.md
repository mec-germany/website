+++
author = "Alang"
categories = ["Security"]
tags = ["cryptography"]
date = "2018-11-25"
description = "what is cryptography?"
featured = ""
featuredalt = ""
featuredpath = ""
linktitle = ""
title = "Introduction to Cryptography"
type = "post"

+++

cryptography is the algorithmic method of providing security of information.

<u>history of modern cryptography</u>

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

<table>
  <tr>
    <th>cryptographic goal</th>
    <th>description</th>
    <th>cryptographic algorithm</th>
  </tr>
  <tr>
    <th>privacy or<br>confidentiality</th>
    <td>keeping information secret from unauthorized parties to see it</td>
    <td>encryption and keys (AES, RSA/ECC)</td>
  </tr>
  <tr>
    <th>integrity</th>
    <td>guarding against improper information modification</td>
    <td>hash (SHA-2, SHA-3)</td>
  </tr>
  <tr>
    <th>authenticity</th>
    <td>the property of being genuine and being able to be verified</td>
    <td>digital signature and message authentication (CMAC, HMAC, ECDSA)</td>
  </tr>
  <tr>
    <th>non-repudiation</th>
    <td>preventing the denial of previous commitments</td>
    <td>digital signature (ECDSA)</td>
  </tr>
</table>