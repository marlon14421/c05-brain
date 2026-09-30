---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1031"
target_object: "T1059.001"
stix_relationship_id: "relationship--6c740f17-8419-4ee0-95ee-71b4ef5ab35b"
---
# Relationship 9227: G1031 — uses → T1059.001

**Source object:** [[01 ATT&CK/G1031 - Saint Bear|G1031: Saint Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Saint Bear](https://attack.mitre.org/groups/G1031) relies extensively on PowerShell execution from malicious attachments and related content to retrieve and execute follow-on payloads.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c740f17-8419-4ee0-95ee-71b4ef5ab35b`.
