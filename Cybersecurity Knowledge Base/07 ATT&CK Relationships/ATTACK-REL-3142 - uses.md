---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1486"
stix_relationship_id: "relationship--89b2422c-6b9a-479c-bb07-52e73967066a"
---
# Relationship 3142: S1242 — uses → T1486

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) can use AES-256 or ChaCha20 for domain-wide encryption of victim servers and workstations and RSA-4096 or RSA-2048 to secure generated encryption keys.(Citation: Trend Micro Agenda Ransomware AUG 2022)(Citation: SentinelOne Qilin NOV 2022)(Citation: Picus Qilin MAR 2025)(Citation: BushidoToken Qilin RaaS JUN 2024)(Citation: Halcyon Qilin.B OCT 2024)(Citation: HC3 Qilin Threat Profile JUN 2024)(Citation: Trend Micro Agenda Ransomware OCT 2025)(Citation: Cisco Talos Qilin Ransomware OCT 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--89b2422c-6b9a-479c-bb07-52e73967066a`.
