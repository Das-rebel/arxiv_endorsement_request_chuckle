# ArXiv Endorsement Request — Audio-First Laughter Detection

## Paper: "Robust Generalization in Audio-First Laughter Detection Through WavLM and Prosodic Ensembles"

**Category**: cs.CL (Computation and Language)  
**Author**: Subhajit Dey  
**Date**: June 2026  
**Status**: Awaiting endorsement  
**Endorsement Code**: (pending from ArXiv)

**GitHub Repo**: https://github.com/Das-rebel/arxiv_endorsement_request_chuckle

---

## Gate 1: Verified LinkedIn Profile ✓

**Profile**: [https://www.linkedin.com/in/subhajitd/](https://www.linkedin.com/in/subhajitd/)

Identity verified through LinkedIn's verification system.

---

## Gate 2: Complete Paper Draft ✓

📄 **[paper_pdf.pdf](paper_pdf.pdf)** — Complete paper draft (327KB)

### Key Results

| Model | Held-Out Comedian F1 | vs Text-Only |
|-------|---------------------|--------------|
| XLM-R text-only | 0.152 | baseline |
| WavLM audio-only | 0.280 | +84% |
| **Ensemble** | **0.587** | **+286%** |

**Statistical Significance**: All improvements p < 0.0001 via bootstrap permutation testing (10,000 iterations)

### Abstract

We demonstrate that audio-first laughter detection achieves robust generalization to unseen comedians — a critical deployment scenario that current text-based approaches fail to address. Our WavLM-Prosody ensemble achieves **F1=0.587** on held-out comedians, **3.9× better** than text-only XLM-R (F1=0.152). This gain stems from audio capturing universal paralinguistic cues that transfer across performers, while text memorizes comedian-specific linguistic patterns.

---

## Gate 3: Academic References

This work builds on established research:

| Paper | Venue | Relevance |
|-------|-------|-----------|
| MultiLinguahah (Callejas et al., 2026) | arXiv:2605.06309 | Unsupervised multilingual laughter segmentation |
| StandUp4AI (Barriere et al., 2025) | ACL/EMNLP 2025 | Multilingual humor dataset |
| MTLLFM (Hanania et al., 2026) | CVPR 2026 Workshop | Temporal laughter localization |
| UR-FUNNY (Hasan et al., 2019) | EMNLP 2019 | Multimodal humor dataset |
| Gillick et al., 2019 | Interspeech 2019 | Learning to detect laughter |
| Bertero & Fung, 2016 | LREC 2016 | Audio/language features for humor |

---

## Outreach Targets

### Primary Targets (Direct Connection to Laughter Detection)

| Name | Affiliation | Contact | Publications | Outreach Status |
|------|-------------|---------|--------------|-----------------|
| **Brian Ravenet** | Université Paris-Saclay | brian.ravenet@universite-paris-saclay.fr | Multiple papers on laughter/humor detection | 🔍 Researching |
| **Valentin Barriere** | Universidad de Chile / CENIA | [valbarriere.github.io](https://valbarriere.github.io) | StandUp4AI (EMNLP 2025), StandUp humor | 🔍 Researching |
| **Sofia Callejas** | ISIR UPMC France | [isir.upmc.fr/personnel/callejas](https://www.isir.upmc.fr/personnel/callejas/?lang=en) | MultiLinguahah (cs.CL 2026) | 🔍 Researching |
| **Eyal Hanania** | TBD | TBD | MTLLFM (CVPR 2026W) | 🔍 Researching |

### Secondary Targets (Affective Computing / Multimodal ML)

Other cs.CL researchers working on audio/affective computing (to be researched).

---

## How to Help

If you are a registered **ArXiv endorser for cs.CL** and find this work appropriate, you can:

1. **Endorse via ArXiv**: When I submit to arxiv.org, an endorsement code will be generated
2. **Provide feedback**: Review the paper draft and suggest improvements
3. **Connect**: Introduce me to other researchers who might endorse

---

## Repository Contents

```
├── README.md              # This file
├── paper_pdf.pdf          # Complete paper draft
├── endorsement_request.txt # Generic outreach message
└── recipients_list.csv    # Tracking outreach efforts
```

---

## Contact

- **Author**: Subhajit Dey
- **LinkedIn**: [linkedin.com/in/subhajitd](https://www.linkedin.com/in/subhajitd/) ✓ Verified
- **GitHub**: [github.com/Das-rebel](https://github.com/Das-rebel)
- **Project**: [ChuckleNet](https://github.com/Das-rebel/ChuckleNet)

---

*Science must walk in the light — this release verifies outreach to qualified endorsers and documents author legitimacy.*
