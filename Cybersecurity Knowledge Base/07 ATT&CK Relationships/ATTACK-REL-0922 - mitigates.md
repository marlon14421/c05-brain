---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1547.006"
stix_relationship_id: "relationship--b783f90e-bd7c-4513-b15a-731637d7078d"
---
# Relationship 0922: M1038 — mitigates → T1547.006

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.006 - Kernel Modules and Extensions|T1547.006: Kernel Modules and Extensions]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Application control and software restriction tools, such as SELinux, KSPP, grsecurity MODHARDEN, and Linux kernel tuning can aid in restricting kernel module loading.(Citation: Kernel.org Restrict Kernel Module)(Citation: Wikibooks Grsecurity)(Citation: Kernel Self Protection Project)(Citation: Increasing Linux kernel integrity)(Citation: LKM loading kernel restrictions)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b783f90e-bd7c-4513-b15a-731637d7078d`.
