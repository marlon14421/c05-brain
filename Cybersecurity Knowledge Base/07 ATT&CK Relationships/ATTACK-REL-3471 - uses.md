---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9015"
target_object: "T1090.001"
stix_relationship_id: "relationship--e0137354-4660-4053-ab7d-9f8358ff6ceb"
---
# Relationship 3471: S9015 — uses → T1090.001

**Source object:** [[01 ATT&CK/S9015 - BRICKSTORM|S9015: BRICKSTORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.001 - Internal Proxy|T1090.001: Internal Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) has leveraged SOCKS Proxy to pivot into victim networks in attempts to resemble legitimate administrative traffic.(Citation: CrowdStrike BRICKSTORM WARP PANDA UNC5221 December 2025)(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Picus Security BRICKSTORM UNC5221 October 2025)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)(Citation: NVISO BRICKSTORM April 2025)(Citation: Google BRICKSTORM September 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e0137354-4660-4053-ab7d-9f8358ff6ceb`.
