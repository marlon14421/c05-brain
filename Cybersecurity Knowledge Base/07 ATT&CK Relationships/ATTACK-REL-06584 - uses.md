---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1046"
target_object: "T1056"
stix_relationship_id: "relationship--58c773e3-a31b-4562-83a5-815cf958b6be"
---
# Relationship 6584: G1046 — uses → T1056

**Source object:** [[01 ATT&CK/G1046 - Storm-1811|G1046: Storm-1811]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056 - Input Capture|T1056: Input Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-1811](https://attack.mitre.org/groups/G1046) has used a PowerShell script to capture user credentials after prompting a user to authenticate to run a malicious script masquerading as a legitimate update item.(Citation: rapid7-email-bombing)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--58c773e3-a31b-4562-83a5-815cf958b6be`.
