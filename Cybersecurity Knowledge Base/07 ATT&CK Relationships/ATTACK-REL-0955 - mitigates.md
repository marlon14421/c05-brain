---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1017"
target_object: "T1598"
stix_relationship_id: "relationship--3de6d2ba-842b-4f60-b177-d8082eebbb1e"
---
# Relationship 0955: M1017 — mitigates → T1598

**Source object:** [[01 ATT&CK/M1017 - User Training|M1017: User Training]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1598 - Phishing for Information|T1598: Phishing for Information]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Users can be trained to identify social engineering techniques and spearphishing attempts.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3de6d2ba-842b-4f60-b177-d8082eebbb1e`.
