---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0106"
target_object: "T1037"
stix_relationship_id: "relationship--6b1cc49f-8d94-4f59-a723-2a70c3edf760"
---
# Relationship 9526: G0106 — uses → T1037

**Source object:** [[01 ATT&CK/G0106 - Rocke|G0106: Rocke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1037 - Boot or Logon Initialization Scripts|T1037: Boot or Logon Initialization Scripts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rocke](https://attack.mitre.org/groups/G0106) has installed an "init.d" startup script to maintain persistence.(Citation: Anomali Rocke March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b1cc49f-8d94-4f59-a723-2a70c3edf760`.
