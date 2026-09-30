---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "T1071.001"
stix_relationship_id: "relationship--79057890-3cd0-4124-8b35-b86db6b4f9d7"
---
# Relationship 5872: G0050 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT32](https://attack.mitre.org/groups/G0050) has used JavaScript that communicates over HTTP or HTTPS to attacker controlled domains to download additional frameworks. The group has also used downloaded encrypted payloads over HTTP.(Citation: Volexity OceanLotus Nov 2017)(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79057890-3cd0-4124-8b35-b86db6b4f9d7`.
