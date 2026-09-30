---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1614.001"
stix_relationship_id: "relationship--c4902c5f-62a8-4eb7-b86a-fb701ce8fc5f"
---
# Relationship 4955: G1053 — uses → T1614.001

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has identified system language codes on a compromised host to determine if the victim falls under a non-supported language code that is prohibited for targeting, including victims associated with Russia and other Commonwealth of Independent States (CIS) that may draw attention of law enforcement in countries where the ransomware operator or affiliates may reside/operate from.(Citation: Avertium Storm-0501 Sabbath Ransomware Arcane January 2022)(Citation: Google Mandiant Storm-0501 Sabbath Ransomware November 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4902c5f-62a8-4eb7-b86a-fb701ce8fc5f`.
