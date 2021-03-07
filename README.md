## KOB Address Verification Service
Version: _TBD_

## Abstract

 A user can make use of this service to get a digital domicile credential which is issued by a state government to prove that the person having the domicile certificate is a resident of that particular State or Union Territory. This project is a part of Kochi Orgbook which aims to enable any association having it's presence in the city of Kochi to register on the KOB VON Network to issue digital proofs and host a verifiable credential registry(VCR) in a transparent and cost efficient manner. KOB Address Verification Service is specifically meant for digitizing the process of verifying and issuing domicile credentials for users and these credentials will be stored in digital wallet which is an android application that can act as a data store on cloud. This credential can be used to avail various benefits such as education, job and other benefits (Resident Quotas in the Government Service and educational institutions, and also in case of jobs where local residents are preferred).


## Motivation

In the current system, a user who require a domicile credential has to apply online and upload documents like ration card, any document to prove address and any document to proof address. The heading officer at the village/muncipality checks for the genuinity of the uploaded documents and conducts a local search about the person who applied for the document(Genuinity is proven solely on the expertise and experience of the officer). When he/she finds that the claims are right, he/she issues a digitally signed domicile proof which can be downloaded and printed by the user. This process takes atleast 2 days to be completed. The biggest challenge with this system is that the credential provided is, at the end, a paper credential, which can be forged very easily. Another issue with the current system is that the domicile credential can be, at any time, revoked by the issuing authority.

KOB Address Verification Service aims to improve efficiency, reduce the time required, and enhance the genuinity of the process with the concept of Verifiable Credentials.

## Status of the project:

Incubation

## Solution 

Basically this project aims to build a network of verifiable credential issuers/verifiers and holders. These Verifiable Credentials are not dependent on centralized authority; instead it is a decentralized(DID) one-which are called SSI. SSI lets the users manage their verifiable credentials on their own. So the credentials cannot be revoked by the issuer without a solid reason.

In case of SSI, genuinity do not depend upon the issuer's expertise , instead they are cryptographically protected using algorithms which aren't easy to forge. It is mandatory to perform cryptocalculations to prove the genuinity attributes. Considerable amount of time can be saved when personal investigation is replaced by already proven legitimate documents.
  
Below is a demo of how verification can be performed:
Steps:
![Step 1](C:\Users\merjo\Desktop\step1.png "Step 1").


Thus the credential provided is verified and another credential is issued based on it which helps eliminate correlation.






 
## Contributors:

[Merlin Joseph](https://github.com/merjos369)

## Testing the project

TBD

## References

- https://kerala.gov.in/documents/10180/a3d88f49-3786-47f1-8b37-5b198b8bebaf
- https://edistrict.kerala.gov.in/openSearch.do?openStat=openSearch
- https://cleartax.in/s/domicile-certificate-vs-incorporation-certificate
- https://www.orgbook.gov.bc.ca/en/home 
