---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0369"
target_object: "T1553.001"
stix_relationship_id: "relationship--f4eabef1-c66d-45b2-a7c7-6c4cefe4862b"
---
# Relationship 4521: S0369 — uses → T1553.001

**Source object:** [[01 ATT&CK/S0369 - CoinTicker|S0369: CoinTicker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.001 - Gatekeeper Bypass|T1553.001: Gatekeeper Bypass]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CoinTicker](https://attack.mitre.org/software/S0369) downloads the EggShell mach-o binary using curl, which does not set the quarantine flag.(Citation: CoinTicker 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4eabef1-c66d-45b2-a7c7-6c4cefe4862b`.
