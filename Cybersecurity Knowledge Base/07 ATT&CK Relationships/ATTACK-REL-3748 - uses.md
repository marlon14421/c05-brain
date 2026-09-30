---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0125"
target_object: "T1027.013"
stix_relationship_id: "relationship--43edea0b-efb8-41ab-bdda-f5aa62de439f"
---
# Relationship 3748: S0125 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0125 - Remsec|S0125: Remsec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

Some data in [Remsec](https://attack.mitre.org/software/S0125) is encrypted using RC5 in CBC mode, AES-CBC with a hardcoded key, RC4, or Salsa20. Some data is also base64-encoded.(Citation: Symantec Remsec IOCs)(Citation: Kaspersky ProjectSauron Technical Analysis)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43edea0b-efb8-41ab-bdda-f5aa62de439f`.
