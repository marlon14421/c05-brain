---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1078"
target_object: "T1037"
stix_relationship_id: "relationship--6a1d81fb-2a8e-44d4-a827-9b0c5e41d078"
---
# Relationship 5016: S1078 — uses → T1037

**Source object:** [[01 ATT&CK/S1078 - RotaJakiro|S1078: RotaJakiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1037 - Boot or Logon Initialization Scripts|T1037: Boot or Logon Initialization Scripts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Depending on the Linux distribution and when executing with root permissions, [RotaJakiro](https://attack.mitre.org/software/S1078) may install persistence using a `.conf` file in the `/etc/init/` folder.(Citation: RotaJakiro 2021 netlab360 analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a1d81fb-2a8e-44d4-a827-9b0c5e41d078`.
