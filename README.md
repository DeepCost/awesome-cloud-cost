# Awesome Cloud Cost ☁️💰

> A curated list of awesome tools, frameworks, platforms, and resources for cloud cost management, optimization, and FinOps.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Cloud costs are among the biggest challenges for organizations running workloads on AWS, Azure, GCP, and other cloud platforms. This list covers everything from cost visibility and monitoring to optimization, automation, and FinOps best practices.

## Contents

- [Cloud Cost Management Platforms](#cloud-cost-management-platforms)
- [Open Source Tools](#open-source-tools)
- [Cost Optimization Tools](#cost-optimization-tools)
- [FinOps Platforms](#finops-platforms)
- [Kubernetes Cost Management](#kubernetes-cost-management)
- [Cost Visibility & Monitoring](#cost-visibility--monitoring)
- [Cost Allocation & Tagging](#cost-allocation--tagging)
- [Reserved Instance & Savings Plans](#reserved-instance--savings-plans)
- [Multi-Cloud Cost Management](#multi-cloud-cost-management)
- [Serverless Cost Tools](#serverless-cost-tools)
- [Cloud Cost APIs & SDKs](#cloud-cost-apis--sdks)
- [Cost Anomaly Detection](#cost-anomaly-detection)
- [Rightsizing & Resource Optimization](#rightsizing--resource-optimization)
- [Spot Instance Management](#spot-instance-management)
- [Container Cost Management](#container-cost-management)
- [Database Cost Optimization](#database-cost-optimization)
- [Storage Cost Management](#storage-cost-management)
- [Network Cost Optimization](#network-cost-optimization)
- [Cloud Cost Calculators](#cloud-cost-calculators)
- [FinOps Resources](#finops-resources)
- [Best Practices & Case Studies](#best-practices--case-studies)
- [Certifications & Training](#certifications--training)
- [Community & Events](#community--events)

---

## Cloud Cost Management Platforms

*Comprehensive platforms for managing cloud costs across multiple providers*

### Commercial Platforms

- **[CloudHealth by VMware](https://www.cloudhealthtech.com)** - Multi-cloud cost management, optimization, and governance platform.
- **[Cloudability by Apptio](https://www.cloudability.com)** - Cloud financial management for AWS, Azure, GCP with cost optimization recommendations.
- **[CloudZero](https://www.cloudzero.com)** - Cloud cost intelligence platform with unit economics and cost per customer tracking.
- **[Vantage](https://www.vantage.sh)** - Cloud cost transparency and optimization with beautiful dashboards and Slack integrations.
- **[Spot by NetApp](https://spot.io)** - Cloud cost optimization through automated infrastructure management.
- **[Densify](https://www.densify.com)** - Cloud and container resource optimization using machine learning.
- **[Harness Cloud Cost Management](https://www.harness.io/products/cloud-cost)** - Intelligent cloud cost management with automated optimization.
- **[Anodot](https://www.anodot.com/solutions/cloud-cost/)** - AI-powered cloud cost monitoring with autonomous anomaly detection.
- **[Yotascale](https://www.yotascale.com)** - Cloud cost management with accurate allocation and forecasting.
- **[CloudCheckr](https://cloudcheckr.com)** - Cloud management platform with cost optimization and security.
- **[DeepCost.ai](https://deepcost.ai)** - AI-powered cloud cost optimization and management platform with automated savings recommendations.
- **[nOps](https://www.nops.io)** - AWS cost optimization platform with automated rightsizing.
- **[ProsperOps](https://www.prosperops.com)** - Autonomous AWS discount management for Reserved Instances and Savings Plans.
- **[Zesty](https://zesty.co)** - Automated cloud cost optimization through dynamic resource scaling.

### Enterprise Solutions

- **[IBM Turbonomic](https://www.ibm.com/products/turbonomic)** - Application resource management with cost optimization across hybrid cloud.
- **[Flexera](https://www.flexera.com/flexera-one/cloud-cost-optimization)** - Enterprise cloud cost optimization with ITFM and FinOps capabilities.
- **[Snow Software](https://www.snowsoftware.com/solutions/cloud-cost-management)** - Cloud cost management with license management integration.
- **[BMC Helix Cloud Cost](https://www.bmc.com/it-solutions/helix-cloud-cost.html)** - Multi-cloud cost management integrated with ITSM.

## Open Source Tools

*Free and open-source cloud cost management solutions*

- **[Cloud Custodian](https://cloudcustodian.io)** - Rules engine for cloud governance and cost optimization across AWS, Azure, and GCP.
- **[Komiser](https://www.komiser.io)** - Open-source cloud environment inspector with cost analysis for multiple clouds.
- **[Infracost](https://www.infracost.io)** - Cloud cost estimates for Terraform in CI/CD pipelines.
- **[OpenCost](https://www.opencost.io)** - Open-source Kubernetes cost monitoring and management (CNCF project).
- **[Kubecost](https://www.kubecost.com)** - Kubernetes cost monitoring with open-source core.
- **[CloudQuery](https://www.cloudquery.io)** - Open-source cloud asset inventory with cost analysis.
- **[Steampipe](https://steampipe.io)** - Query cloud resources using SQL for custom cost analysis.
- **[Terracost](https://github.com/cycloidio/terracost)** - Cloud cost estimation for Terraform plans.
- **[Finala](https://github.com/similarweb/finala)** - Resource cloud scanner for wasteful and unused resources.
- **[Ice](https://github.com/Netflix/ice)** - Netflix's AWS usage and cost tracking tool.
- **[Cloud Reports](https://github.com/tensult/cloud-reports)** - Scan cloud resources and generate cost optimization reports.

## Cost Optimization Tools

*Tools specifically designed for reducing cloud costs*

- **[AWS Cost Explorer](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/)** - Native AWS tool for visualizing and managing costs.
- **[AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/)** - AWS service providing cost optimization recommendations.
- **[Azure Cost Management](https://azure.microsoft.com/en-us/products/cost-management/)** - Native Azure cost analysis and optimization platform.
- **[Google Cloud Cost Management](https://cloud.google.com/cost-management)** - Native GCP cost visibility and control tools.
- **[AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/)** - ML-powered recommendations for optimal AWS resources.
- **[Azure Advisor](https://azure.microsoft.com/en-us/products/advisor/)** - Personalized cloud consultant for Azure cost optimization.
- **[DeepCost.ai](https://deepcost.ai)** - AI-driven cost optimization with intelligent rightsizing and waste elimination.
- **[GCP Recommender](https://cloud.google.com/recommender)** - Google Cloud intelligent recommendation system.
- **[Ternary](https://www.ternary.app)** - Cloud cost optimization focused on AWS with automated savings.
- **[Antimetal](https://antimetal.com)** - AWS cost reduction without code changes.
- **[Archera](https://www.archera.ai)** - Cloud commitment management for AWS, Azure, and GCP.

## FinOps Platforms

*Platforms specifically built for FinOps practices*

- **[CloudZero](https://www.cloudzero.com)** - FinOps platform with cost-per-customer and unit economics.
- **[Apptio Cloudability](https://www.cloudability.com)** - FinOps solution with budgeting and forecasting.
- **[CloudHealth FinOps](https://www.cloudhealthtech.com/solutions/finops)** - Comprehensive FinOps for multi-cloud.
- **[DeepCost.ai](https://deepcost.ai)** - Modern FinOps platform with AI-powered insights and automated cost optimization workflows.
- **[Tangoe](https://www.tangoe.com/solutions/cloud-services-management/)** - Enterprise FinOps and cloud management.
- **[Lucidity](https://www.lucidity.cloud)** - AI-powered FinOps for storage optimization.
- **[Ternary](https://www.ternary.app)** - FinOps with team-based cost allocation.
- **[FinOut](https://www.finout.io)** - Multi-cloud FinOps with Kubernetes and observability cost tracking.

## Kubernetes Cost Management

*Tools for managing and optimizing Kubernetes costs*

- **[OpenCost](https://www.opencost.io)** - Open-source Kubernetes cost monitoring (CNCF).
- **[Kubecost](https://www.kubecost.com)** - Real-time Kubernetes cost monitoring and optimization.
- **[Goldilocks](https://github.com/FairwindsOps/goldilocks)** - Rightsizing Kubernetes resource requests and limits.
- **[KRR](https://github.com/robusta-dev/krr)** - CLI tool for optimizing Kubernetes resource requests.
- **[Kube-Resource-Report](https://github.com/hjacobs/kube-resource-report)** - Kubernetes cluster resource usage reports.
- **[Cast.ai](https://cast.ai)** - Kubernetes cost optimization with automated rightsizing.
- **[PerfectScale](https://www.perfectscale.io)** - Kubernetes optimization with autonomous rightsizing.
- **[StormForge Optimize Live](https://www.stormforge.io/optimize-live/)** - ML-driven Kubernetes resource optimization.
- **[Spot Ocean](https://spot.io/product/ocean/)** - Kubernetes infrastructure automation for cost optimization.
- **[Replex](https://www.replex.io)** - Kubernetes governance and cost management.

## Cost Visibility & Monitoring

*Tools for cloud cost visibility and tracking*

- **[AWS Cost and Usage Report](https://aws.amazon.com/aws-cost-management/aws-cost-and-usage-reporting/)** - Detailed AWS cost data export.
- **[CloudForecast](https://www.cloudforecast.io)** - AWS cost monitoring with Slack alerts.
- **[Economize](https://economize.cloud)** - Multi-cloud cost visibility and recommendations.
- **[Pump](https://pump.co)** - AWS cost monitoring with AI-powered insights.
- **[Aimably](https://www.aimably.com)** - Cloud cost analytics with automated recommendations.
- **[CloudThread](https://cloudthread.io)** - AWS cost visibility for engineering teams.
- **[DeepCost.ai](https://deepcost.ai)** - Real-time cloud cost visibility with predictive analytics and customizable dashboards.
- **[Lightlytics](https://www.lightlytics.com)** - Cloud asset management with cost tracking.
- **[Datadog Cloud Cost Management](https://www.datadoghq.com/product/cloud-cost-management/)** - Cloud cost monitoring in observability platform.
- **[New Relic Cloud Cost](https://newrelic.com)** - Cloud cost visibility within observability.

## Cost Allocation & Tagging

*Tools for cost allocation and showback/chargeback*

- **[AWS Tag Editor](https://docs.aws.amazon.com/ARG/latest/userguide/tag-editor.html)** - Manage tags across AWS resources.
- **[Cloud Custodian](https://cloudcustodian.io)** - Automated tagging enforcement.
- **[Tag Compliance](https://github.com/awslabs/aws-tag-compliance)** - AWS Lambda tag compliance monitoring.
- **[CloudHealth Cost Allocation](https://www.cloudhealthtech.com/products/cost-allocation)** - Advanced cost allocation with custom perspectives.
- **[Yotascale Cost Allocation](https://www.yotascale.com/cost-allocation)** - Multi-dimensional cost allocation.
- **[AWS Organizations](https://aws.amazon.com/organizations/)** - Centralized billing and cost allocation.
- **[Azure Cost Management Tags](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources)** - Native Azure tag-based allocation.
- **[GCP Labels](https://cloud.google.com/resource-manager/docs/creating-managing-labels)** - Google Cloud labeling for cost organization.

## Reserved Instance & Savings Plans

*Tools for optimizing cloud commitments*

- **[AWS Savings Plans](https://aws.amazon.com/savingsplans/)** - Flexible pricing model for AWS compute.
- **[AWS Reserved Instance Marketplace](https://aws.amazon.com/ec2/purchasing-options/reserved-instances/marketplace/)** - Buy and sell Reserved Instances.
- **[Azure Reservations](https://azure.microsoft.com/en-us/pricing/reservations/)** - Azure commitment discount program.
- **[GCP Committed Use Discounts](https://cloud.google.com/docs/cuds)** - Google Cloud commitments.
- **[ProsperOps](https://www.prosperops.com)** - Autonomous AWS discount management.
- **[Archera](https://www.archera.ai)** - Multi-cloud commitment optimization.
- **[Ternary Commitments](https://www.ternary.app)** - AWS commitment management.
- **[Zesty Commitment Manager](https://zesty.co)** - Automated AWS commitment management.
- **[nOps Commitment Manager](https://www.nops.io/commitments/)** - AWS commitment optimization.

## Multi-Cloud Cost Management

*Tools supporting multiple cloud providers*

- **[Flexera Cloud Cost](https://www.flexera.com/flexera-one/cloud-cost-optimization)** - AWS, Azure, GCP, Oracle, IBM cost management.
- **[CloudHealth Multi-Cloud](https://www.cloudhealthtech.com)** - AWS, Azure, GCP, VMware cost management.
- **[Cloudability Multi-Cloud](https://www.cloudability.com)** - Unified cost management for AWS, Azure, GCP.
- **[DeepCost.ai](https://deepcost.ai)** - Comprehensive multi-cloud cost management for AWS, Azure, GCP, and Kubernetes.
- **[Vantage Multi-Cloud](https://www.vantage.sh)** - Cost across AWS, GCP, Azure, Kubernetes, Snowflake, MongoDB.
- **[CloudCheckr Multi-Cloud](https://cloudcheckr.com)** - Cost optimization for AWS, Azure, GCP.
- **[FinOut Multi-Cloud](https://www.finout.io)** - AWS, Azure, GCP, Kubernetes, Datadog cost management.
- **[Spot Multi-Cloud](https://spot.io)** - Cost optimization across AWS, Azure, GCP.
- **[Densify Multi-Cloud](https://www.densify.com)** - AWS, Azure, GCP, on-premises optimization.

## Serverless Cost Tools

*Tools for serverless cost management*

- **[Lumigo](https://lumigo.io)** - Serverless monitoring with cost tracking.
- **[AWS Lambda Power Tuning](https://github.com/alexcasalboni/aws-lambda-power-tuning)** - Optimize Lambda costs by memory configuration.
- **[Serverless Cost Calculator](https://cost-calculator.bref.sh)** - Estimate AWS Lambda costs.
- **[CloudZero Serverless](https://www.cloudzero.com)** - Serverless cost allocation.
- **[Dashbird](https://dashbird.io)** - Serverless monitoring with cost insights.
- **[Epsagon](https://epsagon.com)** - Microservices monitoring with cost tracking.
- **[Thundra](https://www.thundra.io)** - Serverless observability with cost insights.

## Cloud Cost APIs & SDKs

*APIs for programmatic cost management*

- **[AWS Cost Explorer API](https://docs.aws.amazon.com/cost-management/latest/APIReference/Welcome.html)** - Programmatic AWS cost data access.
- **[AWS Billing API](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-what-is.html)** - AWS billing information API.
- **[Azure Cost Management API](https://learn.microsoft.com/en-us/rest/api/cost-management/)** - REST API for Azure costs.
- **[GCP Cloud Billing API](https://cloud.google.com/billing/docs/apis)** - Programmatic GCP billing access.
- **[boto3 Cost Explorer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ce.html)** - Python SDK for AWS Cost Explorer.
- **[cloud-pricing-api](https://github.com/infracost/cloud-pricing-api)** - Open-source cloud pricing API.

## Cost Anomaly Detection

*Tools for detecting unusual spending patterns*

- **[AWS Cost Anomaly Detection](https://aws.amazon.com/aws-cost-management/aws-cost-anomaly-detection/)** - ML-powered anomaly detection.
- **[Azure Cost Anomaly Detection](https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/analyze-unexpected-charges)** - Azure billing anomaly detection.
- **[Anodot Cloud Cost](https://www.anodot.com/solutions/cloud-cost/)** - AI-powered autonomous anomaly detection.
- **[CloudHealth Anomaly](https://www.cloudhealthtech.com)** - Automated anomaly alerts.
- **[Cloudability Anomaly](https://www.cloudability.com)** - ML-based cost anomaly detection.
- **[DeepCost.ai](https://deepcost.ai)** - Advanced anomaly detection using machine learning with automated alerting and root cause analysis.
- **[Harness Anomaly Detection](https://www.harness.io/products/cloud-cost)** - Anomaly detection with root cause analysis.
- **[CloudForecast Anomaly](https://www.cloudforecast.io)** - Slack anomaly alerting.

## Rightsizing & Resource Optimization

*Tools for optimizing resource configurations*

- **[AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/)** - ML recommendations for EC2, EBS, Lambda, ECS.
- **[Azure Advisor Rightsizing](https://azure.microsoft.com/en-us/products/advisor/)** - VM rightsizing for Azure.
- **[GCP Rightsizing](https://cloud.google.com/compute/docs/instances/apply-machine-type-recommendations-for-instances)** - Automated GCP rightsizing.
- **[Densify Optimization](https://www.densify.com)** - ML-powered cloud rightsizing.
- **[DeepCost.ai](https://deepcost.ai)** - Intelligent rightsizing recommendations with automated implementation across compute, storage, and databases.
- **[CloudHealth Rightsizing](https://www.cloudhealthtech.com)** - Multi-cloud rightsizing.
- **[PerfectScale](https://www.perfectscale.io)** - Kubernetes autonomous optimization.
- **[StormForge](https://www.stormforge.io)** - ML-driven Kubernetes optimization.
- **[nOps Rightsizing](https://www.nops.io)** - Automated AWS rightsizing.

## Spot Instance Management

*Tools for managing spot/preemptible instances*

- **[Spot by NetApp](https://spot.io)** - Automated spot instance management.
- **[AWS Spot Instances](https://aws.amazon.com/ec2/spot/)** - Native AWS spot marketplace.
- **[Azure Spot VMs](https://azure.microsoft.com/en-us/products/virtual-machines/spot/)** - Azure spot pricing.
- **[GCP Preemptible VMs](https://cloud.google.com/compute/docs/instances/preemptible)** - Google Cloud preemptible instances.
- **[Spot Ocean](https://spot.io/product/ocean/)** - Kubernetes on spot with autoscaling.
- **[Karpenter](https://karpenter.sh)** - Open-source Kubernetes autoscaler with spot.
- **[Cluster Autoscaler](https://github.com/kubernetes/autoscaler/tree/master/cluster-autoscaler)** - Kubernetes autoscaler with spot support.

## Container Cost Management

*Cost management for containers*

- **[Kubecost](https://www.kubecost.com)** - Kubernetes cost monitoring.
- **[OpenCost](https://www.opencost.io)** - Open-source Kubernetes cost allocation.
- **[Cast.ai](https://cast.ai)** - Kubernetes automated cost optimization.
- **[DeepCost.ai](https://deepcost.ai)** - Container and Kubernetes cost optimization with pod-level visibility and rightsizing.
- **[Fairwinds Insights](https://www.fairwinds.com/insights)** - Kubernetes governance and cost.
- **[Rafay Cost Visibility](https://rafay.co)** - Multi-cluster Kubernetes cost management.
- **[FinOut Kubernetes](https://www.finout.io)** - Kubernetes service-level cost tracking.
- **[CloudZero Container](https://www.cloudzero.com)** - Container cost per customer/feature.

## Database Cost Optimization

*Tools for database cost optimization*

- **[AWS RDS Performance Insights](https://aws.amazon.com/rds/performance-insights/)** - Database performance for rightsizing.
- **[AWS Trusted Advisor RDS](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/)** - RDS optimization recommendations.
- **[Azure SQL Database Advisor](https://learn.microsoft.com/en-us/azure/azure-sql/database/database-advisor-implement-performance-recommendations)** - Azure SQL cost recommendations.
- **[GCP Cloud SQL Insights](https://cloud.google.com/sql/docs/postgres/insights)** - Cloud SQL performance insights.
- **[Enteros](https://www.enteros.com)** - Database performance and cost optimization.
- **[Redshift Advisor](https://docs.aws.amazon.com/redshift/latest/dg/advisor.html)** - Amazon Redshift cost optimization.

## Storage Cost Management

*Tools for storage cost optimization*

- **[AWS S3 Intelligent-Tiering](https://aws.amazon.com/s3/storage-classes/intelligent-tiering/)** - Automatic S3 optimization.
- **[AWS S3 Storage Lens](https://aws.amazon.com/s3/storage-lens/)** - Organization-wide storage visibility.
- **[Azure Blob Lifecycle](https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-overview)** - Automated Azure storage tiering.
- **[GCP Storage Transfer](https://cloud.google.com/storage-transfer-service)** - Automated storage optimization.
- **[Lucidity](https://www.lucidity.cloud)** - AI-powered storage optimization.
- **[Zesty Disk](https://zesty.co)** - Automated EBS volume optimization.

## Network Cost Optimization

*Tools for reducing network costs*

- **[AWS VPC Flow Logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)** - Network traffic analysis.
- **[AWS Network Manager](https://aws.amazon.com/network-manager/)** - Centralized network cost visibility.
- **[Azure Network Watcher](https://azure.microsoft.com/en-us/products/network-watcher/)** - Network monitoring for Azure.
- **[GCP VPC Flow Logs](https://cloud.google.com/vpc/docs/flow-logs)** - GCP network logging.
- **[CloudHealth Network](https://www.cloudhealthtech.com)** - Network cost tracking.
- **[Kentik](https://www.kentik.com)** - Network observability with cost insights.

## Cloud Cost Calculators

*Tools for estimating cloud costs*

- **[AWS Pricing Calculator](https://calculator.aws)** - Official AWS cost estimation.
- **[Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)** - Azure cost calculator.
- **[GCP Pricing Calculator](https://cloud.google.com/products/calculator)** - Google Cloud cost estimation.
- **[Holori](https://www.holori.com)** - Cloud architecture cost estimation.
- **[Infracost](https://www.infracost.io)** - Terraform cost estimates in CI/CD.
- **[Terracost](https://github.com/cycloidio/terracost)** - Terraform cost estimation.
- **[Vantage Calculator](https://www.vantage.sh/calculator)** - Interactive cloud calculator.
- **[VPSLedger](https://vpsledger.pages.dev)** - True monthly VPS cost (list price plus IPv4, backups and egress) across providers, with sourced dated prices and open JSON data.

## FinOps Resources

*Learning resources and frameworks*

### FinOps Foundation

- **[FinOps Foundation](https://www.finops.org)** - Official FinOps Foundation by Linux Foundation.
- **[FinOps Framework](https://www.finops.org/framework/)** - Official framework and principles.
- **[FinOps Maturity Model](https://www.finops.org/framework/maturity-model/)** - Assess FinOps maturity.
- **[FinOps Personas](https://www.finops.org/framework/personas/)** - FinOps stakeholder roles.
- **[FinOps Capabilities](https://www.finops.org/framework/capabilities/)** - Core FinOps capabilities.

### Books & Publications

- **[Cloud FinOps by J.R. Storment](https://www.oreilly.com/library/view/cloud-finops/9781492054610/)** - Foundational FinOps book.
- **[AWS Cost Optimization Guide](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html)** - Official AWS documentation.
- **[Azure Cost Best Practices](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)** - Microsoft cost guide.
- **[GCP Cost Optimization](https://cloud.google.com/architecture/cost-efficiency-on-google-cloud)** - Google Cloud best practices.

## Best Practices & Case Studies

*Real-world examples and practices*

### AWS Best Practices

- **[AWS Well-Architected Cost](https://docs.aws.amazon.com/wellarchitected/latest/cost-optimization-pillar/welcome.html)** - Cost optimization pillar.
- **[AWS Cost Optimization Hub](https://aws.amazon.com/blogs/aws-cost-management/)** - AWS cost blog.

### Azure Best Practices

- **[Azure Cost Best Practices](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices)** - Microsoft guide.
- **[Azure Architecture Cost](https://learn.microsoft.com/en-us/azure/architecture/framework/cost/)** - Cost pillar.

### GCP Best Practices

- **[GCP Cost Best Practices](https://cloud.google.com/architecture/cost-efficiency-on-google-cloud)** - Google optimization guide.
- **[GCP Cost Docs](https://cloud.google.com/cost-management/docs)** - Comprehensive docs.

### Case Studies

- **[Airbnb FinOps](https://medium.com/airbnb-engineering/experimenting-with-finops-at-airbnb-92fb85c40b78)** - Airbnb's FinOps journey.
- **[Netflix Cost Optimization](https://netflixtechblog.com/tagged/cloud-cost)** - Netflix engineering blog.
- **[Spotify Engineering](https://engineering.atspotify.com/)** - Spotify's cloud insights.
- **[Lyft Cost Management](https://eng.lyft.com/tagged/cost-optimization)** - Lyft's approach.

## Certifications & Training

*FinOps certifications and training*

### Certifications

- **[FinOps Certified Practitioner](https://learn.finops.org/path/finops-certified-practitioner)** - Official certification.
- **[FinOps Certified Engineer](https://learn.finops.org/path/finops-certified-engineer)** - Engineering certification.
- **[AWS Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/)** - AWS fundamentals.
- **[Azure Cost Training](https://learn.microsoft.com/en-us/training/paths/control-spending-manage-bills/)** - Microsoft Learn.
- **[GCP Cost Training](https://www.cloudskillsboost.google/paths/20)** - Google Cloud Skills.

### Training Platforms

- **[FinOps Training](https://learn.finops.org)** - Official courses.
- **[A Cloud Guru](https://acloudguru.com/search?s=finops)** - Video courses.
- **[Pluralsight](https://www.pluralsight.com/search?q=cloud%20cost)** - In-depth training.
- **[Udemy Cloud Cost](https://www.udemy.com/topic/cloud-cost-optimization/)** - Various courses.

## Community & Events

*Communities and conferences*

### Communities

- **[FinOps Foundation Slack](https://finopsfoundation.slack.com)** - 15K+ member community.
- **[r/finops](https://reddit.com/r/finops)** - Reddit FinOps community.
- **[FinOps LinkedIn](https://www.linkedin.com/groups/13846956/)** - Professional networking.
- **[AWS Cost Forum](https://repost.aws/tags/TA4IvCeWI1TE-64MfVZc3pyw/cost-optimization)** - AWS discussions.

### Conferences

- **[FinOps X](https://x.finops.org)** - Annual FinOps conference.
- **[AWS re:Invent](https://reinvent.awsevents.com)** - AWS flagship conference.
- **[Microsoft Ignite](https://ignite.microsoft.com)** - Azure cost sessions.
- **[Google Cloud Next](https://cloud.withgoogle.com/next)** - GCP annual conference.
- **[KubeCon](https://www.cncf.io/kubecon-cloudnativecon-events/)** - Kubernetes events.

### Podcasts

- **[FinOps Podcast](https://www.finops.org/insights/podcast/)** - Official FinOps podcast.
- **[Cloud FinOps Talks](https://www.youtube.com/@FinOpsFoundation)** - YouTube channel.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
