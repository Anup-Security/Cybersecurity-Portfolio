# Ports and Protocols

## HTTP

Purpose: Transmit web content between a client and a server.

Port: 80, protocol: TCP

Business Use: Public websites, Internet or intranet portals.

Security Risks:
    1. Lack of data encryption can expose sensitive information when passed in plaintext.
    2. No secure connection can invite Man in the middle attack, session hijacking.
    3. Data integrity issues as it has no way to know if sent data was altered in middle.
    4. Compliance issue as transfer of many sensitive informations like banking details need to adhere to PCI SSC (payment card industry security stantard council), ISO frameworks.

Common Controls:
    1. Redirecting HTTP traffic to HTTPS.
    2. In cases of legacy web applications, isolate the network by either cutting off communication from public internet or proper access control through firewalls.
    3. Administrative control can document use of insecure protocol and allowed exceptions for its use.


## HTTPS

Purpose: Transmission of web content between a client and a server securely over an encrypted channel.

Port: 443, protocols: TCP on a TLS

Business Use: public facing website, web application portals, ecommerce, e banking, etc

Security Risks:
    1. Even though the connection is secure it does not mean it safeguards from vulnerabilities in applications which can create false sense of trust.
    2. Expired TLS certificates can increase downtimes and create mistrust with users.
    3. Use of older version of TLS can have weaker configurations.
    4. Encryption may affecet security monitoring tools due to low visibility

Common Controls:
    1. Regular monitoring of certificates and Auto renewal of TLS certificates.
    2. Establishment of strong cryptographic standards.
    3. Use of trusted Certificate Authorities(CA) and not self signed certificates.


## DNS

Purpose:
Port:
Business Use:
Security Risks:
Common Controls:

## SSH

Purpose:
Port:
Business Use:
Security Risks:
Common Controls:

## RDP

Purpose:
Port:
Business Use:
Security Risks:
Common Controls: