---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1218.011"
stix_relationship_id: "relationship--8f269f6c-9e8b-4296-ab47-2f60c9156b58"
---
# Relationship 4517: G0007 — uses → T1218.011

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) executed [CHOPSTICK](https://attack.mitre.org/software/S0023) by using rundll32 commands such as rundll32.exe “C:\Windows\twain_64.dll” . [APT28](https://attack.mitre.org/groups/G0007) also executed a .dll for a first stage dropper using rundll32.exe. An [APT28](https://attack.mitre.org/groups/G0007) loader Trojan saved a batch script that uses rundll32 to execute a DLL payload.(Citation: Crowdstrike DNC June 2016)(Citation: Bitdefender APT28 Dec 2015)(Citation: Palo Alto Sofacy 06-2018)(Citation: Unit 42 Playbook Dec 2017)(Citation: ESET Zebrocy May 2019)(Citation: Cybersecurity Advisory GRU Brute Force Campaign July 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f269f6c-9e8b-4296-ab47-2f60c9156b58`.
