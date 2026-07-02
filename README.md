# Orchestration (orchestration)
An index and topic collection covering container orchestration and workflow orchestration platforms. Container orchestration platforms like Kubernetes, OpenShift, Amazon EKS, Google Kubernetes Engine, and Azure Kubernetes Service schedule and manage containerized workloads across clusters of machines, handling deployment, scaling, networking, and self-healing. Workflow orchestration engines like Temporal, Apache Airflow, Argo Workflows, AWS Step Functions, Prefect, Dagster, and Kestra coordinate the execution of long-running, multi-step business processes, data pipelines, and durable workflows. This collection brings together the operators, schedulers, control planes, and durable execution engines that turn declarative specifications into running systems.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Orchestration, Container Orchestration, Workflow Orchestration, Kubernetes, Scheduler

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Workload Schema](https://raw.githubusercontent.com/api-evangelist/orchestration/refs/heads/main/json-schema/orchestration-workload-schema.json)
- [JSONSchema - Workflow Definition Schema](https://raw.githubusercontent.com/api-evangelist/orchestration/refs/heads/main/json-schema/orchestration-workflow-definition-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/orchestration/refs/heads/main/json-ld/orchestration-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/orchestration/refs/heads/main/vocabulary/orchestration-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Declarative Workload Scheduling | Container orchestrators like Kubernetes, Nomad, and ECS take declarative workload specifications and continuously reconcile cluster state to match the desired configuration. |
| Horizontal and Event-Driven Autoscaling | Platforms like Kubernetes HPA, KEDA, and Karpenter scale workloads and nodes based on CPU, memory, custom metrics, or external event sources. |
| Durable Workflow Execution | Workflow engines like Temporal, AWS Step Functions, and Inngest provide durable, fault-tolerant execution for long-running, multi-step processes. |
| Data Pipeline Orchestration | Data orchestrators like Airflow, Prefect, Dagster, and Kestra schedule and monitor DAG-based data pipelines across batch, streaming, and ML workloads. |
| GitOps and Continuous Deployment | GitOps controllers like Argo CD and Flux CD reconcile Git-defined manifests into running clusters, enabling auditable continuous deployment. |
| Multi-Cluster and Hybrid Cloud Control Planes | Platforms like Rancher, OpenShift, Tanzu, Mirantis, and Crossplane provide unified control planes for managing many clusters across cloud and on-prem. |
| Serverless Containers and Functions | Services like AWS Fargate, Knative, and Google Cloud Run abstract away node management, billing per request or per second of execution. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Platform | Engineering organizations deploy Kubernetes (EKS, GKE, AKS, OpenShift) as a microservices platform for service discovery, rolling deployments, and automated recovery. |
| Batch and Stream Data Pipelines | Data teams use Airflow, Dagster, Prefect, or Kestra to orchestrate ETL/ELT pipelines, ML training, and reporting jobs across warehouses and lakes. |
| Durable Business Process Workflows | Product teams use Temporal, Step Functions, Conductor, or Inngest to implement order processing, payments, and approval workflows that survive failures. |
| GitOps Continuous Delivery | Platform teams use Argo CD or Flux CD to deliver application changes to many clusters by promoting Git commits across environments. |
| Hybrid Cloud Cluster Fleet Management | Enterprises use Rancher, Tanzu, Mirantis Kubernetes Engine, or OpenShift to manage fleets of clusters across on-prem and public clouds. |
| Event-Driven Background Jobs | Application teams use Inngest, Trigger.dev, KEDA, or Cloud Scheduler to run background jobs triggered by events, schedules, or webhooks. |
| AI Agent Workflow Orchestration | AI teams use durable workflow engines like Temporal and Inngest to orchestrate long-running agent workflows, tool calls, and human-in-the-loop approvals. |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | The de facto container orchestration platform from CNCF for declarative scheduling, scaling, and management of containerized workloads. |
| Amazon EKS | AWS managed Kubernetes service with deep integration into IAM, VPC, Fargate, and other AWS services. |
| Google Kubernetes Engine | Google Cloud's managed Kubernetes service with Autopilot, multi-cluster mesh, and tight GCP integration. |
| Argo Workflows | Kubernetes-native workflow engine for running DAGs of containerized steps for CI/CD, ML, and data processing. |
| Temporal | Durable execution platform for building long-running, fault-tolerant workflows with code-defined state machines. |
| Apache Airflow | Open-source workflow orchestration platform for authoring, scheduling, and monitoring DAG-based data pipelines. |
| AWS Step Functions | Serverless workflow service for coordinating AWS Lambda functions and AWS services into multi-step state machines. |
| Argo CD | Declarative GitOps continuous delivery tool for Kubernetes that automates application deployment from Git repositories. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Workload Schema](json-schema/orchestration-workload-schema.json)
- [Workflow Definition Schema](json-schema/orchestration-workflow-definition-schema.json)

### JSON Structure

- [Workload Structure](json-structure/orchestration-workload-structure.json)
- [Workflow Definition Structure](json-structure/orchestration-workflow-definition-structure.json)

### JSON-LD

- [Orchestration Context](json-ld/orchestration-context.jsonld)

## Vocabulary

- [Orchestration Vocabulary](vocabulary/orchestration-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 8 actions, 3 workflows, and 3 personas across container and workflow orchestration platforms

## Network

This index references the following container and workflow orchestration repositories:

- [Kubernetes](https://github.com/api-evangelist/kubernetes)
- [OpenShift](https://github.com/api-evangelist/openshift)
- [Rancher](https://github.com/api-evangelist/rancher)
- [HashiCorp Nomad](https://github.com/api-evangelist/hashicorp-nomad)
- [Amazon ECS](https://github.com/api-evangelist/amazon-ecs)
- [Amazon EKS](https://github.com/api-evangelist/amazon-eks)
- [AWS Fargate](https://github.com/api-evangelist/fargate)
- [Google Kubernetes Engine](https://github.com/api-evangelist/google-kubernetes-engine)
- [Azure Kubernetes Service](https://github.com/api-evangelist/azure-kubernetes-service)
- [Docker Swarm](https://github.com/api-evangelist/docker-swarm)
- [K3s](https://github.com/api-evangelist/k3s)
- [VMware Tanzu](https://github.com/api-evangelist/vmware-tanzu)
- [Mirantis](https://github.com/api-evangelist/mirantis)
- [Apache Mesos](https://github.com/api-evangelist/apache-mesos)
- [Knative](https://github.com/api-evangelist/knative)
- [KEDA](https://github.com/api-evangelist/keda)
- [Crossplane](https://github.com/api-evangelist/crossplane)
- [Argo CD](https://github.com/api-evangelist/argo-cd)
- [Argo Workflows](https://github.com/api-evangelist/argo-workflows)
- [Flux CD](https://github.com/api-evangelist/fluxcd)
- [Dapr](https://github.com/api-evangelist/dapr)
- [Carvel](https://github.com/api-evangelist/carvel)
- [Codefresh](https://github.com/api-evangelist/codefresh)
- [Facets](https://github.com/api-evangelist/facets)
- [Temporal](https://github.com/api-evangelist/temporal)
- [Conductor](https://github.com/api-evangelist/conductor)
- [Netflix Conductor](https://github.com/api-evangelist/netflix-conductor)
- [Inngest](https://github.com/api-evangelist/inngest)
- [Trigger.dev](https://github.com/api-evangelist/trigger-dev)
- [Apache Airflow](https://github.com/api-evangelist/airflow)
- [Apache DolphinScheduler](https://github.com/api-evangelist/apache-dolphinscheduler)
- [Prefect](https://github.com/api-evangelist/prefect)
- [Dagster](https://github.com/api-evangelist/dagster)
- [Kestra](https://github.com/api-evangelist/kestra)
- [Flyte](https://github.com/api-evangelist/flyte)
- [AWS Step Functions](https://github.com/api-evangelist/aws-step-functions)
- [Google Cloud Workflows](https://github.com/api-evangelist/google-cloud-workflows)
- [Google Cloud Composer](https://github.com/api-evangelist/google-cloud-composer)
- [Google Cloud Scheduler](https://github.com/api-evangelist/google-cloud-scheduler)
- [Google Cloud Deploy](https://github.com/api-evangelist/google-cloud-deploy)
- [Serverless Workflow](https://github.com/api-evangelist/serverless-workflow)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
