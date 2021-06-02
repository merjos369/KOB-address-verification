
# KOB Address Verification Service

Version: TBD


## Dependent Projects

* KOBConnect

* KOBAW

* KOBVCR

* KOBPIU


## Abstract


A user can make use of this service to get a digital domicile credential which is issued by a state government to prove that the person having the domicile certificate is a resident of that particular State or Union Territory. This project is a part of Kochi Orgbook which aims to enable any association having it's presence in the city of Kochi to register on the KOB VON Network to issue digital proofs and host a verifiable credential registry(VCR) in a transparent and cost efficient manner. KOB Address Verification Service is specifically meant for digitizing the process of verifying and issuing domicile credentials for users and these credentials will be stored in digital wallet which is an android application that can act as a data store on cloud. This credential can be used to avail various benefits such as education, job and other benefits (Resident Quotas in the Government Service and educational institutions, and also in case of jobs where local residents are preferred).



## Motivation

In the current system, a user who require a domicile credential has to apply online and upload documents like ration card, any document to prove address and any document to proof address. The heading officer at the village/muncipality checks for the genuinity of the uploaded documents and conducts a local search about the person who applied for the document(Genuinity is proven solely on the expertise and experience of the officer). When he/she finds that the claims are right, he/she issues a digitally signed domicile proof which can be downloaded and printed by the user. This process takes atleast 2 days to be completed. The biggest challenge with this system is that the credential provided is, at the end, a paper credential, which can be forged very easily. Another issue with the current system is that the domicile credential can be, at any time, revoked by the issuing authority.


## Status of the project

Incubation


## Solution

KochiOrgBook is designed in such a way that the users and organizations can completely trust their
identity data stored in a decentralized manner. It ensures data privacy and security in an efficient and
cost effective manner. The subprojects of KOB are linked in such a way that an ecosystem is built
for helping the users to completely digitize the credential issual and verification system.
The basic plan for the address verification service is to allow the users input the address details and a
unique identification number, and provide them with a verifiable credential if the entered address is
right.
KOB Address Verification Service aims to improve efficiency, reduce the time required, and enhance
the genuinity of the process with the concept of Verifiable digital Credentials.

We are using the Blockchain technology in KOB so that the private data of users is most secure. So the service must be able to verify an address without actually viewing an address proof (like an aadhar card, ration card or voter id). This can be made possible by
acquiring the service of a third party digital service provider.

The KOB address verification service mainly consist of:

1. User Interface which allows the user or an organization to enter his/her address.

2. The page where the user/organisation is notified about the verification approval and a verifiable credential.

3. The gateway provided by a digital service provider which actually verifies the address of the
user/holder requesting it.

The third party agency can be any digital service provider who has the address details of the user
and is capable of verifying them upon request. It can be a gas agency, KSEB, or any similar service.
The proposed system does not require address proofs in any form, instead the address entered by the
user through the user interface is passed on to the agency for verification.
This can be easily compared to the payment gateway. Any payment made online is done through a
gateway. We are led to the webpage of the bank and it is there we make our payments. Similarly in
our application, the user's address is passed on to an address verifier(service provider). This
verification, the service provider performs, will be based on a government approved id proof, which
makes it completely reliable. For example, a cooking gas agency will have its users’ address details
stored in their database, after a proper verification of the aadhar card.
The presentation of proofs is done in a peer to peer manner. The address proof generated by the third
party agency is encrypted and saved as a DID document. This DID document is stored in the user’s
wallet or the association wallet. The user/association will be the only entity who can view the
credential.

<img src="whole.PNG" alt="KOB Address Verification System" />

Figure: KOB Address Verification System

The above picture depicts how the verification process takes place through the third party digital
service provider’s gateway.

Breaking down the steps involved in the overall process of credential issue and verification  below :

**Credential Issue:**

1. If a user needs an address proof, he/she establishes a connection with the issuer.

2. The issuer verifies and acknowledges the connection made. Now there is an ecosystem
between the user and the issuer for the smooth transfer of credentials.

3. After the connection is established, the user requests for an address credential(digital).

4. The issuer receives the request, and sees if the user is legitimate. For this, the issuer contacts
a third party digital service provider and passes on the address entered by the user when he
made the request.

5. The third party agency takes the address from the issuer and checks it in its database or
verifies against the government maintained database by the registered secure gateway between the government and the agency.

6. The agency acknowledges the verification by the means of a verifiable credential.

7. This verifiable credential is processed as a DID and is sent to the user as a verification
connection notification.

8. The user accepts this verification connection and it is stored in the wallet.

**Credential Verification**

When the user needs a service in which the user has to produce a proof of address, this service
provider becomes the verifier of the address proof.

9. The verifier sends a verification connection to the user via wallet.

10. User accepts the connection which means that the user gives consent to the verifier to verify
his/her address credential.

11. The verifier verifies the digital credential.


A very important feature considered here is that the service provider can only verify a user's address
if he/she permits them to do so.
When it comes to associations, address verification is done in the same way; the major difference is
the service provider and the documents considered by the service provider. The service provider
considered here will be associations like the National Restaurant Association of India and the
documents considered will be licenses issued for the associations, say a restaurant permit in the case
of a restaurant.
The verifiable credentials obtained after verification are stored in the user's wallet,
KOBConnect for individual users and in KOB Association Wallet in the case of associations. KOB
Association wallet also allows users to search for a particular association to see if they are genuine,
which means that the wallet will contain details of a pool of the verified associations. People can
search and see if an association is genuine.
The address verification service completely depends on the piggybacked digital service provider.
And it is very important that the digital service provider chosen should depend on a legitimate
database which should be genuine and is maintained by an authorised organization. In case of the
KOB, such a trusted database can be the UIDAI maintained CIDR(aadhaar) database. Other options
like the service to home organizations can be considered but they are either private and semi
government. 
We also need the third party agency to issue verifiable credentials as a DID which means that the
agency should be capable of supporting both the verification service and the issual of DID. 


## Usecase of KOB Address Verification Service

<img src="usecase (1).png" alt="KOB Address Verification System" />


## Contributors

[Merlin Joseph](https://github.com/merjos369)

## Testing the project

TBD


## References

[https://kerala.gov.in/documents/10180/a3d88f49-3786-47f1-8b37-5b198b8bebaf](https://kerala.gov.in/documents/10180/a3d88f49-3786-47f1-8b37-5b198b8bebaf)

[https://edistrict.kerala.gov.in/openSearch.do?openStat=openSearch](https://edistrict.kerala.gov.in/openSearch.do?openStat=openSearch)

[https://cleartax.in/s/domicile-certificate-vs-incorporation-certificate](https://cleartax.in/s/domicile-certificate-vs-incorporation-certificate)

[https://www.orgbook.gov.bc.ca/en/home](https://www.orgbook.gov.bc.ca/en/home)

[https://cdn2.vectorstock.com/i/1000x1000/30/91/cash-in-wallet-icon-on-white-background-vector-3473091.jpg](https://cdn2.vectorstock.com/i/1000x1000/30/91/cash-in-wallet-icon-on-white-background-vector-3473091.jpg)

[https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrtcPWfwKrr2qxOGx6yX0VgSK3QLK_5CqXdQ&usqp=CAU](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrtcPWfwKrr2qxOGx6yX0VgSK3QLK_5CqXdQ&usqp=CAU)

[https://t3.ftcdn.net/jpg/02/87/29/60/360_F_287296039_VJdiavV0cHEkoI4Aj3n3ggfXBVxpNwTj.jpg](https://t3.ftcdn.net/jpg/02/87/29/60/360_F_287296039_VJdiavV0cHEkoI4Aj3n3ggfXBVxpNwTj.jpg)
