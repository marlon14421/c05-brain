---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9028"
target_object: "T1027.013"
stix_relationship_id: "relationship--ce788d40-df7d-488d-b864-81d7525c6262"
---
# Relationship 3265: S9028 — uses → T1027.013

**Source object:** [[01 ATT&CK/S9028 - PHPsert|S9028: PHPsert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PHPsert](https://attack.mitre.org/software/S9028) can use multiple obfuscation techniques including XOR encoding, hexadecimal character representation, string concatenation, and randomized variable names.(Citation: sentinelone operationDigitalEye Dec 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce788d40-df7d-488d-b864-81d7525c6262`.
