---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1547.009"
stix_relationship_id: "relationship--39080201-a56c-4daf-83b8-8ec09dd3baea"
---
# Relationship 0437: M1018 — mitigates → T1547.009

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.009 - Shortcut Modification|T1547.009: Shortcut Modification]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit Privileges for Shortcut Creation: While the SeCreateSymbolicLinkPrivilege is not directly related to .lnk file creation, you should still enforce least privilege principles by limiting user rights to create and modify shortcuts, especially in system-critical locations. This can be done through GPO: Computer Configuration > [Policies] > Windows Settings > Security Settings > Local Policies > User Rights Assignment: Create symbolic links. (Citation: UCF STIG Symbolic Links) Regular User Permissions Review: Regularly review and audit user permissions to ensure that only necessary accounts have write access to startup folders and critical system directories.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39080201-a56c-4daf-83b8-8ec09dd3baea`.
