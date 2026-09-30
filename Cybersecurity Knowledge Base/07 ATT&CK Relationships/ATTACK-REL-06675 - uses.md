---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1147"
target_object: "T1497.001"
stix_relationship_id: "relationship--8dc9ad2b-acae-4bd1-8c6b-02b0d6bc5c90"
---
# Relationship 6675: S1147 — uses → T1497.001

**Source object:** [[01 ATT&CK/S1147 - Nightdoor|S1147: Nightdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Nightdoor](https://attack.mitre.org/software/S1147) embeds code from the public `al-khaser` project, a repository that works to detect virtual machines, sandboxes, and malware analysis environments.(Citation: Symantec Daggerfly 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8dc9ad2b-acae-4bd1-8c6b-02b0d6bc5c90`.
