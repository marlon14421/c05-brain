---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1024"
target_object: "T1070.007"
stix_relationship_id: "relationship--6127605c-df31-4810-a24c-77a965399c90"
---
# Relationship 1062: M1024 — mitigates → T1070.007

**Source object:** [[01 ATT&CK/M1024 - Restrict Registry Permissions|M1024: Restrict Registry Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1070.007 - Clear Network Connection History and Configurations|T1070.007: Clear Network Connection History and Configurations]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Protect generated event files and logs that are stored locally with proper permissions and authentication and limit opportunities for adversaries to increase privileges by preventing Privilege Escalation opportunities.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6127605c-df31-4810-a24c-77a965399c90`.
