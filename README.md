# 👋 Hi there! I'm Agung Gunawan

[![Portfolio](https://img.shields.io/badge/-Portfolio-black?labelColor=white&style=for-the-badge&logo=googlechrome&logoColor=black)](https://agunggunawan.com)
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logoColor=white&link=https://www.linkedin.com/in/agunggnn/&logo=linkedin)](https://www.linkedin.com/in/agunggnn/)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:agunawan.id@gmail.com)](mailto:agunawan.id@gmail.com)
[![ProfileViews](https://komarev.com/ghpvc/?username=agunggnn&color=brightgreen&style=for-the-badge)](https://github.com/antonkomarev/github-profile-views-counter)

**Senior DevOps Engineer · RHCSA · Red Hat Certified Specialist in Ansible Automation**  
📍 Jakarta, Indonesia <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" />

> [!NOTE]
> 🚀 Senior DevOps Engineer with **8+ years** building and running production systems for Indonesian financial institutions and Southeast Asian hyperscale tech. Designs CI/CD and deployment pipelines end-to-end across mobile, backend, and cloud-native workloads, with automated quality and security checks built into every stage. Strong background in Kubernetes, Ansible automation, observability, and DevSecOps.

---

## 💼 Work Experience

### Senior DevOps Engineer `CURRENT`
**Financial Sector — Indonesia** <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" />  
*Sep 2025 – Present | Jakarta, Indonesia*

Embedded at a financial-sector client defining how software ships — CI/CD and deployment architecture for mobile, backend, and cloud workloads, with the quality and security gates that go with it.

- 📱 **Mobile CI/CD Pipeline:** Architected a Flutter mobile CI/CD pipeline from scratch on GitLab CI — MR validation (lint, schema, version, dependency audit, SonarQube gate), artifact build, push to Nexus, multi-environment distribution, and automated release to Firebase and Google Play Store.
- 🧪 **Automated Testing:** Integrated Katalon Runtime Engine for Android automated testing, triggering test suites at the QA review stage.
- ☁️ **Cloud Native Backend CI/CD:** Built a new CI/CD pipeline for Python services deploying to Azure Kubernetes Service (AKS) — build, containerization, and multi-environment rollout, with Trivy filesystem vulnerability scanning gating releases on security findings.
- 🔍 **Quality Governance:** Led SonarQube upgrade readiness — assessed scanner compatibility per stack (Java, React/npm), identified pipeline stages that bottleneck developer workflow, and migrated projects onto SonarScanner CLI with tuned quality gates.

**Tech stack:** GitLab CI, Kubernetes, Azure Kubernetes Service (AKS), Flutter, Python, Docker, Trivy, SonarQube, Katalon Runtime Engine, Nexus, Firebase Distribution, Google Play Deploy, Linux (RHEL)

---

### Site Reliability Engineer / DevOps Engineer
**PT. Sea Labs Indonesia (Shopee)** <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" />  
*Aug 2022 – May 2025 · 2 yrs 9 mos | Jakarta, Indonesia*

SRE for the Games & Marketing division at Shopee — one of Southeast Asia's largest e-commerce platforms. Owned service reliability, CI/CD, observability, and infrastructure readiness for peak mega-campaigns (10.10, 11.11, 12.12). Scope expanded to 50% dev / 50% ops in Q1 2025.

- 🔥 **Fire Drill Program:** Initiated and ran the firedrill reliability program — pre-production simulation of infrastructure and network failures (Redis failure, RDS failure, high CPU utilization, pod imbalance, and non-200 HTTP response codes) every campaign cycle, coordinated with engineering leads across teams.
- ⚡ **Automated Troubleshooting:** Calibrated and engineered Prometheus/PromQL alert baselines wired into the internal auto-troubleshooting platform.
- 📊 **Troubleshooting Dashboards:** Designed Grafana troubleshooting dashboards for NOC and engineering, cutting mean-time-to-diagnosis (MTTD) on high-traffic campaign dates.
- 🏢 **GCP to On-Prem Migration:** Led full migration of multi-country applications from Google Cloud Platform (GCP) to Shopee's internal data center — CI/CD, object storage (PV/PVC), MySQL, Nginx load balancing, DNS, Grafana, and Elasticsearch logging.
- 🗄️ **Database Ops:** Supported physical MySQL → AWS RDS migration; created NOC service alert baselines integrated with auto-troubleshooting tooling.
- 🤖 **AI & Automation:** Onboarded teams to the SMART Platform (LLM internal tooling) as Forward Deployed Engineer — built GPT agents, bots, and tool integrations; built CI/CD automation to deploy Cocos Engine on macOS build machines for QA pipelines.

**Tech stack:** Kubernetes, Docker, Prometheus, Grafana, PromQL, Node Exporter, GitLab CI, Ansible, Redis, MySQL, AWS RDS, GCP, Nginx, Elasticsearch, Cocos Engine, Linux

---

### Senior DevOps Engineer
**PT. IT Group Indonesia** <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" />  
*Nov 2019 – Jun 2022 · 3 yrs 7 mos | Jakarta, Indonesia*

Led DevOps engineering projects and consulting engagements for enterprise clients across Indonesian banking, financial services, and telecommunications. Mentored junior engineers and built end-to-end DevOps environments from scratch.

- 🏦 **Large Indonesian Private Bank:** Designed and built a complete DevOps platform from scratch: GitLab CE with PostgreSQL cluster, Jenkins, Nexus Repository, and HA Ansible Tower cluster. Developed Groovy CI/CD pipelines for Java Spring Boot and .NET Core apps, deploying to OpenShift 4 via custom Ansible automation.
- 🏛️ **Indonesian Regional Government Bank:** Implemented Red Hat Satellite with a custom patching and hardening pipeline (scan, apply, rollback); piloted then rolled out across the full production Linux estate.
- 🏢 **State-owned Financial Institution:** Led the full Ansible Tower lifecycle: design proposal, requirements gathering, installation, and patching automation rollout across a mixed Linux and Windows server fleet.
- 📡 **Major Indonesian Telco:** Implemented runtime container security (Sysdig Secure + Monitor, Falco, Anchore) — threat detection, compliance posture, and workload monitoring; integrated image scanning into CI/CD. Produced HLD/LLD documentation and delivered technical handover workshops to client operations.
- 🛡️ **Large Indonesian State Bank & Telco:** RHEL installation and baseline configuration at a major state bank environment. Shift-based incident handling for a major telco: RCA via the Red Hat Knowledge Base, escalation to Red Hat support, OS diagnostics, and security patching.
- ⚙️ **Toolchain & QA Pipelines:** Deployed 3-node HA Ansible Tower, HA Nexus Sonatype EE Repository Manager, RBAC across toolchain (GitLab, Jenkins, Ansible Tower, Nexus, OpenShift 4.2). Implemented Selenium Grid automation testing (Python) and built end-to-end DevSecOps CI/CD pipeline PoC on OpenShift 4.

**Tech stack:** Red Hat OpenShift 4, Kubernetes, Ansible Tower (AWX), Red Hat Satellite, GitLab CE, Jenkins, Groovy Pipelines, Nexus Sonatype Pro, Sysdig Secure, Falco, Anchore, PostgreSQL (EDB), Selenium Grid, RHEL

---

### Linux System Engineer
**PT. IT Group Indonesia** <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" />  
*Nov 2017 – Nov 2019 · 2 yrs | Jakarta, Indonesia*

Top performer from the Red Hat Linux System Administration training cohort, hired directly into a client-facing role; achieved RHCSA within three months. Delivered Linux infrastructure and database engagements across banking, financial services, and telco clients.

- 🐧 **RHEL Administration:** RHEL installation and configuration (NTP/Chrony, network bonding, multipath), security patching, preventive maintenance, and RCA from system logs (syslog, vmcore). Authored OS hardening Bash scripts for RHEL 6 & 7.
- 🗄️ **EnterpriseDB / PostgreSQL:** Cluster replication setup, Enterprise Failover Manager (EFM), PostgreSQL Enterprise Manager (PEM), BART backup/restore at enterprise level.
- 🛰️ **Enterprise Identity & Patching:** Implemented Red Hat Satellite 6.2 for centralized patch and content management; Red Hat Identity Management (IdM/FreeIPA) integrated with Active Directory.
- 🏗️ **Clustering & OpenShift 3:** Implemented Red Hat HA (Pacemaker) and GFS2 Resilient Storage; deployed OpenShift 3.1 with Container Storage, Metrics, Monitoring, and Logging.

**Tech stack:** Red Hat Enterprise Linux (RHEL), OpenShift 3.1, Red Hat Satellite 6.2, Red Hat IdM, Pacemaker HA, GFS2, PostgreSQL (EDB EFM/PEM/BART), Bash Scripting

---

### Independent DevOps Consultant
**Freelance / Project-Based**  
*2022 – Present · Selected Engagements*

- ☁️ **Monolith → Kubernetes Migration (AWS):** Migrated a monolithic application from VM to Kubernetes; deployed multi-environment clusters (non-prod / prod), built GitHub Actions CI/CD, designed reusable Helm templates stored in S3, and managed VPC, subnets, and ingress configuration.
- 📜 **EFK Logging Pipeline:** Built a centralized logging pipeline alongside the Kubernetes migration — Fluentd (via Helm) shipping to Elasticsearch on AWS, visualized in Kibana; wrote a custom Fluentd parser converting unstructured logs to structured JSON with multi-line stack-trace handling.

**Tech stack:** Kubernetes, Amazon EKS, Helm, GitHub Actions, AWS (EC2, RDS, S3, VPC), Fluentd, Elasticsearch, Kibana

---

### Earlier Career (2011 – 2017)
- **IT Staff** — PT. Graha Bara Lestari (Partner PT. PLN), 2013–2017: billing system monitoring, LAN troubleshooting, customer data verification, DB queries, hardware/OS maintenance.
- **IT Hospitality** — PT. NettoCyber (Four Seasons Hotel), 2012–2013: bandwidth management, wireless installation, hardware/software troubleshooting, guest support.
- **Apprentice, IT Support** — PT. Nutrifood Indonesia, 2011: PABX/PC/printer troubleshooting, end-user support, PC installation, video conferencing setup.

---

## 🏢 Career Timeline

Financial Sector <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" /> | [Sea Labs (Shopee)](https://careers.shopee.co.id/) <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" /> | PT. IT Group Indonesia <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" /> | PT. Graha Bara Lestari <img src="https://raw.githubusercontent.com/hjnilsson/country-flags/master/svg/id.svg" width="16" alt="Indonesia flag" />

---

## 🏗️ Industry Expertise

Fintech & Banking (OJK / BI Compliance) 🏦 | E-Commerce Hyperscale 🛒 | Telco Infrastructure 📡 | DevSecOps & OWASP 🛡️ | High Availability & SRE 📈 | Cloud Native & Kubernetes ☁️

---

<details>
  <summary>📜 Certifications & Education</summary>

<br />

### 🎓 Professional Certifications
- 🔴 **RHCSA — Red Hat Certified System Administrator** (2017 · *Cert ID: 180-001-901*)
- 🔴 **Red Hat Certified Specialist in Ansible Automation** (2020 · *Cert ID: 180-001-901*)
- 🐘 **EnterpriseDB Professional — PostgreSQL Advanced Server 9.6** (2019)
- 🐘 **EnterpriseDB Associate — PostgreSQL Advanced Server 9.6** (2018)
- 🛠️ **Certified Jenkins Engineer** — *Linux Academy (2019)*

### 🏫 Education
- 🎓 **Bachelor of Informatics Engineering (S1)** — *STMIK Dharma Negara Bandung (2013 – 2017)*
- 💻 **Computer & Network Engineering (Vocational)** — *SMK Wikrama Bogor (2009 – 2012)*

### 📚 Specialized Training
- 🔴 **Red Hat System Administration — RH124 & RH134** (2017)
- 🐘 **PostgreSQL & EnterpriseDB Associate Training** (2018)

### 🏆 Competition
- **System Administrator Competition — Bogor (2011):** School representative; tasks covered PC assembly/disassembly, LAN cable setup, Linux server configuration (DHCP, DNS, mail, proxy, HTTP server), and internet routing via proxy server.

---

</details>

<details>
  <summary>💻 Featured Projects & Repositories</summary>

<!--START_SECTION:projects-section-->
<table width="100%">
  <thead>
    <tr>
      <th>Project / Repository</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://agunggunawan.com"><img alt="Portfolio" src="https://img.shields.io/badge/-agunggunawan.com-181717?style=for-the-badge&logo=googlechrome&logoColor=white" /></a></td>
      <td>🌐 Personal engineering portfolio, operational philosophy, and consulting offerings.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/agunggnn/falco"><img alt="falco" src="https://img.shields.io/badge/-falco-181717?style=for-the-badge&logo=github&logoColor=white" /></a></td>
      <td>🛡️ Cloud-native runtime security rules and system call monitoring integration.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/agunggnn/k3s"><img alt="k3s" src="https://img.shields.io/badge/-k3s-181717?style=for-the-badge&logo=github&logoColor=white" /></a></td>
      <td>📦 Lightweight Kubernetes cluster infrastructure & automated deployment scripts.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/agunggnn/sonarqube"><img alt="sonarqube" src="https://img.shields.io/badge/-sonarqube-181717?style=for-the-badge&logo=github&logoColor=white" /></a></td>
      <td>🔍 Code quality gates and static application security testing (SAST) workflows.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/agunggnn/hetzer"><img alt="hetzer" src="https://img.shields.io/badge/-hetzer-181717?style=for-the-badge&logo=github&logoColor=white" /></a></td>
      <td>⚡ Zero-plaintext credential protection & sub-2ms secret sniffer for autonomous agents.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/agunggnn/htrn-platform"><img alt="htrn-platform" src="https://img.shields.io/badge/-htrn--platform-181717?style=for-the-badge&logo=github&logoColor=white" /></a></td>
      <td>🚀 Core scalable application infrastructure platform and microservices architecture.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/agunggnn/Hermes-agent-android-PC-companion-app"><img alt="Hermes Companion" src="https://img.shields.io/badge/-Hermes--Companion-181717?style=for-the-badge&logo=github&logoColor=white" /></a></td>
      <td>📱 PC companion application and remote execution telemetry bridge for Hermes Agent.</td>
    </tr>
  </tbody>
</table>
<!--END_SECTION:projects-section-->

---

</details>

<details>
  <summary>🧰 Things I code with</summary>

<!--START_SECTION:code-with-section-->
<table width="100%">
  <thead>
    <tr>
      <th>Category</th>
      <th>Technologies</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>CI/CD Pipelines</th>
      <td>
        <img alt="GitLab CI" src="https://img.shields.io/badge/-GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
        <img alt="Jenkins" src="https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
        <img alt="GitHub Actions" src="https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
        <img alt="Nexus" src="https://img.shields.io/badge/-Nexus_Sonatype-000000?style=flat-square&logo=sonatype&logoColor=white" />
        <img alt="Helm" src="https://img.shields.io/badge/-Helm-0F1689?style=flat-square&logo=helm&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>Container Orchestration</th>
      <td>
        <img alt="Kubernetes" src="https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
        <img alt="Amazon EKS" src="https://img.shields.io/badge/-Amazon_EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white" />
        <img alt="Azure AKS" src="https://img.shields.io/badge/-Azure_AKS-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
        <img alt="OpenShift" src="https://img.shields.io/badge/-OpenShift_3_&_4-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white" />
        <img alt="Docker" src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>Automation & Config</th>
      <td>
        <img alt="Ansible" src="https://img.shields.io/badge/-Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" />
        <img alt="Ansible Tower" src="https://img.shields.io/badge/-Ansible_Tower_(AWX)-EE0000?style=flat-square&logo=ansible&logoColor=white" />
        <img alt="Bash" src="https://img.shields.io/badge/-Bash_/_Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
        <img alt="Red Hat Satellite" src="https://img.shields.io/badge/-Red_Hat_Satellite-EE0000?style=flat-square&logo=redhat&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>Cloud Platforms</th>
      <td>
        <img alt="AWS" src="https://img.shields.io/badge/-AWS_(EC2·EKS·RDS·S3·VPC)-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
        <img alt="Google Cloud" src="https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
        <img alt="Microsoft Azure" src="https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>Observability (O11Y)</th>
      <td>
        <img alt="Prometheus" src="https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
        <img alt="Grafana" src="https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
        <img alt="PromQL" src="https://img.shields.io/badge/-PromQL-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
        <img alt="Fluentd" src="https://img.shields.io/badge/-Fluentd-0E83C8?style=flat-square&logo=fluentd&logoColor=white" />
        <img alt="Elasticsearch" src="https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" />
        <img alt="Kibana" src="https://img.shields.io/badge/-Kibana-005571?style=flat-square&logo=kibana&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>DevSecOps / OWASP</th>
      <td>
        <img alt="SonarQube" src="https://img.shields.io/badge/-SonarQube-4B9FD5?style=flat-square&logo=sonarqube&logoColor=white" />
        <img alt="Trivy" src="https://img.shields.io/badge/-Trivy-1B75BC?style=flat-square&logo=aquasec&logoColor=white" />
        <img alt="Falco" src="https://img.shields.io/badge/-Falco-00AEC7?style=flat-square&logo=falco&logoColor=white" />
        <img alt="Sysdig Secure" src="https://img.shields.io/badge/-Sysdig_Secure_&_Monitor-FF6600?style=flat-square&logo=sysdig&logoColor=white" />
        <img alt="Anchore" src="https://img.shields.io/badge/-Anchore-00A871?style=flat-square&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>Linux Systems</th>
      <td>
        <img alt="RHEL" src="https://img.shields.io/badge/-RHEL-EE0000?style=flat-square&logo=redhat&logoColor=white" />
        <img alt="CentOS" src="https://img.shields.io/badge/-CentOS-262577?style=flat-square&logo=centos&logoColor=white" />
        <img alt="Ubuntu" src="https://img.shields.io/badge/-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" />
        <img alt="Debian" src="https://img.shields.io/badge/-Debian-A81D33?style=flat-square&logo=debian&logoColor=white" />
        <img alt="systemd" src="https://img.shields.io/badge/-systemd_·_LVM_·_NFS-000000?style=flat-square&logo=linux&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>Databases</th>
      <td>
        <img alt="PostgreSQL EDB" src="https://img.shields.io/badge/-PostgreSQL_(EDB)-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img alt="MySQL" src="https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
        <img alt="Redis" src="https://img.shields.io/badge/-Redis-FF4438?style=flat-square&logo=redis&logoColor=white" />
        <img alt="AWS RDS" src="https://img.shields.io/badge/-AWS_RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white" />
      </td>
    </tr>
    <tr>
      <th>Mobile & QA Pipelines</th>
      <td>
        <img alt="Flutter" src="https://img.shields.io/badge/-Flutter_CI/CD-02569B?style=flat-square&logo=flutter&logoColor=white" />
        <img alt="Firebase Distribution" src="https://img.shields.io/badge/-Firebase_Distribution-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
        <img alt="Google Play" src="https://img.shields.io/badge/-Google_Play_Deploy-414141?style=flat-square&logo=googleplay&logoColor=white" />
        <img alt="Katalon" src="https://img.shields.io/badge/-Katalon_Runtime_Engine-336699?style=flat-square&logoColor=white" />
      </td>
    </tr>
  </tbody>
</table>
<!--END_SECTION:code-with-section-->

---

</details>

<details>
  <summary>🎂 Experience</summary>

<!--START_SECTION:experience-section-->
<table width="100%">
  <thead>
    <th colspan="5">Experience (in years)</th>
  </thead>
  <tbody>
    <tr>
      <td><strong>8+</strong> Linux (RHEL / CentOS)</td>
      <td><strong>8+</strong> CI/CD (GitLab, Jenkins)</td>
      <td><strong>7+</strong> Ansible & Automation</td>
      <td><strong>6+</strong> Kubernetes & OpenShift</td>
      <td><strong>6+</strong> Docker & Containers</td>
    </tr>
    <tr>
      <td><strong>5+</strong> Prometheus & Grafana</td>
      <td><strong>5+</strong> PostgreSQL (EDB) / MySQL</td>
      <td><strong>4+</strong> AWS & Cloud Platforms</td>
      <td><strong>4+</strong> DevSecOps (Falco, SonarQube)</td>
      <td><strong>4+</strong> EFK Stack (Logging)</td>
    </tr>
  </tbody>
</table>
<!--END_SECTION:experience-section-->

---

</details>

<details>
  <summary>:octocat: GitHub Stats</summary>

(since June 10, 2018)

[![agunggnn's GitHub stats](https://github-readme-stats-fast.vercel.app/api?username=agunggnn&line_height=28&card_width=490&hide_title=true&hide_border=true&show_icons=true&theme=chartreuse-dark&icon_color=7FFF00&include_all_commits=true&count_private=true)](https://github.com/anuraghazra/github-readme-stats)
[![agunggnn's Top Languages](https://github-readme-stats-fast.vercel.app/api/top-langs?hide_border=true&username=agunggnn&include_all_commits=true&count_private=true&show_icons=true&theme=chartreuse-dark&layout=compact&langs_count=10)](https://github.com/anuraghazra/github-readme-stats)

[![agunggnn's GitHub streak](https://streak-stats.demolab.com/?user=agunggnn&theme=github-green-purple&fire=FF6600)](https://github.com/DenverCoder1/github-readme-streak-stats)

---

</details>
