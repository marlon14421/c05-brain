---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0251"
target_object: "T1547.001"
stix_relationship_id: "relationship--8839b4ad-24cb-4ad3-a407-947f75591973"
---
# Relationship 2948: S0251 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0251 - Zebrocy|S0251: Zebrocy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Zebrocy](https://attack.mitre.org/software/S0251) creates an entry in a Registry Run key for the malware to execute on startup.(Citation: ESET Zebrocy Nov 2018)(Citation: ESET Zebrocy May 2019)(Citation: Accenture SNAKEMACKEREL Nov 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8839b4ad-24cb-4ad3-a407-947f75591973`.
