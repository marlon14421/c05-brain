---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0012"
target_object: "T1124"
stix_relationship_id: "relationship--9158696f-fdc6-4869-a395-5d94c7c13d26"
---
# Relationship 4129: G0012 — uses → T1124

**Source object:** [[01 ATT&CK/G0012 - Darkhotel|G0012: Darkhotel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Darkhotel](https://attack.mitre.org/groups/G0012) malware can obtain system time from a compromised host.(Citation: Lastline DarkHotel Just In Time Decryption Nov 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9158696f-fdc6-4869-a395-5d94c7c13d26`.
