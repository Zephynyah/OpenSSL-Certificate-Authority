# OpenSSL Certificate Authority

This guide demonstrates how to act as your own certificate authority (CA) using the OpenSSL command-line tools. 
This is useful in a number of situations, such as issuing server certificates to secure an intranet website, 
or for issuing certificates to clients to allow them to authenticate to a server.


*   [Introduction](introduction.md)
*   [Create the root pair](create-the-root-pair.md)
    *   [Prepare the directory](create-the-root-pair.md#prepare-the-directory)  
    *   [Prepare the configuration file](create-the-root-pair.md#prepare-the-configuration-file)  
    *   [Create the root key](create-the-root-pair.md#create-the-root-key)  
    *   [Create the root certificate](create-the-root-pair.md#create-the-root-certificate)  
    *   [Verify the root certificate](create-the-root-pair.md#verify-the-root-certificate)  
* [Create the intermediate pair](create-the-intermediate-pair.md)  
    *   [Prepare the directory](create-the-intermediate-pair.md#prepare-the-directory)   
    *   [Create the intermediate key](create-the-intermediate-pair.md#create-the-intermediate-key)   
    *   [Create the intermediate certificate](create-the-intermediate-pair.md#create-the-intermediate-certificate)   
    *   [Verify the intermediate certificate](create-the-intermediate-pair.md#verify-the-intermediate-certificate)   
    *   [Create the certificate chain file](create-the-intermediate-pair.md#create-the-certificate-chain-file)   
* [Sign server and client certificates](sign-server-and-client-certificate.md)  
    *   [Create a key](sign-server-and-client-certificate.md#create-a-key)  
    *   [Create a certificate](sign-server-and-client-certificate.md#create-a-certificate)  
    *   [Verify the certificate](sign-server-and-client-certificate.md#verify-the-certificate)  
    *   [Deploy the certificate](sign-server-and-client-certificate.md#deploy-the-certificate)  
* [Certificate revocation lists](certificate-revocation-lists.md)  
    *   [Prepare the configuration file](certificate-revocation-lists.md#prepare-the-configuration-file)  
    *   [Create the CRL](certificate-revocation-lists.md#create-the-crl)  
    *   [Revoke a certificate](certificate-revocation-lists.md#revoke-a-certificate)  
    *   [Server-side use of the CRL](certificate-revocation-lists.md#server-side-use-of-the-crl)  
    *   [Client-side use of the CRL](certificate-revocation-lists.md#client-side-use-of-the-crl)  
* [Online Certificate Status Protocol](online-certificate-status-protocol.md)  
    *   [Prepare the configuration file](online-certificate-status-protocol.md#prepare-the-configuration-file)  
    *   [Create the OCSP pair](online-certificate-status-protocol.md#create-the-ocsp-pair)  
    *   [Revoke a certificate](online-certificate-status-protocol.md#revoke-a-certificate)  
* [Appendix](appendix/index.md)  
    *   [Root CA configuration file](appendix/root-configuration.md)  
    *   [Intermediate CA configuration file](appendix/intermediate-configuration.md)  

