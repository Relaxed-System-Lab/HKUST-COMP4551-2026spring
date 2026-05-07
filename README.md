# HKUST-COMP4551-2026spring

</div>

<h2 style="text-align: center;"> Large-Scale Machine Learning for Foundation Models </h2>

**Lecturer**: [Binhang Yuan](https://binhangyuan.github.io/site/). 

**Teaching Assistant**: Xu Xu and Jiayi Cheng


## Overview

In recent years, foundation models have fundamentally revolutionized the state-of-the-art of artificial intelligence. Thus, the computation in the training or inference of the foundation model could be one of the most important workflows running on top of modern computer systems. This course unravels the secrets of the efficient deployment of such workflows from the system perspective. Specifically, we will i) explain how a modern machine learning system (i.e., PyTorch) works; ii) understand the performance bottleneck of machine learning computation over modern hardware (e.g., Nvidia GPUs); iii) discuss four main parallel strategies in foundation model training (data-, pipeline-, tensor model-, optimizer- parallelism, etc.); iv) real-world deployment of foundation model including efficient inference and fine-tuning.


## Syllabus 


| Date | Topic |
|-----|------|
|W1 - 02/03,02/05 | - Introduction and Logistics [[Slides](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%201%20-%20Introduction%20and%20Logistics.pdf)]  <br> - ML Preliminary [[Slides](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%201%20-%20Introduction%20and%20Logistics.pdf)] |
|W2 - 02/10,02/12 | - Stochastic Gradient Descent [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%203%20-%20Stochastic%20Gradient%20Descent.pdf) <br> - Automatic Differentiation [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%204%20-%20Automatic%20Differentiation.pdf) |
|W3 - 02/17,02/19 | - Spring Festival |
|W4 - 02/24,02/26 | - Language Model Architecture [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%205%20-%20Language%20Model%20Architecture.pdf) <br> - Large Scale Pretrain Overview [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%206%20-%20LLM%20Pretraining.pdf) |
|W5 - 03/03,03/05 | - Nvidia GPU Performance [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%207%20-%20Nvidia%20GPU%20Performance.pdf)    <br> - Collective Communication Library [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%208%20-%20Nvidia%20Collective%20Communication%20Library.pdf) |
|W6 - 03/10,03/12 | - Data-, Pipeline- Parallel Training [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%209%20-%20Data%20and%20Pipeline%20Parallel%20Training.pdf)  <br> - Tensor Model-, Optimizer- Parallel Training [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2010%20-%20Tensor%20Model%20and%20Optimizer%20Parallel%20Training.pdf)|
|W7 - 03/17,03/19 | - Sequence-, MoE- parallelism [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2011%20-%20MoE%20and%20Sequence%20Parallelism.pdf) <br> - Mid-Term Review [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2012%20-%20Midterm%20Review.pdf) |
|W8 – 03/24,03/26 | - Mid-Term Exam  :heavy_check_mark: <br> - Generative Inference [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2013%20-%20Generative%20Inference%20Overview.pdf)  |
|W9 - 03/31,04/02 | - Inference Alogirhtm Optimizations [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2014%20-%20Generative%20Inference%20Algorithm%20Optimization.pdf) <br> - Inference System Optimizations [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2015%20-%20Generative%20Inference%20System%20Optimization.pdf) |
|W10 - 04/07,04/09| - Spring Break <br> - Prompt Engineering [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2016%20-%20Prompt%20Engineering.pdf)   |
|W11 - 04/14,04/16 | - Inference Time Scaling [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2017%20-%20%20Inference%20Time%20Scaling.pdf) <br> - Retrieval Augmented Generation [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2018%20-%20Retrieval%20Augmented%20Generation.pdf)   |
|W12 - 04/21,04/23 | - LLM Agent [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2019%20-%20LLM%20Agent.pdf) <br> - Parameter Efficient Fine-Tuning [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2020%20-%20Parameter%20Efficient%20Finetuning.pdf) |
|W13 - 04/28, 04/30| - RL Alignment [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2021%20-%20RL%20Alignment.pdf) <br> - LLM Evaluation [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2022%20-%20LLM%20Evaluation.pdf) |
|W14 - 05/05,05/07 | - Guest Speech [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2023%20-%20Relaxed%20System%20Lab%20Research.pdf)  <br> - Final Review [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4551-2026spring/blob/main/Lecture%2024%20-%20Final%20Review.pdf) |


## Grading Policy
- 4 Homework (4 $\times$ 5% $=$ 20%);
- Mid-term exam (30%);
- Final exam (50%).

## Homework 
| Topic | Release |   Due   |
|-------|---------|---------|
| Homework1 |2026/02/22 | 2026/03/04 |
| Homework2 |2026/03/07 | 2026/03/18 |
| Homework3 |2026/04/11 | 2026/04/22 |
| Homework4 |2026/04/27 | 2026/05/06 |




