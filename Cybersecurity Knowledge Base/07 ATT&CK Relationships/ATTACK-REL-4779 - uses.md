---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1105"
stix_relationship_id: "relationship--497ebc9c-e993-4097-9cb0-11b5a13b0bb5"
---
# Relationship 4779: S1245 — uses → T1105

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has downloaded “AnyDesk.exe” into the user’s home directory from the C2 server when checks for the service fail to identify its presence in the victim environment.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025) [InvisibleFerret](https://attack.mitre.org/software/S1245) has also been configured to download additional payloads using a command which calls to the /bow URI.(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--497ebc9c-e993-4097-9cb0-11b5a13b0bb5`.
