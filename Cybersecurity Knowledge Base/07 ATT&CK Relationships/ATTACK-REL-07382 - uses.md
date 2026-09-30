---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1081"
target_object: "T1090"
stix_relationship_id: "relationship--62d56cae-9131-4088-ad0a-810a731d2a9f"
---
# Relationship 7382: S1081 — uses → T1090

**Source object:** [[01 ATT&CK/S1081 - BADHATCH|S1081: BADHATCH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADHATCH](https://attack.mitre.org/software/S1081) can use SOCKS4 and SOCKS5 proxies to connect to actor-controlled C2 servers. [BADHATCH](https://attack.mitre.org/software/S1081) can also emulate a reverse proxy on a compromised machine to connect with actor-controlled C2 servers.(Citation: BitDefender BADHATCH Mar 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62d56cae-9131-4088-ad0a-810a731d2a9f`.
