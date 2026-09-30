---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-651"
status: "Incomplete"
---
# CWE-651: Exposure of WSDL File Containing Sensitive Information

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Server

## Description

The Web services architecture may require exposing a Web Service Definition Language (WSDL) file that contains information on the publicly accessible services and how callers of these services should interact with them (e.g. what parameters they expect and what types they return).

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Limit access to the WSDL file as much as possible. If services are provided only to a limited number of entities, it may be better to provide WSDL privately to each of these entities than to publish WSDL publicly.
- **Architecture and Design:** Make sure that WSDL does not describe methods that should not be publicly accessible. Make sure to protect service methods that should not be publicly accessible with access controls.
- **Architecture and Design:** Do not use method names in WSDL that might help an adversary guess names of private methods/resources used by the service.

## Related weaknesses

- CWE-538 (ChildOf)

## Source

- [CWE-651 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/651.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
