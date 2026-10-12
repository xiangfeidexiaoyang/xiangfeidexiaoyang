<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,15,18,21,24&height=140&section=header&text=Feiyang%20Liu&fontSize=38&fontAlignY=38&desc=M.S.%20Student%20%C2%B7%20THU-CVML%20%C2%B7%20Tsinghua%20University&descAlignY=58&descAlign=50&animation=twinkling" alt="header"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=1F3864&center=true&vCenter=true&width=520&lines=Generative+models+%26+video+diffusion;Post-training+%28SFT%2C+GRPO%2C+OPD%29;Structured+credit+assignment+for+RL" alt="Typing SVG" />

<br/>

<a href="mailto:liufy26@mails.tsinghua.edu.cn">
  <img src="https://img.shields.io/badge/Email-liufy26%40mails.tsinghua.edu.cn-1f3864?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://thu-cvml.github.io/">
  <img src="https://img.shields.io/badge/Lab-THU--CVML-2563eb?style=for-the-badge&logo=readthedocs&logoColor=white" alt="THU-CVML"/>
</a>
<a href="https://github.com/xiangfeidexiaoyang">
  <img src="https://img.shields.io/badge/GitHub-xiangfeidexiaoyang-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

</div>

<br/>

**Affiliation.** Computer Application Technology Laboratory, Tsinghua University · Advisor: [Prof. Chun Yuan](https://thu-cvml.github.io/Overview/Professor/)

**Research interests.** Learning algorithms for generative models and large-scale training: structured credit assignment in RL (physical events, agent sub-goals), post-training (SFT, GRPO, on-policy distillation), and video diffusion / flow matching (physics-aware generation, long-horizon consistency, denoise-step scheduling for far memory).

---

#### Publications & manuscripts

<table>
<tr>
<td width="100%">

*Event-Span GRPO: Event-level Credit Assignment for Physics-aligned Video Generation*  
**First author** · manuscript in preparation  
Group-relative advantages over **physical event spans** (contact, collision, free fall, static segments) rather than full clips; built on DanceGRPO with a Wan2.2-class video backbone, with PhysRVG / Physics-IQ–style evaluation and quality constraints.

*HeadMoE: Data-free Sparse MoE Merging for Multi-site Specialized Models*  
**First author** · manuscript in preparation  
Shared trunk with low-rank, site-specific attention / classification heads and a training-free router from input–subspace alignment; targets federated-style deployment without pooling raw data.

*Late Forcing: Low-Noise Memory Injection for Frozen Few-Step Video Generators*  
**First author** · manuscript in preparation  
For frozen few-step autoregressive video models, **when** retrieved far memory is exposed along the denoising trajectory—not only **what** is retrieved—controls the trade-off between revisit identity and scene progression. **Late Forcing** is a training-free schedule that injects far memory only at low-noise steps, withholds it early in the chunk, and optionally re-ranks retrieval candidates with a memory-free first-step draft; designed to compose with existing section-, layer-, and query-level memory routers under fixed NFE.

</td>
</tr>
</table>

---

#### Code

| Repository | Description |
|------------|-------------|
| [robot_phys_video_gen](https://github.com/xiangfeidexiaoyang/robot_phys_video_gen) | Physics-anchored robot manipulation video generation (WAM-oriented pipeline) |

---

<h3 align="center">Tools</h3>
<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,linux,docker,git,latex,vscode&perline=8&theme=light" alt="skills"/>
  </a>
</div>

<br/>

#### Education

- **Tsinghua University** — M.S., Electronic Information (2026–2028), THU-CVML  
- **Northeastern University** — B.S., Computer Science and Technology (2021–2025)

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/xiangfeidexiaoyang/xiangfeidexiaoyang/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/xiangfeidexiaoyang/xiangfeidexiaoyang/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub contribution grid snake" src="https://raw.githubusercontent.com/xiangfeidexiaoyang/xiangfeidexiaoyang/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,15,18,21,24&height=80&section=footer&animation=twinkling" alt="footer"/>

</div>
