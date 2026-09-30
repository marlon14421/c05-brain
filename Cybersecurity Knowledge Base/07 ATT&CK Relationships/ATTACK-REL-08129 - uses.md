---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0412"
target_object: "T1190"
stix_relationship_id: "relationship--66fe07f5-fe08-4ad1-98b6-cb300007fe42"
---
# Relationship 8129: S0412 — uses → T1190

**Source object:** [[01 ATT&CK/S0412 - ZxShell|S0412: ZxShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZxShell](https://attack.mitre.org/software/S0412) has been dropped through exploitation of CVE-2011-2462, CVE-2013-3163, and CVE-2014-0322.(Citation: Talos ZxShell Oct 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66fe07f5-fe08-4ad1-98b6-cb300007fe42`.
