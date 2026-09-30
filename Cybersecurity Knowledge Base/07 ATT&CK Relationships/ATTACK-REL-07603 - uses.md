---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "T1204.001"
stix_relationship_id: "relationship--788a6ca2-60ac-4f36-b708-c3a57f087b2b"
---
# Relationship 7603: G0050 — uses → T1204.001

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT32](https://attack.mitre.org/groups/G0050) has lured targets to download a Cobalt Strike beacon by including a malicious link within spearphishing emails.(Citation: Cybereason Cobalt Kitty 2017)(Citation: Volexity Ocean Lotus November 2020)(Citation: Amnesty Intl. Ocean Lotus February 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--788a6ca2-60ac-4f36-b708-c3a57f087b2b`.
