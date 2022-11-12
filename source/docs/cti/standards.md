# Standards & Frameworks

Standards and frameworks provide structures to rationalise the distribution and use of threat intel across industries. 
They also allow for common terminology, which helps in collaboration and communication. 

## MITRE ATT&CK

The [MITRE ATT&CK framework](green-frameworks:docs/models/mitre) is a knowledge base of adversary behaviour, focusing on the indicators and tactics. Security 
analysts can use the information to be thorough while investigating and tracking adversarial behaviour.

## TAXII

The [Trusted Automated eXchange of Indicator Information (TAXII)](https://oasis-open.github.io/cti-documentation/taxii/intro) 
defines protocols for securely exchanging threat Intel to have near real-time detection, prevention and mitigation of 
threats. The protocol supports two sharing models:

* Collection: Threat intel is collected and hosted by a producer upon request by users using a request-response model.
* Channel: Threat intel is pushed to users from a central server through a publish-subscribe model.

## STIX

[Structured Threat Information Expression (STIX)](https://oasis-open.github.io/cti-documentation/stix/intro) is a 
language developed for the "specification, capture, characterisation and communication of standardised cyber threat 
information". It provides defined relationships between sets of threat info such as observables, indicators, adversary 
TTPs, attack campaigns, and more.

## Cyber kill chain

Developed by Lockheed Martin, the [Cyber kill chain](green-frameworks:docs/models/ckc) breaks down adversary actions 
into steps. This breakdown helps analysts and defenders identify which stage-specific activities occurred when 
investigating an attack.

## The Diamond Model

The [diamond model](green-frameworks:docs/models/diamond) looks at intrusion analysis and tracking attack groups over 
time. It focuses on four key areas, each representing a different point on the diamond.