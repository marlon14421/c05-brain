---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1071.001"
stix_relationship_id: "relationship--87f45aac-1025-4a44-af9c-db139ea60f78"
---
# Relationship 7602: G0007 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Later implants used by [APT28](https://attack.mitre.org/groups/G0007), such as [CHOPSTICK](https://attack.mitre.org/software/S0023), use a blend of HTTP, HTTPS, and other legitimate channels for C2, depending on module configuration.(Citation: FireEye APT28)(Citation: Cybersecurity Advisory GRU Brute Force Campaign July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87f45aac-1025-4a44-af9c-db139ea60f78`.
