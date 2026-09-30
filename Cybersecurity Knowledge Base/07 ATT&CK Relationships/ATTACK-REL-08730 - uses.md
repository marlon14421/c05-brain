---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9013"
target_object: "T1601"
stix_relationship_id: "relationship--75674204-4937-4d08-b61b-8bf01a9d4362"
---
# Relationship 8730: S9013 — uses → T1601

**Source object:** [[01 ATT&CK/S9013 - DRYHOOK|S9013: DRYHOOK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1601 - Modify System Image|T1601: Modify System Image]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRYHOOK](https://attack.mitre.org/software/S9013) has modified the Ivanti Connect Secure VPN authentication Perl module `DSAuth.pm` by reading its contents in the buffer, then finding and replacing select lines of code.(Citation: Google UNC5221 Ivanti January 2025)(Citation: Picus Security UNC5221 Ivanti May 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75674204-4937-4d08-b61b-8bf01a9d4362`.
