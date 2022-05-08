# GEP#4 : Contributions Guidelines

__Author(s)__ : RSZ
__Start date__ : 04/10/2021
__Last Modification__ : 04/10/2021
__Type Key__ : X
__Status Key__ : A

----------------------

## Introduction

This document explain how you can easily contribute to Grapp.

## Contribute

First of all, __thank you very much__ to all of you who are about to contribute to this project or who are just taking the time to be interested in 🤗.

Contributions in any form are open and widely encouraged. The main way to contribute is to directly participate through Github. You will find the resources to make your contribution to the grapp project and its sub-projects directly on the GEPs repository.

- Please ensure you agree to the [GEP#41: Code of conduct](./gep-41.md).
- Please make sure you understand what a GEP is, by reading [GEP#0: Grapp Enhancement Proposals](./gep-0.md), you can ask questions about it by opening an issue.
- Please ensure that you have read and do not duplicate a potential contribution in progress by reading the content of the GEPs and openned issues. You can find the complete list of GEP in the [GEP#1: GEPs Index](./gep-1.md).
- You can find the addresses of the repositories here : [GEP#12: Website and Repositories](./gep-12.md).

## How to

### By starring the project and sharing

You are interested in the project or you know someone who might be... Don't hesitate to star the project and to share it with your friends as it is a great form of support. We rely heavily on this to build and move forward !

### By opening an Issue

Templates have been made to help you. To talk about or follow a topic related to Grapp Project and development, or for those who don't use git in general, the easiest way to contribute is to create an issue on the [GEPs repository](https://github.com/grapp-project/geps/issues). Obviously, you will need a Github account for that.

__See also__ :
- [Create an issue, Github docs](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue)

### By making Pull Requests

Contributing via pull requests may seem a bit technical at first but is actually very easy for anyone who has used git before or who has had a first experience with. Although it is unfortunate for the history of the project, you can delete your fork after the changes has been accepted.

__See also__ :
- [Fork a repo, Github docs](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
- [Creating a pull request, Github docs](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

### By reviewing

Revisions are made directly via the GEPs, the comments on pull requests and their related issues. To do this, make sure you have read [GEP#0](./gep-0.md) section "GEP Process". You can vote with a simple 👍/👎 or approve/disapprove via an issue or comments on a pull request. In order to guide other contributors in your analysis, try to argue, as much as possible, and express your opinion or your vision.

### By contacting

You don't know how to contribute, yet you want to. Please send your message to contact@grapp-project.org, we will be happy to read and answer your message as soon as possible.

## On what?

Grapp is developed with open specifications and discussions. These are the GEPs. So you can participate directly in the development, you just have to browse the GEPs (or source code) and make improvements.

## Specs and implementation

The specifications and tests included in the functionalities drive the development of the project. Therefore, in order to participate in the development, it is advisable to participate on any element that meets the active or final specifications and whose implementation is not complete.

If a feature is to be added, then it follows the feature specification process defined by the GEPs.

__See also__:
- [GEP#10069: List of all 'Feature request or implementation GEP'](./gep-10069.md)

## Pipes (work in progress)

Everything is mainly provided in the GEPs, so, in order to organise and prioritise the tasks related to these specifications, "pipes" have to be created and publicly visible in order to invite and communicate on progress. The development of grapp is perfectly iterative and must be judiciously articulated in correlation with its specifications. These "pipes" are the connectors to the todo lists of tasks that can be related to one or more GEPs and their status. In this way, current / future / planned tasks can be easily consulted, joined and modified.

## Everything that is not exhaustive

One of the contributions that could be "favourite" would be to develop features. But this is not the case. There are so many other things that could be improved that cannot be listed. Contributions on the followings points are more than welcome and necessary :
- corrections, translations,
- aesthetic improvements,
- communication actions, 
- make the user and contributor experience as smooth and frictionless as possible,
- make the project work, simply,
- provide use cases that have not yet been described,
- provide support to help understand it and improve its documentation,
- security considerations and requirements improvements,
- discussions on the philosophy of the project,

The project needs to continuously improve, organise and define itself properly on all these previous points. But also others which would not have been listed here... This cannot be exhaustive.

## Tools and networks

In order to facilitate the contribution and to condense the tools necessary for the development of the project, you will find here the resources and software that are important or that it seemed appropriate to indicate.

- __grapp-contrib__ (work in progress), a CLI which condenses tools that respond to the processes described in the GEPs.

To communicate and share resources for development :
- Mainly a __Github__ account

## Branches and Versions

Without being pessimistic, but with a realistic view, there will surely be errors and problems with branches and compromised versions during development. The point here is to define some key elements to demystify potential version conflicts.

### Keep your fork up-to-date

__To syncing your fork__ :
- [Syncing a fork, Github docs](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork)

### Grapp Package

The repository concerned is :
- [https://github.com/grapp-project/grapp](https://github.com/grapp-project/grapp).

Whereas the specifications (GEPs) designate and describe a public API, branch names (with the exception of `main` which is the latest version available) should correspond to the version numbers as defined by the [Semantic Versioning 2.0.0](https://semver.org/). Versions are defined in [GEP#7: Releases](./gep-7.md). Some versions may simply be ignored as a source of conflict.

The names of the branches and the management of the branches must respect the considerations made on the [Semantic branching model](https://dev-cafe.github.io/branching-model/) from Roberto Di Remigio, Radovan Bast.

Some appendix are standardized by this GEP :
- __X.X.X__ (no appendix) : Official release.
- __X.X.X__`-patches`, specific version hotfix : Patches for a specific problem have been completed and are awaiting the necessary reviews and peer validation. This includes security patches and fixes.
- __X.X.X__`-dev.__[feature]__`, Feature, branch , may be local (where [feature] here can be a gep number or a short word description).
- __X.X__.0`-dev`, Minor development branch.
- __X__.0.0`-dev`, Major development branch.

No pull requests that would result in a merge with conflicts will be accepted.


### GEPs, Website and grapp-contrib

The repositories concerned are :
- [https://github.com/grapp-project/geps](https://github.com/grapp-project/geps)
- [https://github.com/grapp-project/site](https://github.com/grapp-project/site)
- [https://github.com/grapp-project/contrib_tools](https://github.com/grapp-project/contrib_tools)

Only `main` is considered as the only valid branch for now.

## About content & license

Obviously, any content published within the project must be directly related to and concern Grapp.

Is excluded :
- Any content that does not comply with the code of conduct.
- Any content protected by other rights, such as moral rights, copyright, personal data rights and image rights.
- Content marked with an exception or credited or already attributed.

If you believe that any content on the pproject belongs to you or infringes any property rights, also, if you notice any content that is abnormal/immoral/offensive to you, please contact us immediately to have it removed or modified as soon as possible.

__See also__ :
- [GEP#18: Licenses](./gep-18.md)

## License

- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
