---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9003"
target_object: "T1090.002"
stix_relationship_id: "relationship--a3a71677-e8d4-4d56-8429-50c3ec8fac85"
---
# Relationship 4357: S9003 — uses → T1090.002

**Source object:** [[01 ATT&CK/S9003 - evilginx2|S9003: evilginx2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[evilginx2](https://attack.mitre.org/software/S9003) can route traffic via SOCKS5 and HTTP(S) proxies between an intended phishing victim's machine and legitimate websites.(Citation: Evilginx 2 July 2018)(Citation: Breakdev Evilginx 2.4 SEP 2020)(Citation: Sophos Evilginx MAR 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3a71677-e8d4-4d56-8429-50c3ec8fac85`.
