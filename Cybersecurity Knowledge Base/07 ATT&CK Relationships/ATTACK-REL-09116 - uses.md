---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0010"
target_object: "T1018"
stix_relationship_id: "relationship--b8a1739d-240b-46c1-a25a-b82d1c4e4765"
---
# Relationship 9116: G0010 — uses → T1018

**Source object:** [[01 ATT&CK/G0010 - Turla|G0010: Turla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Turla](https://attack.mitre.org/groups/G0010) surveys a system upon check-in to discover remote systems on a local network using the net view and net view /DOMAIN commands. [Turla](https://attack.mitre.org/groups/G0010) has also used net group "Domain Computers" /domain , net group "Domain Controllers" /domain , and net group "Exchange Servers" /domain to enumerate domain computers, including the organization's DC and Exchange Server.(Citation: Kaspersky Turla)(Citation: ESET ComRAT May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b8a1739d-240b-46c1-a25a-b82d1c4e4765`.
