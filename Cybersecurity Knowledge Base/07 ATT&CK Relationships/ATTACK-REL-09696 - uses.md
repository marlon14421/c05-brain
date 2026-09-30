---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0268"
target_object: "T1497"
stix_relationship_id: "relationship--20dfecf8-b324-4584-9526-9de6a14dfa27"
---
# Relationship 9696: S0268 — uses → T1497

**Source object:** [[01 ATT&CK/S0268 - Bisonal|S0268: Bisonal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bisonal](https://attack.mitre.org/software/S0268) can check to determine if the compromised system is running on VMware.(Citation: Talos Bisonal Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20dfecf8-b324-4584-9526-9de6a14dfa27`.
