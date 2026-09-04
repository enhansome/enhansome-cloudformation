# Awesome cloudformation with stars

## Awesome CloudFormation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources and projects for working with [AWS CloudFormation](https://aws.amazon.com/cloudformation/).

## Contents

* [Awesome CloudFormation <img src="https://awesome.re/badge.svg" alt="Awesome">](#awesome-cloudformation-img-src%22httpsawesomerebadgesvg%22-alt%22awesome%22)
* [Contents](#contents)
* [CloudFormation Samples](#cloudformation-samples)
  * [Templates](#templates)
  * [Modules](#modules)
  * [Resource Types](#resource-types)
  * [Hooks](#hooks)
* [Authoring and Testing Tools](#authoring-and-testing-tools)
* [CLI Tools](#cli-tools)
* [Code Generation](#code-generation)
* [Custom Resource Development](#custom-resource-development)
* [Third Party Resource Types](#third-party-resource-types)
* [Third Party Hooks](#third-party-hooks)
* [Macros](#macros)
* [Public Coverage Roadmap](#public-coverage-roadmap)
* [Blog Posts and Talks](#blog-posts-and-talks)
* [Documentation](#documentation)
  * [Reference Guides](#reference-guides)
    * [AWS](#aws)
    * [3rd parties](#3rd-parties)
* [Contribute](#contribute)
* [License Summary](#license-summary)

## CloudFormation Samples

The following are pre-built CloudFormation Samples demonstrating how to use AWS CloudFormation to construct various canned resources, modules, applications or resource groupings.

### Templates

* [aws-cloudformation-templates](https://github.com/awslabs/aws-cloudformation-templates) ⭐ 5,212 | 🐛 5 | 🌐 Python | 📅 2026-07-28: Sample AWS CloudFormation templates which are intended to support learning how to declare specific AWS resources or solve particular use cases.
* [aws-cf-templates](https://github.com/widdix/aws-cf-templates) ⭐ 2,778 | 🐛 26 | 🌐 Java | 📅 2026-03-04: Free Templates for AWS CloudFormation
* [aws-quickstart](https://github.com/aws-quickstart): Automated gold-standard deployments on AWS
* [asecure.cloud](https://asecure.cloud/): A free repository of customizable AWS security configurations and best practices

### Modules

* [aws-cloudformation-samples](https://github.com/aws-cloudformation/aws-cloudformation-samples/tree/main/modules) ⭐ 147 | 🐛 10 | 🌐 Python | 📅 2026-01-26: Reusable CloudFormation modules to jump start your collection.

### Resource Types

* [aws-cloudformation-samples](https://github.com/aws-cloudformation/aws-cloudformation-samples/tree/main/resource-types) ⭐ 147 | 🐛 10 | 🌐 Python | 📅 2026-01-26: Sample CloudFormation Resource Types

### Hooks

* [aws-cloudformation-samples](https://github.com/aws-cloudformation/aws-cloudformation-samples/tree/main/hooks) ⭐ 147 | 🐛 10 | 🌐 Python | 📅 2026-01-26: Sample CloudFormation Hooks

## Authoring and Testing Tools

These tools are designed to assist in the authoring and testing process for AWS CloudFormation. Tools include template generation, linting and testing applications.

* [cfn-python-lint](https://github.com/aws-cloudformation/cfn-python-lint) ⭐ 2,639 | 🐛 84 | 🌐 Python | 📅 2026-09-04: Validate CloudFormation yaml/json templates against the CloudFormation spec and additional checks. Includes checking valid values for resource properties and best practices.
* [Former2](https://github.com/iann0036/former2) ⭐ 2,413 | 🐛 182 | 🌐 JavaScript | 📅 2026-07-07: Generate CloudFormation / Terraform / Troposphere templates from your existing AWS resource
* [org-formation](https://github.com/OlafConijn/AwsOrganizationFormation) ⭐ 1,489 | 🐛 100 | 🌐 TypeScript | 📅 2026-01-19: a tool that helps you write CloudFormation for your AWS Organization resources and create links between regular cloudformation resources across your accounts and regions.
* [AWSConsoleRecorder](https://github.com/iann0036/AWSConsoleRecorder) ⚠️ Archived: Records actions made in the AWS Management Console and outputs the equivalent CLI/SDK commands and CloudFormation/Terraform templates.
* [cfn-guard](https://github.com/aws-cloudformation/cloudformation-guard) ⭐ 1,388 | 🐛 52 | 🌐 Rust | 📅 2026-09-02: A set of tools to check AWS CloudFormation templates for policy compliance using a simple, policy-as-code, declarative syntax
* [cfn\_nag](https://github.com/stelligent/cfn_nag) ⭐ 1,308 | 🐛 84 | 🌐 Ruby | 📅 2024-08-01: The cfn-nag tool looks for patterns in CloudFormation templates that may indicate insecure infrastructure.
* [taskcat](https://github.com/aws-quickstart/taskcat) ⭐ 1,205 | 🐛 42 | 🌐 Python | 📅 2026-07-24: taskcat is a tool that tests AWS CloudFormation templates. It deploys your AWS CloudFormation template in multiple AWS Regions and generates a report with a pass/fail grade for each region.
* [cfn-diagram](https://github.com/ljacobsson/cfn-diagram) ⭐ 1,021 | 🐛 38 | 🌐 JavaScript | 📅 2024-04-19: CLI tool to visualise CloudFormation/SAM/CDK templates as diagrams.
* [Visual Studio Code extension](https://github.com/aws-cloudformation/aws-cfn-lint-visual-studio-code) ⭐ 289 | 🐛 45 | 🌐 JavaScript | 📅 2026-09-04: CloudFormation Linter integration, autocompletion, reference documentation links on hover
* [cfn flip](https://cfnflip.com/): a tool that converts AWS CloudFormation templates between JSON and YAML formats.
* [cfsec](https://cfsec.dev): CloudFormation static analysis to identify potential misconfigurations before they reach production.

## CLI Tools

This section contains tools which have been designed to improve the experience of interacting with the CloudFormation service through a terminal session.

* [sceptre](https://github.com/Sceptre/sceptre) ⭐ 1,533 | 🐛 26 | 🌐 Python | 📅 2026-08-03: Sceptre is a tool to drive AWS CloudFormation. It automates the mundane, repetitive and error-prone tasks, enabling you to concentrate on building better infrastructure.
* [rain](https://github.com/aws-cloudformation/rain) ⚠️ Archived: A command line tool for working with AWS CloudFormation. It has tools for creating, comparing, and formatting templates and a pleasant CLI experience for creating, updating, and deleting stacks.
* [stacker](https://github.com/cloudtools/stacker) ⭐ 707 | 🐛 79 | 🌐 Python | 📅 2023-11-28: An AWS CloudFormation Stack orchestrator/manager.
* [cfn-teleport](https://github.com/udondan/cfn-teleport) ⭐ 102 | 🐛 2 | 🌐 Rust | 📅 2026-07-01: A command-line tool which can move CloudFormation resources between stacks.
* [stackup](https://github.com/realestate-com-au/stackup) ⭐ 98 | 🐛 11 | 🌐 Ruby | 📅 2025-02-27: Stackup provides a CLI and a simplified Ruby API for dealing with AWS CloudFormation stacks.
* [awscfncli](https://github.com/Kotaimen/awscfncli) ⭐ 58 | 🐛 27 | 🌐 Python | 📅 2023-11-24: awscfncli helps build and manage complex AWS CloudFormation stacks.
* [cfn-teardown](https://github.com/nirdosh17/cfn-teardown) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2024-08-15: Cleanup CloudFormation stacks respecting the order of dependencies.

## Code Generation

If you prefer imperative coding, or just using your favourite programming language, the following projects are intended to abstract the creation of AWS CloudFormation templates.

* [aws-cdk](https://github.com/aws/aws-cdk) ⭐ 12,886 | 🐛 2,867 | 🌐 TypeScript | 📅 2026-09-04: The AWS Cloud Development Kit (AWS CDK) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation.
* [serverless-application-model](https://github.com/awslabs/serverless-application-model) ⭐ 9,563 | 🐛 112 | 🌐 Python | 📅 2026-09-02: The AWS Serverless Application Model (SAM) is an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines of configuration, you can define the application you want and model it.
* [eksctl](https://github.com/weaveworks/eksctl) ⭐ 5,211 | 🐛 93 | 🌐 Go | 📅 2026-09-04: A CLI tool that uses CloudFormation to create clusters on EKS.
* [troposphere (Python)](https://github.com/cloudtools/troposphere) ⭐ 4,944 | 🐛 163 | 🌐 Python | 📅 2026-08-19: The troposphere library allows for easier creation of the AWS CloudFormation JSON by writing Python code to describe the AWS resources. troposphere also includes some basic support for OpenStack resources via Heat.
* [OpenJS Architect](https://github.com/architect/architect) ⭐ 2,622 | 🐛 64 | 🌐 JavaScript | 📅 2026-08-27: Generate AWS CloudFormation and AWS Serverless Application Model code from a very terse and friendly high level manifest file written in `JSON`, `YAML`, `TOML` or `.arc` format
* [mu](https://github.com/stelligent/mu) ⭐ 965 | 🐛 89 | 🌐 Go | 📅 2020-06-18: Similar to how the Serverless Framework improved the developer experience of Lambda and API Gateway, this tool makes it easier for developers to use EKS or ECS as a microservices platform.
* [cfndsl](https://github.com/cfndsl/cfndsl) ⭐ 425 | 🐛 8 | 🌐 Ruby | 📅 2026-08-09: Ruby DSL for generating AWS CloudFormation templates.
* [VaporShell (PowerShell)](https://github.com/scrthq/VaporShell) ⚠️ Archived: A PowerShell module for building, packaging and deploying AWS CloudFormation templates.
* [CloudFormation Snippets for VS Code](https://github.com/dannysteenman/cloudformation-yaml-snippets) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-09-04: This VS Code extension adds autocompletion for all the resources that AWS CloudFormation supports.
* [cfhighlander](https://github.com/theonestack/cfhighlander) ⭐ 24 | 🐛 33 | 🌐 Ruby | 📅 2026-05-11: Ruby DSL for generating AWS CloudFormation templates using Cfndsl in a modular and extensible manner
* [sparkleformation (Ruby)](https://github.com/sparkleformation): A magical Ruby infrastructure orchestration DSL

## Custom Resource Development

When you need to extend AWS CloudFormation to support your own personal or organizational use-cases, the following tools are intended to support the development experience with the [original Custom Resources](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-custom-resources.html) functionality and the new [CloudFormation Registry](https://aws.amazon.com/about-aws/whats-new/2019/11/now-extend-aws-cloudformation-to-model-provision-and-manage-third-party-resources/) experience.

* [custom-resource-helper](https://github.com/aws-cloudformation/custom-resource-helper) ⭐ 384 | 🐛 31 | 🌐 Python | 📅 2024-10-29: Simplify best practice Custom Resource creation, sending responses to CloudFormation and providing exception, timeout trapping, and detailed configurable logging.
* [cloudformation-cli](https://github.com/aws-cloudformation/cloudformation-cli) ⭐ 336 | 🐛 156 | 🌐 Python | 📅 2026-09-04: The CloudFormation Provider Development Toolkit allows you to author your own resource providers that can be used by CloudFormation.
* [cloudformation-cli-python-plugin](https://github.com/aws-cloudformation/cloudformation-cli-python-plugin) ⭐ 107 | 🐛 30 | 🌐 Python | 📅 2026-04-16: The CloudFormation Provider Development Toolkit Python Plugin allows you to autogenerate Python code based on an input schema.
* [cloudformation-cli-go-plugin](https://github.com/aws-cloudformation/cloudformation-cli-go-plugin) ⭐ 53 | 🐛 29 | 🌐 Go | 📅 2023-12-08: The CloudFormation Provider Development Toolkit Go Plugin allows you to autogenerate Go code based on an input schema.
* [cloudformation-cli-java-plugin](https://github.com/aws-cloudformation/cloudformation-cli-java-plugin) ⭐ 30 | 🐛 43 | 🌐 Java | 📅 2026-07-09: The CloudFormation Provider Development Toolkit Java Plugin allows you to autogenerate Java code based on an input schema.

## Third Party Resource Types

The following third-party vendors have created resource types using the CloudFormation CLI and can be downloaded and added to your accounts via the Registry.

* [Datadog](https://github.com/DataDog/datadog-cloudformation-resources#resources-available) ⭐ 55 | 🐛 24 | 🌐 Python | 📅 2026-08-20 Creates Datadog::Integrations::AWS, Datadog::Monitors::Monitor, Datadog::Monitors::Downtime, and Datadog::IAM::User
* [Atlassian](https://github.com/opsgenie/opsgenie-cloudformation-resources) ⭐ 10 | 🐛 6 | 🌐 Java | 📅 2023-06-27 Creates Atlassian::Opsgenie::User, Atlassian::Opsgenie::Team, and Atlassian::Opsgenie::Integration
* [NewRelic](https://github.com/newrelic/cloudformation-partner-integration) ⚠️ Archived Creates NewRelic::Alerts::NrqlAlert
* [Fortinet](https://github.com/fortinet/aws-cloudformation-resource-provider) ⚠️ Archived Creates Fortinet::FortiGate::SystemAdmin, Fortinet::FortiGate::SystemDns, and Fortinet::FortiGate::SystemInterface
* [Spotinst](https://github.com/spotinst/spotinst-aws-cloudformation-registry) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2026-01-26 Creates Spotinst::Elastigroup::Group
* [Densify](https://github.com/densify-dev/cloudformation-optimization-as-code) ⚠️ Archived Creates Densify::Optimization::Recommendation
* [Dynatrace](https://github.com/mnalezin/DynatraceInstallerAgent) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2019-11-19 Creates Dynatrace::Installer::Agent

## Third Party Hooks

* [Open Policy Agent](https://github.com/StyraInc/opa-aws-cloudformation-hook) ⭐ 37 | 🐛 9 | 🌐 Python | 📅 2025-12-15 Hook to allow policy-based decisions on stacks using [Open Policy Agent](https://www.openpolicyagent.org/)

## Macros

* [pl.wrzasq.cform](https://rafalwrzeszcz-wrzasqpl.github.io/pl.wrzasq.cform/cform-macro/guide/deployment.html) Set of CloudFormation macros that aims to simplify template creation (available in AWS Serverless Application Repository as [`wrzasqpl-cform-macro`](https://serverlessrepo.aws.amazon.com/applications/eu-central-1/117504620086/wrzasqpl-cform-macro)).

## Public Coverage Roadmap

The Public Coverage Roadmap is supported by the AWS CloudFormation team to help prioritise coverage work streams and resource improvements.

* [aws-cloudformation-coverage-roadmap](https://github.com/aws-cloudformation/aws-cloudformation-coverage-roadmap) ⭐ 1,140 | 🐛 1,327 | 📅 2026-08-14: This is a public roadmap focused on upcoming coverage support for CloudFormation. Coverage prioritisation is influenced by contributions and feedback to this roadmap.

## Blog Posts and Talks

Our community is our most powerful tool, and the following are hand picked submissions from some of our favourite contributors.

* [YAML Is Better than Your Favorite Language: Fightin' words about Infrastructure as code](https://acloud.guru/series/serverlessconf-nyc-2019/view/yaml-better) by Ben Kehoe
* [AWS CloudFormation Custom Resource Types: A Walkthrough](https://onecloudplease.com/blog/aws-cloudformation-custom-resource-types-a-walkthrough) by Ian McKay
* [The OPA AWS CloudFormation Hook](https://blog.styra.com/blog/the-opa-aws-cloudformation-hook)

## Documentation

### Reference Guides

#### AWS

CloudFormation's [public documentation](https://docs.aws.amazon.com/cloudformation/) is also open-sourced and we love to accept contributions.

* [cloudformation-user-guide](https://github.com/awsdocs/aws-cloudformation-user-guide) ⚠️ Archived: CloudFormation's public documentation source repository
* [aws-cfn-resource-specs](https://github.com/ScriptAutomate/aws-cfn-resource-specs) ⚠️ Archived: A Completely Tracked, Versioned, and Audited Collection Store of CloudFormationResource.json Specification Files. These are the specification files created by AWS and ingested by tools wrapped around CloudFormation template development, such as most tools listed under the [Code Generation](#code-generation) section. The repository includes detailed, automatically generated changelogs about each new release, such as information on new resource types and what regions support them.
* [AWS CloudFormation Workshop](https://cfn101.workshop.aws/): A workshop that takes you through CloudFormation from the beginning up to more advanced topics.

#### 3rd parties

* [Scale Your CloudFormation](https://github.com/jeshan/scale-your-cloudformation) ⚠️ Archived: An in-depth guide for intermediate users on becoming successful with Infrastructure as Code on AWS

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License Summary

This sample code is made available under a modified MIT license. See the LICENSE file.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
