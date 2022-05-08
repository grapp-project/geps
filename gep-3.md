# GEP#3 : Security Considerations

__Author(s)__ : RSZ
__Start date__ : 13/09/2021
__Last Modification__ : 13/09/2021
__Type Key__ : S
__Status Key__ : A

----------------------

## Introduction

This document begins to explain how security is managed on Grapp librairies and softwares. This Docu;enqtion, in addition to the code source, must allow the end-users to evaluate if the software is corresponding to its security requirements.

## Transparency

As an open source software, this project is intented to be transparent, as much as possible, about his security management. Since open source software is in the public domain, (bad) hackers with malicious intent have easy access to the information. This should makes the software more vulnerable than software whose sources are totally opaque and which requires more effort and energy. However, no software is completely bulletproof and open source software shares the same practical risks as traditional software. Integrating security into the development process, both for the contributors and for end user's, is crucial to successful implementation and security management within the software.

The current recommendations and limitations of liability place the full responsibility on the end-user. The user must ensure to use the software in an appropriate context and that it uses the right methods. This approach, although it may seem appropriate to disclaim any liability to users, should not be seen as a directive to place the user in charge, because it is not an ethical nor an optimistic way of thinking about open software. The opening of the source code of the project is intended to test the project in terms of security, to openly discuss about its limits and its code. This is why he is strongly encouraged to contribute in this direction and to be active on the subject. We should, as a contributor or as end user's, participate in a common effort to make projects more secure.

As much as possible, all information must be taken into consdieration and an increased monitoring of this subject must be constantly carried out. We can rely on the fact that if the information remains incomplete, there is a chance that someone else will take over to improve them. The important thing is that it is left freely accessible and documented. This can be a considerable effort that must be commensurate with that the software could provide to users. That is why every contribution counts and is encouraged even if it seems incomplete. All this is the basis for a continuous improvement system that is optimised and revisited : based on the information available and the existing one, everyone can create on it and contribute to improve it.

### User trust

Users' trust must never be misled and we must trust in the user. Grapp must in __no way__ claim to be secure on its own, in any way. User freedom take precedence over software security considerations. The services provided by the software must be able to comply with the requirements of the users. Also, the user must be able to trust the software he is using and be able to verify and access to the code of the software at the very obvious condition that this does not constitute an infringement of rights. In this field and even more in open source software, that only the users that provides the use cases and requirements and this is also what encourages improvement and innovation. Finally, an induced security level is always subjective, the considerations given to users must be transparent and verifiable, at the very least, through the documentation and source code.


## Security Requirements

Relatives documentation are recommendations only and not contracts between a software provider and a client nor contributors and users.

Security may be a feeling that is unique to each user. Security is above all a discipline, the use of mechanisms, methodologies, rigour and is continuous. Grapp must be able to comply with the security requirements of the users primarly. It must, as much as possible, be able to helps the end-user to adopt good practices and, with its tools, to promote the adoption of automated processes on the security within applications and infrastructures and must in no way restrict the freedoms of end-users. As it will not impose any restrictions on the use of the software, the only security requirement being the disclosing of the sources and documentation, when the software is distributed. This documentation and soure code must leave an open debate and provide all the necessary recommendations to end-users. As much as possible, contributors should comply with the followings recommendations.

### Limitations

Grapp is a free and open source software published under a LGPL v3 License and his documentation is published under a Creative Commons CC-BY 4.0. In accordance to theses licences, the software is provided 'as is' and without any warranties. End users could be held responsible of failures or security issues. It's why authors should provide all necessary recommendations, documentation and full source code to allow the user to judge the security of the tool and to give them the freedom to use (partialy or not), as they wish, or not use the software and to adapt it to their own needs if they wish.

## Contributions

Whenever possible, all security recommendations and documentation must be made for contributors and end-users. Even if no warranty is possible, we must to use best practices in this area and security should be considered as a __top priority__.

The project cannot claim to completely remove the inherent security vulnerabilities in infrastructures but he can at least try not to include more (it's complicated, but it's worth the work), anticipate and reduce them by providing the right ones interfaces.

Security vulnerabilities can multiply as the development progresses and the project includes more and more lines of code and features. As a user, contributor we must ensure that the versions of the software is carefully considered. We must use a development methodology that protects the library, as best as possible, from including security vulnerabilities and accept as pledges this work of necessity.

As contributors :
- We have to commit ourselves to use and promote good practices.
- We have to commit ourselves to adopting a process of continuous improvement about security.
- We have to commit ourselves to warn users about security threat and make recommendations.
- We have to commit ourselves, to publicly document everything is related to security about the project.
- We commit ourselves, as quickly as possible, to informing the community if a vulnerability is discovered and describing the problem as well as possible through an issue or any other publicly visible methods.
- We must, as much as possible, ensure and provide increased responsiveness, rethink, test and watch continuously around this subject.
- We must, as much as possible, accept knowledge or technical limitations, anything outside our area of expertise and explicitly provide the limitations for more experienced or specialized members.
- We must, as much as possible, recognize that a version or a component considered unsatisfactory by the users in terms of security must not be redistributed.

## GEPs Type 'S'

In order to facilitate categorisation and indexing, the prioritization, the opening of security bulletins, the implementation of security elements or requirements and to open disucssions around security considerations, GEP(s) includes specific type "S" for "Security or Standards related GEP". All GEP related to this topic must be posted under this type.

## GEPs "Security Considerations" mandatory section for Type 'E'

To encourage a good approach in this area, a note concerning the security aspect must be attached by developpers to each feature in development. To standardize this inside the project, it's mandatory to contributors to write a section about security for each GEP concerning a feature developement (type'E').

## GEPs 31* Security Bulletin

In order to facilitate [the management and communication of any software vulnerability](./gep-301.md), security bulletins are issued in the form of an 'S' type GEP with a number starting with __31*__. A template and information on how to issue them is available in the [GEP#31](./gep-31.md) that defines them.

## Security Watchlist

In order to provide a place where important updated information about security and to provide to contributors a comprehensive lists of things to watch out, a [Security Watchlist](./gep-30.md) is available and must be maintained.

## Versions

For each version of the software and the library, recommendations must be specified in a visible way. The public versions should be separated from the versions under development. 

Development versions is not free of security vulnerabilities or have not a satisfying number of reviews needed to judge them. Readers, members and experienced users are strongly encouraged to contribute to their validation by participating in the project.

## Integrity

Grapp must be provided with a means of verifying the integrity of the version. In order to be able to confirm the integrity of each version, a means of checking its integrity must be provided. For the package, for example, the releases may be accompanied by an integrity file including a computed hash of each essential component and may be distributed with the version and publicly distribued or checkable over an other secure channel.

## Library and software dependancies

The choice of dependencies must be carefully considered. All dependancies should be tracked for security issues and updates. Their integretity and version check are mandatory. In order to encourage this monitoring a list of software dependencies must be maintained as much as possible. This extends to the choice of standards, standards will have to be carefully chosen, implemented and verified.

## Provide recommendations and warnings to the end user

The projet should to encourage and help the end user to adopt good practices about security, to help the user take the necessary decisions to meet an induced security level and warn the user about what can threaten his environment. All this must be done in a visible, clear manner to avoid misinterpretation. Ideally resources should be linked and provided to educate and clarify any content that would require a certain technical level to understand.

## Logging

All security related matters should be logged in a way that is only accessible to the end user and should respect the concept of courtesy limits and sensitive data. This logging allows the end-user to forensic and to set up a continuous monitoring system in accordance with his security requirements.

## Integration

As much as possible, interfaces providing real-time information flows should be written to give to the end-users all the essential information to manage security within their environment and infrastructure.

## A tool for security

As an automation and remote connection tool, Grapp must provide tools to simplify and speed up the security process by assisting users in their security tasks. Everything must be designed so that the end user can judge, justify, accept and integrate a certain level of security. We also must to facilitate - through the implementation of tools that allow this and by providing all the necessary documentation - any audit made on the end-user's infrastructure or applications.

Grapp is primarily a Python program that uses SSH to perform its operations. Grapp is located on layer 7 of the OSI model. Understanding that it does not define itself on the lower layers, it could not claim in any way to have any direct efficiency on threats related to the lower layers. It may be worthwhile to extend also all the revelant concepts and implement a compatibility to lower layers. This is a development area that should be considered as a priority.

## See also

- [Using Trust Assumptions in Security Requirements Engineering](https://www.researchgate.net/publication/250350085_Using_Trust_Assumptions_in_Security_Requirements_Engineering)
- [GEP#30: Security Watchlist](./gep-30.md)
- [GEP#31: Security Bulletins](./gep-31.md)
- [GEP#300: Security Glossary](./gep-300.md)
- [GEP#301: Vulnerability Remediation Procedure](./gep-301.md)

## License

- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)






