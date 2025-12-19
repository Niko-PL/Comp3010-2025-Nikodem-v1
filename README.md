Comp3010-2025-Nikodem-v1

This is my reports
## Risk Assessment
---

## 

## | Risk                          | Risk Level | Consequence                                                                 | Mitigation                                                                 |

## |-------------------------------|------------|-----------------------------------------------------------------------------|----------------------------------------------------------------------------|

## | MFA Disabled                  | 10         | Users can perform sensitive actions without secondary verification.         | Enforce Multi-Factor Authentication (MFA) for all user accounts.           |

## | Excessive IAM Permissions     | 10         | Users have access beyond their required operational scope.                  | Review IAM policies and enforce the principle of least privilege.          |

## | Non-Uniform Operating Systems | 4          | Network-wide policies may not apply consistently across differing systems. | Standardise operating systems and enforce version control.                |

## | No SOC Alerting               | 10         | Critical S3 security changes are not detected or reviewed.                  | Implement SOC alerting for high-risk and security-critical events.         |

## | Lack of Monitoring and IR     | 10         | Critical vulnerabilities may remain undetected and unremediated.           | Establish continuous monitoring and formal incident response procedures.  |

## | Publicly Accessible S3 Bucket | 9          | Sensitive data may be exposed to unauthorised users or the public.          | Restrict bucket access, disable public access, and apply bucket policies. |



---

<img width="1918" height="1078" alt="Ubuntu Setup" src="https://github.com/user-attachments/assets/5e881644-bfd3-41c4-bb02-75c51c905040" />
