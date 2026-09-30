---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1677"
stix_relationship_id: "relationship--2f8d7b68-5278-4972-aec7-2b60fdfb5271"
---
# Relationship 7471: S9008 — uses → T1677

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1677 - Poisoned Pipeline Execution|T1677: Poisoned Pipeline Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has also leveraged GitHub actions from stolen accounts in order to create a malicious Github workflow within `.github/workflows/discussion.yaml`.(Citation: Aikido Shai-Hulud September 2025)(Citation: Netskope Shai-Hulud November 2025)(Citation: Palo Alto Unit 42 Shai-Hulud November 2025)(Citation: Socket Shai-Hulud November 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f8d7b68-5278-4972-aec7-2b60fdfb5271`.
