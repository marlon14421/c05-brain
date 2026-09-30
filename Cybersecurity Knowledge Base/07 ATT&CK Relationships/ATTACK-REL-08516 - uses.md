---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0019"
target_object: "T1040"
stix_relationship_id: "relationship--fcfe071b-e527-44e9-9970-9243a354f563"
---
# Relationship 8516: S0019 — uses → T1040

**Source object:** [[01 ATT&CK/S0019 - Regin|S0019: Regin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Regin](https://attack.mitre.org/software/S0019) appears to have functionality to sniff for credentials passed over HTTP, SMTP, and SMB.(Citation: Kaspersky Regin)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fcfe071b-e527-44e9-9970-9243a354f563`.
