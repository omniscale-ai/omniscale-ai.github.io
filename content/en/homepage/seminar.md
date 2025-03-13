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
