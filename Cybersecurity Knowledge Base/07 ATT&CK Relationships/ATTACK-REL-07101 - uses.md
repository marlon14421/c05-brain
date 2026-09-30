---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1059.001"
stix_relationship_id: "relationship--d37fac03-0b94-4794-b51a-e7db3d64294b"
---
# Relationship 7101: G0129 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has used malicious PowerShell scripts to enable execution.(Citation: Anomali MUSTANG PANDA October 2019)(Citation: Crowdstrike MUSTANG PANDA June 2018)(Citation: Unit42 Chinese VSCode 06 September 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d37fac03-0b94-4794-b51a-e7db3d64294b`.
