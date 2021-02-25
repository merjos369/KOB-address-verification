## KOB Address Verification Service
Version: _TBD_

## Abstract

 A user uses this service to get a digital domicile credential which proves
their domicile. It is useful in a situation when the user or an organization has to prove his/her domicile for
some needs. A domicile credential is a proven claim that a particular person reside in a specific area, issued by an authority.The domicile credential, permits and licenses and similar documents are currently printed on paper known as paper credentials. By bringing the concept of digital verifiable credentials to picture, paper credentials are replaced by digital certificates which are stored in digital wallets which is an android application which act as a data store on cloud.


## Motivation

This project, a part of Kochi Orgbook, is specifically meant for digitizing the process of verifying and issuing the domicile credentials for Organizations. Domicile credntials are require when an organization requires a permit, license etc.
Below are some of the problems with the current situation of issuing and verifying the (paper) credentials:

1. Credentials stored at a  centralized repository.
2. Easy to forge: A digitally signed certificate is downloaded and obtained as a printout, which is very easy to forge.
3. Issue and verification solely depend on the experience and expertise of issuer (Ration card, address proof and identity proof are the documents to be cross checked) and the process is time consuming (Average time required is 2-3 days).
4. Inaccessibility issues: Any failure at the central repository affects information retrieval.

## Status of the project:

Incubation

## Solution 

Basically the project aims to build a network of verifiable credential issuers/verifiers and holders. These Verifiable Credentials are not dependent on centralized authority; instead it is a decentralized(DID) one-which are called SSI. SSI lets the organizations manage their verifiable credentials on their own. Also, with SSI, there will be many more ways to prove integirty of the organization, other than just username and password.

Simply explaining, DID is something similar to a URL, which is passed to a software called DID resolver, returns a DIDDoc, which is a JSON document, globally unique.


Verifiable credentials are cryptographically constructed and proves the four major attributes of any credential, which are
  1. Issuer (Local Governing Body in case of a domicile credential).
  2. If the person producing the credentials is the person to whom the credential was issued to.
  3. If claims are tampered (If wrong address is given as the address to prove the domicile).
  4. If credential has been revoked by the authority?
  
  
  In case of SSI, these do not depend upon a issuer's expertise , instead they are cryptographically protected using algorithms which aren't easy to forge (or other verification mechanisms like email and phone number verification). It is mandatory to perform cryptocalculations to prove the attributes. Considerable amount of time can be saved when personal investigation is replaced by legitimate documents.
  
Below is a demo of how verification can be performed:
  
  
Steps:

1. Installing a wallet (android application) in mobile device and complete the setting up steps.
2. In a browser, give address to get a address verifiable credential.(?)
3. Once address is verified, issuing service issues address credential.

Thus the credential provided is verified and another credential is issued based on it-helps eliminate correlation.
  
  
  
 
## Contributors:

[Merlin Joseph](https://github.com/merjos369)

## Testing the project

TBD

## References

- https://kerala.gov.in/documents/10180/a3d88f49-3786-47f1-8b37-5b198b8bebaf
- https://edistrict.kerala.gov.in/openSearch.do?openStat=openSearch
- https://www.edx.org/professional-certificate/linuxfoundationx-developing-blockchain-based-identity-applications
- https://www.orgbook.gov.bc.ca/en/home 
