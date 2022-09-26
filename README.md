# LPIC-3 Security Guide Study Certification Exam 303-300

LPIC-3 Exam 303: Security

Exam Objectives Version: 3.0

Exam Code: 303-300

About Objective Weights: Each objective is assigned a weighting value. The weights indicate the relative importance of each objective on the exam. Objectives with higher weights will be covered in the exam with more questions.

---

# Topic 331: Cryptography

## 331.1 X.509 Certificates and Public Key Infrastructures (weight: 5)

**Weight**	5

**Description**	Candidates should understand X.509 certificates and public key infrastructures. They should know how to configure and use OpenSSL to implement certification authorities and issue SSL certificates for various purposes.

### Key Knowledge Areas:

- Understand X.509 certificates, X.509 certificate lifecycle, X.509 certificate fields and X.509v3 certificate extensions
- Understand trust chains and public key infrastructures, including certificate transparency
- Generate and manage public and private keys
- Create, operate and secure a certification authority
- Request, sign and manage server and client certificates
- Revoke certificates and certification authorities
- Basic feature knowledge of Let's Encrypt, ACME and certbot
- Basic feature knowledge of CFSSL


#### Understand X.509 certificates

Understand X.509 certificates, X.509 certificate lifecycle, X.509 certificate fields and X.509v3 certificate extensions.


#### Understand trust chains and public key infrastructures

Understand trust chains and public key infrastructures, including certificate transparency.


#### Generate and manage public and private keys

Generate and manage public and private keys


#### Create, operate and secure a certification authority

Create, operate and secure a certification authority


#### Request, sign and manage server and client certificates

Request, sign and manage server and client certificates


#### Revoke certificates and certification authorities

Revoke certificates and certification authorities


#### Basic feature knowledge of Let's Encrypt, ACME and certbot

Basic feature knowledge of Let's Encrypt, ACME and certbot


#### Basic feature knowledge of CFSSL

Basic feature knowledge of CFSSL


### Partial list of the used files, terms and utilities:

- openssl (including relevant subcommands)
- OpenSSL configuration
- PEM, DER, PKCS
- CSR
- CRL
- OCSP


#### openssl (including relevant subcommands)

```bash

```

#### OpenSSL configuration

#### PEM, DER, PKCS

PEM

DER

PKCS

#### CSR

#### CRL

#### OCSP


---

## 331.2 X.509 Certificates for Encryption, Signing and Authentication (weight: 4)

### Weight	4

### Description

Candidates should be able to use X.509 certificates for both server and client authentication. This includes implementing user and server authentication for Apache HTTPD. The version of Apache HTTPD covered is 2.4 or higher.


### Key Knowledge Areas:

#### Understand SSL, TLS, including protocol versions and ciphers

Understand SSL, TLS, including protocol versions and ciphers

#### Configure Apache HTTPD with mod_ssl to provide HTTPS service, including SNI and HSTS

Configure Apache HTTPD with mod_ssl to provide HTTPS service, including SNI and HSTS

#### Configure Apache HTTPD with mod_ssl to serve certificate chains 

Configure Apache HTTPD with mod_ssl to serve certificate chains and adjust the cipher configuration (no cipher-specific knowledge)

#### Configure Apache HTTPD with mod_ssl to authenticate users using certificates

Configure Apache HTTPD with mod_ssl to authenticate users using certificates

#### Configure Apache HTTPD with mod_ssl to provide OCSP stapling

Configure Apache HTTPD with mod_ssl to provide OCSP stapling

#### Use OpenSSL for SSL/TLS client and server tests
Use OpenSSL for SSL/TLS client and server tests


### Partial list of the used files, terms and utilities:

- httpd.conf
- mod_ssl
- openssl (including relevant subcommands)


#### httpd.conf

httpd.conf

#### mod_ssl

mod_ssl

#### openssl (including relevant subcommands)


```bash

```

---
