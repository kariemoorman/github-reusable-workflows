<h1 align='center'>github-reusable-workflows</h1>

<h3>Security Scanning</h3>

<h4><a href='https://github.com/kariemoorman/github-reusable-workflows/blob/main/.github/workflows/container_security_scan.yml' target='_blank'>Docker Container Security Scan</a></h4>

This reusable workflow performs comprehensive security scanning of Docker container images using multiple industry-standard tools:

  - Trivy – Scans container images for known vulnerabilities and misconfigurations, detecting risks in both operating system packages and application dependencies.
  - Snyk – Performs deep vulnerability analysis, identifying issues within container images, dependencies, and runtime environments.
  - Grype – Uses the Anchore database to scan container images for known vulnerabilities.
  - JFrog Xray – Scans both container images and artifacts, identifying security vulnerabilities, license compliance issues, and operational risks.
  - OWASP ZAP – Conducts dynamic application security testing (DAST) on running containers, detecting vulnerabilities that may be exploitable in live environments.


<h4><a href='https://github.com/kariemoorman/github-reusable-workflows/blob/main/.github/workflows/repository_security_scan.yml' target='_blank'>Repository Security Scan</a></h4>

This reusable workflow performs comprehensive repository-level security scanning to identify vulnerabilities, misconfigurations, and exposed secrets in source code and dependencies. It supports configurable execution of the following tools:

  - OWASP Dependency-Check – Identifies vulnerable third-party dependencies used in the repository.
  - Trivy – Scans dependencies, configuration files, and infrastructure-as-code for known vulnerabilities and misconfigurations.
  - TruffleHog – Detects hard-coded secrets, credentials, and sensitive data in source history.
  - Snyk – Analyzes open-source dependencies for known security issues.
  - JFrog Xray – Scans repository artifacts and dependencies for vulnerabilities and license compliance.
  - CodeQL – Performs static application security testing to detect code-level security flaws across supported languages.


<h4><a href='https://github.com/kariemoorman/github-reusable-workflows/blob/main/.github/workflows/terraform_security_scan.yml' target='_blank'>Terraform Security Scan</a></h4>

This reusable workflow performs security scanning on Terraform code to identify vulnerabilities, misconfigurations, and security risks in infrastructure-as-code configurations using the following tools:

  - Checkov – Performs static analysis of Terraform files for security misconfigurations and vulnerabilities, checking against a wide range of security policies and best practices.
  - TFSec – Analyzes Terraform code for common security issues including misconfigurations, access control, and data handling via a predefined set of rules and policies.
  - Trivy – Scans Terraform configurations for vulnerabilities in both infrastructure-as-code and dependencies, identifying potential risks such as outdated libraries or misconfigurations.
  - Snyk – Performs vulnerability analysis on Terraform configurations and dependencies, providing insights into potential risks and compliance issues.

---

<p align='center'>License: <a href='https://github.com/kariemoorman/github-reusable-workflows/blob/main/LICENSE.MD' target='_blank'>GNU Affero General Public License v3.0 (GNU AGPLv3)</a></p>
