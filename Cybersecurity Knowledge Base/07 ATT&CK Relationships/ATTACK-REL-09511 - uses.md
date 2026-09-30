---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0363"
target_object: "T1134"
stix_relationship_id: "relationship--9bd9e08d-efda-4710-8158-9e915dce16d9"
---
# Relationship 9511: S0363 — uses → T1134

**Source object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Empire](https://attack.mitre.org/software/S0363) can use [PowerSploit](https://attack.mitre.org/software/S0194)'s Invoke-TokenManipulation to manipulate access tokens.(Citation: Github PowerShell Empire)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9bd9e08d-efda-4710-8158-9e915dce16d9`.
