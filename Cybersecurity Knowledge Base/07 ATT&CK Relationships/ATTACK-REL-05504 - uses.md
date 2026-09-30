---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0283"
target_object: "T1552.001"
stix_relationship_id: "relationship--c1108137-b707-4358-b4b2-b2f139418f7e"
---
# Relationship 5504: S0283 — uses → T1552.001

**Source object:** [[01 ATT&CK/S0283 - jRAT|S0283: jRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[jRAT](https://attack.mitre.org/software/S0283) can capture passwords from common chat applications such as MSN Messenger, AOL, Instant Messenger, and and Google Talk.(Citation: Kaspersky Adwind Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1108137-b707-4358-b4b2-b2f139418f7e`.
