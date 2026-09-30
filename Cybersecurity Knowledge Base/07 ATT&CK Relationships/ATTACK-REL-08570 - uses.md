---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0108"
target_object: "T1090"
stix_relationship_id: "relationship--4c26e6e8-8303-44ad-9e5d-452dff52858f"
---
# Relationship 8570: G0108 — uses → T1090

**Source object:** [[01 ATT&CK/G0108 - Blue Mockingbird|G0108: Blue Mockingbird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used [FRP](https://attack.mitre.org/software/S1144), ssf, and Venom to establish SOCKS proxy connections.(Citation: RedCanary Mockingbird May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c26e6e8-8303-44ad-9e5d-452dff52858f`.
