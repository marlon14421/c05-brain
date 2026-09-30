---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1553.002"
stix_relationship_id: "relationship--bee27cd8-cc88-4c96-9709-b0398d7d18bc"
---
# Relationship 8648: G0129 — uses → T1553.002

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has used valid legitimate digital signatures and certificates to evade detection.(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)(Citation: Lab52 MUSTANG PANDA PUBLOAD MAY 2023)(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)(Citation: Unit42 Bookworm Nov2015)(Citation: Palo Alto Networks, Unit 42)(Citation: Sophos PlugX September 2022)(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)(Citation: Zscaler)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bee27cd8-cc88-4c96-9709-b0398d7d18bc`.
