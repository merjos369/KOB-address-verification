## KOB Address Verification Service

## Abstract

 A user uses this service to get a digital domicile credential which proves
their domicile. It is useful in a situation when the user has to prove his/her domicile for
some needs. A domicile credential is a proven claim that a particular person reside in a specific area, issued by an authority.The domicile credential, driving license and similar documents are currently printed on paper known as paper credentials stored in users' wallets. By bringing the concept of digital verifiable credentials to picture, paper credentials are replaced by digital certificates which are stored in digital wallets which is an android application which act as a data store on cloud.

## Dependent Projects

## Motivation

- This project, a part of Kochi Orgbook, is specifically meant for digitizing the process of verifying and issuing the domicile credentials. Domicile credntials are require when a person applies for an admission, job, education scholarships etc.
Below are some of the problems with the current situation of issuing and verifying the (paper) credentials:

1. Centralised Identifiers (A central authority issues the paper credentials, control the credentials and have the right to revoke them): 
- Can revoke documents at any time or an attack can destroy all data.
2. Ease to forge: 
- A digitally signed certificate is downloaded and obtained as a printout, which is very easy to forge.
3. Issue and verification solely depend on the experience and expertise of issuer.
- (Ration card, address proof and identity proof are the documents to be cross checked) and the process is time consuming (Average time required is 2-3 days).
4. Inaccessibility issues.

## Status of the project:

Incubation

## Solution

- The Verifiable Credentials are not dependent on centralized authority; instead it is a decentralized one. i.e. none of the credentials are created by the central authority. 
So these authorities will never have the right to revoke the credentials as and when required, say in a situation where the government is trying to suppress its people. This is due to a impeccable feature of blockchain i.e. data, once sent to a blockchain network, cannot be deleted or removed from all the systems, it can only be updated. Thus DIDs give power back to individuals. 
- Another problem with centralized identifiers is also solved by DIDs i.e. if the centralized authority is having a problem, say an attack, it lets the whole system down. But with DIDs, many copies of the given server will be available across the world. Thus making data globally accessible.
(Simply explaining, DID is something similar to a URL, which is passed to a software called DID resolver, returns a DIDDoc, which is a JSON document, globally unique).
- Verifiable credentials are cryptographically constructed and proves the four major attributes of any credential, which are
  1. Issuer (Local Governing Body in case of a domicile credential).
  2. If the person producing the credentials is the person to whom the credential was issued to.
  3. If claims are tampered (If wrong address is given as the address to prove the domicile).
  4. If credential has been revoked by the authority?
  These do not depend upon a person's expertise who issues the credential, instead they are cryptographically protected using algorithms which aren't easy to forge. It is 
  mandatory to perform cryptocalculations to prove the attributes. Considerable amount of time can be saved when personal investigation is replaced by legitimate documents.
 
## Contributors:

Merlin Joseph(https://github.com/merjos369)

## Testing the project

## References

- https://kerala.gov.in/documents/10180/a3d88f49-3786-47f1-8b37-5b198b8bebaf
- https://edistrict.kerala.gov.in/openSearch.do?openStat=openSearch
- https://www.edx.org/professional-certificate/linuxfoundationx-developing-blockchain-based-identity-applications
- https://www.orgbook.gov.bc.ca/en/home 
