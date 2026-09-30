---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1684.001"
stix_relationship_id: "relationship--fd3ff9c1-b745-44b1-8a28-3fb4a12134c7"
---
# Relationship 5712: G0007 — uses → T1684.001

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAMEHUG](https://attack.mitre.org/software/S9035) has sent spearphishing emails impersonating Ukrainian government officials. (Citation: Cato LAMEHUG JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd3ff9c1-b745-44b1-8a28-3fb4a12134c7`.
