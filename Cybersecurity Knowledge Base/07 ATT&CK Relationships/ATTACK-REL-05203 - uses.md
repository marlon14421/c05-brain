---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0053"
target_object: "T1550.003"
stix_relationship_id: "relationship--02a7ea5c-695c-4932-9160-6e0441789670"
---
# Relationship 5203: S0053 — uses → T1550.003

**Source object:** [[01 ATT&CK/S0053 - SeaDuke|S0053: SeaDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550.003 - Pass the Ticket|T1550.003: Pass the Ticket]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some [SeaDuke](https://attack.mitre.org/software/S0053) samples have a module to use pass the ticket with Kerberos for authentication.(Citation: Symantec Seaduke 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02a7ea5c-695c-4932-9160-6e0441789670`.
