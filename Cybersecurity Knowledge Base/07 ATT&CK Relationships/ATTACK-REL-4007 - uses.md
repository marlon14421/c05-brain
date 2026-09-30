---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0173"
target_object: "T1572"
stix_relationship_id: "relationship--e3b79cfa-6ea8-4e7a-85f8-9862702d466a"
---
# Relationship 4007: S0173 — uses → T1572

**Source object:** [[01 ATT&CK/S0173 - FLIPSIDE|S0173: FLIPSIDE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FLIPSIDE](https://attack.mitre.org/software/S0173) uses RDP to tunnel traffic from a victim environment.(Citation: Mandiant FIN5 GrrCON Oct 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3b79cfa-6ea8-4e7a-85f8-9862702d466a`.
