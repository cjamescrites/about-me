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


# MERN Stack

JavaScript Stack that is used for easier and faster deployment of full-stack web apps. Comprising of MongoDB, Express, React, and Node. 

>I have built a full MERN stack application that allows a user to search for current and future weather conditions of any city around the world, and stores previous searches, displaying them to the user.

The MERN Stack provides an end-to-end framework for developers to work in, eand each of these technologies play a big part in web application development.

## MongoDB

NoSQL Database comprising of key-value pairs similar to JSON objects. 

MongoDB is fast due it being a document-oriented database making it easier to index documents. MongoDB is also scalable allowing large data to be handled by dividing it into several machines. 

## Express

Express is a Node.js frame work. Mainly used in designing web applications and APIs. 

Express supports many middlewares which make the corde shorter and easier to write.

## React.js

React is a JavaScript library that is used for development of single-page and mobile applications because of its ability to handle rapidly changing data.

React utilizes a virtual DOM which is a representation of a DOM Object. Any modification in the web application triggers a re-render of the virtual DOM, then the DOM and virtual DOM is compared and changed.

React uses JSX which is a HTML/XML JavaScript extension making it easier to write React components.

Components are the building blocks of UI wherein each component has a logic and contributes to overall UI. Promoting code resuability and make overall web application easier to understand.

## Node.js

JavaScript Environment allowing the user to run their code on a server.

Node Package Manager (NPM) allowing the user to choose from thousands of free packages (node modules) to download.

Node is open-source, single threading, and highly scalable. It's extremely fast, being built on Google Chrome's JavaScript Engine allowing for fast code execution.
