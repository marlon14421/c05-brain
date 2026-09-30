---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0022"
target_object: "T1584.001"
stix_relationship_id: "relationship--2c095f1e-211d-4e84-b521-9cef12f1e83f"
---
# Relationship 7229: C0022 — uses → T1584.001

**Source object:** [[01 ATT&CK/C0022 - Operation Dream Job|C0022: Operation Dream Job]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.001 - Domains|T1584.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Dream Job](https://attack.mitre.org/campaigns/C0022), [Lazarus Group](https://attack.mitre.org/groups/G0032) compromised domains in Italy and other countries for their C2 infrastructure.(Citation: McAfee Lazarus Jul 2020)(Citation: McAfee Lazarus Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c095f1e-211d-4e84-b521-9cef12f1e83f`.
