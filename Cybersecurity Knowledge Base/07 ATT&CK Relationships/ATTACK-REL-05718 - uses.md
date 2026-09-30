---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1552.001"
stix_relationship_id: "relationship--3cf857dc-8e89-487c-b339-68517594bfc7"
---
# Relationship 5718: S9043 — uses → T1552.001

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has collected credentials stored within configuration files.(Citation: Trend Micro TeamPCP MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026) [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has also gathered credentials from files stored in common credential file paths to include targeting git-credentials, azureProfile.json, and application_default_credentials.json.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)(Citation: Flashpoint Mini Shai-Hulud MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cf857dc-8e89-487c-b339-68517594bfc7`.
