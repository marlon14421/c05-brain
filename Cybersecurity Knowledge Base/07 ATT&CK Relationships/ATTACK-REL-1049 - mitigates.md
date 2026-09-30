---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1046"
target_object: "T1542.001"
stix_relationship_id: "relationship--0ee07cbe-2ff1-4ea9-8a72-c83a67ce4bba"
---
# Relationship 1049: M1046 — mitigates → T1542.001

**Source object:** [[01 ATT&CK/M1046 - Boot Integrity|M1046: Boot Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1542.001 - System Firmware|T1542.001: System Firmware]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Check the integrity of the existing BIOS or EFI to determine if it is vulnerable to modification. Use Trusted Platform Module technology. (Citation: TCG Trusted Platform Module) Move system's root of trust to hardware to prevent tampering with the SPI flash memory.(Citation: ESET LoJax Sept 2018) Technologies such as Intel Boot Guard can assist with this. (Citation: Intel Hardware-based Security Technologies)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ee07cbe-2ff1-4ea9-8a72-c83a67ce4bba`.
