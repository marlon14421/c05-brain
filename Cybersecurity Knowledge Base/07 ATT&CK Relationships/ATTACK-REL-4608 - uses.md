---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0263"
target_object: "T1059.005"
stix_relationship_id: "relationship--ccd237b6-c7d6-4941-a1f2-cb563ae90b79"
---
# Relationship 4608: S0263 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0263 - TYPEFRAME|S0263: TYPEFRAME]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TYPEFRAME](https://attack.mitre.org/software/S0263) has used a malicious Word document for delivery with VBA macros for execution.(Citation: US-CERT TYPEFRAME June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ccd237b6-c7d6-4941-a1f2-cb563ae90b79`.
