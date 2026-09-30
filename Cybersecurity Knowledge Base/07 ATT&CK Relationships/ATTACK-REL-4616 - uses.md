---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0671"
target_object: "T1568"
stix_relationship_id: "relationship--03f288cd-a189-4de9-abd4-6b10bda138a4"
---
# Relationship 4616: S0671 — uses → T1568

**Source object:** [[01 ATT&CK/S0671 - Tomiris|S0671: Tomiris]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568 - Dynamic Resolution|T1568: Dynamic Resolution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Tomiris](https://attack.mitre.org/software/S0671) has connected to a signalization server that provides a URL and port, and then [Tomiris](https://attack.mitre.org/software/S0671) sends a GET request to that URL to establish C2.(Citation: Kaspersky Tomiris Sep 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03f288cd-a189-4de9-abd4-6b10bda138a4`.
