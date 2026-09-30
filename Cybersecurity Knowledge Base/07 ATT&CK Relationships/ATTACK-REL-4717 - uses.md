---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0482"
target_object: "T1027"
stix_relationship_id: "relationship--885c54e7-6b1c-4399-a051-1e0b047d6f92"
---
# Relationship 4717: S0482 — uses → T1027

**Source object:** [[01 ATT&CK/S0482 - Bundlore|S0482: Bundlore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bundlore](https://attack.mitre.org/software/S0482) has obfuscated data with base64, AES, RC4, and bz2.(Citation: MacKeeper Bundlore Apr 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--885c54e7-6b1c-4399-a051-1e0b047d6f92`.
