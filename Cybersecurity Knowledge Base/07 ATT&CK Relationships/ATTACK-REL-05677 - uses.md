---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1190"
target_object: "T1090"
stix_relationship_id: "relationship--be2fde8e-796c-4647-9351-edd9c97fe2b3"
---
# Relationship 5677: S1190 — uses → T1090

**Source object:** [[01 ATT&CK/S1190 - Kapeka|S1190: Kapeka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kapeka](https://attack.mitre.org/software/S1190) can identify system proxy settings via `WinHttpGetIEProxyConfigForCurrentUser()` during initialization and utilize these settings for subsequent command and control operations.(Citation: WithSecure Kapeka 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be2fde8e-796c-4647-9351-edd9c97fe2b3`.
