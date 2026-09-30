---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9014"
target_object: "T1505.003"
stix_relationship_id: "relationship--8241e670-5d1a-4091-9ad0-99792d1dfe5b"
---
# Relationship 5939: S9014 — uses → T1505.003

**Source object:** [[01 ATT&CK/S9014 - PHASEJAM|S9014: PHASEJAM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PHASEJAM](https://attack.mitre.org/software/S9014) has inserted Perl-based web shells into legitimate files that provided threat actors with remote access and code execution capabilities on the compromised network appliance.(Citation: Google UNC5221 Ivanti January 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8241e670-5d1a-4091-9ad0-99792d1dfe5b`.
