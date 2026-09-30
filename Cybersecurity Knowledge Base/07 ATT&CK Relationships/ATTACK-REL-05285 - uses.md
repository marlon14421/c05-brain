---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0016"
target_object: "T1583.001"
stix_relationship_id: "relationship--4f1793cb-51f9-47d0-a2a7-374a57f56b82"
---
# Relationship 5285: C0016 — uses → T1583.001

**Source object:** [[01 ATT&CK/C0016 - Operation Dust Storm|C0016: Operation Dust Storm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Dust Storm](https://attack.mitre.org/campaigns/C0016), the threat actors established domains as part of their operational infrastructure.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f1793cb-51f9-47d0-a2a7-374a57f56b82`.
