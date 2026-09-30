---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0382"
target_object: "T1098.007"
stix_relationship_id: "relationship--e5a4c386-e9c0-4b59-b1da-1acfece17977"
---
# Relationship 5812: S0382 — uses → T1098.007

**Source object:** [[01 ATT&CK/S0382 - ServHelper|S0382: ServHelper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.007 - Additional Local or Domain Groups|T1098.007: Additional Local or Domain Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ServHelper](https://attack.mitre.org/software/S0382) has added a user named "supportaccount" to the Remote Desktop Users and Administrators groups.(Citation: Proofpoint TA505 Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e5a4c386-e9c0-4b59-b1da-1acfece17977`.
