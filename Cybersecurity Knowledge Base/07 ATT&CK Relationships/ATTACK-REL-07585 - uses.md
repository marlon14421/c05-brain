---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0402"
target_object: "T1082"
stix_relationship_id: "relationship--9db842bf-d65d-44a8-93ca-aef62cadafc1"
---
# Relationship 7585: S0402 — uses → T1082

**Source object:** [[01 ATT&CK/S0402 - OSX-Shlayer|S0402: OSX/Shlayer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX/Shlayer](https://attack.mitre.org/software/S0402) has collected the IOPlatformUUID, session UID, and the OS version using the command sw_vers -productVersion .(Citation: Carbon Black Shlayer Feb 2019)(Citation: sentinelone shlayer to zshlayer)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9db842bf-d65d-44a8-93ca-aef62cadafc1`.
