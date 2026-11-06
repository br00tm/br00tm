<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Pedro%20Brito&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=DevOps%20%C2%B7%20SRE%20%C2%B7%20Cloud%20Infrastructure&descSize=20&descAlignY=60&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=650&lines=DevOps+%26+Site+Reliability+Engineer;Cloud+Infrastructure+%E2%80%94+GCP+%26+AWS;Observability+%E2%80%94+OpenTelemetry+%C2%B7+Grafana;Application+Security+in+CI%2FCD;Computer+Vision+%26+Deep+Learning)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pedrolbrito)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedrolbmoreira23@gmail.com)
![Location](https://img.shields.io/badge/Brazil%20%C2%B7%20Remote%20(UTC--3)-302b63?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 👋 About me

I'm a **DevOps / Site Reliability Engineer** who owns production cloud infrastructure end to end — from Terraform and CI/CD to observability, incident response and cost control. Today I run the GCP production stack of a high-traffic e-commerce integrator connected to Mercado Livre, Shopee and Amazon, where I'm the primary on-call for production incidents.

Before that, I built and operated an edge-to-cloud computer vision platform for ornamental stone inspection — research I presented at **SBAI 2025** and **SBSE 2025**.

I like understanding systems from the bottom up, which is why I wrote my own container runtime from scratch.

```python
class PedroBrito:
    def __init__(self):
        self.name      = "Pedro Brito"
        self.alias     = "br00tm"
        self.location  = "Espírito Santo, Brazil 🇧🇷 (remote, UTC-3)"
        self.education = "B.Sc. Information Systems @ IFES"
        self.role      = "DevOps Engineer | Site Reliability Engineer"
        self.languages = {"Portuguese": "native", "English": "B2"}

    @property
    def focus(self):
        return [
            "☁️  Production cloud infrastructure on GCP & AWS",
            "📈 Observability — OpenTelemetry, VictoriaMetrics, Jaeger, Loki, Grafana",
            "🚨 Incident response & root-cause analysis",
            "💸 FinOps — making the cloud bill smaller without breaking things",
            "🔐 Application security in CI/CD (SAST, DAST, SCA, secret scanning)",
            "🧠 Computer vision for industrial inspection",
        ]
```

---

## ⚡ Recent highlights

- 📉 **Cut metric cardinality by 85%** (2.2M → ~328K series) and fixed a memory leak in the OTel Collector `spanmetrics` connector.
- 💰 **Reduced cloud security spend by 84%** (~R$8,700/month saved) by moving edge filtering from Cloud Armor Enterprise to Cloudflare.
- 🛡️ **Reduced application vulnerabilities by 80%** by wiring SonarQube, Semgrep, Trivy, OWASP ZAP and GitLeaks into the pipelines.
- 🔍 **Root-caused production incidents** — a MongoDB `COLLSCAN` on a 9M+ document collection, a V8 heap OOM behind a 503 cascade, and a GCP regional network incident that led to a 6-phase multi-region resilience plan.
- 🧪 **99.21% accuracy** across 45 ornamental stone classes with a CNN (Xception) pipeline, delivered through CI/CD that cut the model release cycle from 30 to 10 days.

---

## 🧰 Tech stack

<div align="center">

**Cloud & Infrastructure**

<img src="https://skillicons.dev/icons?i=gcp,aws,terraform,docker,kubernetes,ansible,nginx,cloudflare,linux&theme=dark" />

**CI/CD**

<img src="https://skillicons.dev/icons?i=githubactions,gitlab,jenkins,bitbucket&theme=dark" />

**Observability**

<img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" />
<br/>
<img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
<img src="https://img.shields.io/badge/VictoriaMetrics-621773?style=flat-square" alt="VictoriaMetrics" />
<img src="https://img.shields.io/badge/Jaeger-60D0E4?style=flat-square" alt="Jaeger" />
<img src="https://img.shields.io/badge/Loki-F46800?style=flat-square" alt="Loki" />
<img src="https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white" alt="ELK Stack" />

**Backend, Data & Messaging**

<img src="https://skillicons.dev/icons?i=py,nodejs,ts,cs,bash,fastapi,django,flask,mongodb,redis,postgres,mysql,kafka,rabbitmq&theme=dark" />
<br/>
<img src="https://img.shields.io/badge/NATS_JetStream-27AAE1?style=flat-square&logo=natsdotio&logoColor=white" alt="NATS JetStream" />

**AI & Computer Vision**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,raspberrypi&theme=dark" />

**Security & Networking**

![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2A3A?style=flat-square)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=flat-square&logo=owasp&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

</div>

---

## 🏆 Featured projects

| Project | Description | Stack |
|---------|-------------|-------|
| 🏗️ **[PyBox](https://github.com/br00tm/pybox)** | A container runtime built from scratch in pure Python, talking directly to Linux kernel primitives — namespaces, cgroups v2 and OverlayFS — to replicate Docker's core at the syscall level. | `Python 3.11` `Linux 5.4+` `cgroups v2` `OCI` |
| 📊 **[InfraWatch](https://github.com/br00tm/infrawatch)** | DevOps monitoring system running on a local Kubernetes deployment, with RabbitMQ messaging and MongoDB storage. | `Kubernetes` `RabbitMQ` `MongoDB` `Docker` |
| 🎵 **[NLP-DISCOGRAFY](https://github.com/br00tm/NLP-DISCOGRAFY)** | Natural language processing and analysis applied to music discographies. | `Python` `NLP` `scikit-learn` |
| 📅 **[GEC-Eventometro](https://github.com/br00tm/GEC-Eventometro)** | Event management and metrics platform for communities. | `JavaScript` `HTML` `CSS` |
| 👕 **[Venda-Camisas](https://github.com/br00tm/Venda-Camisas)** | Web storefront for selling T-shirts. | `HTML` `CSS` `JavaScript` |

---

## 🔬 Research & publications

> 📄 **[Convolutional Neural Networks for Segmentation and Classification of Ornamental Stones](https://repositorio.ifes.edu.br/handle/123456789/7211)**
> Undergraduate thesis — IFES · Presented at **SBAI 2025** and **SBSE 2025**

An end-to-end computer vision pipeline for **automated industrial inspection** of marble and granite:

- 🎥 Multi-camera capture with **ArduCam 64MP** and **Raspberry Pi**
- 🎨 Color correction and cross-camera standardization
- 🧵 Video stitching to build full panoramas of stone slabs
- 🤖 Automated conveyor-belt detection with **YOLO** and **CNN** models
- 📐 Camera calibration and image processing pipelines
- ☁️ Edge-to-cloud deployment (Docker Compose, K3s, NATS JetStream, WireGuard)

---

## 📈 GitHub stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=br00tm&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=a855f7&icon_color=a855f7&text_color=c9d1d9"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=br00tm&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a855f7&text_color=c9d1d9&langs_count=8"/>

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=br00tm&theme=tokyonight&hide_border=true&background=0d1117&ring=a855f7&fire=a855f7&currStreakLabel=a855f7)](https://git.io/streak-stats)

</div>

---

<div align="center">

💬 **Open to remote DevOps / SRE opportunities** — feel free to reach out on [LinkedIn](https://linkedin.com/in/pedrolbrito) or by [email](mailto:pedrolbmoreira23@gmail.com).

<br/>

*"Any sufficiently advanced technology is indistinguishable from magic."* — Arthur C. Clarke

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>
