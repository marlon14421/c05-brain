---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0629"
target_object: "T1090"
stix_relationship_id: "relationship--a01e0e7c-1694-4a6a-8fea-4d4d8a83e034"
---
# Relationship 5722: S0629 — uses → T1090

**Source object:** [[01 ATT&CK/S0629 - RainyDay|S0629: RainyDay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RainyDay](https://attack.mitre.org/software/S0629) can use proxy tools including boost_proxy_client for reverse proxy functionality.(Citation: Bitdefender Naikon April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a01e0e7c-1694-4a6a-8fea-4d4d8a83e034`.
