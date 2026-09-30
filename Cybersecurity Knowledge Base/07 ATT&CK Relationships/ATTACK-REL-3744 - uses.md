---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9017"
target_object: "T1573.002"
stix_relationship_id: "relationship--59e256fe-638f-4b1f-81d0-3329b05a1443"
---
# Relationship 3744: S9017 — uses → T1573.002

**Source object:** [[01 ATT&CK/S9017 - DCRAT|S9017: DCRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DCRAT](https://attack.mitre.org/software/S9017) can use certificate-based authentication for C2 servers.(Citation: Zscaler BlindEagle DEC 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59e256fe-638f-4b1f-81d0-3329b05a1443`.
