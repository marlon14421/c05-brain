---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9019"
target_object: "T1102"
stix_relationship_id: "relationship--2065dfc0-837a-4ff0-a929-420d9fa8b2a1"
---
# Relationship 4981: S9019 — uses → T1102

**Source object:** [[01 ATT&CK/S9019 - PureCrypter|S9019: PureCrypter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PureCrypter](https://attack.mitre.org/software/S9019) can use Telegram or Discord to send infection status messages.(Citation: Zscaler PureCrypter JUN 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2065dfc0-837a-4ff0-a929-420d9fa8b2a1`.
