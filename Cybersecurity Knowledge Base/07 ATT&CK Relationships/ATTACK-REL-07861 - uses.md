---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0281"
target_object: "T1048.003"
stix_relationship_id: "relationship--96667f6c-e625-4696-92b5-d65d142b3f43"
---
# Relationship 7861: S0281 — uses → T1048.003

**Source object:** [[01 ATT&CK/S0281 - Dok|S0281: Dok]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dok](https://attack.mitre.org/software/S0281) exfiltrates logs of its execution stored in the /tmp folder over FTP using the curl command.(Citation: hexed osx.dok analysis 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96667f6c-e625-4696-92b5-d65d142b3f43`.
