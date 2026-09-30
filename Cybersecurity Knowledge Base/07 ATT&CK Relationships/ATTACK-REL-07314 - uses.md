---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0482"
target_object: "T1082"
stix_relationship_id: "relationship--132c7780-3fa4-478b-b037-f2c1ad99d98f"
---
# Relationship 7314: S0482 — uses → T1082

**Source object:** [[01 ATT&CK/S0482 - Bundlore|S0482: Bundlore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bundlore](https://attack.mitre.org/software/S0482) will enumerate the macOS version to determine which follow-on behaviors to execute using /usr/bin/sw_vers -productVersion .(Citation: MacKeeper Bundlore Apr 2019)(Citation: 20 macOS Common Tools and Techniques)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--132c7780-3fa4-478b-b037-f2c1ad99d98f`.
