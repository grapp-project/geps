# GEP#31 : Security Bulletins

__Author(s)__ : RSZ
__Start date__ : 13/09/2021
__Last Modification__ : 13/09/2021
__Type Key__ : S 
__Status Key__ : D

----------------------

## Introduction

This document defines how the security bulletin must be edited and what they are intended for.

## Definition

Security bulletins are documents issued by the community containing all the information collected on known or potential vulnerabilities in the project. This document in its format aims to standardize a vulnerability remediation procedure and to create a dynamic around these considerations within the project. Security bulletins should be published and available publicly in order to provide all the necessary information to end-users and/or contributors.

Safety Bulletins are dynamic documents, they evolve over time. This is why each addition / modification within the document must be accompanied by a date in order to maintain a history and consistency in the document.

## Reserved GEP number 31*

All security bulletins should be published in the [main GEPs repository](./gep-12.md) under the number __31*__ (_e-g_ 31001, 31500, 312 are valid security bulletins numbers).

## Template

You can found a template for Security Bulletins in [GEP#996](./gep-996.md).

## Mandatory sections

Security bulletins must include the following mandatory section :

### Summary

To begin with, the summary includes a history of changes in the form of a table with the date and a brief description of the changes made.

_E-g_ :

| Date | Description |
|-|-|
| 22/09/2021 | Patches published on version X.X.X |
| 20/09/2021 | Initial publication |

Secondly, it is common to use indicators and metrics to quantify and assess the risks involved. In this summary, all the latest indicators should be (re)calculated and collected. Vulnerabilities should be assigned a [CVSS 3.1](https://www.first.org/cvss/v3.1/specification-document) vulnerability score as understood by [FIRST](https://www.first.org/). In order to calculate this score easily, calculators are available online here : by [FIRST](https://www.first.org/cvss/calculator/3.1) or by [NIST](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator).

This second part of summary is presented in the form of a quick-read table :

_E-g_ :

| Version(s) | Component(s) | CWE(s) | Base/Overall Score | Remediation Level |
|-|-|-|-|-|
| <=X.X.X | SSHConnection | [261](http://cwe.mitre.org/data/definitions/261.html) | 8.9/6.9 | Temporary fix (RL:T) |


- Version(s) : If identified, the version(s) involved.
- Component(s) : If identified, the component(s) involved.
- (Optional) [CWE](http://cwe.mitre.org/index.html) : If the vulnerability can be identified through a CWE, then it should be provided.
- Base/Overall Score : These are the CVSS scores corresponding to.
- Remediation Level : This is a reminder of the CVSS Remediation Level (RL).
- Details of the scores should be added at the foot of the table.


### Description

This section should be a succinct and comprehensive description of the vulnerability.

### Diagnosis

The objective of the diagnosis is to identify. If a vulnerability is discovered or seem to be present it should be checked whether and how it impacts the software, the components and sources involved should be identified. The diagnosis is based on the information collected on the vulnerability. This information should be collected in this section. Indeed, diagnosis and reporting are linked, this will help to determine the scope and provide indicators to report.

Each advance on the diagnosis or modification of the text must be preceded by their dates.

_E-g_
```
- 20/10/2021 : ...
- 19/10/2021 : ...
```

### Recommendations

The recommendations are intended for end-users who may be impacted by this vulnerability.

As with the diagnosis, any change of recommendation must be indicated and preceded by its date.

### Remediation

The section should be introduced for end-users if actions are to be taken by them and instructions should be provided.

Should follow the list of patches provided with a short description of what they do. Patches can be partial and only reduce the scope of the vulnerability, so it is important to note this correctly.

As with the diagnosis and recommendations, each advance on the remediation or modification of the text must be preceded by their dates.

### Resources

All resources that complement this bulletin such as additional documentation, tests or public exploit sources code should be provided in this section.

### Disclaimer

> The information provided in this Bulletin is provided "as is" without warranty of any kind. This Security Bulletin is open, could be edited by anyone, is given for information only and is not necessarily free of errors nor exceptions.

## License

- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
