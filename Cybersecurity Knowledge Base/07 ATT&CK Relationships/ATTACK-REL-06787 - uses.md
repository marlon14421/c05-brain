---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0281"
target_object: "T1553.004"
stix_relationship_id: "relationship--97c225e6-64ad-42af-8cc4-4fb4deea39fc"
---
# Relationship 6787: S0281 — uses → T1553.004

**Source object:** [[01 ATT&CK/S0281 - Dok|S0281: Dok]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.004 - Install Root Certificate|T1553.004: Install Root Certificate]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dok](https://attack.mitre.org/software/S0281) installs a root certificate to aid in [Adversary-in-the-Middle](https://attack.mitre.org/techniques/T1557) actions using the command add-trusted-cert -d -r trustRoot -k /Library/Keychains/System.keychain /tmp/filename .(Citation: objsee mac malware 2017)(Citation: hexed osx.dok analysis 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97c225e6-64ad-42af-8cc4-4fb4deea39fc`.
