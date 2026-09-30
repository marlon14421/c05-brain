---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0409"
target_object: "T1016.002"
stix_relationship_id: "relationship--b2cf7bc7-d373-4627-9610-73544d1be8cc"
---
# Relationship 5611: S0409 — uses → T1016.002

**Source object:** [[01 ATT&CK/S0409 - Machete|S0409: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016.002 - Wi-Fi Discovery|T1016.002: Wi-Fi Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Machete](https://attack.mitre.org/software/S0409) uses the netsh wlan show networks mode=bssid and netsh wlan show interfaces commands to list all nearby WiFi networks and connected interfaces.(Citation: ESET Machete July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2cf7bc7-d373-4627-9610-73544d1be8cc`.
