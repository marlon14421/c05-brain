---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9003"
target_object: "T1185"
stix_relationship_id: "relationship--7641ab63-39e1-4cd2-8e9c-9bd1ce6da370"
---
# Relationship 6981: S9003 — uses → T1185

**Source object:** [[01 ATT&CK/S9003 - evilginx2|S9003: evilginx2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1185 - Browser Session Hijacking|T1185: Browser Session Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[evilginx2](https://attack.mitre.org/software/S9003) can inject custom POST arguments into requests to silently enable "Remember Me" options during authentication to stay logged in across browser sessions.(Citation: Breakdev Evilginx 2.2 NOV 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7641ab63-39e1-4cd2-8e9c-9bd1ce6da370`.
