---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1070"
target_object: "T1036.004"
stix_relationship_id: "relationship--fe18ff64-8ea8-4e21-97b5-5c46a57a39d9"
---
# Relationship 4560: S1070 — uses → T1036.004

**Source object:** [[01 ATT&CK/S1070 - Black Basta|S1070: Black Basta]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Black Basta](https://attack.mitre.org/software/S1070) has established persistence by creating a new service named `FAX` after deleting the legitimate service by the same name.(Citation: Minerva Labs Black Basta May 2022)(Citation: Cyble Black Basta May 2022)(Citation: Trend Micro Black Basta May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe18ff64-8ea8-4e21-97b5-5c46a57a39d9`.
