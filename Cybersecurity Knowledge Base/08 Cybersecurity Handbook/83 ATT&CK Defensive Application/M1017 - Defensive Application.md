---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1017"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1017: User Training — Defensive Application

## Source record

- [[01 ATT&CK/M1017 - User Training|M1017 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

User Training involves educating employees and contractors on recognizing, reporting, and preventing cyber threats that rely on human interaction, such as phishing, social engineering, and other manipulative techniques. Comprehensive training programs create a human firewall by empowering users to be an active component of the organization's cybersecurity defenses. This mitigation can be implemented through the following measures: Create Comprehensive Training Programs: - Design training modules tailored to the organization's risk profile, covering topics such as phishing, password management, and incident reporting. - Provide role-specific training for high-risk employees, such as helpdesk staff or executives. Use Simulated Exercises: - Conduct phishing simulations to measure user susceptibility and provide targeted follow-up training. - Run social engineering drills to evaluate employee responses and reinforce protocols. Leverage Gamification and Engagement: - Introduce interactive learning methods such as quizzes, gamified challenges, and rewards for successful detection and reporting of threats. Incorporate Security Policies into Onboarding: - Include cybersecurity training as part of the onboarding process for new employees. - Provide easy-to-understand materials outlining acceptable use policies and reporting procedures. Regular Refresher Courses: - Update training materials to include emerging threats and techniques used by adversaries. - Ensure all employees complete periodic refresher courses to stay informed. Emphasize Real-World Scenarios: - Use case studies of recent attacks to demonstrate the consequences of successful phishing or social engineering. - Discuss how specific employee actions can prevent or mitigate such attacks.

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
