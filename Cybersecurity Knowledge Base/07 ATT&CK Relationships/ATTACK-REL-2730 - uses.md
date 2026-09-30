---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0477"
target_object: "T1027.016"
stix_relationship_id: "relationship--6bf3a83b-d66d-4b6a-972c-c348686ebecb"
---
# Relationship 2730: S0477 — uses → T1027.016

**Source object:** [[01 ATT&CK/S0477 - Goopy|S0477: Goopy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.016 - Junk Code Insertion|T1027.016: Junk Code Insertion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Goopy](https://attack.mitre.org/software/S0477)'s decrypter have been inflated with junk code in between legitimate API functions, and also included infinite loops to avoid analysis.(Citation: Cybereason Cobalt Kitty 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6bf3a83b-d66d-4b6a-972c-c348686ebecb`.
