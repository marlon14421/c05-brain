---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0369"
target_object: "T1059.006"
stix_relationship_id: "relationship--b85862ff-5bde-4f6e-8483-901bab69a3a2"
---
# Relationship 7189: S0369 — uses → T1059.006

**Source object:** [[01 ATT&CK/S0369 - CoinTicker|S0369: CoinTicker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CoinTicker](https://attack.mitre.org/software/S0369) executes a Python script to download its second stage.(Citation: CoinTicker 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b85862ff-5bde-4f6e-8483-901bab69a3a2`.
