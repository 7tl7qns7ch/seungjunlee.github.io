# Seungjun Lee

### Contact Information
- **Email:** slee19@bnl.gov
- [**Curriculum Vitae**](/assets/CV_LSJ_250924.pdf)
- [**Google Scholar**](https://scholar.google.com/citations?user=0O-A7g0AAAAJ&hl)
- [**Github**](https://github.com/7tl7qns7ch)
- [**Linkedin**](https://www.linkedin.com/in/seungjun-lee-656946213/)

### Research Interests & Goal
- **Scientific machine learning**
- **Physics-informed neural networks**
- **Generalization**
- **Artificial general intelligence**

My research goal is to develop artificial general intelligence having the ability to think in a scientific way. 
It is common in fields of science and engineering that a well-established governing rule can explain similar phenomena, not just fitting on data from a narrow domain. 
Therefore, it is more scientifically important, and at the same time very challenging, to develop a general model that can explain many related phenomena rather than a narrow model. 
In the field of machine learning, such discussions are considered very important problems, and I am enthusiastic about the study of approaching and applying learning-based models and algorithms from a scientific modeling perspective.

### Education & Career History
- 2025 - current &emsp; Research Staff in Computing and Data Sciences, Brookhaven National Laboratory
- 2024 - 2025 &emsp;&emsp; Research Associate in Computing and Data Sciences, Brookhaven National Laboratory
- 2022 - 2024 &emsp;&emsp; AI researcher at Alsemy, South Korea
- 2017 - 2022 &emsp;&emsp; Ph.D. in Naval Architecture and Ocean Engineering, Seoul National University
- 2012 - 2017 &emsp;&emsp; B.S in Naval Architecture and Ocean Engineering, Seoul National University
- 2009 - 2012 &emsp;&emsp; Student at Hansung Science High School

### Publications
1. Minju Jo, Woojin Cho, Uvini Balasuriya Mudiyanselage, **Seungjun Lee**, Noseong Park, Kookjin Lee, PDEfuncta: Spectrally-Aware Neural Representation for PDE Solution Modeling, Advances in Neural Information Processing Systems, 2025.
2. David Keetae Park, Xihaier Luo, Guang Zhao, **Seungjun Lee**, Miruna Oprescu, Shinjae Yoo, SCENT: Robust Spatiotemporal Learning for Continuous Scientific Data via Scalable Conditional Neural Fields, International Conference on Machine Learning, 2025.
3. **Seungjun Lee**, and Tail Oh, Inducing Point Operator Transformer: A Flexible and Scalable Architecture for Solving PDEs, AAAI Conference on Artificial Intelligence, 2024.
4. Chanwoo Park, **Seungjun Lee**, Junghwan Park, Kyungjin Rim, Jihun Park, Seonggook Cho, Jongwook Jeon, and Hyunbo Cho, Large-Scale Training in Neural Compact Models for Accurate and Adaptable MOSFET Simulation, IEEE Journal of Electron Devices Society, 2024.
5. **Seungjun Lee**, Mesh-Independent Operator Learning for Partial Differential Equations, International Conference on Machine Learning Workshop on AI for Science, 2022.
6. **Seungjun Lee**, Haesang Yang, and Woojae Seong, Identifying Physical Law of Hamiltonian Systems via Meta-Learning, International Conference on Learning Representations, 2021.
7. **Seungjun Lee**, Haesang Yang, Hwiyong Choi, and Woojae Seong, Zero-Shot Single-Microphone Sound Classification and Localization in a Building via the Synthesis of Unseen Features, IEEE Transactions on Multimedia, 2021.
8. **Seungjun Lee**, and Woojae Seong, Meta-Learned Hamiltonian, Neural Information Processing Systems Workshop on Machine Learning and Physical Sciences, 2020.
9. Hwiyong Choi, Haesang Yang, **Seungjun Lee**, and Woojae Seong, Type/position classification of inter-floor noise in residual buildings with a single microphone via supervised learning, IEEE European Signal Processing Conference, 2020.
10. Hwiyong Choi, Haesang Yang, **Seungjun Lee**, and Woojae Seong, Classification of Inter-Floor Noise Type/Position Via Convolutional Neural Network-Based Supervised Learning, Applied Science, 2019.

### Academic Service
ICLR (2025, 2026), Neurips (2025), AAAI (2026), TMLR (2025)

### Teaching
- Teaching Assistant at Seoul National University, Theory of Sound Wave Propagation in the Ocean, Fall 2021

- Teaching Assistant at Seoul National University, Fundamentals of Underwater Acoustics, Spring 2021

- Teaching Assistant at Seoul National University, Creative Experiments in Naval Architecture and Ocean Engineering, Spring 2020

- Teaching Assistant at Seoul National University, Creative Experiments in Naval Architecture and Ocean Engineering, Fall 2019

### Awards
- BK Education Research Group selected excellent graduate students, 2022

- Korean Mathematical Olympiad (high school) - bronze prize, 2010

- Korean Mathematical Olympiad (middle school) - gold prize, 2008

- Korean Physics Olympiad (middle school) - silver prize, 2007

- Korean Mathematical Olympiad (middle school) - silver prize, 2006

### Skills
Python, PyTorch, JAX, Tensorflow, MATLAB, Julia, LATEX, SPICE

### Projects
**1. Developing efficient architecture for solving physical systems (2022.08 - 2024.02)**

![Inducing Point Operator Transformer](/assets/img/ipot.png)

(1) Main content

Developing a flexible and computationally efficient Transformer to learn physical systems handling continuous functions.

(2) Contribution

- Proposing a Transformer that is flexible in handling arbitrary discretization formats 
and scalable to large discretization sizes.

- Handling arbitrary input/output discretization by processing them in the latent space to avoid quadratic complexity.

- Achieving high accuracy and efficient computational costs in several PDE benchmarks and real-world scenarios.

**2. Developing robust physics-based neural networks for analyzing dynamic systems (2021.03 - 2022.08)**

![Identifying Physical Laws](/assets/img/hamaml.png)

(1) Main content

Proposing a method using meta-learning algorithms to model governing equations from similar dynamical systems, enabling rapid learning for new systems even with limited measurement data.

(2) Contribution

- Using a meta-learning algorithm to extract governing rules across similar dynamical systems.

- Using Neural ODEs and the Hamiltonian equations to continuously model dynamical systems and utilize the energy conservation principle.

- Simulating various systems with different physical properties and initial conditions and validating the capability to efficiently learn new systems even with limited data.

**3. Learning-based sound source classification and localization with limited data (2019.03 - 2021.02)**

![Zero-Shot Source Localization](/assets/img/zssl.png)

(1) Main content

Developing a generative model to robustly estimate the position of sound sources, even from unseen locations within a building during the training.

(2) Contribution

- Applying Zero-shot learning techniques to the problem of sound classification and localization, involving simultaneously classifying the type and location of sound sources.

- Using conditional GAN to map sound data to their corresponding types and locations of sound sources and to augment data for unseen locations.

- Collecting extensive real-world environment sound datasets, including various types and locations to develop a robust sound generative model.

### Research Approach
Here is an example of my research approach to achieve my research goal. Scientists have established a wave equation (model) to describe the sound that is made when a string is plucked. Even if the physical properties of the string, such as its thickness or length, change, the wave equation can still explain related phenomena, with only the parameters of the equation changing. Especially, with a small amount of data available for a new string (such as its position over time), the frequencies of the sound produced by the new string can be predicted. In addition, the new wave can be explained by the same equation through appropriate transformations (encoding/projection) from raw data, even if the medium (domain) changes, such as a string,
water, air, or a metal plate. Furthermore, the wave equation can mathematically predict the various characteristics of general waves (such as reflection, refraction, diffraction, and interference), and this has been proven through the experience or experiments of many people, and it has been established as a very reliable model for explaining general waves. Therefore, it is scientifically more important to make a general model that can explain general waves, rather than a narrow model that is only suitable for sound produced by one instance of string. In the field of machine learning, similar discussions are also very important. I am researching and applying machine learning models and algorithms from a scientific modeling perspective.
