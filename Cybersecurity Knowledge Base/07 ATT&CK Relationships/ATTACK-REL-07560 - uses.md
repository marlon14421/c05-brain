---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0389"
target_object: "T1204.002"
stix_relationship_id: "relationship--ac8ba4ea-f9dc-4d0c-85d9-0df3041fd304"
---
# Relationship 7560: S0389 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0389 - JCry|S0389: JCry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[JCry](https://attack.mitre.org/software/S0389) has achieved execution by luring users to click on a file that appeared to be an Adobe Flash Player update installer. (Citation: Carbon Black JCry May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac8ba4ea-f9dc-4d0c-85d9-0df3041fd304`.
