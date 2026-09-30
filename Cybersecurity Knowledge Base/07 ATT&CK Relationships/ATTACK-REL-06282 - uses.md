---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0598"
target_object: "T1059"
stix_relationship_id: "relationship--7e3bdb4d-76b3-42ce-8f68-587320e39ec7"
---
# Relationship 6282: S0598 — uses → T1059

**Source object:** [[01 ATT&CK/S0598 - P.A.S. Webshell|S0598: P.A.S. Webshell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059 - Command and Scripting Interpreter|T1059: Command and Scripting Interpreter]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[P.A.S. Webshell](https://attack.mitre.org/software/S0598) has the ability to create reverse shells with Perl scripts.(Citation: ANSSI Sandworm January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e3bdb4d-76b3-42ce-8f68-587320e39ec7`.
