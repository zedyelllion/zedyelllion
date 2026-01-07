# 👋 Hi, I'm Zeyu Liang

I am a Master's student in **Artificial Intelligence** at **Northeastern University**, with a strong research focus on **Reinforcement Learning**, **Multi-Agent Systems**, and **Learning-based Decision Making**.

My past work spans **multi-agent reinforcement learning with LLM collaboration**, **symbolic testing of numerical programs**, and **parallel computing systems**.   


---

## 🔬 Research Interests

- Multi-Agent Reinforcement Learning (MARL)
- Learning with Large Language Models (LLMs)
- Game Theory & Self-Play
- Decision-Making under Uncertainty (MDP / POMDP)
- AI Safety and Robust Learning Systems
- Systems for Learning (Testing, Parallelism, Scalability)

---

## 🧠 Research Projects

Keywords: Dec-POMDP · CTDE-inspired training · MAGRPO · Multi-turn LLM collaboration

Formalized multi-LLM collaboration as a cooperative Dec-POMDP: each agent observes partial, prompt-based information and outputs natural-language actions; the system/reward model provides joint rewards over multi-turn interactions 

Introduced MAGRPO, extending GRPO to multi-agent, multi-turn settings by sampling groups of joint rollouts and using group-relative Monte-Carlo advantages to coordinate agents without training a large centralized value model 

Evaluated on two collaboration domains:

Writing: 2 Qwen agents learn complementary roles (concise TLDR + detailed summary; background + method/experiments for arXiv-style expansion), improving structure/style coherence vs. prompt-level baselines 

Coding: 2 Qwen coder agents generate a helper + main function; rewards include structure/syntax/tests and an explicit cooperation bonus when main correctly uses helper; introduced CoopHumanEval to reduce non-cooperative noise in HumanEval 

Empirically, MAGRPO outperforms single-model and prompt-only multi-agent baselines in overall return and cooperation metrics, especially in multi-turn coding with external feedback signals

---

### 🔹 YUSE: Symbolic Testing for Floating-Point Programs
**Keywords:** Symbolic Execution · Floating-Point Errors · Software Testing  

- Developed techniques for detecting **floating-point inconsistencies and corner-case bugs**
- Focused on numerical instability, path explosion, and solver scalability
- Contributed to modeling, testing, and evaluation components of the framework
- This project strengthened my interest in **robust and reliable systems**

---

### 🔹 Parallel Computing on RTEMS (Paor Project)
**Keywords:** Parallelism · Embedded Systems · Performance Optimization  

- Worked on system-level parallel computation in real-time operating systems
- Designed and evaluated parallel strategies under strict timing constraints
- Gained experience bridging **systems research** with **algorithmic design**

---

## 🛠 Technical Skills

**Programming**
- Python, C++, Java
- PyTorch, TensorFlow, JAX
- NumPy, SciPy, scikit-learn

**Reinforcement Learning**
- PPO, MAPPO, DQN, QMIX, IQL
- Self-play, centralized training & decentralized execution
- Custom Gym / POMDP environments

**Systems & Tools**
- Linux, Git, HPC clusters (SBATCH)
- LaTeX, TikZ, UML
- Docker (basic), Jupyter


 (poster / technical report)

---

## 🎓 Background

- **M.S. in Artificial Intelligence**, Northeastern University 
- **B.S. in Mathematics**, University of California, San Diego

---

## 📫 Contact

- Email: liang.zey@northeastern.edu / zeliang@ucsd.edu
- GitHub: https://github.com/zedyelllion
- Google Scholar: https://scholar.google.com/citations?user=kQJPSiUAAAAJ&hl=en

---

⭐ *I am always happy to discuss research ideas, collaborations, and PhD opportunities.*
