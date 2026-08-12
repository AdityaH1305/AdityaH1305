<!-- ============================ HEADER ============================ -->

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f2027,50:203a43,100:2c5364&text=Aditya%20Harikrishnan&fontSize=46&fontColor=ffffff&fontAlignY=34&desc=Backend%20%E2%80%A2%20Full-Stack%20%E2%80%A2%20Machine%20Learning&descSize=16&descAlignY=53&animation=fadeIn" width="100%" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=00F7FF&center=true&vCenter=true&width=620&lines=B.Tech+CSE+%40+IIIT+Pune;Designing+systems%2C+not+just+scripts.;Deep+learning+%7C+APIs+%7C+System+design;Turning+research+papers+into+running+code." />

<br/>

<a href="https://www.linkedin.com/in/aditya-harikrishnan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://adityaharikrishnan.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" /></a>
<a href="mailto:adityaharikrishnan@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=AdityaH1305&style=flat-square&color=00f7ff&label=Profile+Views" />

</div>

---

## 🧠 About

```python
from dataclasses import dataclass, field

@dataclass
class Aditya:
    role:     str  = "Software Developer"
    edu:      str  = "B.Tech CSE @ IIIT Pune"
    focus:    list = field(default_factory=lambda: [
        "Deep Learning & Computer Vision",
        "Backend architecture & scalable APIs",
        "Recommender systems",
    ])
    stack:    list = field(default_factory=lambda: ["Python", "PyTorch", "FastAPI", "Next.js"])
    learning: list = field(default_factory=lambda: ["MLOps", "Distributed Systems", "Model Serving at Scale"])

    def philosophy(self) -> str:
        return "Ship it, measure it, then make it fast."
```

I like the part of the stack where research meets production — training a segmentation network is only half the job, the other half is serving it behind an API that doesn't fall over. Most of what I build sits somewhere on that line.

<br/>

```mermaid
flowchart LR
    A["📊 Data"] --> B["🧠 Model<br/>PyTorch · TF · OpenCV"]
    B --> C["⚙️ Service<br/>FastAPI · Flask"]
    C --> D["🖥️ Interface<br/>React · Next.js"]
    C --> E["🗄️ Storage<br/>MySQL · SQLite"]
    D --> F["🚀 Deploy<br/>Docker · Linux · Git"]
    E --> F
```

---

## ⚡ Tech Stack

<table width="100%">
<tr>
<td width="150" valign="middle"><b>Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=python,java,js,c,html,css&theme=dark" /></td>
</tr>
<tr>
<td valign="middle"><b>ML / AI</b></td>
<td><img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sklearn&theme=dark" /></td>
</tr>
<tr>
<td valign="middle"><b>Frameworks</b></td>
<td><img src="https://skillicons.dev/icons?i=fastapi,flask,react,nextjs&theme=dark" /></td>
</tr>
<tr>
<td valign="middle"><b>Data</b></td>
<td><img src="https://skillicons.dev/icons?i=mysql,sqlite&theme=dark" /></td>
</tr>
<tr>
<td valign="middle"><b>Tooling</b></td>
<td><img src="https://skillicons.dev/icons?i=git,github,docker,linux,vscode,postman&theme=dark" /></td>
</tr>
</table>

---

## 🚀 Featured Work

<table width="100%">
<tr>

<td width="50%" valign="top">

### 🧬 Modified Double U-Net

> Enhanced Double U-Net architecture for **medical image segmentation** — encoder–decoder stacking with squeeze-and-excitation and ASPP-style context capture, implemented end-to-end in PyTorch.

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/Computer%20Vision-00A98F?style=flat-square" />
<img src="https://img.shields.io/badge/Segmentation-6E56CF?style=flat-square" />

<a href="https://github.com/Aditya11835/Modified_DoubleUNet_Implementation"><img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</td>

<td width="50%" valign="top">

### 🎮 Ludex

> Hybrid **recommendation engine** for Steam. Content-based TF-IDF signals fused with Implicit ALS collaborative filtering to handle cold-start users without losing personalization.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Implicit%20ALS-F7931E?style=flat-square" />
<img src="https://img.shields.io/badge/TF--IDF-4B8BBE?style=flat-square" />

<a href="https://github.com/Aditya11835/Ludex"><img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</td>

</tr>
<tr>

<td width="50%" valign="top">

### 🚶 Gait Multi-Modal Fusion

> Deep learning framework for **gait recognition** across multiple modalities, with feature-level fusion to stay robust where any single modality degrades.

<img src="https://img.shields.io/badge/Deep%20Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/Multi--Modal-9333EA?style=flat-square" />
<img src="https://img.shields.io/badge/Biometrics-0EA5E9?style=flat-square" />

<a href="https://github.com/AdityaH1305/Gait-Multi-Modal-Fusion"><img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</td>

<td width="50%" valign="top">

### 🚁 SynthRescue

> AI disaster-response platform: **YOLO** detection over aerial imagery piped into Gemini for situational reasoning, served through a FastAPI backend and a Next.js operator dashboard.

<img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />

<a href="https://github.com/AdityaH1305/SynthRescue"><img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</td>

</tr>
</table>

---

## 📊 GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=AdityaH1305&theme=tokyonight&hide_border=true&border_radius=8" />

</div>

---

## 🐍 Contribution Graph

<div align="center">
<img src="https://raw.githubusercontent.com/AdityaH1305/AdityaH1305/output/github-contribution-grid-snake-dark.svg" />
</div>

---

## 🏆 Highlights

<table width="100%">
<tr>
<td width="50%" align="center">
<img src="https://img.shields.io/badge/ISRO-Machine%20Learning%20Intern-FF6D00?style=for-the-badge&logo=rocket&logoColor=white" /><br/>
<sub><b>Indian Space Research Organisation</b><br/>Applied ML research internship</sub>
</td>
<td width="50%" align="center">
<img src="https://img.shields.io/badge/Microsoft-AZ--900%20Certified-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" /><br/>
<sub><b>Azure Fundamentals</b><br/>Cloud infrastructure &amp; services</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://img.shields.io/badge/Research-Hybrid%20RecSys-9333EA?style=for-the-badge" /><br/>
<sub><b>Technical Documentation</b><br/>Hybrid recommendation systems</sub>
</td>
<td align="center">
<img src="https://img.shields.io/badge/Shipped-Full--Stack%20Apps-00A98F?style=for-the-badge" /><br/>
<sub><b>End-to-End Delivery</b><br/>Multiple production-style applications</sub>
</td>
</tr>
</table>

---

## 🤝 Connect

<div align="center">

<a href="https://www.linkedin.com/in/aditya-harikrishnan/"><img src="https://skillicons.dev/icons?i=linkedin" /></a>
<a href="mailto:adityaharikrishnan@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" /></a>
<a href="https://adityaharikrishnan.vercel.app/"><img src="https://skillicons.dev/icons?i=vercel&theme=dark" /></a>

<br/><br/>

<i>"Building software that is scalable, intelligent and impactful."</i>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:2c5364,50:203a43,100:0f2027" width="100%" />
