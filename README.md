# tcpdf-pdf-signing-example
A self-contained example of basic PDF signing using TCPDF

# PEM generation
- `http://dss.nowina.lu/pki-factory/keystore/good-user-crl-ocsp.p12`
- `openssl pkcs12 -info -in good-user-crl-ocsp.p12 -nokeys -legacy > chain.pem`
- `openssl pkcs12 -info -in good-user-crl-ocsp.p12 -nodes -nocerts --legacy > key.pem`
