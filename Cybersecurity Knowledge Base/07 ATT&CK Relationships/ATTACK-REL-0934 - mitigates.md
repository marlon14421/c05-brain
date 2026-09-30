---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1590.002"
stix_relationship_id: "relationship--9e6ba901-ece5-44a0-8315-1f9b833fe78a"
---
# Relationship 0934: M1054 — mitigates → T1590.002

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1590.002 - DNS|T1590.002: DNS]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider implementing policies for DNS servers, such as Zone Transfer Policies, that enforce a list of validated servers permitted for zone transfers.(Citation: DNS-msft)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e6ba901-ece5-44a0-8315-1f9b833fe78a`.
