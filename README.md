### I fix broken infrastructure — Terraform state, Kubernetes misconfigs, cloud cost blind spots.

Fractional SRE work: state repair, drift cleanup, and the kind of "why is prod down" debugging most teams only need occasionally but always need fast.

- 🔧 [terraform-state-surgery](https://github.com/jz-wilson/terraform-state-surgery) — reproducible Terraform state failures (drift, botched refactors, orphaned resources, provider migrations), each with the exact error, diagnosis, and CI-verified fix. The playbook I use on state-repair engagements.
- ☁️ [cloud-price-exporter](https://github.com/jz-wilson/cloud-price-exporter) — production Prometheus exporter for AWS/Azure cloud pricing. Go, fully tested, CI/CD with auto-releases, Helm chart.

Available for fractional/contract SRE work — Terraform, Kubernetes, observability.
