---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0587"
target_object: "T1205"
stix_relationship_id: "relationship--5488dd31-2a28-4250-89ff-963214f46b92"
---
# Relationship 9901: S0587 — uses → T1205

**Source object:** [[01 ATT&CK/S0587 - Penquin|S0587: Penquin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Penquin](https://attack.mitre.org/software/S0587) will connect to C2 only after sniffing a "magic packet" value in TCP or UDP packets matching specific conditions.(Citation: Leonardo Turla Penquin May 2020)(Citation: Kaspersky Turla Penquin December 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5488dd31-2a28-4250-89ff-963214f46b92`.
