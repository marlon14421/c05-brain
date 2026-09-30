---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0012"
target_object: "T1588.002"
stix_relationship_id: "relationship--5f3f6350-5e69-4b50-a0c7-c1f04ae85976"
---
# Relationship 7142: C0012 — uses → T1588.002

**Source object:** [[01 ATT&CK/C0012 - Operation CuckooBees|C0012: Operation CuckooBees]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation CuckooBees](https://attack.mitre.org/campaigns/C0012), the threat actors obtained publicly-available JSP code that was used to deploy a webshell onto a compromised server.(Citation: Cybereason OperationCuckooBees May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f3f6350-5e69-4b50-a0c7-c1f04ae85976`.
