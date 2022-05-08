# GEP#18 : Licenses

__Author(s)__ : RSZ
__Start date__ : 13/09/2021
__Last Modification__ : 13/09/2021
__Type Key__ : I
__Status Key__ : A

----------------------

## Introduction

This document gives a few words on the choice of license applied to Grapp Project.

## GEPs

All GEPs documents related to the Grapp Enhancement Proposals are distributed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

You are free to share, copy, distribute, communicate, adapt, remix and transform the content and resources by any means and in any format, provided that you must visibly attribute a link or mention to the original paper.

## Grapp package

![LGPL v3](./assets/gep-18/lgpl3.png) 

Grapp package is released under the [LGPL v3 or later](https://www.gnu.org/licenses/lgpl-3.0.html) license.

Any work (including recipes) which uses the licensed material as a library is not subject to redistribution of its source nor under the same license. This exclusive condition of the LGPL is permissive.

Assuming that you have a file a project that uses grapp library, you can put any compatible license on it and do whatever you want with it, including commercial use. This is a free software.

If you wish to produce and distribute a derivative work, namely a project based directly on the sources (even partially) then you are obliged to distribute them under the same conditions (see notes below).

### Note

With Grapp, it is expected that all users can take full advantage of it. All recognition must be given to the contributors without whom the project would not be viable. Each user should be able to use this software as they wish. It is not the intention of the project to prevent anyone from creating a business from this project or around it and this is a rather desired result.

Initially, the opening of Grapp is intended to create a community and to involve all contributors who want to participate in the project around a joint effort. In its philosophy, it wishes to provide an alternative to paid solutions that could be opaque to its users and participate in making the software more open and free.

Also, because it allows remote connection and deal with sensitive data, security consideration is a primary focus in the development and within Grapp. Security is not incompatible with open source and free software. On the contrary, it allows for innovation and continuous improvement through transparency. The users must have transparency about what they are using and users should be trusted. In this respect, security also means transparency of the methods used. Indeed, the project does not hide how sensitive data is used and processed, so in order to be in line with the transparency due to any audit performed by a third-party wishing to verify and validate its processes. Accordingly, this allows the end-user to verify the compliance of the software with its security and privacy rules and possibly adapt them by creating their own version.

It is for these reasons of transparency and security that a limitation must be made on derived work. When distributed, a library derived directly from grapp source code should be redistributed under the same conditions. The MIT or BSD licenses are too permissive for this, in contrast, the original GPL imposes a little too many restrictions for redistributions.

The GPL seems to be a good solution for Grapp packages. It is designed in an approach that inspired Grapp. The licensed material is the source code of the library. This obliges users who make derivative work from the library and who distributes it to give the source code, document modifications and provide it under the same conditions. By this grant, the end user will always have the possibility to access and audit the source code regardless of the distribution. This promotes joint effort and the use of the library remains totally free.

## Grapp UI

A relevant exception could be considered for the UI component. The UI could be distributed under [AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html).

### Note

For security reasons, it would be wise not to distribute this component on a public network in its initial form (as Saas). This applies in particular to probable derivative works. If someone would like to do this, he should rather adapt the work from the components of the library which is under LGPL, more permissive and which does not take into account these network considerations.

The UI component should remain only in a private context, not be redistributed (as the AGPL intends) via the network or in SaaS, because it is not its vocation. Globally the AGPL associated with the UI would oblige those who wish to do SaaS with it (only the UI components) to pulish the source code of the derivative work and to document all modifications. This would provide transparency to the end-user on this SaaS and derivative work.

This would not at all be to restrict the use of Grapp, but rather as an additional security consideration for the end-users.

## License

- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
