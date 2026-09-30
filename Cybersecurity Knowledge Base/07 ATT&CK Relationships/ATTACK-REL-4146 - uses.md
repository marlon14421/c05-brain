---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1555.003"
stix_relationship_id: "relationship--8117e136-627c-41bf-94ae-c99ff300c5a1"
---
# Relationship 4146: S1245 — uses → T1555.003

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has stolen login data, autofill data, cryptocurrency wallets, and payment information saved in web browsers such as Chrome, Brave, Opera, Yandex and Edge, to include versions affiliated with major operating systems on Windows, Linux, and macOS.(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025) [InvisibleFerret](https://attack.mitre.org/software/S1245) has also leveraged the command `ssh_zcp` to copy browser data to include extensions and cryptocurrency wallet data.(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8117e136-627c-41bf-94ae-c99ff300c5a1`.
