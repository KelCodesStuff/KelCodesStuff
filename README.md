# Hello, I'm Kel! 👋🏼

I am a **Senior Cloud Infrastructure Engineer** with 12+ years of experience building scalable cloud architectures and modernizing software delivery ecosystems across GCP and AWS. 

I specialize in abstracting cloud infrastructure complexity into standard, self-service developer platforms and AI-assisted workflows that accelerate feature team velocity. My core expertise lies in optimizing build systems, reducing cloud spend, and designing Kubernetes environments while maintaining high architectural and security standards.

---

## [Kalshi-Trading-Bot](https://github.com/kelcodesstuff/Kalshi-Trading-Bot) Production-Grade Trading Infrastructure
*A secure, automated blueprint for hosting high-availability, event-driven containerized applications.*

A production-grade implementation of an event-driven algorithmic trading bot, designed to serve as a reference architecture for zero-trust cloud infrastructure, automated GitOps delivery pipelines, and real-time observability. Beyond the trading strategy, it demonstrates how to orchestrate state, secrets, and telemetry in a hardened cloud environment.

*   **Infrastructure as Code (IaC):** Orchestrated cloud resource deployment programmatically via **Terraform**, enforcing declarative configurations, structural validation checks, and tag-based associations.

*   **Perimeter & Network Security:** Provisioned an isolated **DigitalOcean** VPC network and enforced firewall rules to block unauthorized inbound connections and limit outbound egress strictly to DNS, HTTP/S, and NTP boundaries.

*   **Zero-Trust Secrets Management:** Integrated **Doppler** to inject application secrets and RSA cryptographic credentials directly into container memory at startup, eliminating the need to store plaintext keys or `.env` configs on the host disk.

*   **Container Hardening & Least Privilege:** Engineered **multi-stage Docker builds** to minimize runtime surface areas, executing services under a low-privilege system user while restricting database and telemetry port bindings to `127.0.0.1` to prevent public exposure.

*   **Observability Pipeline:** Configured a local **Grafana Alloy** telemetry collector to scrape application-level Prometheus metrics (API latency histograms, inventory levels, PnL) and remote-write them directly to Grafana Cloud.

*   **Automated GitOps Pipeline:** Programmed a **GitHub Actions** workflow executing automated testing (`pytest-cov`), terraform validation, security scanning (`tfsec`), image publication to GitHub Container Registry (GHCR), and SSH-based remote deployments.

*   **Disaster Recovery & Redundancy:** Authored a POSIX-compliant PostgreSQL backup script featuring transaction-consistent dumps and archive verification (`gzip -t`), coupled with automated daily **DigitalOcean** snapshot backups for full-host recovery.
  
**Stack:** Terraform, Docker/Compose, GitHub Actions, Grafana Alloy, Doppler Secrets Manager, PostgreSQL, Bash, Python.

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
