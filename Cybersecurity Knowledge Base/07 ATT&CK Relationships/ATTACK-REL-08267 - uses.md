---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0071"
target_object: "T1059.003"
stix_relationship_id: "relationship--3ada7220-b5a6-45b9-a7ca-4a26423da831"
---
# Relationship 8267: S0071 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0071 - hcdLoader|S0071: hcdLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[hcdLoader](https://attack.mitre.org/software/S0071) provides command-line access to the compromised system.(Citation: Dell Lateral Movement)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ada7220-b5a6-45b9-a7ca-4a26423da831`.
