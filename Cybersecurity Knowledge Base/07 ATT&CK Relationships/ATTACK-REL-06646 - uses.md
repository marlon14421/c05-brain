---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1161"
target_object: "T1564.011"
stix_relationship_id: "relationship--7b979855-6b0e-4230-b940-d57d35787cbf"
---
# Relationship 6646: S1161 — uses → T1564.011

**Source object:** [[01 ATT&CK/S1161 - BPFDoor|S1161: BPFDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.011 - Ignore Process Interrupts|T1564.011: Ignore Process Interrupts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BPFDoor](https://attack.mitre.org/software/S1161) sets its process to ignore the following signals; `SIGHUP`, `SIGINT`, `SIGQUIT`, `SIGPIPE`, `SIGCHLD`, `SIGTTIN`, and `SIGTTOU`.(Citation: Deep Instinct BPFDoor 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b979855-6b0e-4230-b940-d57d35787cbf`.
