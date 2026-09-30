---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1035"
target_object: "T1071.001"
stix_relationship_id: "relationship--e1684251-e7a6-462b-891e-62a1290152af"
---
# Relationship 9633: S1035 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1035 - Small Sieve|S1035: Small Sieve]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Small Sieve](https://attack.mitre.org/software/S1035) can contact actor-controlled C2 servers by using the Telegram API over HTTPS.(Citation: DHS CISA AA22-055A MuddyWater February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1684251-e7a6-462b-891e-62a1290152af`.
