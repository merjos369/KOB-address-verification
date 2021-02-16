## KOB Address Verification Service

## Abstract

 A user uses this service to get a digital domicile credential which proves
their domicile. It is useful in a situation when the user has to prove his/her domicile for
some needs.
 A domicile credential is a proven claim that a particular person reside in a specific area, issued by an authority.The domicile credential, driving license and similar documents are currently printed on paper known as paper credentials stored in users' wallets.
 By bringing the concept of digital verifiable credentials to picture, paper credentials are replaced by digital certificates which are stored in digital wallets which is an android application which act as a data store on cloud.
## Dependent Projects

## Motivation

- This project, a part of Kochi Orgbook, is specifically meant for digitizing the process of verifying and issuing the domicile credentials. Domicile credntials are require when a person applies for an admission, job, education scholarships etc.
Below are some of the problems with the current situation of issuing and verifying the (paper) credentials:

1. Centralised Identifiers (A central authority issues the paper credentials, control the credentials and have the right to revoke them): 
- Can revoke documents at any time or an attack can destroy all data.
2. Ease to forge: 
- A digitally signed certificate is downloaded and obtained as a printout, which is very easy to forge.
3. Issue and verification solely depend on the experience and expertise of issuer 
(Ration card, address proof and identity proof are the documents to be cross checked) and the process is time consuming (Average time required is 2-3 days).
4. Inaccessibility issues.

## Status of the project:
Incubation

## Solution

- : DID gives power back to individuals and a documents on Blockchain cannot be deleted.
- : Digital credentials which are protected cryptographically. 
- : Digital credentials are proven by using crypto calculations and saves time.
- : Globally accessible verifiable credentials.

## Contributors:

Merlin Joseph(https://github.com/merjos369)


## Testing the project

## References

- https://kerala.gov.in/documents/10180/a3d88f49-3786-47f1-8b37-5b198b8bebaf
- https://edistrict.kerala.gov.in/openSearch.do?openStat=openSearch
- https://www.edx.org/professional-certificate/linuxfoundationx-developing-blockchain-based-identity-applications
- https://www.orgbook.gov.bc.ca/en/home
- 

## Key Terms
The four major attributes of any credential are:
1. Issuer(Local Governing Body)
2. If the person producing the credentials is the person to whom the credential was issued to.
3. If claims are tampered(If wrong address is given).
4. If credential has been revoked?

Here digital verifiable credentials are those which are cryptographically constructed and  proves the above attributes.

DID : Decentralized Identifiers are created by owners, independent of any central authority.
- Almost similar to a URL.
- DID is passed to a software called DID Resolver which in turn returns the credential, which is a JSON document which is globally unique.
