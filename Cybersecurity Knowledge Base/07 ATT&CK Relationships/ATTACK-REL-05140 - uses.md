---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0658"
target_object: "T1098.004"
stix_relationship_id: "relationship--5b6ff16b-9958-432c-bad9-5260d549117a"
---
# Relationship 5140: S0658 — uses → T1098.004

**Source object:** [[01 ATT&CK/S0658 - XCSSET|S0658: XCSSET]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.004 - SSH Authorized Keys|T1098.004: SSH Authorized Keys]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XCSSET](https://attack.mitre.org/software/S0658) will create an ssh key if necessary with the ssh-keygen -t rsa -f $HOME/.ssh/id_rsa -P command. [XCSSET](https://attack.mitre.org/software/S0658) will upload a private key file to the server to remotely access the host without a password.(Citation: trendmicro xcsset xcode project 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b6ff16b-9958-432c-bad9-5260d549117a`.
