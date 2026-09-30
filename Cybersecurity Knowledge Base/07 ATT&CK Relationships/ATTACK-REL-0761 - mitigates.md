---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1017"
target_object: "T1684"
stix_relationship_id: "relationship--d9f8babb-0b1b-4eb9-aa0c-13c5507561ce"
---
# Relationship 0761: M1017 — mitigates → T1684

**Source object:** [[01 ATT&CK/M1017 - User Training|M1017: User Training]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1684 - Social Engineering|T1684: Social Engineering]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Reduces success of phishing/vishing/impersonation and modern “human interface” lures.(Citation: SE SentinelOne 2)(Citation: Sophos User Interaction)(Citation: Unit 42 Global Incident Response Report 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9f8babb-0b1b-4eb9-aa0c-13c5507561ce`.
