# Torches bug bounty
---

## Vulnerability Severity

| **Impact** | Likelihood | Severity |
| ---------- | ---------- | -------- |
| High       | High       | Critical |
| High       | Medium     | Severe   |
| High       | Low        | Moderate |
| Medium     | High       | Severe   |
| Medium     | Medium     | Moderate |
| Medium     | Low        | Low      |
| Low        | High       | Moderate |
| Low        | Medium     | Low      |

*Likelihood*: Likelihood represents the possibility that a particular vulnerability is discovered and exploited.

*Impact*: Impact measures the loss caused by an attack using this vulnerability.

*Severity*: Severity indicates the magnitude of the vulnerability.

Likelihood and impact are divided into three levels: high, medium and low.

Severity is decided by likelihood and impact with four levels: critical, severe, moderate and low.



---

## Reward Range

| **Technical severity** | Reward range      |
| ---------------------- | ----------------- |
| P1 - Critical          | $ 1,001 or above  |
| P2 - Severe            | $ 501 - $ 1,000 |
| P3 - Moderate          | $ 201 - $ 500   |
| P4 - Low               | $ 10 - $ 200     |



---

## Vulnerability Classifications  

### In Scope:

:information_source: https://github.com/TorchesFinance/torches-protocol



### P1 (Critical):

**Vulnerabilities that could undermine the fund safety of any user or business runner, including:**

1. Vulnerabilities that could undermine the safety of any user's fund/fee.
2. Vulnerabilities that could severely undermine trading or token economy.
3. Vulnerabilities that could disrupt the governance of protocol.



### P2 (Severe):

**Vulnerabilities with similar impact as P1 vulnerabilities, but are dependent on specific prerequisites, including:**

1. Vulnerabilities that could undermine or disrupt trading or token economy.
2. Vulnerabilities that could disrupt or manipulate the oracle price feed service.
3. Vulnerabilities that could cause user can not redeem their funds and rewards.

   

### P3 (Moderate):

**Vulnerabilities of critical functions, including:**

1. Failed to call deposit or withdraw funtcion of contracts.
2. Config params mismatch.

### P4 (Low):

**Client and UI bugs, including:**

1. Web UI bugs.
2. Failure to load data.
3. Some query functions cannot be used.



---


Not including: 

- **Speculation without any evidence.  Including but not limited to:**

1. Theoretical vulnerabilities.
2. Use of known vulnerable libraries without actual proof of concept.


- **Phishing (E.g. HTTP Basic Authentication Phishing).**
- **Internally known issues, duplicate issues, or issues which have already been made public.**


## How to submit

Open new issues with template on github [Repo](https://github.com/TorchesFinance/bug-bounty/issues/new) 

Wait for response ;-)