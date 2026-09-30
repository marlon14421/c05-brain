---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1159"
target_object: "T1027.013"
stix_relationship_id: "relationship--45258d6a-3717-4542-ac17-e7343fae0304"
---
# Relationship 4610: S1159 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1159 - DUSTTRAP|S1159: DUSTTRAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DUSTTRAP](https://attack.mitre.org/software/S1159) begins with an initial launcher that decrypts an AES-128-CFB encrypted file on disk and executes it in memory.(Citation: Google Cloud APT41 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45258d6a-3717-4542-ac17-e7343fae0304`.
