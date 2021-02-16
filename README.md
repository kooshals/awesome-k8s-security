<a href="https://kubernetes.io/">
    <img src="https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png"
         alt="Kubernetes logo" title="Kubernetes" height="100" width="100" />
</a></br>

# Awesome Kubernetes (K8s) Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list for Kubernetes (K8s) Security resources such as articles, books, tools, talks and videos.  

# Disclaimer
Most of the resources are in English, the ones that aren't will be flagged as such. Most of the contents of this list are public free, please use them for educational purposes only!

Not all the tools have been tested or reviewed, use them at your own risk! Also, I don't consider myself a K8s Security expert, I'm just learning and helping others learn along with me. Thanks!

# Contents
These are the main contents of this awesome list. Everything related to the security of Kubernetes, either breaking or improving it, will be added down below. If you have any other good recommendations, feel free to submit a PR!

- [💊 The Basics](#basics)
- [💼 Official Pages](#official)
- [📹 Talks and Videos](#videos)
- [📰 Blogs and Articles](#blogs-articles)
- [🗒️ Books](#books)
- [📆 Certifications](#certifications)
- [🔥 CVEs](#cves)
- [📑 Slides](#slides)
- [🧪 Trainings](#trainings)
- [🐾 Repositories](#repositories)
- [📂 Papers](#papers)
- [🎤 Podcasts](#podcasts)
- [🧰 Jobs](#jobs)
- [📡 Community](#community)

## The Basics
To understand about Kubernetes Security you first need to understand the basics of how Kubernetes works and all the components involved. Here's some links and materials to help you with that journey:

[Kubernetes in 5 mins](https://www.youtube.com/watch?v=PH-2FfFD2PU)

[Kubernetes Concepts Explained in 9 minutes!](https://www.youtube.com/watch?v=QJ4fODH6DXI)

[Kubernetes 101](https://www.aquasec.com/resources/kubernetes-101/)

[Kubernetes: Getting Started](https://azure.microsoft.com/en-us/overview/kubernetes-getting-started/)

[Kubernetes The Hard Way - Kelsey Hightower](https://github.com/kelseyhightower/kubernetes-the-hard-way)

[Kubernetes Challenge](https://github.com/hector-vido/kubernetes-challenge) 🇧🇷

[Kubernetes de K a S - Erlon Pinheiro](https://github.com/erlonpinheiro/kubernetes_de_k_a_s) 🇧🇷

[Kubernetes Training](https://github.com/ashishrpandey/kubernetes-training)

[Introduction to Kubernetes](https://www.edx.org/course/introduction-to-kubernetes)

[Kube Academy](https://kube.academy/)

[Game of Pods (KodeKloud)](https://kodekloud.com/p/game-of-pods)

[Uncomplicating Kubernetes (Jefferson Noronha aka LinuxTips)](https://www.youtube.com/watch?v=zz1p3gjyHgc) 🇧🇷

## Official Pages

[Kubernetes.io](https://kubernetes.io/)

[Kubernetes GitHub](https://github.com/kubernetes/kubernetes)

[Kubernetes Security and Disclosure Information](https://kubernetes.io/docs/reference/issues-security/security/)

[Cloud Native Security](https://kubernetes.io/docs/concepts/security/overview/)

[Pod Security Standards](https://kubernetes.io/docs/concepts/security/pod-security-standards/)

[CNCF SIG Security](https://github.com/cncf/sig-security)

[CNCF SIG Security Meeting Notes](https://docs.google.com/document/d/170y5biX9k95hYRwprITprG6Mc9xD5glVn-4mB2Jmi2g/edit)

[CNCF SIG Security Mailing List](https://lists.cncf.io/g/cncf-sig-security)

[Kubernetes SIG Security](https://github.com/kubernetes/community/tree/master/sig-security)

[Kubernetes SIG ecurity Meeting Notes](https://docs.google.com/document/d/1GgmmNYN88IZ2v2NBiO3gdU8Riomm0upge_XNVxEYXp0/edit)

[Kubernetes SIG Auth (Authorization, Authentication, and Cluster Security Policy)](https://github.com/kubernetes/community/tree/master/sig-auth)

[Kubernetes Security Audit 2019 Results](https://github.com/kubernetes/community/tree/master/sig-security/security-audit-2019)

[Kubernetes Security Audit 2021 RFP](https://github.com/kubernetes/community/blob/master/sig-security/security-audit-2021/RFP.md)

## Talks and Videos

[Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down - Carson Anderson, DOMO](https://www.youtube.com/watch?v=90kZRyPcRZw)

[Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down - Carson Anderson, DOMO  (Extended Version)](https://vimeo.com/245778144/4d1d597c5e)

[Advanced Persistence Threats: The Future of Kubernetes Attacks (RSAC 2020)](https://www.youtube.com/watch?v=CH7S5rE3j8w)

[Kubernetes Security Best Practices - Ian Lewis, Google](https://www.youtube.com/watch?v=wqsUfvRyYpw)

[Securing Kubernetes Secrets (Cloud Next '19)](https://www.youtube.com/watch?v=DNKcRUyz4Hw)

[Jay Beale - Attacking and Defending Kubernetes - DEF CON 27 Packet Hacking Village](https://www.youtube.com/watch?v=2fmAuR3rnBo)

[The State of Kubernetes Security - Liz Rice](https://www.youtube.com/watch?v=_l56oUxHSio)

[DIY Pen-Testing for Your Kubernetes Cluster - Liz Rice, Aqua Security](https://www.youtube.com/watch?v=fVqCAUJiIn0)

[Kubernetes Security 101: Best Practices to Secure your Cluster](https://www.youtube.com/watch?v=d-pIWfDaZK8&t=3408s)

[Kubernetes Security 101: OWASP Natal Virtual Meeting](https://youtu.be/CF-ScdbhU5o) 🇧🇷

## Blogs and Articles

[Kubernetes Security](https://kubernetes-security.info/)

[Introducing Kubernetes Goat](https://blog.madhuakula.com/introducing-kubernetes-goat-8624f6d70e9e)

[Threat Matrix for Kubernetes](https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/)

[Open Sourcing the Kubernetes Security Audit](https://www.cncf.io/blog/2019/08/06/open-sourcing-the-kubernetes-security-audit/)

[Amazon EKS Best Practices Guide for Security](https://aws.github.io/aws-eks-best-practices/)

[Protecting Against Kubernetes Threats: Chapter 1 - Initial Access](https://www.stackrox.com/post/2020/06/protecting-against-kubernetes-threats-chapter-1-initial-access/)

[Securing the 4Cs of Cloud Native](https://www.trendmicro.com/vinfo/us/security/news/virtualization-and-cloud/securing-the-4-cs-of-cloud-native-systems-cloud-cluster-container-and-code)

[The Basics of Keeping Kubernetes Clusters Secure](https://www.trendmicro.com/vinfo/us/security/news/security-technology/the-basics-of-keeping-your-kubernetes-cluster-secure-part-1)

[The Basics of Keeping Kubernetes Cluster Secure: Worker Nodes and Related Components](https://www.trendmicro.com/vinfo/us/security/news/virtualization-and-cloud/the-basics-of-keeping-kubernetes-cluster-secure-worker-nodes-and-related-components)

[How to Secure Your Kubernetes Cluster](https://containerjournal.com/topics/container-security/how-to-secure-your-kubernetes-cluster/)

[Kubernetes Security 101: Best Practices To Secure Your Cluster](https://www.devseccon.com/kubernetes-security-101-best-practices-to-secure-your-cluster-secadvent-day-17/)

[Risk8s Business: Risk Analysis of Kubernetes Clusters](https://tldrsec.com/guides/kubernetes/)

[How to Set Up and Manage Logs with Kubernetes](https://iamondemand.com/blog/how-to-set-up-and-manage-logs-with-kubernetes/)

[The Current State of Kubernetes Threat Modelling](https://www.marcolancini.it/2020/blog-kubernetes-threat-modelling/)

## Books

[Kubernetes: Up and Running, Second Edition by Brendan Burns, Joe Beda and Kelsey Hightower](https://azure.microsoft.com/en-us/resources/kubernetes-up-and-running/)

[Container Security by Liz Rice](https://containersecurity.tech/)

[Kubernetes Security by Liz Rice and Michael Hausenblas](https://info.aquasec.com/kubernetes-security)

[Learn Kubernetes Security by Kaizhe Huang and Pranjal Jumde](https://www.amazon.com/Learn-Kubernetes-Security-orchestrate-microservices-ebook/dp/B087Q9G51R)

[Hacking Kubernetes by Andrew Martin, Michael Hausenblas](https://learning.oreilly.com/library/view/hacking-kubernetes/9781492081722/)

## Certifications

- [CKAD](https://www.cncf.io/certification/ckad/)

- [CKA](https://www.cncf.io/certification/cka/)

- [CKS](https://www.cncf.io/certification/cks/)

- [Certified Kubernetes Security Specialist (CKS)](https://github.com/walidshaari/Certified-Kubernetes-Security-Specialist)

- [CKSS-Certified-Kubernetes-Security-Specialist](https://github.com/ibrahimjelliti/CKSS-Certified-Kubernetes-Security-Specialist)

- [Certified Kubernetes Security Specialist Study Guide](https://github.com/stackrox/Kubernetes_Security_Specialist_Study_Guide)

- [References for CKS Exam Objectives](https://github.com/abdennour/certified-kubernetes-security-specialist)

## CVEs

[Exploring container security: Vulnerability management in open-source Kubernetes](https://cloud.google.com/blog/products/containers-kubernetes/exploring-container-security-vulnerability-management-in-open-source-kubernetes)

[CVE-2018-18264: Privilege escalation through Kubernetes dashboard](https://sysdig.com/blog/privilege-escalation-kubernetes-dashboard)

## Slides

[Communication is Key - Understanding Kubernetes Networking (KubeCon EU 2020)](https://static.sched.com/hosted_files/kccnceu20/3d/Communication_is_Key.pdf)

[Seccomp Profiles and you: A practical guide (KubeCon EU 2020)](https://www.slideshare.net/DuffieCooley/seccomp-profiles-and-you-a-practical-guide)

[Advanced Persistence Threats: The Future of Kubernetes Attacks (KubeCon EU 2020)](https://speakerdeck.com/iancoldwater/advanced-persistence-threats-the-future-of-kubernetes-attacks)

[Help! My Cluster Is On The Internet!](https://bit.ly/SamK8sSec)

## Trainings

[Secure Kubernetes](https://securekubernetes.com/)

[Cloud Native Security Tutorial](https://tutorial.kubernetes-security.info/)

[Kubernetes Security (Advanced Concepts)](https://acloudguru.com/course/kubernetes-security-advanced-concepts)

[Kubernetes Goat Guide](https://madhuakula.com/kubernetes-goat/)

[Katacoda Kubernetes Goat Videos](https://katacoda.com/madhuakula/scenarios/kubernetes-goat)

[Attacking and Auditing Docker Containers and Kubernetes Clusters](https://github.com/appsecco/attacking-and-auditing-docker-containers-and-kubernetes-clusters)

[A Cloud Guru Kubernetes Security](https://acloudguru.com/course/kubernetes-security)

[SANS Cloud-Native Security Defending Containers and Kubernetes](https://www.sans.org/event/stay-sharp-blue-team-ops-and-cloud-dec-2020/course/cloud-native-security-defending-containers-kubernetes)

[Tutorial: Getting Started With Cloud-Native Security - KubeCon EU 2020 - Liz Rice & Michael Hausenblas](https://youtu.be/MisS3wSds40)

[Control Plane Security Training](https://control-plane.io/training/)

[Kubernetes Exam Simulator](https://killer.sh/cks)

[Kubernetes Security Workshop](https://github.com/scotty-c/kubernetes-security-workshop)

[Linux Academy - Kubernetes Security](https://github.com/linuxacademy/content-kubernetes-security)

## Repositories 

### Learning

[Bust-a-Kube](https://www.bustakube.com/)

[kube-goat](https://github.com/ksoclabs/kube-goat)

[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)

[Kubernetes Networking Labs for KubeCon EU 2020 Talk](https://github.com/korvus81/k8s-net-labs)

[CNCF Security Audits](https://github.com/magnologan/cncf-security-audits)

### Attacking

[kube-hunter](https://github.com/aquasecurity/kube-hunter)

[Peirates](https://github.com/inguardians/peirates)

### Defending

[Kubernetes Audit by Trail of Bits](https://github.com/trailofbits/audit-kubernetes)

[falco](https://github.com/falcosecurity/falco)

[kubesec](https://github.com/controlplaneio/kubesec)

[kube-bench](https://github.com/aquasecurity/kube-bench)

[trivy](https://github.com/aquasecurity/trivy)

[MKIT](https://github.com/darkbitio/mkit)

[kubetap](https://github.com/soluble-ai/kubetap)

[kube-forensics](https://github.com/keikoproj/kube-forensics)

[k8s-security-dashboard](https://github.com/k8scop/k8s-security-dashboard)

[CIS Kubernetes Benchmark - InSpec Profile](https://github.com/dev-sec/cis-kubernetes-benchmark)

[Kube PodSecurityPolicy Advisor](https://github.com/sysdiglabs/kube-psp-advisor)

[Inspektor Gadget](https://github.com/kinvolk/inspektor-gadget)

[Starboard](https://github.com/aquasecurity/starboard)

[Advocacy Site for Kubernetes RBAC](https://github.com/mhausenblas/rbac.dev)

[Helm-Snyk](https://github.com/snyk-labs/helm-snyk)

[Krane](https://github.com/appvia/krane)

[rakkess](https://github.com/corneliusweig/rakkess)

[kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can)

[Kubernetes Security - Best Practice Guide](https://github.com/freach/kubernetes-security-best-practice)

[External Secrets](https://github.com/external-secrets/external-secrets)

## Papers

[Kubernetes Security Assessment](https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/Kubernetes%20Final%20Report.pdf)

[Kubernetes Security Whitepaper](https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/Kubernetes%20White%20Paper.pdf)

[Kubernetes Threat Model](https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/Kubernetes%20Threat%20Model.pdf)

[Kubernetes Attack Tree](https://github.com/cncf/financial-user-group/tree/master/projects/k8s-threat-model)

[Attacking Kubernetes - A Guide for Administrators and Penetration Testers](https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/AtredisPartners_Attacking_Kubernetes-v1.0.pdf)

[CIS Kubernetes Benchmark v1.5.0](https://www.cisecurity.org/benchmark/kubernetes/)

[Kubernetes é seguro por default ou à prova de má configuração?](https://medium.com/@p0ssuidao/kubernetes-%C3%A9-seguro-por-default-ou-aprova-de-m%C3%A1-configura%C3%A7%C3%A3o-9d3bccc2f342) 🇧🇷

## Podcasts

[TGI Kubernetes](https://www.youtube.com/playlist?list=PL7bmigfV0EqQzxcNpmcdTJ9eFRPBe-iZa)

[The Podlets](https://thepodlets.io)

[Kubecast](https://www.kubecast.com/)

[Kubernetes Podcast (from Google)](https://kubernetespodcast.com/)

[PodCTL - Enterprise Kubernetes](https://www.podctl.com/)

## Jobs

[Kube Careers](https://kube.careers/)

## Community

[Kubernetes Slack](https://kubernetes.slack.com)

[CNCF Slack](https://cloud-native.slack.com)

[kubepwn](https://github.com/alexivkin/kubepwn)

[awesome-kubernetes-security](https://github.com/ksoclabs/awesome-kubernetes-security)

[awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes)

[awesome-istio](https://github.com/mstrYoda/awesome-istio)

[awesome-falco](https://github.com/developer-guy/awesome-falco)