# NovaQ
Global Quantum Industry Challenge 
https://www.pqic.org/challenge-about

# NeuroQuantum Nexus– Global Industry Challenge 2025
Life Sciences: Use quantum and hybrid computing to analyze brain activity data, uncovering new insights beyond traditional methods

What is the timeline for the challenge? The timeline for the challenge can be found here. Key dates to be aware of:

    Challenge Launch: April 14, 2025
    Challenge Opens: April 15, 2025
    First Phase Submission: May 5, 2025 (extended to Thursday, May 8, 11:59PM EST)
    Second Phase Submission: May 28, 2025
    Final Submission: June 29, 2025
    Awards: Quantum World Congress (September 16-18, 2025)

Phase 1- Proposal outline submitted

Phase 2
Decoding Neural Circuits with NISQ-Based Spike Analysis
Overview
Understanding the complex dynamics of neural circuits is crucial for unravelling brain function and developing effective treatments for neurological disorders. Quantum computing’s ability to naturally handle probabilistic models and perform complex iterative calculations with potential speedups makes it a uniquely promising approach for unravelling the brain’s intricate communication networks. This challenge invites participants to develop innovative techniques utilizing Noisy Intermediate-Scale Quantum (NISQ) devices or hybrid quantum-classical approaches to analyze a provided neural network calcium signals dataset. Participants may explore relevant quantum algorithms such as VQA, QAOA, Quantum Neural Networks (QNNs), or Quantum Graph Neural Networks (QGNNs).
Watch the Launch Webinar Recording For NeuroQuantum Nexus Here
Phase 2 Submission Criteria: Quantum Model Design & Dataset Engagement
In this phase, your team will design a quantum-enhanced analysis framework for uncovering collective patterns in neural activity data. You will select a modeling strategy, engage deeply with the provided dataset(s), and define a pipeline that prepares you for meaningful simulation in Phase 3.
1. Neural Problem Framing
Begin by defining the biological dataset and the target phenomena. Choose between:

    Calcium imaging data (e.g., from Bowen et al.)
    Electrophysiological spike train data (e.g., from Buccino et al.) Clarify what high-order neural dynamics you're targeting, such as:
    Spike synchrony or phase locking
    Motif-level co-activation patterns
    Community structure among neurons Explain how uncovering these dynamics could advance understanding of collective behavior in neural systems.

2. Quantum Modeling Strategy
Design a quantum or hybrid quantum-classical approach suited for capturing non-trivial structure in neural data. Valid options include:

    QNNs (Quantum Neural Networks) for classification or time-series prediction,
    QGNNs (Quantum Graph Neural Networks) for modeling neuron-neuron interaction graphs,
    VQE or QAOA for graph-based optimization or motif detection,
    Hybrid quantum-classical pipelines where quantum kernels or embeddings enhance classical models. Provide a conceptual diagram or pseudocode of your architecture, and explain:
    How quantum layers enhance representation power (e.g., capturing entanglement-like dependencies),
    What specific patterns do you aim to learn that classical models might miss?

3. Classical vs. Quantum Comparison Plan
Define a state-of-the-art classical baseline for comparison, such as:

    Multivariate autoregressive models (MARs),
    Hidden Markov models or LSTMs for temporal structure,
    PCA, ICA, or k-means clustering for dimensionality reduction and motif discovery. Explain how you’ll evaluate whether quantum models offer improvements, e.g., via accuracy, sparsity, interpretability, or sensitivity to higher-order correlations.

4. Data Preprocessing & Encoding Pipeline
Construct a preprocessing pipeline for the neural data that includes:

    Noise filtering and normalization of calcium fluorescence or spike rate data,
    Dimensionality reduction (e.g., t-SNE, PCA) to extract key features,
    Spike binning, thresholding, or correlation matrix construction to prepare for quantum input encoding. Describe how your processed data will be:
    Mapped to qubit states or graph structures,
    Encoded using amplitude encoding, angle embedding, or adjacency matrix input to a quantum model. Include visualizations or summaries of the data structure, embedding dimension, and qubit mapping.

5. Resource Requirements & Execution Plan
Please consider which quantum hardware or simulators best align with your proposed solution. Available platforms include:

    Amazon Braket SV1, DM1 TN1
    Fire Opal error mitigation software + IBM hardware
    IBM Eagle r3, Heron r1, Heron r2
    IonQ, Aria-1 Forte-1
    IQM Garnett
    NVIDIA GPUs with Qiskit GPU / Cirq GPU / Pennylane Lightning / Cu Quantum available out of the box.
    qBraid QIR simulator
    QuEra Aquila
    Rigetti Ankaa-2, Aspen M3 Justify your platform selection(s) and include technical details, such as expected, and provide more details in the next section. Estimate the runtime gains or efficiency improvements you expect based on your modifications and configuration. Specify:
    The number of qubits needed to represent your data or graph,
    Expected circuit depth, particularly for variational or optimization-based models,
    Feasibility of hybrid execution or classical fallback for large-scale comparisons.

Submission Requirements

    Maximum 3 pages PDF (not including references), using 11-point Times New Roman font and single spacing, and submit it through the Aqora platform. Only one submission is required per team.
    Your submission must include:
        Defined neural signal target and analysis goal
        Quantum model structure and theoretical basis
        Classical benchmark method for comparison
        Preprocessing pipeline and quantum encoding method
        Execution platform, resource needs, and Phase 3 planning  

Phase 3: Pattern Detection & Quantum Insight
In this final phase, you will execute your full quantum or hybrid pipeline and analyze its effectiveness in detecting high-order patterns in neural spike data. Emphasis will be placed on neuroscientific relevance, model performance compared to classical baselines, and the broader potential for neurotechnology applications. More details to come for teams downselected to the final in Phase 3. Refer to the FAQs in the Event Overview for more information about team formation, submission, and more.
Download NeuroQuantum Nexus Challenge Document: NeuroQuantum Nexus - Challenge.pdf
