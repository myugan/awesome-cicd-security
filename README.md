# Awesome CI/CD Security [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

List of awesome resources about CI/CD security included books, blogs, videos, tools and cases.

## Table of Contents

  - [Books](#books)
  - [Guidelines](#guidelines)
  - [Blogs](#blogs)
    - [General](#general)
    - [GitLab](#gitlab)
    - [GitHub Actions](#github-actions)
    - [Jenkins](#jenkins)
    - [ArgoCD](#argocd)
  - [Videos](#videos)
  - [Repositories](#repositories)
  - [Tools](#tools)
  - [Playground](#playground)
  - [Cases](#cases)

## Books

- [Advanced Infrastructure Penetration Testing](https://www.packtpub.com/product/advanced-infrastructure-penetration-testing/9781788624480)

## Guidelines
- [Defending Continuous Integration/Continuous Delivery (CI/CD) Environment from CISA & NSA](https://media.defense.gov/2023/Jun/28/2003249466/-1/-1/0/CSI_DEFENDING_CI_CD_ENVIRONMENTS.PDF)

## Blogs

### General

- [Top 10 CI/CD Security Risks](https://github.com/nathanawmk/top-10-cicd-security-risks)
- [Continuous Delivery 3.0 Maturity Model (CD3M)](https://nisi.nl/continuousdelivery/articles/maturity-model)
- [Visualizing CI/CD from an attacker’s perspective](https://medium.com/cider-sec/visualizing-ci-cd-from-an-attackers-perspective-22dfa38c9d09)
- [The Anatomy of an Attack Against a Cloud Supply Pipeline](https://www.paloaltonetworks.com/blog/2021/10/anatomy-ci-cd-pipeline-attack/)
- [When Supply-Chain Attacks Meet CI/CD Infrastructures](https://blogs.vmware.com/networkvirtualization/2021/12/29260.html/)
- [CI/CD Supply Chain Attacks for Data Exfiltration or Cloud Account Takeover](https://www.praetorian.com/blog/ci-cd-supply-chain-attacks-for-data-exfiltration-or-cloud-account-takeover/)
- [Detecting Malicious Activity in CI/CD Pipeline with Tracee](https://blog.aquasec.com/cicd-pipeline-security-tool-tracee)
- [Let’s Hack a Pipeline: Argument Injection](https://devblogs.microsoft.com/devops/pipeline-argument-injection/)
- [Let’s Hack a Pipeline: Stealing Another Repo](https://devblogs.microsoft.com/devops/pipeline-stealing-another-repo/)
- [Let’s Hack a Pipeline: Shared Infrastructure](https://devblogs.microsoft.com/devops/pipeline-shared-infrastructure/)
- [Poorly Configured CI/CD Systems Can Be A Backdoor Into Your Infrastructure](https://thenewstack.io/poorly-configured-ci-cd-systems-can-be-a-backdoor-into-your-infrastructure/)
- [Assess Vulnerabilities and Misconfigurations in CICD Pipelines: Part 1](https://success.qualys.com/discussions/s/article/000005841)
- [Assess Vulnerabilities and Misconfigurations in CICD Pipelines: Part 2](https://success.qualys.com/discussions/s/article/000005842)
- [Defending software build pipelines from malicious attack](https://www.ncsc.gov.uk/blog-post/defending-software-build-pipelines-from-malicious-attack)
- [Cloud Native Best Practices: Security Policies in CI/CD Pipelines](https://blog.aquasec.com/cloud-native-security-best-practices-devops-security)

### Azure DevOps Server

- [Azure DevOps server supply-chain attack tree (map, Attack surface, threat modeling)](https://github.com/sergiomarotco/Azure-DevOps-server-supply-chain-attack-tree)

### GitLab

- [Abusing GitLab Runners](https://frichetten.com/blog/abusing-gitlab-runners/)
- [Critical GitLab vulnerability could allow attackers to steal runner registration tokens](https://portswigger.net/daily-swig/critical-gitlab-vulnerability-could-allow-attackers-to-steal-runner-registration-tokens)
- [Understanding GitLab's Security Threats and Strengthening Your Preparedness](https://www.mitiga.io/blog/understanding-gitlabs-security-threats-and-strengthening-your-preparedness)
- [Securing GitLab CI pipelines with Sysbox](https://blog.nestybox.com/2020/10/21/gitlab-dind.html)
- [GitLab - Security for self-managed runners](https://docs.gitlab.com/runner/security/)

### GitHub Actions

- [Stealing arbitrary GitHub Actions secrets](https://blog.teddykatz.com/2021/03/17/github-actions-write-access.html)
- [Exploiting GitHub Actions on open source projects](https://medium.com/tinder/exploiting-github-actions-on-open-source-projects-5d93936d189f)
- [GitHub Action Runners Analyzing the Environment and Security in Action](https://www.trendmicro.com/vinfo/us/security/news/cybercrime-and-digital-threats/github-action-runners-analyzing-the-environment-and-security-in-action)
- [What the fork? Imposter commits in GitHub Actions and CI/CD](https://www.chainguard.dev/unchained/what-the-fork-imposter-commits-in-github-actions-and-ci-cd)
- [The GitHub Actions Worm: Compromising GitHub Repositories Through the Actions Dependency Tree](https://www.paloaltonetworks.com/blog/prisma-cloud/github-actions-worm-dependencies/)
- [Unpinnable Actions: How Malicious Code Can Sneak into Your GitHub Actions Workflows](https://www.paloaltonetworks.com/blog/prisma-cloud/unpinnable-actions-github-security/)
- [Long Live the Pwn Request: Hacking Microsoft GitHub Repositories and More](https://www.praetorian.com/blog/pwn-request-hacking-microsoft-github-repositories-and-more/)
- [One Supply Chain Attack to Rule Them All – Poisoning GitHub’s Runner Images](https://adnanthekhan.com/2023/12/20/one-supply-chain-attack-to-rule-them-all/)
- [TensorFlow Supply Chain Compromise via Self-Hosted Runner Attack](https://www.praetorian.com/blog/tensorflow-supply-chain-compromise-via-self-hosted-runner-attack/)
- [Self-hosted runner security](https://docs.github.com/en/actions/hosting-your-own-runners/about-self-hosted-runners#self-hosted-runner-security)
- [Automatically Secure Your CI/CD Pipelines Using Tracee GitHub Action](https://blog.aquasec.com/ci-cd-pipeline-security-tracee-github-action)
- [Keeping your GitHub Actions and workflows secure Part 1: Preventing pwn requests](https://securitylab.github.com/research/github-actions-preventing-pwn-requests/)
- [Keeping your GitHub Actions and workflows secure Part 2: Untrusted input](https://securitylab.github.com/research/github-actions-untrusted-input/)
- [Keeping your GitHub Actions and workflows secure Part 3: How to trust your building blocks](https://securitylab.github.com/research/github-actions-building-blocks/)
- [Github Actions Security Best Practices](https://engineering.salesforce.com/github-actions-security-best-practices-b8f9df5c75f5)
- [Security hardening for GitHub Actions](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions)

### Jenkins

- [Attacking Jenkins](https://msgpeek.net/blog/2020/02/attacking-jenkins/)
- [Attacking Jenkins with Shared Libraries](https://oxhat.blogspot.com/2022/07/attacking-backdooring-and-exfiltrating.html)
- [Reflections on trusting plugins: Backdooring Jenkins builds](https://www.synopsys.com/blogs/software-security/backdooring-jenkins-builds-and-security-measures/)
- [Securing Jenkins](https://www.jenkins.io/doc/book/security/securing-jenkins/)
- [How to Secure Jenkins Pipelines without the hassle](https://www.contrastsecurity.com/security-influencers/how-to-secure-jenkins-pipelines-without-the-hassle#:~:text=Navigate%20to%20your%20Jenkins%20UI,available%20to%20your%20Jenkins%20instance.)

### ArgoCD

- [ArgoCD SSRF](https://blog.calif.io/p/argo-cd-csrf)
- [Redis or Not – Revealing a Critical Vulnerability in Argo CD Kubernetes Controller](https://cycode.com/blog/revealing-argo-cd-critical-vulnerability/)
- [Six Critical Blindspots While Securing Argo CD](https://dnastacio.medium.com/gitops-argocd-security-cbb6fb6378bb)
- [Security Considerations](https://argo-cd.readthedocs.io/en/stable/security_considerations/)
- [Argo CD Security Practices](https://www.youtube.com/watch?v=3IoLH1j6cm0)

## Videos

- [Attacking Development Pipelines For Actual Profit](https://www.youtube.com/watch?v=AQCvfzwcGso)
- [Exploiting Continuous Integration (CI) and Automated Build systems](https://www.youtube.com/watch?v=mpUDqo7tIk8)
- [Continuous Intrusion: Why CI Tools Are An Attacker's Best Friends](https://www.youtube.com/watch?v=0H6jd5yG7_A)
- [OMGCICD - From Intern to Production by: Denis Andzakovic](https://www.youtube.com/watch?v=I8aBGT4LPeo)
- [Attacking Argo CD with Argo CD (and then Defending) - Michael Crenshaw, Intuit](https://www.youtube.com/watch?v=bRNMI29F2fI)
- [Challenges to Securing CI/CD Pipelines](https://www.youtube.com/watch?v=Pd6akunYaZc)
- [How to Build a Compromise Resilient CI/CD](https://www.youtube.com/watch?v=ArS31CxneUA)

## Repositories
- [Threat Matrix for CI/CD Pipeline](https://github.com/rung/threat-matrix-cicd)
- [Jenkins Attack Framework](https://github.com/Accenture/jenkins-attack-framework)
- [pwn_jenkins](https://github.com/gquere/pwn_jenkins)

## Tools
- [Gato](https://github.com/praetorian-inc/gato) - A tool that helps blue teamers and offensive security practitioners find weaknesses in GitHub organization's public and private repositories.
- [clank](https://github.com/chainguard-dev/clank) - Simple tool that allows you to detect imposter commits in GitHub Actions workflows.
- [legitify](https://github.com/Legit-Labs/legitify) - Detect and remediate misconfigurations and security risks across all your GitHub and GitLab assets.
- [poutine](https://github.com/boostsecurityio/poutine) - A security scanner that detects misconfigurations and vulnerabilities in the build pipelines of a repository.
- [Harden-Runner](https://github.com/step-security/harden-runner) - Network egress filtering and runtime security for GitHub-hosted and self-hosted runners.
- [Cimon](https://github.com/CycodeLabs/cimon-action) - Runtime security solution for your CI/CD pipeline.
- [Vulert](vulert.com) - VVulert secures software by detecting vulnerabilities in open-source dependencies—without accessing your code. It supports Js, PHP, Java, Python, and more.
- [Raven](https://github.com/CycodeLabs/raven) - A powerful security tool designed to perform massive scans for GitHub Actions CI workflows and digest the discovered data into a Neo4j database

## Playground

- [CI/CDon't](https://hackingthe.cloud/aws/capture_the_flag/cicdont)
- [CI/CD Goat](https://github.com/cider-security-research/cicd-goat)
- [GitHub Actions Goat](https://github.com/step-security/github-actions-goat)

## Cases

- [10 real-world stories of how we’ve compromised CI/CD pipelines](https://research.nccgroup.com/2022/01/13/10-real-world-stories-of-how-weve-compromised-ci-cd-pipelines/)
- [CI/CD pipeline attacks: A growing threat to enterprise security](https://limacharlie.io/blog/cicd-pipeline-attacks)
- [Poisoned pipelines: Security researcher explores attack methods in CI environments](https://portswigger.net/daily-swig/poisoned-pipelines-security-researcher-explores-attack-methods-in-ci-environments)
- [Travis CI Flaw Exposes Secrets of Thousands of Open Source Projects](https://thehackernews.com/2021/09/travis-ci-flaw-exposes-secrets-of.html)
- [GitHub Actions being actively abused to mine cryptocurrency on GitHub servers](https://www.bleepingcomputer.com/news/security/github-actions-being-actively-abused-to-mine-cryptocurrency-on-github-servers/)
- [Report: Software supply chain attacks increased 300% in 2021](https://venturebeat.com/2022/01/27/report-software-supply-chain-attacks-increased-300-in-2021/)
- [Critical vulnerability discovered in popular CI/CD framework](https://www.itpro.co.uk/security/cyber-security/361400/critical-vulnerability-discovered-in-popular-cicd-framework)
- [Malicious Kubernetes Helm Charts can be used to steal sensitive information from Argo CD deployments](https://apiiro.com/blog/malicious-kubernetes-helm-charts-can-be-used-to-steal-sensitive-information-from-argo-cd-deployments/)
- [New Attacks on Kubernetes via Misconfigured Argo Workflows](https://www.intezer.com/blog/container-security/new-attacks-on-kubernetes-via-misconfigured-argo-workflows/)
- [Argo CD Security Bug Opens Kubernetes Cloud Apps to Attackers](https://threatpost.com/argo-cd-security-bug-kubernetes-cloud-apps/178239/)
- [Ransomware attacks on GitHub, Bitbucket, and GitLab – what you should know](https://gitprotect.io/blog/ransomware-attacks-on-github-bitbucket-and-gitlab-what-you-should-know/)
- [Compromising CI/CD Pipelines with Leaked Credentials](https://blog.gitguardian.com/security-zines-2-compromising-ci-cd-pipelines/)

## [Contributing](contributing.md)

Your contributions are always welcome.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
