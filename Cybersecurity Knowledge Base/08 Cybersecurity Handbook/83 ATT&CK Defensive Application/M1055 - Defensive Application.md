---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1055"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1055: Do Not Mitigate — Defensive Application

## Source record

- [[01 ATT&CK/M1055 - Do Not Mitigate|M1055 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

The Do Not Mitigate category highlights scenarios where attempting to mitigate a specific technique may inadvertently increase the organization's security risk or operational instability. This could happen due to the complexity of the system, the integration of critical processes, or the potential for introducing new vulnerabilities. Instead of direct mitigation, these situations may call for alternative strategies such as detection, monitoring, or response. The Do Not Mitigate category underscores the importance of assessing the trade-offs between mitigation efforts and overall system integrity. This mitigation can be implemented through the following measures: Complex Systems Where Mitigation is Risky: - Interpretation: In certain systems, direct mitigation could introduce new risks, especially if the system is highly interconnected or complex, such as in legacy industrial control systems (ICS). Patching or modifying these systems could result in unplanned downtime, disruptions, or even safety risks. - Use Case: In a power grid control system, attempting to patch or disable certain services related to device communications might disrupt critical operations, leading to unintended service outages. Risk of Reducing Security Coverage: - Interpretation: In some cases, mitigating a technique might reduce the visibility or effectiveness of other security controls, limiting an organization’s ability to detect broader attacks. - Use Case: Disabling script execution on a web server to mitigate potential PowerShell-based attacks could interfere with legitimate administrative operations that rely on scripting, while attackers may still find alternate ways to execute code. Introduction of New Vulnerabilities: - Interpretation: In highly sensitive or tightly controlled environments, implementing certain mitigations might create vulnerabilities in other parts of the system. For instance, disabling default security mechanisms in an attempt to resolve compatibility issues may open the system to exploitation. - Use Case: Disabling certificate validation to resolve internal communication issues in a secure environment could lead to man-in-the-middle attacks, creating a greater vulnerability than the original problem. Negative Impact on Performance and Availability: - Interpretation: Mitigations that involve removing or restricting system functionalities can have unintended consequences for system performance and availability. Some mitigations, while effective at blocking certain attacks, may introduce performance bottlenecks or compromise essential operations. - Use Case: Implementing high levels of encryption to mitigate data theft might result in significant performance degradation in systems handling large volumes of real-time transactions.

## Defensive focus

Assess the control as an implementable safeguard with a defined owner, target population, configuration, exception path, and evidence of operation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets and versions support this control, and where are exceptions required?
- Does the control reduce the relevant exposure without disabling a legitimate business function?
- How is coverage measured and configuration drift detected?
- What compensating control applies where the primary safeguard is unavailable?
- What test demonstrates continued effectiveness after updates?

## Safe validation

Pilot configuration changes in a representative test group, obtain owner approval, and preserve a tested rollback plan. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
