# PharmaScan 

PharmaScan is an automated cheminformatics and drug-screening pipeline designed to evaluate small molecule compounds. It bridges raw chemical structures and pharmacological profiling by predicting critical pharmacokinetic parameters, toxicity risks, and drug-likeness metrics in a single reproducible workflow.

## Key Features
- **Molecular Property Prediction:** Computes essential physicochemical descriptors including molecular weight, logP, polar surface area (PSA), and hydrogen bond donors/acceptors.
- **Drug-Likeness Scoring:** Evaluates compounds against established pharmacological rules (such as Lipinski's Rule of Five) to filter viable drug candidates.
- **Toxicity & Risk Flagging:** Proactively identifies structural alerts, reactive functional groups, and potential toxicity risks.
- **Streamlined Profiling:** Replaces manual multi-tool lookups with an integrated, high-throughput computational pipeline.

## Workflow Overview
1. **Input:** User supplies molecular structures (SMILES strings or compound files).
2. **Processing:** Molecular descriptors and topological properties are computed.
3. **Evaluation:** Compliance with drug-likeness rules and toxicological alerts are assessed.
4. **Diagnostic Reporting:** Generates a comprehensive pharmacological profile and risk classification report.
   
## Usage
You can run the complete analysis pipeline interactively via Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NaAREbidQX4gC9DDNTIasexnfAI0Vfuj?usp=sharing)
