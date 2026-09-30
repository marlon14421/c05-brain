---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1195.001"
stix_relationship_id: "relationship--e71858de-cf0c-4fc7-a253-988344f94ad3"
---
# Relationship 7022: S9043 — uses → T1195.001

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1195.001 - Compromise Software Dependencies and Development Tools|T1195.001: Compromise Software Dependencies and Development Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has published itself on compromised victim code repositories to propagate malicious versions of packages to other victims.(Citation: Trend Micro TeamPCP MAY 2026)(Citation: Flashpoint Mini Shai-Hulud MAY 2026)(Citation: Flashpoint Mini Shai-Hulud MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e71858de-cf0c-4fc7-a253-988344f94ad3`.
