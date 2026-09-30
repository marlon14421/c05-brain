---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1053"
target_object: "T1490"
stix_relationship_id: "relationship--f9e62f6d-a091-44a9-91e6-3660b89ba2b9"
---
# Relationship 0366: M1053 — mitigates → T1490

**Source object:** [[01 ATT&CK/M1053 - Data Backup|M1053: Data Backup]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider implementing IT disaster recovery plans that contain procedures for taking regular data backups that can be used to restore organizational data.(Citation: Ready.gov IT DRP) Ensure backups are stored off system and is protected from common methods adversaries may use to gain access and destroy the backups to prevent recovery. In cloud environments, enable versioning on storage objects where possible, and copy backups to other accounts or regions to isolate them from the original copies.(Citation: Unit 42 Palo Alto Ransomware in Public Clouds 2022) On ESXi servers, ensure that disk images and snapshots of virtual machines are regularly taken, with copies stored off system.(Citation: Crowdstrike Hypervisor Jackpotting Pt 2 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f9e62f6d-a091-44a9-91e6-3660b89ba2b9`.
