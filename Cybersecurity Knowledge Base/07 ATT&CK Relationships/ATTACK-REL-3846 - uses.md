---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0436"
target_object: "T1083"
stix_relationship_id: "relationship--4b2baed3-8e3c-4ab6-9b92-f147a9ab7d13"
---
# Relationship 3846: S0436 — uses → T1083

**Source object:** [[01 ATT&CK/S0436 - TSCookie|S0436: TSCookie]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TSCookie](https://attack.mitre.org/software/S0436) has the ability to discover drive information on the infected host.(Citation: JPCert TSCookie March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b2baed3-8e3c-4ab6-9b92-f147a9ab7d13`.
