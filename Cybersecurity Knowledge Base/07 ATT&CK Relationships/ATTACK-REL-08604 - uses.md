---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0482"
target_object: "T1098.004"
stix_relationship_id: "relationship--6723c87e-f60a-465f-96cd-78d63d17ba01"
---
# Relationship 8604: S0482 — uses → T1098.004

**Source object:** [[01 ATT&CK/S0482 - Bundlore|S0482: Bundlore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.004 - SSH Authorized Keys|T1098.004: SSH Authorized Keys]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bundlore](https://attack.mitre.org/software/S0482) creates a new key pair with ssh-keygen and drops the newly created user key in authorized_keys to enable remote login.(Citation: MacKeeper Bundlore Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6723c87e-f60a-465f-96cd-78d63d17ba01`.
