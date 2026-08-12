# Hello, I'm Kel! 👋🏼

I am a **Senior Cloud Infrastructure Engineer** with 12 years in software engineering including 7 years building on GCP and AWS

I specialize in abstracting cloud infrastructure complexity into standard, self-service developer platforms and GitOps workflows that accelerate feature team velocity. Expertise in Kubernetes lifecycle, multi-region Terraform design, and Argo CD GitOps, with a security-first approach to secrets management and hardened build pipelines.


## Technical Highlights

**[Event-Driven Trading Infrastructure](https://github.com/kelcodesstuff/Kalshi-Trading-Bot)**

A production-grade event-driven algorithmic trading bot, designed to serve as a reference architecture for zero-trust cloud infrastructure, automated GitOps delivery pipelines, and real-time observability.

*   **Infrastructure as Code (IaC):** Orchestrated cloud resource deployment programmatically via **Terraform**, enforcing declarative configurations, structural validation checks, and tag-based associations.

*   **Perimeter & Network Security:** Provisioned an isolated **DigitalOcean** VPC network and enforced firewall rules to block unauthorized inbound connections and limit outbound egress strictly to DNS, HTTP/S, and NTP boundaries.

*   **Zero-Trust Secrets Management:** Integrated **Doppler** to inject application secrets and RSA cryptographic credentials directly into container memory at startup, eliminating the need to store plaintext keys or configs on the host disk.

*   **Container Hardening & Least Privilege:** Engineered **multi-stage Docker builds** to minimize runtime surface areas, executing services under a low-privilege system user while restricting database and telemetry port bindings to prevent public exposure.

*   **Observability Pipeline:** Configured a local **Grafana Alloy** telemetry collector to scrape application-level Prometheus metrics (API latency histograms, inventory levels, PnL) and remote-write them directly to Grafana Cloud.

*   **Automated GitOps Pipeline:** Programmed a **GitHub Actions** workflow executing automated testing with coverage metrics, terraform validation, security scanning, image publication to GitHub Container Registry (GHCR), and SSH-based remote deployments.

*   **Disaster Recovery & Redundancy:** Authored a POSIX-compliant PostgreSQL backup script featuring transaction-consistent dumps and archive verification, coupled with automated daily **DigitalOcean** snapshot backups for full-host recovery.
  
**Stack:** DigitalOcean, Terraform, Docker/Compose, GitHub Actions, Grafana Alloy, Doppler Secrets Manager, PostgreSQL, Python.


## Skills

<table style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th align="left" valign="top" width="16.6%">Languages</th>
      <th align="left" valign="top" width="16.6%">Cloud Platforms</th>
      <th align="left" valign="top" width="16.6%">CI/CD & Infra</th>
      <th align="left" valign="top" width="16.6%">Data Systems</th>
      <th align="left" valign="top" width="16.6%">Observability & Security</th>
      <th align="left" valign="top" width="16.6%">AI Tooling</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        Go<br/>
        Python<br/>
        Node.js<br/>
        Bash<br/>
        Swift<br/>
        Kotlin
      </td>
      <td valign="top">
        AWS (EKS, ECS, EC2, S3)<br/>
        GCP (GKE, GCE, GCS)<br/>
        DigitalOcean
      </td>
      <td valign="top">
        Kubernetes<br/>
        Helm<br/>
        Argo CD<br/>
        Terraform<br/>
        Atlantis<br/>
        Docker<br/>
        GitHub Actions<br/>
        CircleCI<br/>
        Buildkite<br/>
        Bazel
      </td>
      <td valign="top">
        PostgreSQL<br/>
        Redis<br/>
        BigQuery<br/>
        Pub/Sub
      </td>
      <td valign="top">
        Datadog<br/>
        Prometheus<br/>
        Grafana<br/>
        OpenTelemetry<br/>
        Sentry<br/>
        HashiCorp Vault<br/>
        Doppler<br/>
        Snyk
      </td>
      <td valign="top">
        Claude Code<br/>
        Gemini API<br/>
        OpenAI API<br/>
        Model Context Protocol (MCP)
      </td>
    </tr>
  </tbody>
</table>


### 
<p align="center">
  <img width="2752" height="1536" alt="CI-CD" src="https://github.com/user-attachments/assets/8a1c5689-f224-4b69-9710-427c52c3e044" />
</p>
