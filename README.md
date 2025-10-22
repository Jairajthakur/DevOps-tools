# 🚀 Curated List of DevOps Tools
![Alt Text](assets/GitHub.png)

---

# Your Ultimate DevOps Toolkit! 🛠️
![Alt Text](assets/DevOps.jpg)

A collection of essential DevOps tools for **development, deployment, monitoring, automation, security, and more**. Whether you're a beginner exploring DevOps or a seasoned engineer looking for the best tools, this repository has everything you need!

---

# 📌 Table of Contents
🚀 [Development Environment Tools](#Development-Environment-Tools)<br>
📝 [Source Code Management (SCM)](#Source-Code-Management-SCM)<br>
⚙️ [Build Tools](#Build-Tools)<br>
⚡ [Continuous Integration (CI) Tools](#Continuous-Interation-(CI)-Tools)<br>
📦 [Artifact Management Tools](#Artifact-Management-Tools)<br>
🔍 [Code Analysis Tools](Code-Analysis-Tools)<br>
⚡ [Continuous Delivery (CD) & GitOps Tools](Continuous-Delivery-(CD)-&-GitOps-Tools)<br>
🏗️ [Infrastructure Provisioning Tools](Infrastructure-Provisioning-Tools)<br>
🔄 [Backup & Restoration Tools](Backup-&-Restoration-Tools)<br>
💰 [Cloud Cost Management Tools](Cloud-Cost-Management)<br>
⚙️ [Configuration Management Tools](Configuration-Management-Tools)<br>
🔐 [Secret Management Tools](Secret-Management-Tools)<br>
🔎 [Config & Service Discovery Tools](Config-&-Service-Discovery-Tools)<br>
📦 [Containerization Tools](Containerization-Tools)<br>
🎛️ [Container Orchestration Tools](Container-Orchestration-Tools)<br>
🔒 [Container Security Tools](Container-Security-Tools)<br>
📜 [Policy Management Tools](Policy-Management-Tools)<br>
🔗 [Service Mesh Tools](Service-Mesh-Tools)<br>
📜 [Logging Tools](Logging-Tools)<br>
📊 [Monitoring & Observability Tools](Monitoring-&-Observability-Tools)<br>
📊 [Visualization Tools](Visualization-Tools)<br>
🏗️ [Internal Developer Platform (IDP) Tools](Internal-developer-Platform-(IDP)-Tools)<br>
🔗 [API Tools](API-Tools)<br>
🤝 [Collaboration Tools](Collaboration-Tools)<br>
📅 [Planning & Project Management Tools](Planning-&-Project-Management-Tools)<br>
🖥️ [IDE (Integrated Development Environment) Tools](IDE-(Integrated-Development-Environment)-Tools)<br>
🐞 [Bug & Issue Tracking Tools](Bug-&-Issue-Tracking-Tools)<br>
🧪 [Test Automation & Performance Testing Tools](Test-Automation-&-Performance-Testing-Tools)<br>
📚 [Centralized Documentation Management Tools](Centralized-Documentation-Management-Tools)<br>
☁️ [Cloud Provider](Cloud-Provider)<br>
🎯 [Conclusion: Choosing the Right DevOps Tools](Conclusion-Choosing-the-Right-DevOps-Tools)<br>

---

# Development Environment Tools

Development environment tools **streamline the setup** of consistent software configurations, ensuring **fast recovery and higher developer productivity**.

## ⚡ Virtualization and Containerization<br>
🔹 [VirtualBox](https://www.virtualbox.org/) (Open Source) – Enterprise-grade virtualization for x86 and AMD64/Intel64 systems.<br>
🔹 [QEMU](https://www.qemu.org/) (Open Source) – Open-source machine emulator and virtualizer.<br>
🔹 [Vagrant](https://developer.hashicorp.com/vagrant) (Open Source) – Automates the setup and management of virtual machines.<br>
## 🛠️ Containerized Development<br>
🔹 [Docker Desktop](https://www.docker.com/products/docker-desktop/) (Open Source) – Simplifies containerized application development.<br>
🔹 [Podman Desktop](https://podman.io/) (Open Source) – A daemonless container engine for Linux environments.<br>
🔹 [Rancher Desktop](https://rancherdesktop.io/) (Open Source) – Manage and deploy Kubernetes clusters locally.<br>
## ☸ Kubernetes Local Clusters<br>
🔹 [Minikube](https://minikube.sigs.k8s.io/docs/) (Open Source) – Run Kubernetes clusters locally with ease.<br>
🔹 [Minishift](https://okd.io/minishift/) (Open Source) – Deploy a single-node OpenShift cluster in a VM.<br>
🔹 [kind](https://kind.sigs.k8s.io/) (Open Source) – Spin up Kubernetes clusters using Docker containers.<br>
🔹 [k3d](https://k3d.io/stable/) (Open Source) – Lightweight wrapper for running k3s in Docker.<br>

---

# Source Code Management (SCM)
Version control tools **keep track of every change**, making collaboration and automation seamless in DevOps.

## 🌍 Cloud-Based SCM Platforms
🔹 [GitHub](https://github.com/) (Free & Paid) – The most popular Git-based repository hosting platform.<br>
🔹 [Bitbucket](https://bitbucket.org/) (Free & Paid) – SCM solution by Atlassian, supports Git & Mercurial.<br>
🔹 [GitLab](https://about.gitlab.com/) (Free & Paid) – Complete DevOps platform with CI/CD integration.<br>
🔹 [Azure Repos](https://azure.microsoft.com/en-us/products/devops/repos/) (Free & Paid) – Cloud-based Git & TFVC repositories.<br>
🔹 [AWS CodeCommit](https://aws.amazon.com/codecommit/) (Free & Paid) – Fully-managed Git hosting by AWS.<br>
🔹 [Google Cloud Source Repositories](https://cloud.google.com/source-repositories/docs/) (Free & Paid) – Scalable, private Git repositories on Google Cloud.<br>

## 🔧 Self-Hosted & Open-Source SCM
🔹 [Codeberg](https://codeberg.org/) (Free & Paid) – Community-driven Forgejo instance.
🔹 [Forgejo](https://forgejo.org/) (Open Source) – Self-hosted Git service, a Gitea fork.
🔹 [Fossil](https://fossil-scm.org/home/doc/trunk/www/index.wiki) (Free) – SCM with a built-in wiki & issue tracker.
🔹 [Gitea](https://about.gitea.com/) (Open Source) – Lightweight self-hosted Git service.
🔹 [Gogs](https://gogs.io/) (Open Source) – Simple, self-hosted Git repository system.

---

# ⚙️ Build Tools

Build tools automate software compilation and **generate deployable artifacts** efficiently.

## ☕ Java & JVM-Based Builds
🔹 [Maven](https://maven.apache.org/) (Java) (Open Source) – A comprehensive project management and build tool.
🔹 [Gradle](https://gradle.org/) (Java, Kotlin, Groovy, Scala, Python, C++) (Free & Paid) – High-performance build automation.

## 📦 JavaScript & Web Development
🔹 [npm](https://www.npmjs.com/) (JavaScript) – The package manager for Node.js applications.

## 💎 Ruby & .NET Build Systems
🔹 [Rake](https://ruby.github.io/rake/) (Ruby) (Open Source) – Task management and build automation for Ruby projects.
🔹 [MSBuild](https://github.com/dotnet/msbuild) (.NET) (Open Source) – The official build system for **.NET applications**.

## 🐍 Python Build Tools
🔹 [Pybuilder](https://pybuilder.io/) (Python) (Open Source) – A lightweight tool for Python project automation.


---

# ⚡ Continuous Integration (CI) Tools

Continuous Integration (CI) automates code integrations, providing **instant feedback** on changes. This helps teams **detect and resolve issues faster**, reducing software release cycles.

## 🚀 Popular CI/CD Platforms
🔹 [Jenkins](https://www.jenkins.io/) (Open Source) – Java-based automation server with Groovy-based pipeline support.
🔹 [GitHub Actions](https://github.com/features/actions) (Free & Enterprise) – Built-in CI/CD for GitHub repositories.
🔹 [GitLab CI/CD](https://docs.gitlab.com/ci/) (Free & Enterprise) – YAML-based pipelines, cloud and self-hosted.
🔹 [CircleCI](https://circleci.com/) (Free & Paid) – Cloud-based CI/CD, YAML-configured workflows.
🔹 [Drone](https://www.drone.io/) (Free & Paid) – Container-first CI/CD, self-hosted or cloud-based.

## 🏗️ Enterprise & Commercial Solutions
🔹 [TeamCity](https://www.jetbrains.com/teamcity/) (Free & Enterprise) – JetBrains' powerful CI/CD tool.
🔹 [Travis CI](https://www.travis-ci.com/) (Open Source) – Cloud-native CI for GitHub repositories.
🔹 [Bamboo](https://www.atlassian.com/software/bamboo) (Free & Enterprise) – Atlassian's CI/CD solution with tight Jira integration.
🔹 [RazorOps CICD](https://razorops.com/) (Free & Paid) – Container-first CI/CD SaaS and on-premises solutions.
🔹 [Buildkite](https://buildkite.com/) (Free & Paid) – Self-hosted CI/CD with scalable build agents.
