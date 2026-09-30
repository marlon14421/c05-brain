---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1078.004"
stix_relationship_id: "relationship--619c6c5c-fd82-4d38-b55b-b7eb0678cda7"
---
# Relationship 7644: S9008 — uses → T1078.004

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has leveraged compromised accounts to log into cloud services to access cloud hosted repositories.(Citation: Aikido Shai-Hulud September 2025)(Citation: Netskope Shai-Hulud November 2025)(Citation: Palo Alto Unit 42 Shai-Hulud November 2025)(Citation: Wiz Shai-Hulud September 2025)(Citation: Microsoft Shai-Hulud December 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--619c6c5c-fd82-4d38-b55b-b7eb0678cda7`.
