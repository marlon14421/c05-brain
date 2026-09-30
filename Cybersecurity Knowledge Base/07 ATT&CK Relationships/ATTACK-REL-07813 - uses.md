---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0382"
target_object: "T1053.005"
stix_relationship_id: "relationship--d535f0e8-dc89-448c-828d-7464767a51a3"
---
# Relationship 7813: S0382 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0382 - ServHelper|S0382: ServHelper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ServHelper](https://attack.mitre.org/software/S0382) contains modules that will use [schtasks](https://attack.mitre.org/software/S0111) to carry out malicious operations.(Citation: Proofpoint TA505 Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d535f0e8-dc89-448c-828d-7464767a51a3`.
