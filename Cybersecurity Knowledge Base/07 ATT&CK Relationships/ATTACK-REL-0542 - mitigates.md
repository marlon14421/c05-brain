---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1037"
target_object: "T1557.003"
stix_relationship_id: "relationship--265401e7-92fa-46ea-b5d3-e64c387f6a8d"
---
# Relationship 0542: M1037 — mitigates → T1557.003

**Source object:** [[01 ATT&CK/M1037 - Filter Network Traffic|M1037: Filter Network Traffic]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1557.003 - DHCP Spoofing|T1557.003: DHCP Spoofing]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider filtering DHCP traffic on ports 67 and 68 to/from unknown or untrusted DHCP servers. Additionally, port security may also be enabled on layer switches. Furthermore, consider enabling DHCP snooping on layer 2 switches as it will prevent DHCP spoofing attacks and starvation attacks. Consider tracking available IP addresses through a script or a tool. Additionally, block DHCPv6 traffic and incoming router advertisements, especially if IPv6 is not commonly used in the network.(Citation: ntlm_relaying_kerberos_del)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--265401e7-92fa-46ea-b5d3-e64c387f6a8d`.
