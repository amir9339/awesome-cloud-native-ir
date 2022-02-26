# ☁️ Awesome cloud-native Incident Response [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of free tools and resources for cloud-native environments incident response
Inspired by [awesome-incident-response](https://github.com/meirwah/awesome-incident-response)

## Contents
- [📚 Books](#books)
- [🧪 CTFs / Labs](#ctfs-labs)
- [🧾 Evidence Collection](#evidence-collection)
- [🔎 Forensics Tools](#forensics-tools)
- [🦮 Guides](#guides)
- [🔬 Scanners](#scanners)
- [🧰 Live Monitoring](#live-monitoring)
- [🔫 Penetration Testing](#penetration-testing)

## Books
- [Container Security](https://www.oreilly.com/library/view/container-security/9781492056690/), Liz Rice from Aqua Security
- [Kubernetes Security](https://info.aquasec.com/kubernetes-security), Liz Rice from Aqua Security & Michael Hausenblas


## CTFs / Labs
- [Docker Forensics lab](https://attackdefense.pentesteracademy.com/listingnoauth?labtype=container-security-image-security&subtype=container-security-image-security-forensics) - The labs in this section deal with the forensics aspects of Docker components: extracting artifacts from Docker images, locate backdoors in containers, using checkpoints and recover the container state.
- [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) - Kubernetes Goat 🐐 is a "Vulnerable by Design" Kubernetes Cluster. Designed to be an intentionally vulnerable cluster environment to learn and practice Kubernetes security.

## Evidence Collection
- [kube-forensics](https://github.com/keikoproj/kube-forensics) - kube-forensics allows an admin to dump the current state of a running pod and all its containers so that IR teams can perform off-line forensic analysis.

## Forensics Tools
- [Docker Forensics Toolkit](https://github.com/docker-forensics-toolkit/toolkit) - A toolkit for the post-mortem examination of Docker containers from forensic HDD copies.
- [Google's cloud-forensics-utils](https://github.com/google/cloud-forensics-utils) - Google's Python library to carry out DFIR analysis on the Cloud.
- [Tracee](https://github.com/aquasecurity/tracee) - Linux Runtime Security and Forensics using eBPF.
- [volatility-docker](https://github.com/amir9339/volatility-docker) - A suite of Volatility 3 plugins for memory forensics of Docker containers.

## Guides
- [AWS guide for EKS and k8s IR](https://aws.github.io/aws-eks-best-practices/security/docs/incidents/)
- [Great Docker forensics tutorial](https://blog.compass-security.com/2021/11/docker-forensics/)
- [Kubernetes Security Best Practices](https://github.com/kabachook/k8s-security) - The repo containes a set of Kubernetes security notes and best practices.

## Scanners
- [kube-bench](https://github.com/aquasecurity/kube-bench) - Checks whether Kubernetes is deployed according to security best practices as defined in the CIS Kubernetes Benchmark.
- [Popeye](https://github.com/derailed/popeye) - A Kubernetes cluster resource sanitizer.
- [Trivy](https://aquasecurity.github.io/trivy/v0.24.0/) - Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues.

## Live Monitoring
- [Falco](https://falco.org/) - Cloud-native runtime security project, is the de facto Kubernetes threat detection engine.

## Penetration Testing
- [docker-escape-tool](https://github.com/PercussiveElbow/docker-escape-tool) - Tool to test if you're in a Docker container and attempt simple breakouts.
- [kubesploit](https://github.com/cyberark/kubesploit) - Kubesploit is a cross-platform post-exploitation HTTP/2 Command & Control server and agent dedicated for containerized environments written in Golang and built on top of Merlin project.
- [kube-hunter](https://github.com/aquasecurity/kube-hunter) - kube-hunter hunts for security weaknesses in Kubernetes clusters. The tool was developed to increase awareness and visibility for security issues in Kubernetes environments.
