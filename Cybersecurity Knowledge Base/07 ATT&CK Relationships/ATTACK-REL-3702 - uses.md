---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0048"
target_object: "T1190"
stix_relationship_id: "relationship--5debdfdd-fe10-4872-a8a2-63309c28d309"
---
# Relationship 3702: C0048 — uses → T1190

**Source object:** [[01 ATT&CK/C0048 - Operation MidnightEclipse|C0048: Operation MidnightEclipse]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation MidnightEclipse](https://attack.mitre.org/campaigns/C0048), threat actors exploited CVE-2024-3400 in Palo Alto Networks GlobalProtect.(Citation: Volexity UPSTYLE 2024)(Citation: Palo Alto MidnightEclipse APR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5debdfdd-fe10-4872-a8a2-63309c28d309`.
