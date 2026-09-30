---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0196"
target_object: "T1560.001"
stix_relationship_id: "relationship--73faed96-608b-4740-894f-0e2eaee92343"
---
# Relationship 4312: S0196 — uses → T1560.001

**Source object:** [[01 ATT&CK/S0196 - PUNCHBUGGY|S0196: PUNCHBUGGY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PUNCHBUGGY](https://attack.mitre.org/software/S0196) has Gzipped information and saved it to a random temp file before exfil.(Citation: Morphisec ShellTea June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73faed96-608b-4740-894f-0e2eaee92343`.
