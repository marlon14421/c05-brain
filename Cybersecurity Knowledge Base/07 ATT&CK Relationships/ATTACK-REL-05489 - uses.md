---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1187"
target_object: "T1505.003"
stix_relationship_id: "relationship--e1308e9f-b130-4979-88ca-dbdf36e3ba78"
---
# Relationship 5489: S1187 — uses → T1505.003

**Source object:** [[01 ATT&CK/S1187 - reGeorg|S1187: reGeorg]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[reGeorg](https://attack.mitre.org/software/S1187) is a web shell that has been installed on exposed web servers for access to victim environments.(Citation: Mandiant APT29 Eye Spy Email Nov 22)(Citation: Cadet Blizzard emerges as novel threat actor)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1308e9f-b130-4979-88ca-dbdf36e3ba78`.
