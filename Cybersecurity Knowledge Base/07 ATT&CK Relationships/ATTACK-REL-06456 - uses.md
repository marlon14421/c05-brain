---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9013"
target_object: "T1056.001"
stix_relationship_id: "relationship--55b5ee19-4623-4c5d-9f8f-1c20a3263af6"
---
# Relationship 6456: S9013 — uses → T1056.001

**Source object:** [[01 ATT&CK/S9013 - DRYHOOK|S9013: DRYHOOK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRYHOOK](https://attack.mitre.org/software/S9013) has captured user credentials and passwords in plaintext and has encrypted them in a stored file on the network device.(Citation: Google UNC5221 Ivanti January 2025)(Citation: Picus Security UNC5221 Ivanti May 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--55b5ee19-4623-4c5d-9f8f-1c20a3263af6`.
