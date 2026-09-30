---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0185"
target_object: "T1505.003"
stix_relationship_id: "relationship--bbe37d7e-ad35-4c74-a57c-9a398ef6b1be"
---
# Relationship 5558: S0185 — uses → T1505.003

**Source object:** [[01 ATT&CK/S0185 - SEASHARPEE|S0185: SEASHARPEE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SEASHARPEE](https://attack.mitre.org/software/S0185) is a Web shell.(Citation: FireEye APT34 Webinar Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bbe37d7e-ad35-4c74-a57c-9a398ef6b1be`.
