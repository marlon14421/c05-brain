---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0283"
target_object: "T1016"
stix_relationship_id: "relationship--ef97d2bb-7e5a-4c3b-8e7d-cc4fb098c47d"
---
# Relationship 8191: S0283 — uses → T1016

**Source object:** [[01 ATT&CK/S0283 - jRAT|S0283: jRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[jRAT](https://attack.mitre.org/software/S0283) can gather victim internal and external IPs.(Citation: Kaspersky Adwind Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef97d2bb-7e5a-4c3b-8e7d-cc4fb098c47d`.
