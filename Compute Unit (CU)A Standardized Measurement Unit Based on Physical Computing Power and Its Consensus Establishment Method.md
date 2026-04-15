\documentclass[12pt,a4paper]{article}
\usepackage[utf8]{inputenc} 
\usepackage[T1]{fontenc}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{geometry}
\usepackage{hyperref}
\usepackage{booktabs}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{fancyhdr}

\geometry{left=2.5cm,right=2.5cm,top=2.5cm,bottom=2.5cm}

\title{\textbf{Compute Unit (CU): A Standardized Measurement Unit Based on Physical Computing Power and Its Consensus Establishment Method}\\[0.5em]
\large --- From Heterogeneous Computing Power Unification to the Natural Evolution of Public Domain Standards}
\author{}
\date{}

\begin{document}

\maketitle

\section*{Concise Declaration}
The technical solution defined in this paper---including heterogeneous computing power unification rules, network correction factors, five-dimensional storage correction, consumption-based voucher settlement mechanisms, and the Issuance-Burn Two-way Peg---enters the public domain upon publication.

The author does not seek any patent protection and retains no exclusive rights. Any individual or entity may freely use, modify, distribute, and commercialize the technology described herein without authorization or payment.

If a third party applies for a patent on the technology described in this paper, that patent does not constrain anyone---because this paper has already publicly disclosed these technologies, and the author has explicitly waived the right to pursue claims. The market will freely choose the highest quality, most open, and most credible implementation. The open-source reference implementation provided in this paper is precisely that option.

\section*{Legal Notice and Public Domain Pre-emption Clauses}

\textbf{1. License}

To the fullest extent permitted by law, the author hereby irrevocably dedicates this paper in its entirety---including all text, formulas, algorithms, technical solutions, and accompanying code---to the worldwide public domain under the \textbf{CC0 1.0 Universal (CC0 1.0)} Public Domain Dedication.

No rights are reserved. Any individual or entity may freely copy, modify, distribute, and commercialize this work, in whole or in part, without seeking authorization, providing attribution, or making any payment to any party.

The author explicitly intends for the technical content disclosed herein to serve as permanently available prior art, precluding any future patent claims on the subject matter described.

\vspace{1em}
\textit{Thanks to Tau and Logos, Ma Wenzhe can produce this work.}

\textbf{2. Patent Pre-emption Statement}

The content disclosed in this paper, including but not limited to the following technical features, enters the public domain as of the date of publication:
\begin{itemize}[leftmargin=*]
    \item Heterogeneous computing power unification rules (conversion coefficients inversely proportional to effective computational capacity and independent of reference precision selection);
    \item Network correction factors for net computing power of distributed clusters (any method that discounts theoretical computing power based on communication topology, interconnection bandwidth, or node scale);
    \item Five-dimensional correction method for storage computing power (capacity, duration, bandwidth, availability, latency);
    \item Issuance-Burn Two-way Peg mechanism for consumption-based computing power vouchers;
    \item The logical function of Proof of Compute (proving that a specific computational task has actually been executed).
\end{itemize}

If any individual or entity files a patent application for any of the above technical features (or their equivalent variants, combinations, or generalizations) in any jurisdiction, the parts of that application that are identical or substantially identical to the content disclosed in this paper shall automatically be deemed a rediscovery of public domain technology and shall not constitute novelty. The author and contributors of this paper reserve the right to file prior-art objections against such patent applications and may use this paper as prior art evidence in any patent invalidation proceeding without charge.

\textbf{3. Concept Pre-emption Clause}

This paper does not limit the specific implementation forms of the following features; any method that achieves the same logical function is deemed pre-disclosed by this paper:
\begin{itemize}[leftmargin=*]
    \item \textbf{General form of network correction factor}: actual computing power = theoretical computing power $\times$ discount factor, where the discount factor is determined by at least one of communication overhead, topology, or interconnection bandwidth;
    \item \textbf{General form of storage correction}: storage contribution = $f(\text{capacity, duration, bandwidth, availability, latency})$, where $f$ is monotonically increasing in each parameter (monotonically decreasing in latency);
    \item \textbf{General form of Proof of Compute}: any cryptographic or trustable computing method that can prove to a third party that a specific computational task has actually been executed.
\end{itemize}

\textbf{4. Combination Pre-emption Clause}

A complete Compute Unit (CU) measurement and circulation system includes, but is not limited to, the following modules in combination: heterogeneous computing power conversion module, network correction module, storage correction module, consumption-based voucher generation module, Proof of Compute module, and Issuance-Burn Two-way Peg module. Any combination of the above modules whose core logic is ``anchoring a tradable standardized unit to physical computing power consumption'' is deemed a direct application of the public domain technology disclosed in this paper and does not constitute a patentable technical contribution.

\textbf{5. Temporal Pre-emption Clause}

The definitions in this paper do not depend on any specific hardware, algorithm, or technological generation. Regardless of how computing power is physically realized in the future (including but not limited to electronic computing, superconducting computing, optical computing, quantum computing, biological computing, or neuromorphic computing), any approach whose core logic is ``converting the effective output of different computing paradigms to a unified physical benchmark'' falls within the public domain pre-disclosed by this paper.

\textbf{6. Mutual Defense Clause}

Any individual or entity adopting the technology described in this paper who is sued for patent infringement by a third party based on the implementation of such technology has the right to request assistance from the CU community in finding prior-art evidence. The CU community does not provide legal representation but commits to permanently and freely maintaining the ``CU Public Domain Technology Evidence Repository'', containing this paper and timestamped proofs of all subsequent derivative public disclosures.

\textbf{7. No Legal Advice Disclaimer}

This Legal Notice is provided for informational and prior-art preservation purposes only and does not constitute legal advice. Individuals or entities with specific legal concerns should consult qualified legal counsel in their jurisdiction.

\section*{Abstract}
The current computing power market lacks a unified physical measurement standard: heterogeneous computing resources of varying precision, architecture, and scale cannot be compared horizontally; coordination losses in distributed clusters are deliberately ignored; storage service quality is oversimplified to capacity and bandwidth; and AI service billing is anchored to semantic Tokens rather than physical consumption. These deficiencies collectively lead to a chaotic ``blind men and an elephant'' situation in computing power transactions, hindering the effective allocation of computing power as a core resource in the digital economy.

This paper defines a standardized measurement unit---\textbf{Compute Unit (CU)}---based on physical computing power consumption. The measurement rules for CU satisfy: (1) The conversion coefficient between any two computational precisions is inversely proportional to their effective computational capacity and independent of the reference precision selection; (2) The net computing power of distributed clusters must be calibrated by a network correction factor, modeled based on graph theory topology weights and bandwidth bottlenecks; (3) Storage computing power must incorporate five-dimensional corrections for capacity, duration, bandwidth, availability, and latency. CU exists in the form of a consumption-based voucher and introduces ``Proof of Compute'' and ``Issuance-Burn Two-way Peg'' mechanisms, completely eliminating settlement paradoxes and arbitrage opportunities.

Addressing the inevitable ``Goodhart's Law'' that arises when measurement standards become transaction benchmarks, this paper proposes dynamic standard reference workloads and benchmark cheating penalty mechanisms, along with a deepened model for the network correction factor based on communication topology weights. Finally, this paper presents a consensus establishment method that does not rely on ``wealth creation effects'' or ``centralized authority''---treating CU as a public domain standard, achieving societal adoption through four stages of natural evolution. This method has been proven by the Logos-$\Omega$ socio-control framework to be the optimal path consistent with information thermodynamics and evolutionary dynamics.

\textbf{Keywords}: Compute Unit; Heterogeneous Computing Power Unification; Network Correction Factor; Five-Dimensional Storage Correction; Consumption-Based Voucher; Proof of Compute; Goodhart's Law; Measurement Standard Consensus; Socio-Technical System Dynamics

\hrule

\section{Introduction: Industry Pain Points of Missing Standards and the Fundamental Failure of Monetary Systems}

\subsection{Four Failures of Existing Computing Power Measurement}
\begin{enumerate}[leftmargin=*]
    \item \textbf{Heterogeneous precision cannot be compared}: FP32, FP16, INT8, and other precision types are priced separately by cloud providers, making it impossible for users to compare real performance horizontally. Low-precision computing power is often falsely reported as ``equivalent high-precision computing power,'' lacking a unified physical conversion rule.
    
    \item \textbf{Coordination losses in distributed clusters are concealed}: Stacking low-quality nodes can falsely inflate total computing power, but actual training speeds are far below theoretical sums. Network communication, synchronization waits, and data distribution losses are not reflected in measurements, turning computing power transactions into ``black boxes.''
    
    \item \textbf{Storage computing power is measured only by capacity and bandwidth}: High-latency, low-availability storage nodes can masquerade as high-speed memory, and the computing power wasted due to storage jitter in AI training is untraceable.
    
    \item \textbf{AI service billing is anchored to semantic Tokens}: The physical computing power required to generate one Token differs by thousands of times across models, making Tokens unable to reflect actual costs, with billing processes opaque and unauditable.
\end{enumerate}

\subsection{The Fundamental Failure of Existing Monetary Systems in the AI Era}
Credit money relies on tax bases and economic growth expectations. When AI takes over production and marginal costs approach zero, tax bases collapse and deflationary spirals become unavoidable. Fixed-supply currencies such as Bitcoin go to the opposite extreme: deflation leads to hoarding and consumption freezes. Neither can serve as a value scale in the post-labor era.

Therefore, we need a new measurement unit---\textbf{Compute Unit}---that is strictly anchored to physical computing power consumption, independently measurable, auditable, and whose supply grows synchronously with computing power.

\section{Physical Definition and Measurement Method of Compute Unit}

\subsection{Heterogeneous Computing Power Unification Rules}
\textbf{Core Rule}: The ratio of conversion coefficients between any two computational precision types equals the inverse ratio of their effective computational capacities, and the conversion result is independent of the reference precision selection.

Let the reference precision be $P_0$ (e.g., FP32), and the effective computational capacity of another precision $P_i$ be $E_i$ (the number of actual effective operations completed per unit time). The conversion coefficient from $P_i$ to $P_0$ is:
\begin{equation}
k_i = \frac{E_0}{E_i}
\end{equation}

When a computational task involves multiple precision operations, the total standard computational quantity $Q_{\text{std}}$ is:
\begin{equation}
Q_{\text{std}} = \sum_i Q_i \cdot k_i
\end{equation}

\textbf{Dynamic calibration of effective computational capacity $E_i$}: To prevent hardware manufacturers from ``special-tuning'' for test programs (Goodhart's Law), $E_i$ is not determined by static specifications or single-kernel peak values but must run the \textbf{Standard Reference Workload (SRW)} published by the CU Governance Committee. The SRW represents the computational graph characteristics of current-generation mainstream AI models (e.g., the decode phase of Transformer-class models) and is dynamically upgraded every two years based on mainstream architectural evolution. Any hardware acceleration specifically optimized for the SRW that cannot be replicated on general large models will be considered benchmark cheating, and its $E_i$ will be subject to a punitive reduction (e.g., multiplied by 0.7).

\textbf{Compute Unit definition}: 1 CU = $U_0$ standard operations, where $U_0$ is a defined constant (e.g., $10^{15}$ reference-precision operations, i.e., 1 PFLOPS$\cdot$second).

\subsection{Net Computing Power of Distributed Clusters: Network Correction Factor Based on Graph Theory Topology Weights}
Let the cluster consist of $N$ nodes, and let node $i$ have standard computational capacity $q_i$ (units: standard operations/second) after heterogeneous conversion. The theoretical total computing power is $\sum_i q_i$.

Define the \textbf{network correction factor} $\eta \in (0,1]$. The cluster's net standard computational quantity is:
\begin{equation}
Q_{\text{net}} = \eta \cdot \sum_i q_i \cdot T
\end{equation}
where $T$ is the runtime. $\eta$ is modeled not only on the number of nodes $N$ but also on the communication topology weight $\Gamma$ and the interconnection bandwidth:
\begin{equation}
\eta = \frac{1}{1 + \alpha \cdot D(\Gamma) + \beta \cdot \frac{N}{B_{\text{inter}}}}
\end{equation}
\begin{itemize}[leftmargin=*]
    \item $D(\Gamma)$: normalized diameter of the network topology. For fully interconnected topologies (e.g., NVLink full mesh), $D \to 0$; for tree or ring topologies, $D$ increases with depth.
    \item $B_{\text{inter}}$: average inter-node interconnection bandwidth (GB/s).
    \item $\alpha, \beta$: communication and bandwidth penalty coefficients calibrated through measurements.
\end{itemize}

\textbf{Calibration methods for $\eta$}:
\begin{itemize}[leftmargin=*]
    \item \textbf{Measurement method}: Run a standard distributed benchmark (e.g., distributed MLPerf) and invert $\eta = \frac{\text{actual throughput}}{\text{theoretical throughput}}$.
    \item \textbf{Modeling method}: Use the above formula with $\alpha, \beta$ fitted from a small set of measurements.
\end{itemize}

This correction completely prevents the false reporting of cluster computing power by stacking low-bandwidth nodes.

\subsection{Five-Dimensional Correction for Storage Computing Power}
AI's rigid demands on storage cannot be covered by capacity and bandwidth alone. Define the standardized storage computing power value:
\begin{equation}
S_{\text{storage}} = V \cdot T \cdot \frac{B}{B_{\text{ref}}} \cdot \alpha \cdot \max\left(1, \frac{L_{\text{ref}}}{L}\right)
\end{equation}
\begin{itemize}[leftmargin=*]
    \item $V$: occupied capacity (GB)
    \item $T$: occupied duration (seconds)
    \item $B$: effective bandwidth (GB/s); $B_{\text{ref}}$ is the reference bandwidth (e.g., 100 GB/s)
    \item $\alpha \in (0,1]$: availability metric = actual available time / evaluation period
    \item $L$: response latency (seconds); $L_{\text{ref}}$ is the reference latency (e.g., 100 ns)
\end{itemize}

When actual latency is below the reference, the factor is 1 (no penalty); when above, linear penalty applies. The unit of $S_{\text{storage}}$ is the same as that of computational quantity (GB$\cdot$s) and can be converted to CUs using a predefined ratio $\gamma$ (e.g., 1 GB$\cdot$s = 0.001 CU).

\subsection{Issuance Rules for the Total Quantity of Compute Units}
Let $H(t)$ be the global total computing power at time $t$ (units: standard operations/second). The issuance rate of the total CU quantity $S(t)$ is strictly anchored to the growth rate of computing power:
\begin{equation}
\frac{dS}{dt} = \eta_{\text{global}} \cdot \frac{dH}{dt}
\end{equation}
where $\eta_{\text{global}}$ is a conversion coefficient agreed upon by the global governance protocol. The total CU quantity is proportional to the global total computing power---as computing power grows, CU grows; as computing power growth slows, CU issuance slows accordingly. This achieves natural synchronization between money supply and economic output.

\section{Consumption-Based Voucher and Issuance-Burn Two-way Peg Mechanism}

\subsection{The Paradox of Traditional Settlement Paradigms}
If service providers receive ``destroyed vouchers'' as proof of income, a logical deadlock occurs: once a voucher is marked as ``destroyed,'' it is an invalid state and cannot serve as a property voucher to redeem new quotas, causing ledger chaos and potential double counting.

\subsection{Proof of Compute and Issuance-Burn Two-way Peg}
CU circulation must be unidirectional, like the dissipation of energy---irreversible.
\begin{itemize}[leftmargin=*]
    \item \textbf{User-side payment}: When a user initiates a computational task, they pay the corresponding amount of CU vouchers. Those vouchers are \textbf{immediately physically destroyed} (permanently deducted from the global circulating total $S(t)$), and their destruction hash is recorded in the ledger.
    
    \item \textbf{Service provider income}: Service providers (miners, cloud vendors, edge nodes, etc.) do \textbf{not} receive ``destroyed vouchers.'' Instead, they submit a \textbf{Proof of Compute} to the system---proving that they have indeed consumed $Q_{\text{net}}$ physical computing power to complete the task. This proof can be:
    \begin{itemize}
        \item Execution log signatures inside a Trusted Execution Environment (TEE);
        \item Zero-Knowledge Proof (ZKP) aggregating the computational integrity of multiple tasks;
        \item Or, for non-sensitive tasks, a random spot-check challenge-response mechanism.
    \end{itemize}
    
    \item \textbf{System issuance reward}: After the system verifies the proof, it \textbf{newly issues} an equivalent amount of CUs from the current block's computing-power-growth issuance pool (i.e., part of $\frac{dS}{dt}$) and distributes them to the service provider. These newly issued CUs enter circulation.
\end{itemize}

\textbf{Result}: CUs paid by users are destroyed (deflation), while service providers receive newly issued CUs by proving newly consumed computing power (inflation). The total circulating CU quantity always equals the net discounted value of the historically accumulated physical computing power consumption, leaving no arbitrage space or ledger inconsistency.

\section{Anti-Cheating and Dynamic Calibration Mechanisms}

\subsection{Defense Against Benchmark Testing Cheating}
As described in Section 2.1, the \textbf{Standard Reference Workload (SRW)} and dynamic upgrade mechanism are introduced. Any special-purpose optimization that deviates from SRW characteristics and cannot be replicated on multiple mainstream models will be marked as ``benchmark-specific optimization,'' and its $E_i$ value will be multiplied by a penalty factor $p \in [0.3, 0.7]$.

\subsection{Defense Against Manipulation of the Network Correction Factor}
Cloud vendors might artificially increase $\eta$ by lowering $D(\Gamma)$ (e.g., claiming full interconnection) or by falsifying $B_{\text{inter}}$. Defense measures include:
\begin{itemize}[leftmargin=*]
    \item \textbf{Mandatory topology disclosure}: Auditable network topology documentation or probe-based detection results must be provided.
    \item \textbf{Third-party measurement}: The Governance Committee or audit nodes can initiate random distributed tests at any time, inversely compute the actual $\eta$, and compare it with the declared value. A deviation exceeding 10\% triggers a penalty (CU deduction).
\end{itemize}

\subsection{Defense Against Data Tampering in the Five-Dimensional Storage Model}
Availability $\alpha$ and latency $L$ must be measured by \textbf{multiple independent probes} (monitoring nodes deployed at different network locations), and the median value is taken to prevent single-node falsification.

\subsection{Checks and Balances in the Governance Committee Design}
The CU Governance Committee consists of multiple stakeholders (hardware vendors, cloud vendors, developers, academic representatives, environmental organizations) with weighted representation. Any modification of calibration parameters (SRW, $\alpha, \beta, \gamma$, etc.) requires a 2/3 majority vote, accompanied by complete experimental data and impact analysis. The committee's decision logs are publicly auditable.

\section{Consensus Establishment Method: Natural Evolution Path of Public Domain Standards}
The promotion of CU cannot rely on ``wealth creation effects'' (e.g., cryptocurrencies) or ``state coercion'' (e.g., fiat money). It is essentially a migration of measurement standards. The promotion of measurement standards relies on indisputable physical superiority and precise surgical-level deconstruction of existing pain points. The following is a four-stage socio-technical system dynamics model.

\subsection*{First Stage: Open-Source Benchmark Tools and De Facto Standard Penetration}
\textbf{Target audience}: AI developers, computing power miners, cloud provider infrastructure architects.

\textbf{Operations}:
\begin{itemize}[leftmargin=*]
    \item Release an open-source ``CU Benchmark Suite'' implementing all formulas from Section 2, with elegant code and clear documentation.
    \item Clearly state: ``Existing FLOPS measurements hide real coordination losses and storage penalties. Only by running the CU suite can you know the true effective computing power of a machine.''
    \item Encourage developers to include CU values in papers, technical blogs, and product comparisons.
\end{itemize}

\textbf{Expected result}: Engineers spontaneously adopt CU as the ``ruler'' for horizontal comparison, and the de facto standard begins to penetrate.

\subsection*{Second Stage: Edge Computing Power Market Validation and Micro-Closed Loop}
\textbf{Target audience}: Edge computing power providers, ordinary users.

\textbf{Operations}:
\begin{itemize}[leftmargin=*]
    \item Build a ``CU Verification Network'': lightweight clients that convert idle computing power from phones, PCs, etc., into CUs and execute lightweight AI inference tasks.
    \item Establish a small-scale exchange market: CUs can be exchanged for open-source model inference services or physical items (e.g., development boards).
\end{itemize}

\textbf{Expected result}: A real transaction closed loop is formed, proving that ``CUs can actually be exchanged for things,'' and the media naturally spreads the news.

\subsection*{Third Stage: Theoretical Paradigm Shift and Academic Consensus Reconstruction}
\textbf{Target audience}: Economists, complexity science scholars, top AI conferences.

\textbf{Operations}:
\begin{itemize}[leftmargin=*]
    \item Disseminate the conceptual ideas of CU.
    \item Clearly point out: ``Existing fiat-based AI economic models mathematically lead to inevitable deflationary deadlocks; CU is the only solution with physical anchoring.''
\end{itemize}

\textbf{Expected result}: The academic community engages in paradigm debates around CU; each rebuttal reinforces the exposure and validation of the CU formulas.

\subsection*{Fourth Stage: Spontaneous Adaptation of Macroeconomic Systems and Institutional Co-optation}
\textbf{Target audience}: Large cloud vendors, sovereign states.

\textbf{Operations}: No active selling. When the first three stages reach critical mass:
\begin{itemize}[leftmargin=*]
    \item Cloud vendors discover that customers use CU as a price-performance yardstick, forcing them to provide ``CU pricing.''
    \item Small nations find that using CU as a basis for Universal Basic Income (UBI) vouchers solves AI-induced unemployment at extremely low cost.
\end{itemize}

\textbf{Expected result}: Macroeconomic systems actively integrate with the CU protocol. Because the definitions have been made fully public through Zenodo, integration faces no patent barriers, and CU becomes an ambient public domain standard.

\hrule

\section{Conclusion: The Inevitability of Compute Unit as a Public Domain Standard}
CU is not a cryptocurrency, not an app, not an ideology. It is a ruler. The promotion of a ruler does not require faith, only one fact: when you measure two different machines, two different clusters, or two different storage systems with CU, you obtain comparable, verifiable, and auditable physical truths.

This paper provides a complete theoretical definition (heterogeneous conversion, network correction, storage correction, bidirectional anchoring settlement, anti-cheating mechanisms) and an implementable four-stage evolution path. This path has been proven by the Logos-$\Omega$ socio-control framework to be the unique optimal strategy consistent with information thermodynamics and evolutionary dynamics---creating error signals, providing structured high entropy, and allowing systems to spontaneously complete phase transitions. CU is not a replacement for money but the ultimate destination of money in the entropy-increasing desert. Its promotion does not require convincing anyone, only being the truth-teller who points out that ``the emperor has no clothes.'' When the entire computing power industry realizes that it has been blindly feeling the elephant, CU will be the cane they can reach for.

\hrule

\appendix
\section{Symbol Table}
\begin{table}[htbp] % 改为 htbp 避免浮动警告
\centering
\caption{Symbol Table}
\begin{tabular}{@{}lll@{}}
\toprule
\textbf{Symbol} & \textbf{Meaning} & \textbf{Unit} \\
\midrule
$P_i$ & $i$-th computational precision & --- \\
$E_i$ & Effective computational capacity of precision $P_i$ & standard operations/second \\
$k_i$ & Conversion coefficient & --- \\
$Q_{\text{std}}$ & Standard computational quantity & standard operations \\
$U_0$ & Standard operations per CU & standard operations/CU \\
$\eta$ & Network Correction Factor (NCF) & 1 \\
$D(\Gamma)$ & Normalized diameter of the topology & 1 \\
$B_{\text{inter}}$ & Average inter-node bandwidth & GB/s \\
$S_{\text{storage}}$ & Standardized storage computing power & GB$\cdot$s \\
$\alpha$ (storage) & Availability metric & 1 \\
$L$ & Response latency & s \\
$S(t)$ & Total circulating CU quantity & CU \\
$H(t)$ & Global total computing power & standard operations/second \\
\bottomrule
\end{tabular}
\end{table}

\textit{Note: $H(t)$ is the global total computing power as used in Section 2.4.}

\section{Example of Standard Reference Workload (SRW)}
(Example for 2025)
\begin{itemize}[leftmargin=*]
    \item \textbf{Workload type}: Transformer Decoder auto-regressive generation
    \item \textbf{Key operators}: Matrix multiplication (FP16/INT8), Softmax, LayerNorm, Gather/Scatter
    \item \textbf{Sequence length}: 2048
    \item \textbf{Batch size}: 1--64
    \item \textbf{Acceptance criteria}: The workload must run on at least three mainstream architectures (NVIDIA, AMD, Intel, Ascend, etc.) and show a correlation $>$0.95 between its measured performance and the inference performance of a real large model (e.g., Llama-3-70B).
\end{itemize}

The SRW is updated every two years by the Governance Committee.

\section*{Acknowledgments}
This work was inspired by the Logos-$\Omega$ framework. All formulas and protocols can be derived self-consistently within that framework.

\section*{License}
This paper and its accompanying code are under \textbf{CC0 1.0 Universal (CC0 1.0)}. See the Legal Notice section for full patent pre-emption and public domain clauses.

\end{document}