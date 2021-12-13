# List of all dns types
#####################
A \n
AAAA \n
AFSDB \n
APL
CAA
CDNSKEY
CDS
CERT
CNAME
CSYNC
DHCID
DLV
DNAME
DNSKEY
DS
EUI48
EUI64
HINFO
HIP
HTTPS
IPSECKEY
KEY
KX
LOC
MX
NAPTR
NS
NSEC
NSEC3
NSEC3PARAM
OPENPGPKEY
PTR
RRSIG
RP
SIG
SMIMEA
SOA
SRV
SSHFP
SVCB
TA
TKEY
TLSA
TSIG
TXTURI
ZONEMD

# Command line to get all info
for i in $(cat dns_type_list.txt);do; host -t $i domain.com.br; done
