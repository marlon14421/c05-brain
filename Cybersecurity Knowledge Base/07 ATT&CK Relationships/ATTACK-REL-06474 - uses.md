---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0089"
target_object: "T1552.001"
stix_relationship_id: "relationship--aec49e52-c54e-45be-a476-70aa0dc42cfb"
---
# Relationship 6474: S0089 — uses → T1552.001

**Source object:** [[01 ATT&CK/S0089 - BlackEnergy|S0089: BlackEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackEnergy](https://attack.mitre.org/software/S0089) has used a plug-in to gather credentials stored in files on the host by various software programs, including The Bat! email client, Outlook, and Windows Credential Store.(Citation: F-Secure BlackEnergy 2014)(Citation: Securelist BlackEnergy Nov 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aec49e52-c54e-45be-a476-70aa0dc42cfb`.
