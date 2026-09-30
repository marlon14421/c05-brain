---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0019"
target_object: "T1518.001"
stix_relationship_id: "relationship--2e77d363-e38f-40ad-a6ef-9222dc12793d"
---
# Relationship 5379: G0019 — uses → T1518.001

**Source object:** [[01 ATT&CK/G0019 - Naikon|G0019: Naikon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Naikon](https://attack.mitre.org/groups/G0019) uses commands such as netsh advfirewall firewall to discover local firewall settings.(Citation: Baumgartner Naikon 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e77d363-e38f-40ad-a6ef-9222dc12793d`.
