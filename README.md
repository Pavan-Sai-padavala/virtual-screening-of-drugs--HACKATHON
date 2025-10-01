# virtual-screening-of-drugs--HACKATHON
Built as part of the FutureStack GenAI Hackathon, this project leverages Cerebras models and Dockerized containers to develop a multi-agent application for virtual screening and ranking of potential drug candidates.

HACKATHON PAGE: https://www.wemakedevs.org/hackathons/futurestack25

HACKATHON SPONSORS:
- CEREBRAS AI (https://www.cerebras.ai/)
- META (https://www.meta.ai/)
- DOCKER (https://www.docker.com/)
## Background Overview:

Drug discovery is a time-intensive and costly process, often requiring years of research and billions of dollars in investment. A critical step in this pipeline is virtual screening — evaluating large libraries of molecules to identify potential drug candidates that can bind effectively to target proteins.

ADMET (Absorption, Distribution, Metabolism, Excretion, and Toxicity)
are the key pharmacokinetic and safety properties of a drug candidate. Even if a molecule shows good binding to a target protein, it must also satisfy ADMET requirements to be a viable therapeutic.
- Absorption (A): How well a drug is absorbed into the bloodstream (e.g., oral bioavailability).
- Distribution (D): How the drug spreads throughout tissues and organs once in the body.
- Metabolism (M): How the body’s enzymes (especially in the liver) chemically transform the drug.
- Excretion (E): How the drug and its metabolites are eliminated from the body (urine, feces, etc.).
- Toxicity (T): Whether the compound has harmful side effects (e.g., liver toxicity, mutagenicity).

## Virtual Screening of Drugs:
This project integrates ADMET prediction into a multi-agent AI system, enabling:

- Screening of drug candidates for binding affinity (virtual screening & docking)
- Filtering based on ADMET properties
- Ranking to highlight the most promising and safe candidates

## DATASET Description:
This project uses publicly available molecular datasets:

- MoleculeNet (moleculenet.org)
- ZINC Database (zinc.docking.org)

The molecular data is represented in SMILES (Simplified Molecular-Input Line-Entry System) format (https://reference.wolfram.com/language/ref/format/SMILES.html), which encodes the structure of molecules as text strings.
