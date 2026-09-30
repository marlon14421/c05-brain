---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0402"
target_object: "T1222.002"
stix_relationship_id: "relationship--544cc12a-53c4-4a56-b480-bfc79beee93c"
---
# Relationship 5834: S0402 — uses → T1222.002

**Source object:** [[01 ATT&CK/S0402 - OSX-Shlayer|S0402: OSX/Shlayer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1222.002 - Linux and Mac Permissions|T1222.002: Linux and Mac Permissions]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX/Shlayer](https://attack.mitre.org/software/S0402) can use the chmod utility to set a file as executable, such as chmod 777 or chmod +x .(Citation: 20 macOS Common Tools and Techniques)(Citation: Carbon Black Shlayer Feb 2019)(Citation: Shlayer jamf gatekeeper bypass 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--544cc12a-53c4-4a56-b480-bfc79beee93c`.
