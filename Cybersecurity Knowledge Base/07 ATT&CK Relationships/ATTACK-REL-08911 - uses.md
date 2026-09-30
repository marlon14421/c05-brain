---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1178"
target_object: "T1102"
stix_relationship_id: "relationship--74ab1575-0934-4344-bfa7-7cf97015d5c5"
---
# Relationship 8911: S1178 — uses → T1102

**Source object:** [[01 ATT&CK/S1178 - ShrinkLocker|S1178: ShrinkLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShrinkLocker](https://attack.mitre.org/software/S1178) uses a subdomain on the legitimate Cloudflare resource "trycloudflare[.]com" to obfuscate the threat actor's actual address and to tunnel information sent from victim systems.(Citation: Kaspersky ShrinkLocker 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74ab1575-0934-4344-bfa7-7cf97015d5c5`.
