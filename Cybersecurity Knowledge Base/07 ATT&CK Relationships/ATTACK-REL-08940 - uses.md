---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1167"
target_object: "T1083"
stix_relationship_id: "relationship--d67b8cc9-00e4-4f9b-8771-03a34739e01b"
---
# Relationship 8940: S1167 — uses → T1083

**Source object:** [[01 ATT&CK/S1167 - AcidPour|S1167: AcidPour]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AcidPour](https://attack.mitre.org/software/S1167) can identify specific files and directories within the Linux operating system corresponding with storage devices for follow-on wiping activity, similar to [AcidRain](https://attack.mitre.org/software/S1125).(Citation: SentinelOne AcidPour 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d67b8cc9-00e4-4f9b-8771-03a34739e01b`.
