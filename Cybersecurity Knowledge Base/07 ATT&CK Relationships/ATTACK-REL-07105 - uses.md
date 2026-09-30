---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1059.007"
stix_relationship_id: "relationship--4677c432-d537-4d61-bc25-efe1b608c378"
---
# Relationship 7105: G1057 — uses → T1059.007

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has used the MeshCentral command-line interface utility meshctrl.js and npm to interact with compromised systems. Specifically for npm, [ShinyHunters](https://attack.mitre.org/groups/G1057) has checked for the authenticode tool using the command `npm list global authenticode`.(Citation: Google_SHOracle_Jun2026) Additionally, [ShinyHunters](https://attack.mitre.org/groups/G1057) has used the MeshCentral command to execute the propagation script: ` node meshctrl.js RunCommand --loginuser admin --loginpass '[password]' --id '[agent_id]' --run 'bash /tmp/[victim_abbreviation]_fanout.sh' `.(Citation: Google_SHOracle_Jun2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4677c432-d537-4d61-bc25-efe1b608c378`.
