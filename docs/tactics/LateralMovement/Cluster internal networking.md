---
hide:
  - toc
  - footer
---

# Cluster Internal Networking

!!! info inline end
    ID: ???<br>
    Tactic: [Lateral Movement](../LateralMovement/index.md) <br>
    MITRE technique: [T1210](https://attack.mitre.org/techniques/T1210/)

Kubernetes networking behavior allows traffic between pods in the cluster as a default behavior. Attackers who gain access to a single container may use it for network reachability to another container in the cluster.

## Mitigations

|ID|Mitigation|Description|
|--|----------|-----------|