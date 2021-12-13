# List of all dns types

A <br />
AAAA <br />
AFSDB <br />
APL <br />
CAA <br />
CDNSKEY <br />
CDS <br />
CERT <br />
CNAME <br />
CSYNC <br />
DHCID <br />
DLV <br />
DNAME <br />
DNSKEY <br />
DS <br />
EUI48 <br />
EUI64 <br />
HINFO <br />
HIP <br />
HTTPS <br />
IPSECKEY <br />
KEY <br />
KX <br />
LOC <br />
MX <br />
NAPTR <br />
NS <br />
NSEC <br />
NSEC3 <br />
NSEC3PARAM <br />
OPENPGPKEY <br />
PTR <br />
RRSIG <br />
RP <br />
SIG <br />
SMIMEA <br />
SOA <br />
SRV <br />
SSHFP <br />
SVCB <br />
TA <br />
TKEY <br />
TLSA <br />
TSIG <br />
TXTURI <br />
ZONEMD <br />

# Command line to get all info
for i in $(cat dns_type_list.txt);do; host -t $i domain.com.br; done
