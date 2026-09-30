---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9015"
target_object: "T1572"
stix_relationship_id: "relationship--867a8718-5f12-42db-8fa7-667d51d868be"
---
# Relationship 2672: S9015 — uses → T1572

**Source object:** [[01 ATT&CK/S9015 - BRICKSTORM|S9015: BRICKSTORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) has utilized a SOCKS proxy to tunnel access within the victim network and exfiltrate files from internal shares, code repositories, and other endpoints.(Citation: CrowdStrike BRICKSTORM WARP PANDA UNC5221 December 2025)(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Picus Security BRICKSTORM UNC5221 October 2025)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)(Citation: NVISO BRICKSTORM April 2025)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)(Citation: Google BRICKSTORM September 2025) [BRICKSTORM](https://attack.mitre.org/software/S9015) has also leveraged Yamux for combining multiple concurrent logical streams over a single a socket.(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: NVISO BRICKSTORM April 2025)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--867a8718-5f12-42db-8fa7-667d51d868be`.
