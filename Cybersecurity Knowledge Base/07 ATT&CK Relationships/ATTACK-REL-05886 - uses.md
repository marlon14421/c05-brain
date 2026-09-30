---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1023"
target_object: "T1036.005"
stix_relationship_id: "relationship--ddb0965b-83ac-4746-bfaa-a7356691ef43"
---
# Relationship 5886: G1023 — uses → T1036.005

**Source object:** [[01 ATT&CK/G1023 - APT5|G1023: APT5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT5](https://attack.mitre.org/groups/G1023) has named exfiltration archives to mimic Windows Updates at times using filenames with a `KB .zip` pattern.(Citation: Mandiant Pulse Secure Update May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ddb0965b-83ac-4746-bfaa-a7356691ef43`.
