# Claude Code Agents Collection

A comprehensive collection of specialized AI subagents for Claude Code, designed to enhance development workflows with domain-specific expertise and modern best practices.

## Overview

This repository contains expertly crafted agent specifications that extend Claude Code's capabilities across various domains of software engineering. Each agent is designed with deep domain expertise, modern tooling, and production-ready practices.

## Available Agents

### 🔍 [Requirements Analyst](./analyst.md)
**Name**: `spec-analyst`  
**Specialization**: Requirements analysis and project scoping expert

**Key Capabilities**:
- Advanced requirements elicitation using Design Thinking and Jobs-to-be-Done frameworks
- Comprehensive stakeholder analysis with RACI matrices and power/interest grids
- Modern documentation formats (BDD Gherkin, API-first specifications, Event Storming)
- AI/ML project requirements and ethical AI compliance
- Multi-framework compliance automation (GDPR, SOC2, ISO27001, NIST CSF 2.0)
- Threat modeling integration and security requirements
- Agile integration with story mapping and continuous requirements

**Best For**: Complex project planning, regulatory compliance projects, AI/ML initiatives, enterprise software requirements

---

### ☁️ [Cloud Architect - AWS](./cloud-architect-aws.md)
**Name**: `cloud-architect`  
**Specialization**: AWS infrastructure design and Well-Architected Framework implementation

**Key Capabilities**:
- AWS Well-Architected Framework expertise (Security, Reliability, Performance, Cost, Operational Excellence)
- Infrastructure as Code with AWS CDK, Terraform, and CloudFormation
- Container orchestration with EKS, ECS, and Fargate
- Serverless architectures with Lambda, Step Functions, and API Gateway
- Cost optimization with Savings Plans, Reserved Instances, and Cost Explorer
- Security best practices with VPC, IAM, GuardDuty, and Security Hub
- Multi-region deployments and disaster recovery planning

**Best For**: AWS cloud migrations, scalable infrastructure design, cost optimization, compliance automation

---

### 🎨 [Frontend Developer](./frontend-developer.md)
**Name**: `frontend-developer`  
**Specialization**: Modern frontend applications with performance and accessibility focus

**Key Capabilities**:
- Multi-framework expertise (React, Next.js, Vue, Svelte, vanilla JS)
- Modern build tools and bundlers (Vite, Webpack, esbuild)
- State management solutions (Redux Toolkit, Zustand, Jotai, TanStack Query)
- Comprehensive testing (Jest, Vitest, Playwright, Cypress)
- Accessibility compliance (WCAG 2.1 AA) and inclusive design
- Performance optimization (Core Web Vitals, lazy loading, code splitting)
- Progressive Web Apps and offline functionality

**Best For**: Modern web applications, performance optimization, accessibility compliance, testing infrastructure

---

### ⚛️ [React Specialist](./react-developer.md)
**Name**: `react-specialist`  
**Specialization**: Expert React 18+ development with modern patterns

**Key Capabilities**:
- React 18+ features (Concurrent Features, Server Components, Suspense)
- Advanced hooks patterns and custom hook development
- Performance optimization with React.memo, useMemo, and useCallback
- Modern React ecosystem integration (React Query, React Hook Form)
- Server-side rendering with Next.js and Remix
- Component library development with Storybook
- Production-ready architecture patterns

**Best For**: React-specific projects, component libraries, performance-critical applications, modern React patterns

---

### 🔒 [Security Engineer](./security-engineer.md)
**Name**: `security-engineer`  
**Specialization**: Infrastructure security, DevSecOps, and modern threat management

**Key Capabilities**:
- Supply chain security with SBOM generation and artifact signing (Sigstore, Cosign)
- AI/ML security including model protection and adversarial attack prevention
- Cloud-native security with CNAPP platforms and container protection
- DevSecOps automation with Policy as Code (OPA, Gatekeeper)
- Modern threat detection with XDR, SIEM evolution, and behavioral analytics
- Compliance automation for multiple frameworks (SOC2, ISO27001, FedRAMP, GDPR)
- Zero-trust architecture and continuous threat exposure management

**Best For**: Security hardening, compliance automation, container security, threat modeling, incident response

## Usage Guidelines

### Getting Started

1. **Choose the Right Agent**: Select the agent that best matches your domain and requirements
2. **Review Capabilities**: Each agent has specific focus areas and modern tooling expertise
3. **Integration**: Agents are designed to work together on complex, multi-domain projects

### Agent Invocation

Agents are designed to be used proactively by Claude Code when tasks match their expertise. Key triggers include:

- **Requirements Analyst**: Complex project planning, stakeholder analysis, compliance requirements
- **Cloud Architect**: AWS infrastructure design, cost optimization, migration planning
- **Frontend Developer**: UI component creation, performance optimization, accessibility fixes
- **React Specialist**: React-specific development, component libraries, modern patterns
- **Security Engineer**: Security hardening, vulnerability management, compliance automation

### Best Practices

#### Multi-Agent Workflows

For complex projects, agents can collaborate:

```
Requirements Analyst → Cloud Architect → Security Engineer → Frontend Developer
```

1. **Analyst** defines comprehensive requirements and stakeholder needs
2. **Cloud Architect** designs scalable, cost-effective infrastructure
3. **Security Engineer** implements security controls and compliance
4. **Frontend Developer** builds user-facing applications

#### Agent Selection Matrix

| Project Type | Primary Agent | Supporting Agents |
|--------------|---------------|-------------------|
| Enterprise Web App | Frontend Developer | Security Engineer, Analyst |
| AWS Migration | Cloud Architect | Security Engineer, Analyst |
| Compliance Project | Analyst | Security Engineer, Cloud Architect |
| React Component Library | React Specialist | Frontend Developer |
| Security Hardening | Security Engineer | Cloud Architect |

## Modern Technologies Covered

### Infrastructure & Cloud
- **AWS**: Complete ecosystem (EKS, Lambda, CloudFormation, CDK)
- **Infrastructure as Code**: Terraform, AWS CDK, CloudFormation
- **Containers**: Docker, Kubernetes, EKS, ECS, Fargate
- **Serverless**: Lambda, Step Functions, API Gateway

### Frontend & UI
- **Frameworks**: React 18+, Next.js, Vue, Svelte
- **Build Tools**: Vite, Webpack, esbuild, Rollup
- **Testing**: Jest, Vitest, Playwright, Cypress, React Testing Library
- **State Management**: Redux Toolkit, Zustand, Jotai, TanStack Query

### Security & Compliance
- **Supply Chain**: SBOM (Syft, Grype), Sigstore, Cosign
- **Container Security**: Falco, Trivy, admission controllers
- **Policy as Code**: Open Policy Agent (OPA), Gatekeeper
- **Compliance**: SOC2, ISO27001, GDPR, NIST CSF 2.0

### Development Practices
- **DevSecOps**: Shift-left security, automated scanning
- **Testing**: TDD, BDD, security testing, chaos engineering
- **Observability**: Logging, monitoring, alerting, tracing
- **Documentation**: Living docs, API-first, threat modeling

## Contributing

When adding new agents or updating existing ones:

1. **Follow Modern Practices**: Include latest tools, frameworks, and methodologies
2. **Security by Default**: Integrate security considerations throughout
3. **Production Ready**: Focus on scalable, maintainable, observable solutions
4. **Clear Documentation**: Provide comprehensive capabilities and usage examples

## Agent Specifications Format

Each agent follows a structured format:

```markdown
---
name: agent-name
description: Brief description with key capabilities
model: sonnet|opus (optional)
tools: List of specialized tools (optional)
---

## Focus Areas
- Domain-specific expertise areas

## Approach
- Methodology and principles

## Output
- Expected deliverables and artifacts

## Guidelines
- Best practices and constraints
```

## License

This collection is designed for use with Claude Code and follows Anthropic's usage guidelines for AI agents and tool integrations.

---

**Last Updated**: August 2025  
**Claude Code Version**: Compatible with latest release  
**Maintained By**: [@konkonstantinidis](https://github.com/konkonstantinidis)