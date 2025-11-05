# ⚡ Compilers and Runtimes for AI: From Prompts to Accelerators  
### EECS 598 · Fall 2025  
*Cutting Edge and Emerging Technologies from the Programming Interface down to Hardware Acceleration of AI*

---

## 📖 Course Summary

The science and art of creating **efficient AI systems** spans the entire computing stack—from high-level language abstractions down to specialized hardware accelerators. This course provides a comprehensive exploration of AI compiler and runtime techniques, covering everything from **language-level AI compiler systems** (DSPy, SGLang, MTP, Guidance, LMQL) to **hardware-level acceleration** (GPU kernels, TPU compilation, custom ASICs, and emerging AI chips).

Students will learn how modern AI compilers and runtime systems like **PyTorch, JAX, TVM, TensorRT, VLLM, and specialized LLM compilers** orchestrate the full pipeline from prompt engineering and program synthesis down to optimized execution on heterogeneous hardware. The course covers the complete spectrum: **prompt-level optimizations**, **graph-level transformations**, **kernel-level tuning**, **memory hierarchy optimization**, and **distributed system coordination**.

### What You’ll Do
- Explore **language-level AI compiler techniques** (prompt optimization, program synthesis, declarative AI programming) and **traditional compiler optimizations** (graph-level transformations, kernel tuning, memory management, distributed training)  
- Work hands-on with **cutting-edge AI compiler ecosystems** (DSPy, SGLang, MTP, Guidance, LMQL, MLIR, TVM, PyTorch, CUDA) and **heterogeneous hardware platforms** (GPUs, TPUs, custom accelerators, emerging AI chips)  
- Identify and focus on a **specific research project** within the scope of these technologies, demonstrating novel compiler/runtime optimizations for targeted AI workloads  
- Present a **capstone project** that delves deep into a particular aspect of AI compilation, from language-level innovations to hardware-level breakthroughs  

Projects teams will be on the smaller side (~2–3 students) and will include selecting a focused research direction, designing targeted optimization approaches, building specialized compiler/runtime components, and benchmarking performance improvements.  

### What You’ll Learn
- The **comprehensive landscape of AI systems**: from language-level AI compiler techniques (DSPy, SGLang, MTP) to hardware-level acceleration (GPU kernels, TPU compilation, custom ASICs)  
- **State-of-the-art techniques**: prompt-level optimization, program synthesis, graph-level transformation, auto-tuning, quantization, inference acceleration, and emerging AI chip architectures  
- **Critical research skills**: interpreting papers, evaluating cutting-edge systems, presenting technical ideas, and bridging the gap between high-level AI programming and low-level hardware optimization  

Grading is **research project-centric**. You’ll showcase your project’s evolution through presentations, paper reviews, and final demos.  

---

## 👨‍🏫 Instruction Team
- **Instructor**: [Jason Mars](http://www.jasonmars.org) (📧 profmars@umich.edu)  
- **GSI**: *TBD*  

---

## 🗓 Logistics
- **Lecture**: TBD  
- **Credits**: 4  
- **Office Hours**: On Demand  
- **GSI Office Hours**: TBA  
- **Course Discussion**: Piazza (TBD)  
- **Canvas**: TBD  
- **Recorded Lectures**: Available on Canvas  

---

## 📅 Schedule

| Week | Topics | Description | Notes/Links |
|------|--------|-------------|-------------|
| **Aug 25-27** | Course Introduction & Overview<br>Introduction to Compilers for AI | Lecture |  |
| **Sep 1-3** | Labor Day (Holiday)<br>Foundations of AI Compiler Systems | Lecture |  |
| **Sep 8-10** | [Open]<br>[DSPy](https://arxiv.org/pdf/2310.03714), [TVM](https://arxiv.org/abs/1802.04799)  | Papers and Discussion |  |
| **Sep 15-17** | [MTP](https://arxiv.org/abs/2405.08965), [Relay](https://arxiv.org/abs/1904.08368) <br>[GEPA](https://arxiv.org/abs/2507.19457), [Ansor](https://arxiv.org/abs/2006.06762) | Papers and Discussion |  |
| **Sep 22-24** | [Pytorch2](https://dl.acm.org/doi/10.1145/3620665.3640366), [TorchBench](https://arxiv.org/abs/2304.14226) <br>[TorchTitan](https://arxiv.org/abs/2410.06511), [ECLIP](https://arxiv.org/abs/2506.12598) | Papers and Discussion|  |
| **Sep 29 - Oct 1** | [Triton](https://dl.acm.org/doi/10.1145/3315508.3329973), [Geak](https://arxiv.org/abs/2507.23194) <br>[OpFusion](https://arxiv.org/abs/2301.13062), [MemSafeXLA](https://arxiv.org/abs/2206.14148) |Papers and Discussion |  |
| **Oct 6-8** | Group Presentations<br>Group Presentations | Pitches |  |
| **Oct 13-15** | Fall Study Break (Holiday)<br> |Papers and Discussion |  |
| **Oct 20-22** | [MLIR](https://arxiv.org/abs/2002.11054), [Glow](https://arxiv.org/abs/1805.00907) <br> [Repo Deconstruct] | Tech Talks |  |
| **Oct 27-29** | [EffPagedAttn](https://arxiv.org/abs/2309.06180), [EffLLMServ](https://arxiv.org/abs/2503.18292) <br>[NvidiaAmpere](https://arxiv.org/abs/2208.11174), [AMDsDTW](https://arxiv.org/abs/2403.06931) |Papers and Discussion
| **Nov 3-5** | Group Presentations<br>Group Presentations | Updates |  |
| **Nov 10-12** | [TPUs](https://arxiv.org/abs/2304.01433), [MTIA](https://dl.acm.org/doi/pdf/10.1145/3579371.3589348) <br>[MLFleet](https://arxiv.org/pdf/2502.06982) + [Special Guest?] | Papers and Discussion|  |
| **Nov 17-19** | [Repo Deconstruct] <br> [Repo Deconstruct] | Papers and Discussion|  |
| **Nov 24-26** | Flex Day (Repo Deconstruction Due) <br>Thanksgiving Recess (Holiday) | Presentations |  |
| **Dec 1-3** | Final Project Presentations<br>Course Wrap-up & Future Directions | Presentations | |

---

## 📂 Tentative List of Papers

| # | Technology Category | Paper Title | Year | Link |
|:--:|:------------------|:-------------|:----:|:-----|
| 1 | **LMQL** | **Prompting Is Programming: A Query Language for Large Language Models** | 2022 | [Paper](https://arxiv.org/abs/2212.06094) |
| 2 | **DSPy** | **DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines** | 2023 | [DSPy](https://arxiv.org/pdf/2310.03714) |
| 3 | **DSPy** | **Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs** | 2024 | [Paper](https://arxiv.org/abs/2406.11695) |
| 4 | **DSPy** | **GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning** | 2025 | [GEPA](https://arxiv.org/abs/2507.19457) |
| 5 | **SGLang** | **SGLang: Efficient Execution of Structured Language Model Programs** | 2023 | [Paper](https://arxiv.org/abs/2312.07104) |
| 6 | **MTP** | **Meaning-Typed Programming: Language Abstraction and Runtime for Model-Integrated Applications** | 2025 | [MTP](https://arxiv.org/abs/2405.08965) |
| 7 | **Apache TVM** | **TVM: An Automated End-to-End Optimizing Compiler for Deep Learning** | 2018 | [TVM](https://arxiv.org/abs/1802.04799) |
| 8 | **Apache TVM** | **Relay: A High-Level Compiler for Deep Learning** | 2019 | [Relay](https://arxiv.org/abs/1904.08368) |
| 9 | **Apache TVM** | **Ansor: Generating High-Performance Tensor Programs for Deep Learning** | 2020 | [Ansor](https://arxiv.org/abs/2006.06762) |
| 10 | **PyTorch 2** | **PyTorch 2: Faster Machine Learning Through Dynamic Python Bytecode and Graph Compilation for DNNs** | 2024 | [Pytorch2](https://dl.acm.org/doi/10.1145/3620665.3640366) |
| 11 | **PyTorch 2** | **TorchBench: Benchmarking PyTorch with High API Surface Coverage** | 2023 | [TorchBench](https://arxiv.org/abs/2304.14226) |
| 12 | **PyTorch 2** | **TorchTitan: One-stop PyTorch native solution for production ready LLM pretraining** | 2024 | [TorchTitan](https://arxiv.org/abs/2410.06511) |
| 13 | **PyTorch ROCm** | **ECLIP: Energy-efficient and Practical Co-Location of ML Inference Pipelines on GPUs** | 2025 | [ECLIP](https://arxiv.org/abs/2506.12598) |
| 14 | **Triton** | **Triton: An Intermediate Language and Compiler for Tiled Neural Network Computations** | 2019 | [Triton](https://dl.acm.org/doi/10.1145/3315508.3329973) |
| 15 | **Triton** | **Geak: Introducing Triton Kernel AI Agent & Evaluation Benchmarks** | 2025 | [Geak](https://arxiv.org/abs/2507.23194) |
| 16 | **OpenXLA** | **Operator Fusion in XLA: Analysis and Evaluation** | 2023 | [OpFusion](https://arxiv.org/abs/2301.13062) |
| 17 | **OpenXLA** | **Memory Safe Computations with XLA Compiler** | 2022 | [MemSafeXLA](https://arxiv.org/abs/2206.14148) |
| 18 | **Google MLIR** | **MLIR: A Compiler Infrastructure for the End of Moore's Law** | 2020 | [MLIR](https://arxiv.org/abs/2002.11054) |
| 19 | **Meta Glow** | **Glow: Graph Lowering Compiler Techniques for Neural Networks** | 2018 | [Glow](https://arxiv.org/abs/1805.00907) |
| 20 | **vLLM** | **Efficient Memory Management for Large Language Model Serving with PagedAttention** | 2023 | [EffPagedAttn](https://arxiv.org/abs/2309.06180) |
| 21 | **vLLM** | **Effective Memory Management for Serving LLM with Heterogeneity** | 2025 | [EffLLMServ](https://arxiv.org/abs/2503.18292) |
| 22 | **GPU ISA & Architecture** | **Demystifying the Nvidia Ampere Architecture through Microbenchmarking and Instruction-level Analysis** | 2023 | [NvidiaAmpere](https://arxiv.org/abs/2208.11174) |
| 23 | **GPU ISA & Architecture** | **Cambricon: An Instruction Set Architecture for Neural Networks** | 2016 | [Cambricon](https://dl.acm.org/doi/10.1145/3331469) |
| 24 | **CUDA/ROCm** | **Optimizing sDTW for AMD GPUs** | 2024 | [AMDsDTW](https://arxiv.org/abs/2403.06931) |
| 25 | **TPU ISA & Architecture** | **TPU v4: An Optically Reconfigurable Supercomputer for Machine Learning with Hardware Support for Embeddings** | 2023 | [TPUs](https://arxiv.org/abs/2304.01433) |
| 26 | **TPU ISA & Architecture** | **MTIA: First Generation Silicon Targeting Meta's Recommendation Systems** | 2023 | [MTIA](https://dl.acm.org/doi/pdf/10.1145/3579371.3589348) |
| 27 | **TPU ISA & Architecture** | **Machine Learning Fleet Efficiency: Analyzing and Optimizing Large-Scale Google TPU Systems with ML Productivity Goodput** | 2016 | [MLFleet](https://arxiv.org/pdf/2502.06982) |
| 28 | **OpenVINO** | **OpenVINO Deep Learning Workbench: Comprehensive Analysis and Tuning of Neural Networks Inference** | 2019 | [Paper](https://openaccess.thecvf.com/content_ICCVW_2019/papers/SDL-CV/Gorbachev_OpenVINO_Deep_Learning_Workbench_Comprehensive_Analysis_and_Tuning_of_Neural_ICCVW_2019_paper.pdf) |
| 29 | **OpenVINO** | **Leveraging Speculative Sampling and KV-Cache Optimizations Together for Generative AI using OpenVINO** | 2023 | [Paper](https://arxiv.org/abs/2311.04951) |
| 30 | **Intel PlaidML** | **Stripe: Tensor Compilation via the Nested Polyhedral Model** | 2019 | [Paper](https://arxiv.org/abs/1903.06498) |

*Need to add some compound AI papers, Graphine, and a few others*

---


## 📊 Grading

This is a very 'do based' course, we'll be learning, creating, innovating and sharing. A significant portion of the grade is allocated to the research project. Most (if not all) does very well in this class as long as you stay engaged on the journey. Lets create some amazing stuff! 😊

**Research Project: 80%**
- Project Pitch: 10%
- Project Update: 10%
- Video Lightning Talk: 15%
- Final Presentation: 20%
- Paper Write-Up: 25%

**Participation, Impact, and Engagement: 20%**
- Paper Presentations: 10%
- Repo Deconstructions: 5% ([Project Details](repo-deconstruction-project.md))
- Paper Vibe Logs: 5% / #No of Papers

---

## 🎯 How We'll Work

This course emphasizes collaborative learning and knowledge sharing. Students will actively participate in presentations that showcase their understanding and discoveries from the course materials.

### Grading and Logistics


**Grading Basis**
- Grading will be based on each student's GitHub repository for this class. Your repo is the official record of your work and deliverables.

**Repository Registration**
- Each student must enter their U-M uniquename and GitHub repository link in the "GitHub repos" tab of the same Google Sheet used for student presentations (https://docs.google.com/spreadsheets/d/1y7yw2zQt6hjsVg0bTg0fLS1cplkk9_-1nd-qYPybwfE/edit?usp=sharing).

**Paper Vibe Logs**
- Upload your paper vibe logs to your GitHub repository.
- Vibe logs are due the same day as the paper being presented.
- Each student submits their own vibe log (no group submissions).
- Each vibe log should contain about 5–10 questions you asked to GPT about the paper being presented.

### "Vibe Learning" Log

A key component of our learning methodology is the **"vibe learning" presentation**. In these sessions, students will:

- **Walk through AI conversation logs**: Present a curated log of their conversations with AI systems where they learned interesting concepts from the course papers
- **Teach back to the class**: Use their AI interaction logs as a foundation to explain complex compiler and runtime concepts to their peers
- **Demonstrate understanding**: Show how they've internalized and can communicate technical concepts through their AI-assisted learning journey
- **Share insights**: Highlight unexpected discoveries, connections, and "aha moments" that emerged from their AI conversations

This approach leverages the power of AI as a learning companion while ensuring students develop deep understanding through the process of teaching others. Students will learn not just from the papers themselves, but from each other's unique learning paths and AI-assisted discoveries.

### Student Presentations

Students should sign up for a paper here (in the paper signup tab): https://docs.google.com/spreadsheets/d/1y7yw2zQt6hjsVg0bTg0fLS1cplkk9_-1nd-qYPybwfE/edit?usp=sharing

#### Presentation Slides

- Aim for **15–20 slides**
- Cover the paper’s **motivation**, **problem**, **key ideas/methodology**, **system/architecture**, **evaluation/results**, **limitations/trade-offs**, and **key takeaways**
- Include **relevant figures/diagrams/tables** from the paper (or simplified redraws) to clearly tell the story
- Use a clear narrative: problem → idea → how it works → why it’s better → evidence → implications
- For style and pacing, watch recent paper talks on YouTube from top architecture/systems conferences such as **ISCA**, **MICRO**, **ASPLOS**, and **HPCA**




---

## 🛠 Notes
- https://medium.com/geekculture/ai-compilers-ae28afbc4907
- https://developer.nvidia.com/blog/understanding-ptx-the-assembly-language-of-cuda-gpu-computing/
- https://rocm.blogs.amd.com/software-tools-optimization/amdgcn-isa/README.html

---

⭐ *Prepare to build the next generation of compilers and runtimes for AI.*  
