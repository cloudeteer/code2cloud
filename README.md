# From Code to Cloud: Building Resilient Infrastructure with IaC and Automated Deployments

**Event:** [Tech Meetup Berlin 2025](https://www.eventbrite.com/e/tech-meetup-berlin-powered-by-leaseweb-tickets-1575552402649)  
**Speaker:** Roman Schwarz (@rswrz), Melody Sofia Eroshevich (@neonwhiskers)  
**Date:** 2025-10-16  
**Location:** Berlin, Germany  

## About the Talk

In modern cloud environments, resilience is driven not only by architecture but primarily by deployment automation.
As a Site Reliability Engineer, I will demonstrate how resilient, secure, and scalable platforms are built through Infrastructure as Code and automated deployment pipelines.

The talk covers:

- Infrastructure as Code best practices (modularization, repeatability, idempotency)
- Automated deployments with integrated code validation, policy enforcement, and security checks
- Embedding resilience in code – recovery mechanisms, rollbacks, and self-healing automation
- Continuous compliance using tools like policy-as-code frameworks and cloud-native policy engines
- Shift-left security: embedding security checks into the CI/CD pipeline instead of post-production
- Lessons learned from real-world experience – how automation can drastically reduce mean time to recovery (MTTR)

Attendees will gain practical insights and concrete patterns to build their own platforms reliably, securely, and scalably from first commit to production — with resilience as a core principle, not an afterthought.

- Audience: SREs, DevOps Engineers, Cloud Architects, Security Engineers
- Level: Advanced

---

## Slide References

**Resource** | **Description / Purpose** | **Link**
-- | -- | --
CLOUDETEER DECODED Blog | Engineering blog by Cloudeteer with deep dives into cloud technologies and infrastructure automation. | [https://engineering.cloudeteer.de/](https://engineering.cloudeteer.de/)
CLOUDETEER Terraform Modules | Official Cloudeteer Terraform modules for reusable infrastructure components. | [https://registry.terraform.io/namespaces/cloudeteer](https://registry.terraform.io/namespaces/cloudeteer)
Leaseweb Terraform Provider | Terraform provider for managing LeaseWeb infrastructure. | [https://registry.terraform.io/providers/LeaseWeb/leaseweb/](https://registry.terraform.io/providers/LeaseWeb/leaseweb/)
Terraform Docs & Guides | Official HashiCorp Terraform documentation and learning resources. | [https://developer.hashicorp.com/terraform](https://developer.hashicorp.com/terraform)
Trivy | Security scanner for containers, IaC, and dependencies. | [https://trivy.dev/](https://trivy.dev/)
TFLint | Linter for Terraform code to detect errors and enforce best practices. | [https://github.com/terraform-linters/tflint](https://github.com/terraform-linters/tflint)
Conftest | Tool for testing configuration files using Open Policy Agent (OPA). | [https://www.conftest.dev/](https://www.conftest.dev/)
Checkov | Static analysis tool for scanning IaC for security and compliance misconfigurations. | [https://www.checkov.io/](https://www.checkov.io/)
