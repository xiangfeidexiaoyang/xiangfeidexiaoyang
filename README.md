<h1 align="center">刘飞阳 · Feiyang Liu</h1>

<p align="center">
  <strong>大模型后训练 · 视频生成 · Agentic RL</strong><br/>
  <em>LLM Post-Training · Video Generation · Agentic RL</em>
</p>

<p align="center">
  清华大学 电子信息 硕士（在读）｜ THU-CVML · 袁春 教授<br/>
  <em>M.S. Electronic Information, Tsinghua University (THU-CVML)</em><br/>
  东北大学 计算机 学士 ｜ <em>B.S. CS, Northeastern University (985 / Double First-Class)</em>
</p>

<p align="center">
  <a href="mailto:liufy26@mails.tsinghua.edu.cn">liufy26@mails.tsinghua.edu.cn</a>
  ·
  <a href="mailto:2071890969@qq.com">2071890969@qq.com</a>
  ·
  18784736800
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Post--Training-1f3864?style=flat-square" alt="Focus"/>
  <img src="https://img.shields.io/badge/GRPO-Event--Span-2563eb?style=flat-square" alt="GRPO"/>
  <img src="https://img.shields.io/badge/Video-Wan2.2%20%2B%20Flow-0ea5e9?style=flat-square" alt="Video"/>
  <img src="https://img.shields.io/badge/Stack-verl%20%7C%20vLLM%20%7C%20FSDP-64748b?style=flat-square" alt="Stack"/>
</p>

---

### 关于我 · About

求职方向：**大模型算法实习生** — 后训练 / Agentic RL / 视频生成。

我主要做 **信用分配粒度更细的后训练**（整段 clip → 物理事件 / 子目标 step）和 **生成模型**（扩散、Flow Matching、少步视频 DiT）。工程上熟悉 **verl + vLLM + FSDP** 全链路：SFT、规则奖励 GRPO、多轮 SWE Agent、On-Policy Distillation，并关注训推 logprob 对齐与 rollout 预算公平对照。

I work on **finer-grained credit assignment** in post-training (clip-level → physical events / agent sub-goals) and **generative modeling** (diffusion, flow matching, few-step video DiT). I ship end-to-end **verl / vLLM / FSDP** pipelines for SFT, rule-based GRPO, multi-turn SWE agents, and OPD—with careful held-out eval and rollout-budget-matched baselines.

---

### 科研 · Research

| 方向 | 状态 | 一句话 |
|------|------|--------|
| **Event-Span GRPO** — 物理对齐视频生成的事件级信用分配 | 在写稿 | 优势按碰撞/接触/静止等事件分组，接入 DanceGRPO × **Wan2.2-TI2V-5B** |
| **HeadMoE** — 无数据多中心稀疏 MoE 合并 | 在写稿 | 共享底座 + 低秩 head 专家，zero-shot 路由，OOD Macro F1 提升 |
| **Late Forcing** — 冻结少步 Flow 的长时序记忆（CVPR 2027 冲刺） | 实验进行中 | 远记忆仅在**低噪声步**注入；训练免费，叠在现有 memory router 上 |
| **噪声阶段感知 MoE 路由** | 调研 | TRACK × SplitMoE：路由应感知去噪阶段 |
| **RECAP → 视频 Flow** | 调研 | 优势条件化 flow matching 能否搬到视频 DiT（与 idea1 实验独立） |

> 主页不列未公开论文数字；完整指标见稿件与内部实验记录。

---

### 开源项目 · Selected Repos

| Repo | 说明 |
|------|------|
| [**robot_phys_video_gen**](https://github.com/xiangfeidexiaoyang/robot_phys_video_gen) | WAM 数据集上的物理锚定机器人操作视频生成 |
| [**InsightFlow**](https://github.com/xiangfeidexiaoyang/InsightFlow) | 企业级 RAG / Agent：混合检索、LangGraph 路由 |
| [**Enterprise-Copilot**](https://github.com/xiangfeidexiaoyang/Enterprise-Copilot) | Text-to-SQL + 自纠错 + RBAC 权限感知 RAG |
| [**Bustub-lfy**](https://github.com/xiangfeidexiaoyang/Bustub-lfy) | CMU 15-445 风格关系型存储引擎（B+ 树、缓冲池、并发） |

---

### 技能栈 · Skills

**Post-training:** SFT · GRPO / RLVR · multi-turn Agent RL · OPD（冷启动 & 合版门控）· PPO / DPO 边界 · advantage / reward / rollout 改写  

**Generation:** DDPM · Flow Matching · DanceGRPO · 扩散盲超分（DDPM + U-Net）  

**Eval:** Pass@K · SWE FAIL_TO_PASS / PASS_TO_PASS · PSNR / SSIM · PhysRVG / Physics-IQ / HPSv3  

**Systems:** PyTorch · Docker · Linux · Git · C++17（数据库内核）

---

### 荣誉 · Highlights

MCM/ICM 国际一等奖 · 全国大学生数学竞赛国评省一等奖 · 东大创新创业卓越奖学金 · 科研训练优秀

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=xiangfeidexiaoyang&show_icons=true&theme=default&hide_border=true" height="150" alt="stats"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=xiangfeidexiaoyang&layout=compact&hide_border=true" height="150" alt="langs"/>
</p>

<p align="center"><sub>Last updated: 2026-10</sub></p>
