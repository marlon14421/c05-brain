---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-285"
status: "Draft"
---
# CWE-285: Improper Authorization

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Server, Database Server

## Description

The product does not perform or incorrectly performs an authorization check when an actor attempts to access a resource or perform an action.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that you perform access control checks related to your business logic. These checks may be different than the access control checks that you apply to more generic resources such as files, connections, processes, memory, and database records. For example, a database may restrict access for medical records to a specific database user, but each record might only be intended to be accessible to the patient and the patient's doctor.
- **System Configuration:** Use the access control capabilities of your operating system and server environment and define your access control lists accordingly. Use a "default deny" policy when defining these ACLs.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-284 (ChildOf)

## Source

- [CWE-285 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/285.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
