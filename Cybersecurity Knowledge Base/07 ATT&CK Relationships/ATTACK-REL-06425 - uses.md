---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0368"
target_object: "T1083"
stix_relationship_id: "relationship--7c958b31-ef21-4231-9a8f-a66cb7db3355"
---
# Relationship 6425: S0368 — uses → T1083

**Source object:** [[01 ATT&CK/S0368 - NotPetya|S0368: NotPetya]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NotPetya](https://attack.mitre.org/software/S0368) searches for files ending with dozens of different file extensions prior to encryption.(Citation: US District Court Indictment GRU Unit 74455 October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7c958b31-ef21-4231-9a8f-a66cb7db3355`.
