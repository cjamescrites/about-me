# Cloud & DevOps

## Cloud
> On-demand availability of computer system resources that don't require direct active management by the user. 

## DevOps
Combination of software development and IT operations that shortens development life cycle and provides continuous delivery of updates.

>I have deployed AWS instances, created VPCs, and AMIs utilizing Terraform and Jenkins.

Cloud reduces operating cost by using a pay-as-you-go model allowing companies to allocate resources based on demand. Cloud is also more reliable due to being connected to multiple data centers versus a singular on-site server.

DevOps reduces overall cost by cutting a development life cycle, as well as faster product delivery and issue resolution.

## CICD
Methodology to deliver apps by introducing automation into the stages of app development. Main concepts are continuous integration, delivery, and deployment.

>I have created Jenkins pipeline that has the capability of automatically deploying an app via GitHub.

CICD pipelines allows you to constantly push updates with immediate feedback with the ability to rollback previous pushes to ensure working versions are always live.

## Jenkins
Tool that helps automate the building, testing, and deployment which faciliates CICD.

## Provisioning
The process of setting up infrastructure.

>Wrote bash scripts that provisioned several Vagrant environments, interconnected them, and installed all required dependencies.

Provisioning reduces time needed to run redundant commands and install dependenices, and user errors when others use your application.

## Networking
Creating and managing connections between applications.

Networking allows your applications to be accessible locally or globally, and allows you to regulate the traffic, and prevent security risks.

## Principle of Least Privilege
Restricting access rights to what is needed for a user to perform their role's responsibilities.

Principle of Least Privelege adds security in the foundation of an application by restricting privileges/access by default to every user.

## IAC
Infrastructure management approach that houses configuration information in standardized files.

Infrastructure as code simplifies large-scale configuration and management by automating config steps which also minimizes human error.

## Packer
Tool that creates cross-platform machine images from a single source configuration.

>I utilized Packer to deploy and connect environments for an Node application and MongoDB on an AWS instance.

Packer provides many benefits including fast infrastructure deployment, and greater testability. This not only cuts down production time, but development time as well by decreasing provision wait time, and testing while the machine image is being built.

## Terraform 
IAC tool that lets you build, change, and version cloud resouces safely and efficiently.

>I have created multiple terrform environments for AWS and GCP.

Terraform allows you to manage infrastructure over multiple cloud platforms, and track resourse changes throughout your deployment.
