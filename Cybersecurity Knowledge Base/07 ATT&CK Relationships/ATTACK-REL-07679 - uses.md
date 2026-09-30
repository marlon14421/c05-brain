---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9037"
target_object: "T1684.001"
stix_relationship_id: "relationship--09bef668-b821-4228-adb3-35a4605ac3e9"
---
# Relationship 7679: S9037 — uses → T1684.001

**Source object:** [[01 ATT&CK/S9037 - RustyWater|S9037: RustyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RustyWater](https://attack.mitre.org/software/S9037) has impersonated TMCell (Altyn Asyr CJSC), the primary mobile operator in Turkmenistan, sending phishing emails with the email domain `info@tmcell`.(Citation: CloudSEK_RustyWater_Jan2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--09bef668-b821-4228-adb3-35a4605ac3e9`.
