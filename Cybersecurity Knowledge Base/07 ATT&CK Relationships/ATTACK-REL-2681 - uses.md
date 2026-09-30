---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9013"
target_object: "T1556"
stix_relationship_id: "relationship--c15efd63-269b-41c5-a664-cea3dff17c5f"
---
# Relationship 2681: S9013 — uses → T1556

**Source object:** [[01 ATT&CK/S9013 - DRYHOOK|S9013: DRYHOOK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1556 - Modify Authentication Process|T1556: Modify Authentication Process]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DRYHOOK](https://attack.mitre.org/software/S9013) has intercepted and logged user credentials by modifying the Perl module in Ivanti Connect Secure VPN edge-devices located within `/home/perl/DSAuth.pm`.(Citation: Google UNC5221 Ivanti January 2025)(Citation: Picus Security UNC5221 Ivanti May 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c15efd63-269b-41c5-a664-cea3dff17c5f`.
