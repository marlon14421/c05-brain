---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0635"
target_object: "T1140"
stix_relationship_id: "relationship--353dd407-0850-4bc4-a447-cd1b708b3833"
---
# Relationship 3139: S0635 — uses → T1140

**Source object:** [[01 ATT&CK/S0635 - BoomBox|S0635: BoomBox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BoomBox](https://attack.mitre.org/software/S0635) can decrypt AES-encrypted files downloaded from C2.(Citation: MSTIC Nobelium Toolset May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--353dd407-0850-4bc4-a447-cd1b708b3833`.
