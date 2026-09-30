---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0022"
target_object: "T1090.002"
stix_relationship_id: "relationship--4f76fd4d-a638-41a0-90b9-bd4ada6f93f3"
---
# Relationship 6419: G0022 — uses → T1090.002

**Source object:** [[01 ATT&CK/G0022 - APT3|G0022: APT3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

An [APT3](https://attack.mitre.org/groups/G0022) downloader establishes SOCKS5 connections for its initial C2.(Citation: FireEye Operation Double Tap)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f76fd4d-a638-41a0-90b9-bd4ada6f93f3`.
