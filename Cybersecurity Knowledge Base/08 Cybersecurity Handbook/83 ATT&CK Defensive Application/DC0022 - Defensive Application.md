---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0022"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0022: Cloud Storage Deletion — Defensive Application

## Source record

- [[01 ATT&CK/DC0022 - Cloud Storage Deletion|DC0022 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Cloud Storage Deletion refers to the removal or destruction of cloud storage infrastructure, such as buckets, containers, or directories, within a cloud environment. Monitoring this activity is critical to detecting potential unauthorized or malicious actions, such as data destruction by adversaries or accidental deletions that may lead to data loss. Examples: - AWS S3 Bucket Deletion: An AWS user deletes an S3 bucket using the `DeleteBucket` API call. - Azure Blob Storage Container Deletion: A user deletes a container in Azure Blob Storage using the `Delete Container` operation. - Google Cloud Storage Bucket Deletion: A Google Cloud user deletes a bucket using the `storage.buckets.delete` API. - OpenStack Swift Container Deletion: A user deletes a container in OpenStack Swift using the `DELETE` method. This data component can be collected through the following measures: Enable Logging for Cloud Storage Services - AWS S3: Enable AWS CloudTrail to log DeleteBucket API actions. - Azure Blob Storage: Enable Azure Monitor and Diagnostic Logs to capture Delete Container operations. Use Azure Event Grid to capture and trigger alerts for container deletion. - Google Cloud Storage: Enable Data Access logs in Cloud Audit Logs to monitor storage.buckets.delete API calls. - OpenStack Swift: Configure Swift logging to capture DELETE requests for containers. Centralized Logging and Analysis - Use platforms like Splunk or native SIEMs to forward and analyze logs for anomalies in cloud storage deletions.

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
