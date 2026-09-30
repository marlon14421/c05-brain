---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1105"
target_object: "T1083"
stix_relationship_id: "relationship--741fd887-1d55-489b-a77f-3a1d28016305"
---
# Relationship 4208: S1105 — uses → T1083

**Source object:** [[01 ATT&CK/S1105 - COATHANGER|S1105: COATHANGER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[COATHANGER](https://attack.mitre.org/software/S1105) will survey the contents of system files during installation.(Citation: NCSC-NL COATHANGER Feb 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--741fd887-1d55-489b-a77f-3a1d28016305`.
