# 2025-04-21 Notice of New Personal Key Certificate

In early April of 2025, there was a catastrophic loss of the air-gapped system and all its backups which I was using to manage the generation and editing of my personal OpenPGP-compliant ("PGP") key-certificate.  Note that this was not a security compromise, but rather accidental destruction of systems and data.  Unfortunately, this has made it impossible for me to update or revoke the key-certificate that I have been using up until this point.

I've therefore gone ahead and created a completely new PGP key-certificate (along with its constituent subkeys) for myself.  At the time of writing, this newly-issued key-certificate's info is the following:

```
pub   rsa4096/0xB610F59B30E506F0 2025-04-18 [C] [expires: 2027-04-18]
      Key fingerprint = DC30 10BF 60E9 9F4F 1900  D558 B610 F59B 30E5 06F0
uid   Ross Blair | Personal ID (Ross Blair's authoritative OpenPGP standard [PGP] key-certificate.  Intended for uses relating to Ross Blair's direct personal and professional work.  Note that Ross's work done on behalf of other companies, organizations, or third party legal entities may not be signed with this key-certificate.) <no_reply.rb.pgp_key_certs@mailbox.org>
sub   rsa4096/0x43AD2A88B488F8FF 2025-04-18 [S] [expires: 2027-04-18]
      Key fingerprint = D23C 8278 C88F 748E 0C80  C444 43AD 2A88 B488 F8FF
sub   rsa4096/0xFD042E11DF1AD7EF 2025-04-18 [E] [expires: 2027-04-18]
      Key fingerprint = B268 672C A8BB 3F86 06CE  CC3F FD04 2E11 DF1A D7EF
sub   rsa4096/0x2D9AAD4BCB3AE4D5 2025-04-18 [A] [expires: 2027-04-18]
      Key fingerprint = E577 1AF8 535D 291F 6F4D  F424 2D9A AD4B CB3A E4D5
```

You can reference the old archived key-certificate's public key data in the file "Archived_IKC--2C19753DB7975FDF_public_key_cert_data.asc", and you reference the newly issued key-certificate's public key data in the file "Newly_Issued_IKC--B610F59B30E506F0_public_key_cert_data.asc".  Both files are available in the same directory as this notice.

As of today, my GitHub profile and API endpoint will be updated with the newly issued key-certificate and its various key-pairs, and the new key certificate will be posted on my X \(formerly Twitter\) account: `@rb_27059241`.


---
> -- Ross Blair
> 
> © 2025 [Ross Blair](https://github.com/ross-blair-27059241).
> 
> To verify the authenticity of this document with this written signature here, please first refer to the following three peices of information:
>
>   1. The document file which you are reading at this very moment, referred to in this context as the "source file".
>   2. The GPG-public-key-detached-signature-file corresponding to the source file, often referred to as the "signature file".  The signature file bares the same name as its source file plus a ".sig" suffix.  The signature file can be located in the same directory as this source file.
>   3. The OpenPGP standard \(PGP\) key-certificate belonging to the source file's author: [Ross Blair](https://github.com/ross-blair-27059241).  The PGP key-certificate's certifying-primary-key-pair's public-key bares the PGP fingerprint `DC30 10BF 60E9 9F4F 1900  D558 B610 F59B 30E5 06F0`.  Available via Github API [here](https://api.github.com/users/ross-blair-27059241/gpg_keys) or direct download [here](https://github.com/ross-blair-27059241/ross-blair-27059241).
>
> To doubly verify the authenticity of this PGP key-certificate you've just retrieved \(mentioned above in step 3\), check that the PGP fingerprint of that key-certificate's certifying-primary-key-pair's public-key is the same as that fingerprint specified in the account profile of Ross Blair's X \(formerly Twitter\) account: `@rb_27059241`.
>
> With these peices of data/information, and the authenticity of the PGP public key-certificate confirmed, you can move on to the final step of truly verifying this signed document. Download and install the application [GnuPG](https://gnupg.org/index.html) - or a derivative program like [GPGTools](https://gpgtools.org). Then use this program to to verify that this file was indeed signed by the holder of the PGP private key corresponding to Ross Blair's PGP public key.  There are two technical steps to this process:
>   1. Import Ross Blair's PGP public key-certificate to your GPG program's keystore.  Run this \(or some very similar\) CLI command: `gpg --import [public-key-file]`.
>   2. Finally, verify Ross Blair's signature on this document. Run this \(or some very similar\) CLI command: `gpg --verify [signature-file-name] [source-file-name]`.
>
> The resulting message from the GPG program on your command line should confirm that the signature is valid, and that this signed document is authentic.
> 