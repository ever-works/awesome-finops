# Awesome FinOps

A curated directory of cloud cost management, Kubernetes cost and FinOps tools.

## 📑 Table of Contents

- [Chargeback & Billing (2)](#chargeback--billing)
- [Cloud Cost Management (17)](#cloud-cost-management)
- [Commitment & Savings Automation (7)](#commitment--savings-automation)
- [IaC Cost Estimation (3)](#iac-cost-estimation)
- [Kubernetes Cost (2)](#kubernetes-cost)
- [Open Source FinOps (5)](#open-source-finops)


## Chargeback & Billing

- [CloudHealth by VMware](https://cloudhealth.vmware.com/) - Multi-cloud cost management, governance, and automation platform for AWS, Azure, and Google Cloud. Supports chargeback, showback, and policy-based cost controls. Enterprise paid solution. ([Read more](/details/cloudhealth-by-vmware.md)) `Cloud Cost Management` `Chargeback And Billing` `Multi Cloud` `Paid` `Enterprise` `Api`
- [ServiceNow Cloud Cost Management](https://www.servicenow.com/) - ServiceNow Cloud Cost Management integrates FinOps into its IT service management platform, connecting cost optimization to existing incident management, change requests, and service catalogs. Cost optimization requests flow through existing approval workflows, and change management connects infrastructure changes to cost impacts. The service catalog displays cost estimates for resource requests, making it best suited for regulated industries prioritizing governance and audit trails over velocity. ([Read more](/details/servicenow-cloud-cost-management.md)) `Enterprise` `ITSM` `Api` `Governance` `Approval Workflows`

## Cloud Cost Management

- [Apptio Cloudability](https://www.apptio.com/products/cloudability) - Multi-cloud cost management and FinOps platform for cost allocation, chargeback/showback, budgeting, and optimization across AWS, Azure, and Google Cloud. Helps finance and engineering teams unify cloud spend reporting and reduce waste. Enterprise paid solution acquired by IBM. ([Read more](/details/apptio-cloudability.md)) `Cloud Cost Management` `Chargeback And Billing` `Multi Cloud` `Paid` `Enterprise` `Api`
- [AWS Cost Explorer](https://aws.amazon.com/aws-cost-management/aws-cost-explorer) - Native AWS tool for visualizing, understanding, and managing cloud costs and usage. Supports budgets, forecasts, and reservation coverage reports. Basic access is free; API usage may incur charges. ([Read more](/details/aws-cost-explorer.md)) `Cloud Cost Management` `AWS` `Free Plan` `Freemium` `Api`
- [Azure Cost Management + Billing](https://azure.microsoft.com/en-us/services/cost-management) - Microsoft Azure service for monitoring, allocating, and optimizing cloud spending. Includes budgets, cost alerts, and chargeback capabilities. Free for Azure customers. ([Read more](/details/azure-cost-management-billing.md)) `Cloud Cost Management` `Chargeback And Billing` `Azure` `Free` `Api`
- [Cloud Cost Analyzer](https://cloudcostanalyzer.com) - Cloud Cost Analyzer scans AWS and Azure accounts for cost waste using 92 automated checks, including idle NAT gateways, gp2 volumes, and over-provisioned instances. It provides savings estimates through a read-only, developer-first CLI. The free tier covers up to 5,000 resources per scan on one AWS account; paid tiers add resource IDs and exact remediation steps. ([Read more](/details/cloud-cost-analyzer.md)) `Free Plan` `CLI` `AWS` `Azure`
- [CloudHealth by Broadcom](https://cloudhealth.vmware.com/) - CloudHealth provides enterprise-grade, policy-driven cost governance with solid multi-cloud visibility and customizable governance policies. Its strengths lie in financial operations including budget tracking, forecasting, and cost allocation that satisfy finance teams. For platform engineers, this means strong executive reporting but fewer developer-facing features, making it better suited for organizations prioritizing financial governance and executive visibility over developer self-service. ([Read more](/details/cloudhealth-by-broadcom.md)) `Enterprise` `Multi Cloud` `Api` `Financial Governance`
- [CloudZero](https://www.cloudzero.com/) - Cloud cost intelligence platform focused on SaaS cost of goods sold and engineering-centric cost allocation. Helps teams correlate cloud spend with business metrics. Pricing is custom and enterprise-focused. ([Read more](/details/cloudzero.md)) `Cloud Cost Management` `SaaS COGS` `Paid` `Enterprise` `Api` `AI Powered`
- [Datadog Cloud Cost Management](https://www.datadoghq.com/product/cloud-cost-management/) - Datadog Cloud Cost Management correlates application performance with infrastructure costs, enabling teams to see which services consume the most resources and identify cost spikes alongside error rates. It provides service-level cost attribution mapping spending to specific applications and teams, with anomaly detection leveraging existing monitoring capabilities. Cloud provider coverage focuses primarily on AWS and Azure, with GCP support still maturing. ([Read more](/details/datadog-cloud-cost-management.md)) `Observability` `Multi Cloud` `Api` `AWS` `Azure`
- [Finout](https://www.finout.io/) - Cloud cost observability platform that unifies AWS, Azure, GCP, Snowflake, and Datadog spend. Supports chargeback, showback, and virtual tagging for shared costs. Paid service with enterprise plans. ([Read more](/details/finout.md)) `Cloud Cost Management` `Chargeback And Billing` `Multi Cloud` `Paid` `Enterprise` `Api`
- [Flexera One](https://www.flexera.com/) - Flexera One is a cloud cost optimization platform that expanded from software asset management, excelling in hybrid environments that manage both traditional data center and public cloud resources. It provides unified visibility across on-premises, private, and public cloud infrastructure with a strong policy engine for cost guardrails and compliance. Kubernetes support has improved but remains less sophisticated than cloud-native alternatives, making it best suited for organizations with significant legacy infrastructure alongside cloud-native workloads. ([Read more](/details/flexera-one.md)) `Enterprise` `Multi Cloud` `Api` `Hybrid Cloud`
- [Google Cloud Cost Management](https://cloud.google.com/cost-management) - Google Cloud suite of tools for cost tracking, budgeting, and optimization. Provides detailed billing reports and cost allocation across GCP services. Free to use. ([Read more](/details/google-cloud-cost-management.md)) `Cloud Cost Management` `GCP` `Free` `Api`
- [Harness Cloud Cost Management](https://harness.io/products/cloud-cost-management) - Cloud and Kubernetes cost management module within the Harness platform. Provides cost visibility, anomaly detection, and automated governance for cloud spend. Paid service with tiered plans. ([Read more](/details/harness-cloud-cost-management.md)) `Cloud Cost Management` `Kubernetes Cost` `Paid` `Enterprise` `Api`
- [Parsivex](https://parsivex.com) - Parsivex scans AWS accounts for idle EC2 instances, unattached EBS volumes, oversized RDS databases, stale snapshots, and NAT gateway overuse. The free tier provides a monthly scan for one AWS account and returns total monthly waste plus a category breakdown. Paid plans provide access to itemized findings and scheduled re-scans. ([Read more](/details/parsivex.md)) `Free Plan` `AWS` `CLI`
- [Pump.co](https://pump.co/) - Pump.co combines GPT-powered natural language processing with automated cost optimization, enabling teams to query costs conversationally and receive executable optimization scripts. It supports natural language cost queries, automated script generation compatible with Terraform and CloudFormation, and group buying power that aggregates demand across customers for better AWS, GCP, or Azure rates. ([Read more](/details/pump-co.md)) `AI Powered` `Natural Language` `Terraform` `Multi Cloud` `Developer First`
- [Replex](https://www.replex.io/technology) - Commercial FinOps platform for cloud cost management and visibility across cloud providers. ([Read more](/details/replex.md)) `Paid` `Enterprise` `Api`
- [SoftwareOne Cloud Financial Management](https://www.softwareone.com/zh-cn/cloud-financial-management) - Commercial cloud financial management service from SoftwareOne for managing cloud spend. ([Read more](/details/softwareone-cloud-financial-management.md)) `Paid` `Enterprise`
- [Ternary](https://www.ternary.com/) - Multi-cloud cost management platform for AWS, Azure, and GCP. Provides cost allocation, anomaly detection, and budget tracking for finance and engineering teams. Paid enterprise offering. ([Read more](/details/ternary.md)) `Cloud Cost Management` `Multi Cloud` `Paid` `Enterprise` `Api`
- [Vantage](https://vantage.sh/) - Cloud cost management platform that centralizes AWS, Azure, GCP, and Kubernetes spend. Designed for engineering and finance teams to track budgets, anomalies, and unit costs. Offers a free tier and paid plans. ([Read more](/details/vantage.md)) `Cloud Cost Management` `Multi Cloud` `Freemium` `Api` `Enterprise`

## Commitment & Savings Automation

- [Antimetal](https://antimetal.com/) - Antimetal is an AI-powered autopilot for AWS cost optimization that makes autonomous purchasing decisions for Reserved Instances and Savings Plans based on real-time usage analysis. It shifts from advisory to autonomous FinOps by executing optimization strategies 24/7 without human approval gates, operating on a guaranteed savings model where customers pay only a percentage of actual savings achieved. ([Read more](/details/antimetal.md)) `AI Powered` `AWS` `Autonomous` `Savings Automation` `Zero Integration`
- [Densify](https://www.densify.com/) - Cloud and Kubernetes resource optimization platform that rightsizes workloads and manages commitments. Analyzes usage patterns to reduce cloud spend and improve efficiency. Paid enterprise solution. ([Read more](/details/densify.md)) `Commitment & Savings Automation` `Kubernetes Cost` `Paid` `Enterprise` `Api`
- [IBM Turbonomic](https://www.ibm.com/products/turbonomic) - Application resource management platform that optimizes cloud and Kubernetes costs through automated actions. Ensures application performance while reducing overprovisioning. Enterprise paid solution. ([Read more](/details/ibm-turbonomic.md)) `Commitment & Savings Automation` `Kubernetes Cost` `Paid` `Enterprise` `Api` `AI Powered`
- [nOps](https://www.nops.io/) - AWS cost optimization platform focused on commitment automation, anomaly detection, and cost allocation. Helps FinOps teams reduce waste and manage Savings Plans. Offers free and paid tiers. ([Read more](/details/nops.md)) `Commitment & Savings Automation` `Cloud Cost Management` `AWS` `Freemium` `Paid` `AI Powered`
- [ProsperOps](https://www.prosperops.com/) - Autonomous AWS commitment discount management service that optimizes Reserved Instances and Savings Plans. Uses AI to maximize savings without engineering effort. Pricing is based on savings achieved. ([Read more](/details/prosperops.md)) `Commitment & Savings Automation` `AWS` `Paid` `Enterprise` `AI Powered` `Api`
- [Spot by NetApp](https://spot.io/) - Cloud infrastructure automation platform that optimizes compute, storage, and Kubernetes costs. Leverages spot instances and commitment discounts to reduce spend. Paid enterprise service. ([Read more](/details/spot-by-netapp.md)) `Commitment & Savings Automation` `Kubernetes Cost` `Paid` `Enterprise` `Api` `AI Powered`
- [Zesty](https://zesty.co/) - Autonomous cloud commitment management platform that purchases and sells AWS Savings Plans and Reserved Instances. Aims to maximize savings with minimal manual intervention. Paid service. ([Read more](/details/zesty.md)) `Commitment & Savings Automation` `Paid` `Enterprise` `AI Powered`

## IaC Cost Estimation

- [Infracost](https://www.infracost.io/) - Open source CLI and API that generates cloud cost estimates for Terraform and other IaC before deployment. Enables cost visibility in CI/CD pipelines. Free CLI with paid cloud collaboration features. ([Read more](/details/infracost.md)) `IaC Cost Estimation` `Terraform` `Open Source` `Free Plan` `Freemium` `Api`
- [Pulumi](https://www.pulumi.com) - Pulumi is a modern infrastructure as code platform that enables teams to build, deploy, and manage cloud infrastructure using familiar programming languages and tools. It supports multiple cloud providers and integrates with existing CI/CD workflows. Pulumi offers both open source and commercial editions for infrastructure management. ([Read more](/details/pulumi.md)) `Open Source` `Infrastructure As Code` `Multi Cloud`
- [Scalr](https://scalr.com) - Scalr is a Terraform Automation and Collaboration (TACO) product used for collaboration and automation on infrastructure and configurations managed by Terraform. It provides full Terraform CLI support, OPA integration, and a hierarchical configuration model. All features are included with up to 50 runs per month free, and there is no SSO tax. ([Read more](/details/scalr.md)) `Terraform` `Free Plan` `Automation`

## Kubernetes Cost

- [CAST AI](https://cast.ai/) - Kubernetes automation platform that optimizes cloud costs through rightsizing, spot instance orchestration, and cluster autoscaling. Targets DevOps and platform teams managing EKS, AKS, and GKE. Paid enterprise service. ([Read more](/details/cast-ai.md)) `Kubernetes Cost` `Commitment & Savings Automation` `Paid` `Enterprise` `AI Powered`
- [Kubecost](https://kubecost.com/) - Kubernetes cost monitoring and optimization tool that allocates spend by cluster, namespace, deployment, and service. Provides real-time cost allocation and savings recommendations. Offers a free community edition and paid enterprise tiers. ([Read more](/details/kubecost.md)) `Kubernetes Cost` `Kubernetes` `Freemium` `Paid` `Enterprise` `Api`

## Open Source FinOps

- [Cloud Custodian](https://cloudcustodian.io/) - Open source cloud governance tool for cost optimization, security, and compliance across AWS, Azure, and GCP. Uses policies to manage resources and reduce waste. Free and Apache 2.0 licensed. ([Read more](/details/cloud-custodian.md)) `Open-Source FinOps` `Cloud Cost Management` `Open Source` `Self Hosted` `Free` `Api`
- [Economize](https://economize.cloud/) - Open source cloud cost management platform for tracking and optimizing multi-cloud spend. Provides cost allocation, anomaly detection, and self-hosted deployment. Free and community-driven. ([Read more](/details/economize.md)) `Open-Source FinOps` `Cloud Cost Management` `Open Source` `Self Hosted` `Free` `Api`
- [kube-opex-analytics](https://github.com/rchakode/kube-opex-analytics) - Open-source tool that helps organizations track the resources consumed by their Kubernetes clusters to prevent overpaying. ([Read more](/details/kube-opex-analytics.md)) `Open Source` `Kubernetes` `Self Hosted`
- [kube-resource-report](https://codeberg.org/hjacobs/kube-resource-report) - Open-source tool that reports Kubernetes cluster and pod resource requests versus usage and generates static HTML reports for FinOps visibility. ([Read more](/details/kube-resource-report.md)) `Open Source` `Kubernetes` `Self Hosted`
- [OpenCost](https://www.opencost.io/) - Open source Kubernetes cost monitoring project under the CNCF. Provides real-time cost allocation and container cost metrics for self-hosted deployments. Free to use and community-driven. ([Read more](/details/opencost.md)) `Kubernetes Cost` `Open Source` `Self Hosted` `Free` `Api`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg