---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "T1205"
stix_relationship_id: "relationship--15c274dd-c045-43d6-a038-fa969dd04c8d"
---
# Relationship 5115: C0029 — uses → T1205

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Cutting Edge](https://attack.mitre.org/campaigns/C0029), threat actors sent a magic 48-byte sequence to enable the PITSOCK backdoor to communicate via the `/tmp/clientsDownload.sock` socket.(Citation: Mandiant Cutting Edge Part 3 February 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15c274dd-c045-43d6-a038-fa969dd04c8d`.
