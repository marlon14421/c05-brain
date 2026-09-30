---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9009"
target_object: "T1555.006"
stix_relationship_id: "relationship--7e7151b1-8407-4cac-a843-f2605fb25377"
---
# Relationship 9299: S9009 — uses → T1555.006

**Source object:** [[01 ATT&CK/S9009 - TruffleHog|S9009: TruffleHog]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.006 - Cloud Secrets Management Stores|T1555.006: Cloud Secrets Management Stores]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TruffleHog](https://attack.mitre.org/software/S9009) can obtain secrets from AWS Secrets and GCP Secret Manager.(Citation: Black Hills Information Security TruffleHog January 2024)(Citation: Github TruffleSecurity Trufflehog April 2025) [TruffleHog](https://attack.mitre.org/software/S9009) has also gathered passwords, secrets and API keys from source repositories, .env files, and git history.(Citation: Netskope Shai-Hulud November 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e7151b1-8407-4cac-a843-f2605fb25377`.
