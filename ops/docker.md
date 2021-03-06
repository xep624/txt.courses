# Docker security

## About the course

{% hint style="danger" %}
Work in progress
{% endhint %}

### Overview

The **Docker** security course is a great course to get some more insights and hands-on experience with Docker security. The topics in this course are the absolute fundamentals of what you should know to work with Docker responsibly. It goes from building minimalistic images to real live exploitation and mitigation of containerized solutions. The strictly Docker related part takes only half day. 

In the one-day long version of the course we will not only learn Docker security, but also get means to continuously scan for vulnerabilities in for both appsec and infrastructure. Armed with this knowledge we can get a great understanding of the progression of the security maturity of your company. However, knowledge is useless if we have no effective way to handle it. Because of this the '**Security test automation**' part of the course also introduces means of setting up a vulnerability management process.

### Properties

title: **Docker security**

audience: XOX

duration: 0.5 day \(3hrs education time\)

developed by: Riccardo ten Cate

### Prerequisites

XOX

## Agenda

### Docker security

#### Docker security fundamentals

* This topic will talk about the Docker security fundamentals such as using minimalistic images, principle of least privilege etc.

#### Docker vulnerability scanning

* How do we scan our docker images for security continuously even before we deploy them to production? What are the best practices for vulnerability scanning on Docker images.

#### Docker scratch images

* Using minimalistic images is a nice way to get starting. However, for very critical infrastructure

  we may want to build our own images from scratch.

#### Using a keyvault to protect your secrets

* By deploying applications through Docker it becomes more important than ever to handle your secrets correctly. Are all your secrets in one place? are they not checked in into version control? Are they laying around in your CI tools?

#### Docker hacking

* Let's play this hands-on CTF game where we effectively need to break out of a Docker container and take over the host machine.

### Security test automation

#### Learning Vault 

* When using Docker it is essential to prevent key-sprawl. Secrets and API keys are often overlooked and leave an enormous attack surface that can be abused. How does Vault work, and how does it help secure your delivery pipeline.

#### Security test automation 

* How to create a schalable and CI platform agnostic approach for integrating security test automation into your organizations CI/CD pipelines.

#### Vulnerability management system 

* When scanning your containers and infrastructure continuously for vulnerabilities it is essential to have a process and a vulnerability management system in place to handle all the metrics that are generated by your favourite tooling.

## Trainers

* [Riccardo ten Cate](../trainers/riccardo-ten-cate.md)

