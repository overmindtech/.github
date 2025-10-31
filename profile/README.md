<p align="center">
  <picture width="120px" align="center">
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.prod.website-files.com/6241e92445c21f9c1245a940/69047fa84e22dce67b16f483_logo.png">
    <img alt="Overmind" src="https://cdn.prod.website-files.com/6241e92445c21f9c1245a940/69047fa84e22dce67b16f483_logo.png" width="120px" align="center">
  </picture>
<h1 align="center">Overmind</h1>

<p align="center">
  <a href="https://discord.com/invite/5UKsqAkPWG" rel="nofollow"><img src="https://img.shields.io/discord/1088753599951151154?label=Discord&logo=discord&logoColor=white" alt="Discord Server"></a>
</p>

<p align="center">
  <a href="https://overmind.tech"> 💻  Website</a> | <a href="https://docs.overmind.tech">📖 Docs</a> | <a href="https://app.overmind.tech/api/auth/signup">🚀 Sign up</a> | <a href="https://www.linkedin.com/company/overmindtech/">🙌 Follow us</a>
</p>

# What is Overmind?

Overmind helps you deploy infrastructure changes with confidence by simulating their impact before they go live. We analyze your Terraform plans against real-time dependency data from AWS, GCP, and Kubernetes to show you exactly what could be affected by your changes — giving you full visibility into blast radius, risks, and expected outcomes without changing your existing tools or workflows.

## The Problem

Developers spend 15–20% of their time on code reviews — and up to 30% of those are for routine or minor changes. Teams face this dilemma: react when it matters or get bogged down reviewing every single change without context.

Hidden dependencies across AWS, GCP, and Kubernetes environments create invisible blast radius that only becomes apparent when something breaks. Critical services might depend on that "simple" change in ways that aren't visible in your `.tf` files.

## How Overmind Solves It

<table style="width: 100%; table-layout: fixed;">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <img width="100%" src="https://uploads-ssl.webflow.com/6241e92445c21f9c1245a940/66607bb64e562f2d332dad8b_blast_radius.png" /><br/>
        <b>🔍 Blast Radius Analysis:</b> Your mapped cloud resources and their connections help you understand pre and post deployment impact across 120+ AWS resources, GCP services, and all Kubernetes objects.
    </td>
    <td style="width:50%; vertical-align: top;">
      <img width="100%" src="https://uploads-ssl.webflow.com/6241e92445c21f9c1245a940/66607454e2bf59158c49565a_health%20check%20risk.png" /><br/>
      <b>🚨 Risk Assessment:</b> See the real impact of every change with LLM-powered analysis that delivers clear, actionable risk assessments straight to your pull requests.
    </td>
  </tr>
</table>

### 🎯 Signals: Follow data-driven Signals, not gut feelings

Let strong signals guide your reviews — **positive signals speed up PR approvals with confidence, while negative signals trigger deeper checks to mitigate potential risks**.

- **Democratize tribal knowledge**: Centralize organizational context that typically lives within a team's collective memory
- **Closes the loop**: Learns from previous changes to improve predictions
- **Find the needle in the haystack**: Even in the largest of changes

<p>

# Getting Started

## 5-minute setup

Get started in minutes — no workflow changes required. Free forever for one repository with full feature access, no time limits, no credit card required.

## Quick Start

Install the Overmind CLI:

```bash
brew install overmindtech/overmind/overmind-cli
```

Analyze your changes:

```bash
overmind terraform plan
```

[Install on other platforms](https://github.com/overmindtech/cli/)

![Running 'overmind terraform plan' and viewing in the app](https://uploads-ssl.webflow.com/6241e92445c21f9c1245a940/666039f90a7a42bebcfaf692_overmind_cli_demo%20(1).gif)

## React when it matters, directly from the PR

Overmind alerts you only when it counts. See Signals, Risks, and expected changes directly in your pull requests as clear, actionable comments with our [GitHub Action](https://github.com/overmindtech/terraform-example):

```yaml
- uses: overmindtech/actions/submit-plan@main
  with:
    ovm-api-key: ${{ secrets.OVM_API_KEY }}
    plan-json: ./tfplan.json
```

## Deploy with confidence across all teams & workflows

- **AWS**: Secure access through customer-managed IAM roles with minimal read-only permissions
- **GCP**: Dedicated service accounts with granular, read-only IAM roles following least privilege
- **Kubernetes**: Complete cluster resource discovery and relationship mapping
- **Azure**: Managed identity with read-only permissions scoped to your resources

## Key Features

### Auto-tagging
Automatically categorize infrastructure changes to ensure consistent change management, enforce compliance, and streamline reviews for every modification.

### Risks
Evaluate potential failure points, spot configuration issues, and get recommendations for safe deployment with human-readable explanations.

### Signals
Routine changes get positive signals that accelerate approvals. Complex changes get negative signals that trigger deeper review processes.

## What Our Customers Say

> "Overmind has revolutionized our IaC change management. It excels in risk evaluation, preventing issues before they arise. Fewer delays and less scrambling to fix things last minute."
> 
> **Tobias McCurry, Global Security @Whiskerlabs**

> "Overmind not only simplifies risk assessment, it democratises it, enabling even your newest team members to confidently deploy changes faster."
> 
> **Nigel Kersten, Chief Product Officer @Platform.sh**

## Security, Privacy, and Compliance built in

- Information Security Management System audit in progress
- Service Organization Controls audit in progress  
- Secure, read-only access with principle of least privilege
- All operations logged and auditable

## Enterprise Ready

When you're ready to scale beyond one repository:

- **Unlimited repositories and users**
- **SSO and enterprise security** 
- **24/7 priority support**
- **On-premise deployment options**
- **Custom integrations**

## Prevent outages before they cost you customers

Contact [sales@overmind.tech](mailto:sales@overmind.tech) for enterprise pricing or [schedule a live demo](https://overmind.tech/demo) with our team today.

## Join the Community

- Join our [Discord](https://discord.com/invite/5UKsqAkPWG)
- Contact us via email at [sales@overmind.tech](mailto:hello@overmind.tech)  
- Follow us on [LinkedIn](https://www.linkedin.com/company/overmindtech/)

## Additional Resources

- [Documentation](https://docs.overmind.tech)
- [Getting Started Guide](https://docs.overmind.tech/getting-started/quickstart)
- [Overmind Blog](https://overmind.tech/blog)

---

Overmind is made with ❤️ in 🇺🇸🇬🇧🇦🇹🇫🇷🇷🇴
