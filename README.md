# Rebooting the Web of Trust X: Buenos Aires (March 2020) [CANCELLED]

This repository contains documents related to RWOT10, the tenth
Rebooting the Web of Trust design workshop, which will be held
in Buenos Aires, Argentina, from the evening of March 16th to the late afternoon of March 20th, 2020.

The goal of the workshop is to generate five technical white papers 
and/or proposals on topics decided by the group that would have the 
greatest impact on the future.

___RWOT10 has unfortunately been cancelled due to governmental and corporate concerns over the novel coronavirus (COVID-19). Please watch for announcement of RWOT11 this September; we are also considering whether to hold virtual events this March, during the RWOT10 dates.___

## Topics & Advance Readings

Though RWOT10 was cancelled, you can still find papers in our [Topics & Advance Readings directory](topics-and-advance-readings) on interesting subjects. Read them over, consider what people are concerned about right now in the field, and think about whether you'd like to advance these topics at RWOT11.

## Topical Listing of Topcs & Advance Readings

### Authorization and Delegation

[Delegated Authorization - The Alice to Bob Use Case](delegated-authorization.md)
  * by [Adrian Gropper](mailto:agropper@healthurl.com)
  * "Identity, identifiers and credentials are not an end in themselves. They are essential ingredients, among others, for practical transactions involving multiple parties. Decentralization challenges transaction protocols that support self-sovereignty for individuals in highly asymmetric relationships with institutions. The Alice to Bob Use Case merges the SSI and open authorization domains to speed adoption of emerging standards while also promoting decentralization."
  * #did #web #outreach #authorization #storage

### Communication

[An RWOT Animation Project](decentralized_animation_creative_brief.md)
  * by [Erica Connell](http://wonderlandstageandscreen.com) and [Joe Andrieu](https://joeandrieu.com)
  * A creative brief for a proposed 1 minute animation on decentralized identity
  * #creative #communications #outreach
  
### Compliance

[Credential Types for Compliance](credential_types_for_compliance.md)
  * by [Rieks Joosten](mailto:rieks.joosten@tno.nl)
  * Creating what one might call an SSI infrastructure is one thing, actually using it is quite another. A prerequisite for using it is a positive business case, and for may, also (provable) compliance with applicable laws, regulations and policies. This paper aims to come to grips with this compliance aspect. 
  * While the contents and structure are intentionally left open, an illustration is given of how this might work, using the [Mya use-cases](https://drive.google.com/file/d/10sfYKp6Ohi_rLsNqb1GBrhuE0IuoBX2k/view) of the [whitepaper](https://sovrin.org/wp-content/uploads/Guardianship-Whitepaper.pdf) on guardianship of the [Sovrin Guardianship Task Force](https://docs.google.com/document/d/1ymWzCwu2Ud6FMGZdU8md03KCvaxmT41-gQYIRXo09Xw/edit#heading=h.8oej31ec0two). It also gives a basis for discussing/developing credential types for compliance-related purposes, such as for guardianship, mandates and delegation.
  * #compliance #jurisdiction #guardianship #mandates #delegation 

### Confidential Computing

[TEE & e As Privacy Proofs](tee-privacy-vc.md)
  * by Tarek El-Gillani ([tarek@cloudmask.com](mailto:tarek@cloudmask.com))
  * "Using VCs and Trusted Execution Environment, Applications developers/providers can demonstrate to end-users that they indeed restrict access to their private data for the agreed-upon purpose and time duration."
  * #tee #vc #privacy
  
### DID

[DID and the Web](DID_and_the_Web.md)
  * by [Ivan Herman](https://www.w3.org/People/Ivan/)
  * "The DID (and VC) Use Cases documents have a number of interesting use cases, from health care application to university credentials, or from corporate tax issues to travel documents. There is, however, comparatively little about what the use cases and requirements are on the relationship of DIDs (and VC's) _and the Web_."
  * #did #web #semanticweb #outreach

[Why Matrix Parameters?](why-matrix-parameters.md)
  * by [Markus Sabadello](https://danubetech.com/)
  * "Matrix parameters are a syntax component of DID URLs that make it possible to include parameters for the DID resolution process in a DID URL. This topic paper discussed why the community introduced matrix parameters in DID URL syntax, and how their use is different from the more familiar query parameters."
  * #did #url #matrixparameters

[Interplanetary Linked Data (IPLD) using CBOR and COSE-signed payloads ](ipld-cbor.md)
  * by [jonnycrunch](https://github.com/jonnycrunch)
  * "In this paper, I aim to discuss Concise Binary Object Representation (CBOR), which is the native data format used when storing IPLD objects and why it is a superior document syntax for representing DID documents.  In making my case, I will also explain how content addressing through hash-based linking is a better approach as compared to [JSON-LD]((https://www.w3.org/TR/json-ld/)) and how to cryptographically sign a CBOR data in IPLD using COSE."
  * #did #ipld #cbor #cose

[Quantum Secure DIDs](QuantumSecureDIDs.md)
  * by [Carsten Stöcer](https://spherity.com)
  * "To address the risk of the advent of quantum computers for decentralized identity solutions, we propose to introduce a simple method using one-time signing keys and key rotation to protect our digital identity while using existing cryptographic ciphers for signing and hashing. Sam Smith's KERI is a potential candidate for implementing the proposed method. This approach shall allow us already today to prepare for the age of quantum attacks on our identity infrastructure."
  * #did #KERI #KERL #Quantum #Computing #KeyRotation

### Ecosystem Development

[Bearing Witness](bearing-witness.md)
  * by [Eric Welton](mailto:eric@korsimoro.com)
  * "How does verifying a pre-existing credential differ from primary
  issuance.  How can the act of __bearing witness__ to a credential become part of the
  digital ecology - or does it have no place at all?"
  * #ssi-lite

[Building a Self-Issued OpenID Connect Provider](building-a-self-issued-openid-connect-provider.md)
  * by [Peter Saxton](mailto:peterhsaxton@gmail.com)
  * What is the smallest step towards adopting a system of decentralized credentials?
  Can we build a compelling Self-Issued OpenID Connect Provider today.
  * #authentication #web #oidc

[Digital Wallets: Interoperability support for multiple data hubs, data services and portability](digital-wallets-interoperability-support-for-multiple-data-hubs-data-services-and-portability.md)
  * by [Ron Kreutzer](mailto:ron@pillarproject.io)
  * Multiple data hubs/vaults/lockers will likely exist in a user's identity ecosystem, and digital wallets must be able to interact with a variety of storage providers as well as data services that act upon this data. A set of standards or operating principles need to exist to allow interoperability as well as portability that allow a user to swap digital wallet providers.
  * #digitalwallet #datavault

[Mapping Adequacies](mapping-adequacies.md)
  * by [Juan Caballero]("mailto:caballerojuan_AT_pm.me")
  * A set of heuristics that could help documentation of best-practices and not-best-practices be widely understood by technical and non-technical readers with a wide range of levels of experience and agendas.
  * #documentation #compliance #ssi-lite #bestpractices

### Encrypted Data Vault

[An Encrypted Data Vault Sprint](edv-sprint.md)
  * by [Manu Sporny](https://www.linkedin.com/in/manusporny/)
  * "A list of suggestions on work that could be completed at RWOT10 to move the Encrypted Data Vault specification forward."
  * #ssi #storage #edv

### Registries and Interoperability

[Using Registries to Facilitate Interoperability](Using_Registries_to_Facilitate_Interoperability.md)
  * by [Michael B. Jones](mailto:mbj@microsoft.com)
  * This topic paper will explore how and why registries are used in practice to facilitate interoperability among software systems implementing a standard.
  * #registries #interoperability #extensibility #experiences #lessons

### Use Cases

[Sharing Personal Health Data to Improve Treatment of Chronic Conditions](use_case_sharing_personal_health_data_to_improve_treatment_of_chronic_conditions.md)
  * by [Benay Dara-Abrams](mailto:benay@dara-abrams.com)
  * "Believing that no single app or device provides all the information for an individual's health story, Open mHealth is focused on making patient-generated data from disparate sources accessible, developing the IEEE P1752 Standard for Mobile Health Data to harmonize and help make sense of digital health data. I would like to work with others to develop scenarios demonstrating how decentralized digital identity can help in protecting Personally Identifiable Information (PII), Personal Information (PI), and Protected Health 
Information (PHI) while facilitating sharing of personal health data to improve monitoring and treatment of chronic conditions."
  * #use-case #open-mhealth #did #ieee-p1752

### Verifiable Claims
[Verifiable Claims for Postal Addresses: A Use Case for Decentralized Postal Services using DIDs, VCs and Blockchains](https://github.com/WebOfTrustInfo/rwot10-buenosaires/blob/master/topics-and-advance-readings/vc-postal-addresses.md)
  * by Moses MA
  * We propose to facilitate the collaborative drafting of a technical paper that describes the principles and key design considerations for verifiable “physical address” claims. The global postal network now seeks to understand the “decentralization revolution” and help to develop game-changing, blockchain-powered new business models for the world. We believe that, in turn, the active endorsement, support and participation of the global postal industry could provide a tipping point for adoption of DIDs and VCs. This is a first step toward that desired future.
  * #did #vc #physical-address
  
## Alphabetical Listing of Topics & Advance Readings

* [An Encrypted Data Vault Sprint](edv-sprint.md)
* [An RWOT Animation Project](decentralized_animation_creative_brief.md)
* [Bearing Witness](bearing-witness.md)
* [Building a Self-Issued OpenID Connect Provider](building-a-self-issued-openid-connect-provider.md)
* [Credential Types for Compliance](credential_types_for_compliance.md)
* [Delegated Authorization - The Alice to Bob Use Case](delegated-authorization.md)
* [Digital Wallets: Interoperability support for multiple data hubs, data services and portability](digital-wallets-interoperability-support-for-multiple-data-hubs-data-services-and-portability.md)
* [DID and the Web](DID_and_the_Web.md)
* [Interplanetary Linked Data (IPLD) using CBOR and COSE-signed payloads ](ipld-cbor.md)
* [Mapping Adequacies](mapping-adequacies.md)
* [Quantum Secure DIDs](QuantumSecureDIDs.md)
* [An RWOT Animation Project](decentralized_animation_creative_brief.md)
* [Sharing Personal Health Data to Improve Treatment of Chronic Conditions](use_case_sharing_personal_health_data_to_improve_treatment_of_chronic_conditions.md)
* [TEE & VC As Privacy Proofs](tee-privacy-vc.md)
* [Using Registries to Facilitate Interoperability](Using_Registries_to_Facilitate_Interoperability.md)
* [Verifiable Claims for Postal Addresses: A Use Case for Decentralized Postal Services using DIDs, VCs and Blockchains](https://github.com/WebOfTrustInfo/rwot10-buenosaires/blob/master/topics-and-advance-readings/vc-postal-addresses.md)
* [Why Matrix Parameters?](why-matrix-parameters.md)


## Complete Rebooting the Web of Trust Listing

A different repository is available for each of the Rebooting the Web of Trust design workshops:

* [Rebooting the Web of Trust X: Buenos Aires (March 2020)](https://github.com/WebOfTrustInfo/rwot10-buenosaires)
* [Rebooting the Web of Trust IX: Prague (September 2019)](https://github.com/WebOfTrustInfo/rwot9-prague)
* [Rebooting the Web of Trust VIII: Barcelona (March 2019)](https://github.com/WebOfTrustInfo/rwot8-barcelona)
* [Rebooting the Web of Trust VII: Toronto (September 2018)](https://github.com/WebOfTrustInfo/rwot7-fall2018)
* [Rebooting the Web of Trust VI: Santa Barbara (March 2018)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2018)
* [Rebooting the Web of Trust V: Boston (October 2017)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017)
* [Rebooting the Web of Trust IV: Paris (April 2017)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2017)
* [Rebooting the Web of Trust III: San Francisco (October 2016)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2016)
* [Rebooting the Web of Trust II: ID2020 (May 2016)](https://github.com/WebOfTrustInfo/ID2020DesignWorkshop)
* [Rebooting the Web of Trust I: San Francisco (November 2015)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust)

## License

All of the contents of this directory are licensed [Creative Commons CC-BY](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust/blob/master/final-documents/LICENSE-CC-BY-4.0.md) their contributors.
