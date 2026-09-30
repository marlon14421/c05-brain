---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0245"
target_object: "T1112"
stix_relationship_id: "relationship--7e559e10-483a-42ca-8ddf-d8ca04ed8bd2"
---
# Relationship 9395: S0245 — uses → T1112

**Source object:** [[01 ATT&CK/S0245 - BADCALL|S0245: BADCALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADCALL](https://attack.mitre.org/software/S0245) modifies the firewall Registry key SYSTEM\CurrentControlSet\Services\SharedAccess\Parameters\FirewallPolicy\StandardProfileGloballyOpenPorts\\List .(Citation: US-CERT BADCALL)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e559e10-483a-42ca-8ddf-d8ca04ed8bd2`.
