---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0273"
target_object: "T1090"
stix_relationship_id: "relationship--a13feeb0-d376-4460-8335-f86c0f163d4b"
---
# Relationship 4256: S0273 — uses → T1090

**Source object:** [[01 ATT&CK/S0273 - Socksbot|S0273: Socksbot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Socksbot](https://attack.mitre.org/software/S0273) can start SOCKS proxy threads.(Citation: TrendMicro Patchwork Dec 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a13feeb0-d376-4460-8335-f86c0f163d4b`.
