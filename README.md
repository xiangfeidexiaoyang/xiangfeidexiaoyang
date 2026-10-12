### Feiyang Liu

**M.S. Student** · Electronic Information  
[THU-CVML](https://thu-cvml.github.io/) · Computer Application Technology Laboratory, Tsinghua University  
Advisor: [Prof. Chun Yuan](https://thu-cvml.github.io/Overview/Professor/)

**Email:** [liufy26@mails.tsinghua.edu.cn](mailto:liufy26@mails.tsinghua.edu.cn)

---

**Research interests.** Learning algorithms for generative models and large-scale model training: reinforcement learning with structured credit assignment (physical events, agent sub-goals), post-training pipelines (SFT, GRPO, on-policy distillation), and video diffusion / flow matching (including physics-aware generation, long-horizon consistency, and when far memory should enter few-step denoising).

---

#### Publications & manuscripts

*Event-Span GRPO: Event-level Credit Assignment for Physics-aligned Video Generation*  
First author · manuscript in preparation  
Group-relative advantages over **physical event spans** (contact, collision, free fall, static segments) rather than full clips; built on DanceGRPO with a Wan2.2-class video backbone, with PhysRVG / Physics-IQ–style evaluation and quality constraints.

*HeadMoE: Data-free Sparse MoE Merging for Multi-site Specialized Models*  
First author · manuscript in preparation  
Shared trunk with low-rank, site-specific attention / classification heads and a training-free router from input–subspace alignment; targets federated-style deployment without pooling raw data.

*Late Forcing: Low-Noise Memory Injection for Frozen Few-Step Video Generators*  
First author · manuscript in preparation  
For frozen few-step autoregressive video models, **when** retrieved far memory is exposed along the denoising trajectory—not only **what** is retrieved—controls the trade-off between revisit identity and scene progression. **Late Forcing** is a training-free schedule that injects far memory only at low-noise steps, withholds it early in the chunk, and optionally re-ranks retrieval candidates with a memory-free first-step draft; designed to compose with existing section-, layer-, and query-level memory routers under fixed NFE.

---

#### Code

| Repository | Description |
|------------|-------------|
| [robot_phys_video_gen](https://github.com/xiangfeidexiaoyang/robot_phys_video_gen) | Physics-anchored robot manipulation video generation (WAM-oriented pipeline) |

---

#### Education

- **Tsinghua University** — M.S., Electronic Information (2026–2028), THU-CVML  
- **Northeastern University** — B.S., Computer Science and Technology (2021–2025)
