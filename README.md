<div align="center">

<!-- Self-hosted static SVG. capsule-render emits paths with an empty "d" that only exist inside SMIL, so the background vanished when animation did not run. -->
<img src="assets/banner.svg" width="100%" alt="Le Bao Duy - DevOps Engineer, multi-cloud architecture" />

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=60A5FA&center=true&vCenter=true&width=700&lines=DevOps+Engineer+%C2%B7+multi-cloud+and+on-prem+platforms;Driving+AI-DLC+adoption+across+a+bank+IT+Division;CKA+%C2%B7+CKS+%C2%B7+AWS+SA+Associate+%C2%B7+ITIL+Foundation" alt="typing" />
</a>

<br/><br/>

<a href="https://linkedin.com/in/lebaoduy"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:vn.lebaoduy@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://pvcombank.com.vn"><img src="https://img.shields.io/badge/PVcomBank-0F172A?style=for-the-badge&logo=googlechrome&logoColor=60A5FA" alt="Website" /></a>
<a href="https://github.com/vnlebaoduy?tab=followers"><img src="https://img.shields.io/github/followers/vnlebaoduy?style=for-the-badge&color=1e3a8a&labelColor=0f172a&logo=github&logoColor=white" alt="Followers" /></a>
<img src="https://komarev.com/ghpvc/?username=vnlebaoduy&style=for-the-badge&color=4c1d95&label=PROFILE+VIEWS" alt="Views" />

</div>

---

### About

- **DevOps engineer** with 3+ years in multi-cloud (AWS, GCP) and on-premise infrastructure, preceded by 5+ years as a developer and R&D engineer.
- Currently a Center Specialist at **PVcomBank**, leading the rollout of **AI-DLC** (AI-Driven Development Life Cycle) guidelines across the entire IT Division — defining how AI coding assistants are used from requirements through release, with guardrails for banking security and compliance.
- I work across the whole stack, which is what makes the architectural calls possible: event-driven serverless pipelines, container orchestration, IaC, production ML/AI serving, and Python/Java/React application code.
- Based in **Ha Noi, Vietnam** 🇻🇳 · English (professional working proficiency).

---

### Certifications

<div align="center">

<img src="https://img.shields.io/badge/CKS-Certified%20Kubernetes%20Security%20Specialist-326CE5?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0b1120" alt="CKS" />
<img src="https://img.shields.io/badge/CKA-Certified%20Kubernetes%20Administrator-326CE5?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0b1120" alt="CKA" />
<br/>
<img src="https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=0b1120" alt="AWS SAA" />
<img src="https://img.shields.io/badge/ITIL-Foundation%20v5-6A2C91?style=flat-square&labelColor=0b1120" alt="ITIL Foundation" />

</div>

---

### Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,gcp,kubernetes,docker,terraform,ansible,jenkins,gitlab,githubactions,linux&theme=dark" alt="cloud, containers, IaC and CI/CD" />
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,kafka,prometheus,grafana,elasticsearch,nginx&theme=dark" alt="data, messaging and observability" />
<br/>
<img src="https://skillicons.dev/icons?i=py,fastapi,go,java,spring,ts,react,nextjs,pytorch,tensorflow&theme=dark" alt="languages, frameworks and ML" />

</div>

<p align="center"><sub>No icon exists for these, so they are listed in text: Proxmox, VMware, KVM, Oracle Database, PostGIS/pgvector, vLLM, YOLO/SAHI, Wazuh, Falco, Trivy, Graylog.</sub></p>

---

### Selected engineering work

Most of this is internal to employers rather than public repositories, so it is described here instead of linked.

| Project | Scope | Outcome |
| --- | --- | --- |
| **AI-DLC adoption** · PVcomBank | SDLC governance for AI coding assistants in a regulated bank: guardrails, data-classification rules, human review checkpoints, playbooks and training. | Adopted across the entire IT Division. |
| **Ship detection pipeline** · GCP | Event-driven hybrid compute — spot GCE MIG for I/O-bound 16→8-bit conversion, Cloud Run on L4 GPU for YOLO OBB + SAHI inference, wired through GCS notifications, Pub/Sub and Eventarc with a DLQ. Terraform-managed. | 12K+ files/day · **3× cost reduction** (~$5,400 → ~$1,800/month) · 35–45s warm latency · ~75% storage compression. |
| **GeoGPT** | On-premise Qwen3-14B served with vLLM, RAG on PostgreSQL + pgvector (no separate vector DB), natural-language queries over AIS vessel tracking and satellite imagery, plus offline geocoding for air-gapped operation. | Full data sovereignty, zero per-token cost, sub-second retrieval. |
| **Space FM** | Multi-tenant STAC platform for petabyte-scale imagery: pgstac partitioning, ARQ ingestion workers, TiTiler COG tiles, Next.js + MapLibre frontend, RBAC with 60+ permissions and short-lived STS credentials. | 100M+ STAC items · <500ms p95 search on 10M · <200ms tile generation · 315+ backend tests. |
| **Datacenter buildout** · Vegastar | End-to-end design to Uptime Institute Tier II principles: N+1 UPS with diesel generator and ATS, CO2 suppression, precision cooling, 25GbE/SFP28 fabric and 20Gbps SAN, plus vendor and BOM ownership. | 53+ VMs provisioned via Terraform/Ansible across Proxmox/KVM and VMware. |
| **Geospatial training platform** · AWS | Open edX on Auto Scaling, ELB and CloudFront, provisioned with Terraform, hardened with WAF and encryption, monitored with CloudWatch. | 3,000+ concurrent users. |

<sub>Also: SOC build to Vietnam Level 3 information-security standard (Graylog, SIEM/XDR/SOAR, Golang automation) · Traffic Police command centre (Oracle/RMAN, 50M+ records) · AIS data synchronisation on Kafka.</sub>

<sub>Awards at Vegastar: Best Product of the Year (2025, 2018), Employee of the Year (2023), Second Prize in the Creative Product Contest (2019).</sub>

---

### Open source

| Repository | What it is |
| --- | --- |
| **[pi-kiro-connect](https://github.com/vnlebaoduy/pi-kiro-connect)** | Kiro (AWS CodeWhisperer/Q) provider for `pi` and Oh My Pi — kiro-cli-compatible login, live model catalog, credit usage. |
| **[KiroCrew](https://github.com/vnlebaoduy/KiroCrew)** | A persistent workspace for development work that self-improves and continues beyond one session. |
| **[aidlc-workflows](https://github.com/vnlebaoduy/aidlc-workflows)** | AI-DLC adaptive workflow steering rules for AI coding agents. |
| **[aidlc-dashboard-v2](https://github.com/vnlebaoduy/aidlc-dashboard-v2)** | Read-only web dashboard for an AI-DLC run: status, progress, blockers, timing and usage. |
| **[fastapi-keycloak-boilerplate](https://github.com/vnlebaoduy/fastapi-keycloak-boilerplate)** | FastAPI boilerplate with user management and authentication via Keycloak. |
| **[airflow-minio-postgres-fastapi](https://github.com/vnlebaoduy/airflow-minio-postgres-fastapi)** | Data-store stack with GitHub Actions CI/CD doing SSH deploy to remote Docker Compose. |

---

### GitHub activity

<div align="center">

<!-- Generated in-repo daily by .github/workflows/profile-3d.yml - not dependent on any third-party uptime -->
<img src="profile-3d-contrib/profile-night-view.svg" width="98%" alt="3D contribution calendar" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=vnlebaoduy&theme=github_dark" width="98%" alt="profile summary" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=vnlebaoduy&theme=github_dark" width="49%" alt="repos per language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=vnlebaoduy&theme=github_dark" width="49%" alt="most committed language" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=vnlebaoduy&theme=github_dark" width="49%" alt="stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=vnlebaoduy&utcOffset=7&theme=github_dark" width="49%" alt="productive time" />

<br/>

<img src="https://streak-stats.demolab.com/?user=vnlebaoduy&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D" width="60%" alt="contribution streak" />

</div>

---

<div align="center">

<sub>Open to work on platform engineering, multi-cloud architecture and AI-assisted delivery workflows — <a href="mailto:vn.lebaoduy@gmail.com">say hello</a>.</sub>

<img src="assets/footer.svg" width="100%" alt="" />

</div>
