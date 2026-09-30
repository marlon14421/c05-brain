---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9023"
target_object: "T1573.002"
stix_relationship_id: "relationship--2eae4409-f8ae-45dd-91f4-6d1d4e386178"
---
# Relationship 4046: S9023 — uses → T1573.002

**Source object:** [[01 ATT&CK/S9023 - HiddenFace|S9023: HiddenFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HiddenFace](https://attack.mitre.org/software/S9023) can use RSA-2048 in addition to symmetric algorithms in C2.(Citation: Trend Micro Earth Kasha NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2eae4409-f8ae-45dd-91f4-6d1d4e386178`.
