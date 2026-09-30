---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1246"
target_object: "T1555.003"
stix_relationship_id: "relationship--0cba3f24-f1b0-4184-afd4-f7bd3d34c49b"
---
# Relationship 3402: S1246 — uses → T1555.003

**Source object:** [[01 ATT&CK/S1246 - BeaverTail|S1246: BeaverTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BeaverTail](https://attack.mitre.org/software/S1246) has stolen passwords saved in web browsers.(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)(Citation: Socket HexEval BeaverTail Contagious Interview June 2025)(Citation: PaloAlto Unit42 ContagiousInterview BeaverTail InvisibileFerret October 2024) [BeaverTail](https://attack.mitre.org/software/S1246) has also been known to collect login data from Firefox within key3.db, key4.db and logins.json from `/.mozilla/firefox/` for exfiltration.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cba3f24-f1b0-4184-afd4-f7bd3d34c49b`.
