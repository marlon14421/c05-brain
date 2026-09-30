---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0242"
target_object: "T1055.013"
stix_relationship_id: "relationship--41ac0542-9215-466a-ba43-05bd8b9e330b"
---
# Relationship 9056: S0242 — uses → T1055.013

**Source object:** [[01 ATT&CK/S0242 - SynAck|S0242: SynAck]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.013 - Process Doppelgänging|T1055.013: Process Doppelgänging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SynAck](https://attack.mitre.org/software/S0242) abuses NTFS transactions to launch and conceal malicious processes.(Citation: SecureList SynAck Doppelgänging May 2018)(Citation: Kaspersky Lab SynAck May 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41ac0542-9215-466a-ba43-05bd8b9e330b`.
