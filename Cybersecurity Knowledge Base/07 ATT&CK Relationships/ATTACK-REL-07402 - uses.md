---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0486"
target_object: "T1082"
stix_relationship_id: "relationship--34775b6e-f7dd-4b0f-bbb4-c696bfbda1c2"
---
# Relationship 7402: S0486 — uses → T1082

**Source object:** [[01 ATT&CK/S0486 - Bonadan|S0486: Bonadan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bonadan](https://attack.mitre.org/software/S0486) has discovered the OS version, CPU model, and RAM size of the system it has been installed on.(Citation: ESET ForSSHe December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--34775b6e-f7dd-4b0f-bbb4-c696bfbda1c2`.
