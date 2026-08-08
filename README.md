# Hello, I'm Kel

Senior Cloud Infrastructure Engineer with 12+ years of experience building scalable cloud architectures and modernizing software delivery ecosystems across GCP and AWS. Specializes in abstracting cloud infrastructure complexity into standard, self-service developer platforms and AI-assisted workflows that accelerate feature team velocity. Expertise in optimizing build systems, reducing cloud spend, and designing GitOps-driven Kubernetes environments while maintaining high architectural and security standards.

---

### Areas of Expertise
*   **CI/CD & Delivery:** Modernizing and parallelizing high-throughput deployment pipelines and monorepos to establish secure, repeatable paths to production.
*   **Developer Ecosystems:** Building self-service internal developer platforms, custom CLI tools, and portal architectures to abstract cloud complexity and increase product engineering autonomy.
*   **Ephemeral Infrastructure:** Architecting dynamic, pull-request-scoped validation environments and parallel testing clusters to eliminate integration bottlenecks and accelerate feedback loops.
*   **Cloud & Platform Architecture:** Provisioning immutable, scalable environments across AWS and GCP to eliminate configuration drift.
*   **Observability & Telemetry:** Building distributed tracing and telemetry pipelines to turn complex production systems into transparent, easily debugged platforms.

---

## Featured Project: Production-Grade Trading Infrastructure
### [Kalshi-Trading-Bot](https://github.com/kelcodesstuff/Kalshi-Trading-Bot)
*A secure, automated blueprint for hosting high-availability, event-driven containerized applications.*

This project demonstrates how to architect, secure, and monitor a continuous algorithmic trading platform in production. Beyond the core trading logic, it serves as a reference architecture for robust infrastructure-as-code (IaC), zero-trust secrets hygiene, and push-based telemetry pipelines.

*   **Infrastructure as Code & Hardened Networking:** Managed via **Terraform** to provision isolated VPC networks, resource tags, and egress-filtered firewalls restricting outbound traffic strictly to DNS, HTTP/S, and NTP boundaries.
*   **Zero-Trust Secrets Management:** Integrated **Doppler** to inject application secrets and RSA cryptographic credentials directly into container memory at startup, eliminating the need to store plaintext keys or `.env` configs on the host disk.
*   **Hardened Containers:** Engineered **multi-stage Docker builds** to minimize runtime surface areas, executing services under a low-privilege system user while restricting database and telemetry port bindings to `127.0.0.1`.
*   **Observability Pipeline:** Configured a local **Grafana Alloy** telemetry collector to scrape application-level Prometheus metrics (API latency histograms, inventory levels, PnL) and remote-write them directly to Grafana Cloud.
*   **Automated GitOps Pipeline:** Programmed a **GitHub Actions** workflow executing automated testing (`pytest-cov`), terraform validation, security scanning (`tfsec`), image publication to GitHub Container Registry (GHCR), and SSH-based remote deployments.
*   **Disaster Recovery:** Authored a POSIX-compliant PostgreSQL backup script featuring transaction-consistent dumps, archive verification (`gzip -t`), and self-pruning retention schedules.

**Stack:** Terraform, Docker/Compose, GitHub Actions, Grafana Alloy, Doppler Secrets Manager, PostgreSQL, Python.

---

## Skills

<table style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th align="left" valign="top" width="16.6%">Programming</th>
      <th align="left" valign="top" width="16.6%">Cloud Services</th>
      <th align="left" valign="top" width="16.6%">CI/CD & Infra</th>
      <th align="left" valign="top" width="16.6%">Data Systems</th>
      <th align="left" valign="top" width="16.6%">Observability</th>
      <th align="left" valign="top" width="16.6%">AI Tooling</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        Go<br/>
        Python<br/>
        Bash<br/>
        Swift<br/>
        Kotlin
      </td>
      <td valign="top">
        AWS<br/>
        GCP<br/>
        DigitalOcean
      </td>
      <td valign="top">
        GitHub Actions<br/>
        CircleCI<br/>
        ArgoCD<br/>
        Kubernetes<br/>
        Terraform<br/>
        Docker<br/>
        Buildkite<br/>
        Bazel
      </td>
      <td valign="top">
        PostgreSQL<br/>
        Redis
      </td>
      <td valign="top">
        Datadog<br/>
        Sentry<br/>
        Prometheus<br/>
        Grafana
      </td>
      <td valign="top">
        Gemini<br/>
        Claude Code<br/>
        Agentic Workflows<br/>
        MCP Servers
      </td>
    </tr>
  </tbody>
</table>

---

### 
<p align="center">
  <img width="2752" height="1536" alt="CI-CD" src="https://github.com/user-attachments/assets/8a1c5689-f224-4b69-9710-427c52c3e044" />
</p>
