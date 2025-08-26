---
title: "Seminar"
header_menu_title: "Seminar"
navigation_menu_title: "Seminar"


weight: 4
header_menu: true
---

#### Multiscale Modelling and Machine Learning

We are pleased to invite you to our seminar to foster discussion and collaboration related to Multiscale Modeling. It will be mostly related to materials, life and quantum sciences.

Time: Friday, 2:00 PM – 4:00 PM, bi-weekly

Venue: S17-0406, S17, NUS, Singapore


##### 2025-08-29
- Speaker: Zhao Yue
    - Title: Deep Learning Methods for Solving High-dimensional PDEs: EPR-Net and Deep Picard Iteration
    - Abstract: In this talk, we explore two deep learning methods for solving high-dimensional PDEs. First, we introduce EPR-Net, a novel deep learning approach for constructing potential landscapes of high-dimensional non-equilibrium steady-state (NESS) systems. The coincidence between the minimum loss of EPR-Net and the entropy production rate in NESS theory allows simultaneous potential landscape construction and clear physical interpretation. EPR-Net can be combined with dimensionality reduction and extended to systems with state-dependent diffusion coefficients. Next, we propose Deep Picard Iteration (DPI) for solving high-dimensional nonlinear parabolic PDEs. DPI combines Picard iteration with neural networks, avoiding the computational difficulties of directly optimizing PDE objective functions. It uses the Feynman-Kac formula for function evaluation, the Bismut-Elworthy-Li formula for gradient estimation. Numerical experiments demonstrate DPI's faster convergence, lower computational cost, and higher solution accuracy compared to existing methods.

##### 2025-07-18
- Speaker: Andrei Okhotin
    - Title: MiAD: Mirage Atom Diffusion for De Novo Crystal Generation
    - Abstract: In recent years, diffusion-based models have demonstrated exceptional performance in searching for simultaneously stable, unique, and novel (S.U.N.) crystalline materials. However, most of these models don’t have the ability to change the number of atoms in the crystal during the generation process, which limits the variability of model sampling trajectories. In this paper, we demonstrate the severity of this restriction and introduce a simple yet powerful technique, mirage infusion, which enables diffusion models to change the state of the atoms that make up the crystal from existent to non-existent (mirage) and vice versa. We show that this technique improves model quality by up to x2.45 compared to the same model without this modification. The resulting model, Mirage Atom Diffusion (MiAD), is an equivariant joint diffusion model for de novo crystal generation that is capable of altering the number of atoms during the generation process. MiAD achieves an 8.1% S.U.N. rate on the MP-20 dataset, which substantially exceeds existing state-of-the-art approaches.


##### 2025-06-20
- Speaker: Maevskiy Artem
    - Title: Accelerating the Discovery of Superionic Conductors with Machine Learning
    - Abstract: Discovering new superionic materials is essential for advancing solid-state batteries, which offer improved energy density and safety compared to traditional lithium-ion batteries. Conventional computational methods for identifying such materials are resource-intensive and not easily scalable. In this talk, I will discuss how AI-powered computational approaches can be leveraged for multiscale modelling to predict ionic mobility in solids. I will present our novel method that utilizes universal interatomic potential models and heuristic structure descriptors to quickly screen for promising ionic conductor candidates.

- Speaker: Nikita Kazeev
    - Title: AI for Inorganic Materials: Grand Scheme of Things and Research Gaps
    - Abstract: I'll review the computational material design pipeline, from structure generation to first-principles evaluation and experiment. The focus will be on the concrete research gaps potentially addressable with machine learning.

##### 2025-06-06
- Speaker Jiaxi Zhao
    - Title: Recent advances in charge density prediction
    - Abstract: Since the introduction of foundation models to the fields of materials science and molecular modeling, researchers have primarily focused on large interatomic potential energy surface models. While such models are extremely powerful for constructing machine-learned force fields (MLFFs) for molecular dynamics simulations, they are generally not capable of providing finer quantum mechanical properties such as band gaps.
In contrast, the prediction of charge (electronic) density has emerged as a new research direction in the past one to two years, aiming to learn the electronic density obtained from density functional theory (DFT) calculations.
In this talk, I will present an overview of recent advances in this area, with an emphasis on different representations of electronic density and on methods for incorporating equivariance into the models.
A list of references is provided below.
    Higher-Order Equivariant Neural Networks for Charge Density Prediction in Materials
    Cracking the Quantum Scaling Limit with Machine Learned Electron Densities
    A Recipe for Charge Density Prediction
    Uni-3DAR: Unified 3D Generation and Understanding via Autoregression on Compressed Spatial Tokens
    Foundation Models for Atomistic Simulation of Chemistry and Materials

##### 2025-05-23
- Speaker: Raymond (Zhu Ruiming)
    - Title: Dis-CSP: Disordered Crystal Structure Predictions
    - Abstract: Most synthesized crystalline inorganic materials are compositionally disordered, meaning that multiple atoms occupy the same lattice site with partial occupancy. Moreover, the computed physical properties of disordered inorganic crystals are configuration dependent, because of this partial occupancy, making it extremely challenging to solve purely by computational methods: this makes property-oriented search impractical. Crystal structure prediction (CSP), for such crystals is crucial for the eventual development of highly efficient and stable functional materials. However, existing generative models cannot handle the complexities of disordered inorganic crystals. To address this gap, we introduce an equivariant representation, based on theoretical crystallography, along with a generative model capable of generating valid structures that allow for compositional disorder and vacancies, which we call Dis-CSP. We train Dis-CSP on experimental inorganic structures from the Inorganic Crystal Structure Database (ICSD), which is the world's largest database of identified inorganic crystal structures. We show that Dis-CSP can effectively generate disordered inorganic crystal materials while preserving the inherent symmetry of the crystals throughout the generation process.


##### 2025-05-09
- Speaker: Ziqiao Meng
    - Title: Introduction to recent advances in crystal material generation
    - Abstract: Material discovery has long been a challenging task due to the vast search space, complex and heterogeneous structures, and high experimental costs. Recently, there has been growing interest in leveraging deep learning techniques to accelerate this process. Inspired by the remarkable success of deep generative models in text and image domains, directly generating crystal structures using generative models has emerged as a promising direction. In this talk, we will provide an overview of recent advances in deep generative approaches for crystal material generation, covering diffusion models, flow matching, and autoregressive methods. 

##### 2025-04-25
Cancelled due to ICLR schedule conflict.

##### 2025-04-11
- Speaker: Pinchen Xie (https://salinelake.github.io/), Lawrence Berkeley National Laboratory. 
    - Time: 2:00 PM – 4:00 PM
    - Zoom Link:  https://nus-sg.zoom.us/j/84688289643?pwd=NndSC7K2kPkHt4dgHbMMa91haOoInK.1
    - Meeting ID: 846 8828 9643
    - Passcode: 992775
    - Title: Data-driven Applications of Coarse-grained Molecular Dynamics and Quantum Dynamics
    - Abstract: The simulation of all-atom molecular dynamics is limited in both length and time scales. The same difficulty applies to simulating the unitary dynamics of large, closed quantum systems. Therefore, we turn to modeling coarse-grained molecular dynamics and open quantum dynamics, using approximate, non-Markovian representations of less relevant degrees of freedom. The equations of motion for these effective models can be derived from simulation or experimental data. We will present a few examples and introduce the open-source packages we have developed for these purposes.

##### 2025-03-28
Cancelled due to NUS Well-Being Day.

##### 2025-03-14
- Speaker: Vitalii Kapitan
    - Title: From Microstates to Thermodynamic Properties: A Study of Spin Glasses
    - Abstract:
      Spin glass is a prototypical disordered system that retains the full spectrum of complex collective behavior observed in interacting, frustrating elements. Despite being the subject of intense research for over five decades, spin glasses remain an intriguing and unresolved problem. This presentation will highlight our research on spin glasses, particularly focusing on the application of deep neural networks and numerical Monte Carlo methods. We consider a data-driven approach that uses these networks to study the functional relationship between macroscopic thermodynamic properties, such as average energy and magnetization, and the microarchitecture (i.e., the spatial distribution of exchange integrals) of spin glass configurations.


- Speaker: Aiqing Zhu
    - Title: Kinetic theory and its machine learning-based hydrodynamic approximations
    - Abstract:
      Kinetic theory serves as a nice bridge between continuum and atomistic models. It can either be viewed as an approximation to the hierarchy of equations for the many-particle probability densities obtained from molecular dynamics, or as a microscopic model for the phase-space probability distribution of a particle, from which continuum models can be derived. In this presentation, we will provide an overview of the fundamental concepts and key features of kinetic theory, following Weinan E's Principles of Multiscale Modeling. Additionally, we will discuss recent advances in developing interpretable and robust hydrodynamic approximations for kinetic equations, with a focus on the machine learning-based approach proposed in Han et al., "Uniformly Accurate Machine Learning-Based Hydrodynamic Models for Kinetic Equations."

##### 2025-02-28
- Speakers: Sohei Arisaka and Wu Shiqi.
  - Title: Constructing Continuum Mechanics: Multiscale Challenges and Machine Learning Solutions
  - Abstract:
    Continuum mechanics provides a fundamental framework for modelling the behaviour of solids and fluids, but its formulation requires appropriate closure models to bridge multiple scales. This presentation explores how scientists construct continuum mechanics models based on conservation laws and address the multiscale challenges that arise. We discuss how unknown terms emerge from material characteristics in solids (constitutive laws) and from unresolved fluid motion (turbulence models). Furthermore, we review recent advances in leveraging machine learning to enhance continuum mechanics simulations, including differentiability in neural physics simulators for transient dynamics and data-driven discovery of constitutive laws. Through this discussion, we aim to highlight the evolving methodologies that integrate physics-based and data-driven approaches for improving multiscale modelling in continuum mechanics.
  - Review some insights and results about Continuum Mechanics from Weinan E's book, [Principles of Multiscale Modeling](https://web.math.princeton.edu/~weinan/papers/weinan_book.pdf), and [List B. et al. Differentiability in unrolled training of neural physics simulators on transient dynamics](https://www.sciencedirect.com/science/article/pii/S0045782524006960)


##### 2025-02-14
- Speaker: Prof. Duane Loh. 
  - Date: Friday, 14 Feb, 2025
  - Time: 3:00 PM – 5:00 PM
  - Venue: S17-04-06
  - Title: Discovering the Secrets of Complexity with AI-companions in Science
  - Abstract:
    Complex systems are among the most challenging to study due to their intricate interplay of numerous components, encompassing the rich dynamics of many interacting particles, chemical reactions, biological processes, and pharmacological interactions. These systems reflect the complexity of life and the physical world, making their study vital across all branches of science.

    Complex systems are challenging to model because they involve a vast number of interacting degrees of freedom. Capturing and predicting these interactions with high accuracy is daunting due to the sheer scale and complexity of behaviors and phases that can emerge. This diversity makes it difficult to create comprehensive models that can reliably predict system behavior across different scenarios.

    Physicists often approach the challenge of complex systems through a technique known as coarse-graining. This method involves selectively simplifying a system by focusing on key variables while averaging out less critical internal degrees of freedom. By sacrificing some detail, this approach allows for greater predictability and understanding of the system’s behavior at larger length and timescales, as well as at higher levels of complexity.

    Traditionally, coarse-graining has been an art, guided by the intuition and insight of experienced researchers. While this approach can yield powerful results, it often relies on strokes of genius and a fair share of luck. Now, machine learning is democratizing this process, equipping researchers with the tools to identify optimal coarse-graining strategies more efficiently and effectively. This technological advance empowers even the non-expert to uncover insights that were once accessible only to the most seasoned scientists.

    In this talk, I will share the experience of how our students and postdocs, equipped with machine learning tools, have embarked on such journeys of data-driven discovery in complex systems. From uncovering novel spatiotemporal motifs in quantum materials, non-reciprocal interactions between biological cells, deciphering the language of functional disorder in piezoelectric materials, unveiling the structural origins of vibrant colors in butterfly wing scales, to creating novel computational lenses for cryo-electron microscopy. They have collectively pushed the boundaries of how we think about complex systems.

    These experiences, I believe, show us how AI has become indispensable for understanding and discovering the secrets in complex systems.

  - Short biography
    Duane Loh is an Associate Professor in the Departments of Physics and Biological Sciences at the National University of Singapore (NUS) and a Principal Investigator at the NUS Centre for Bio-imaging Sciences. His research focuses on developing computational lenses, innovative tools that fuse machine learning with scientific and instrument priors to decode complex and chaotic dynamics at the nanometer scale.

    Duane's group pioneered these computational lenses for single-particle diffractive imaging using X-ray free-electron lasers, where they applied unsupervised learning to discover transient intermediate states and spontaneous order formation in highly dynamic systems. They extended these methods to electron-based imaging, overcoming challenges too complex for traditional hardware-based microscopy alone.

    By combining advanced microscopy with statistical learning, Duane is leading efforts to explore nucleation processes, nanocrystal growth, and self-organization in both physical and biological systems. Building on their expertise in understanding complexity in physical systems,

    Duane’s group is now applying these data-driven approaches to understanding the complex many-body dynamics of biological cells and the spread of vector-borne diseases. This work continues to bridge the gap between massive, complex datasets and foundational scientific understanding, pushing the boundaries of discovery in both physical and biological sciences.

##### 2025-01-31
- Speaker: Prof. Lei Huan,
  - Time: 9:30 AM – 10:30 AM (**please note the change of time for this session**) 
  - Zoom Link: https://nus-sg.zoom.us/j/87589685476?pwd=M99AQERg8SGwJYnzg1gIxVZEmGkBjI.1  (**please note that it is an online zoom session**) 
  - Meeting ID: 875 8968 5476
  - Passcode: 791821
  - Title: An energy-stable machine-learning model of non-Newtonian hydrodynamics with molecular fidelity
  - Abstract: One essential challenge in the computational modeling of multiscale systems is the availability of reliable and interpretable closures that faithfully encode the micro-dynamics. For systems without clear scale separation, there generally exists no such a simple set of macro-scale field variables that allow us to project and predict the dynamics in a self-determined way. We introduce a machine-learning-based approach that enables us to systematically pass the micro-scale physical laws onto the macro-scale. The non-Newtonian hydrodynamics of polymeric fluids is used as an example to illustrate the essential idea. To faithfully retain molecular fidelity, we establish a micro-macro correspondence via a set of encoders for the micro-scale polymer configurations and their macro-scale counterparts, a set of nonlinear conformation tensors. The dynamics of these conformation tensors, with a new form of the objective tensor derivative, can be derived from the micro-scale model and preserves a macro-scale energy variational formulation, and therefore, ensures the energy stability. Unlike our conventional wisdom about ML modeling, the training only uses time-discrete samples. The final model, named the deep non-Newtonian model (DeePN2), retains a multi-scale nature with clear physical interpretation and strictly preserves the frame-indifference constraints. We show that DeePN2 can faithfully capture the broadly overlooked viscoelastic differences arising from the specific molecular structural mechanics without human intervention.
  
##### 2025-01-17
- Zhu Aiqing, review some insights and results from Weinan E's book, [Principles of Multiscale Modeling](https://web.math.princeton.edu/~weinan/papers/weinan_book.pdf)
- Chen Mengyi, review of [Wang J. et al. Machine learning of coarse-grained molecular dynamics force fields – 2019](https://pubs.acs.org/doi/pdf/10.1021/acscentsci.8b00913)
