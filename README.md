# ArXiv Endorsement Request — Robust Generalization in Audio-First Laughter Detection

## Category: cs.CL (Computation and Language)

## Endorsement Status
- **Endorsement Code**: (pending)
- **Status**: Awaiting endorsement
- **Date**: June 2026
- **Author**: Subhajit Dey
- **LinkedIn**: [linkedin.com/in/subhajitd](https://www.linkedin.com/in/subhajitd/) ✓ Verified

---

## About This Paper

**Title**: Robust Generalization in Audio-First Laughter Detection Through WavLM and Prosodic Ensembles

**arXiv Categories**: cs.CL, cs.AI, cs.LG

### Abstract (500 words)

We demonstrate that audio-first laughter detection achieves robust generalization to unseen comedians — a critical deployment scenario that current text-based approaches fail to address. Our WavLM-Prosody ensemble achieves **F1=0.587** on held-out comedians, **3.9× better** than text-only XLM-R (F1=0.152). This gain stems from audio capturing universal paralinguistic cues that transfer across performers, while text memorizes comedian-specific linguistic patterns. On per-comedian held-out evaluation, audio degrades only 54% (0.608→0.280) versus text's 81% collapse (0.819→0.152). All improvements are statistically significant (p < 0.0001). Our system enables sub-millisecond CPU inference with ~1MB model weights, operates language-agnostically across English and Chinese, and requires no speaker-specific adaptation for deployment.

### Key Contributions

1. **First audio-first laughter detection with validated comedian generalization**
2. **Quantified modality gap**: Audio degrades only 54% vs text's 81% collapse on held-out evaluation
3. **Statistical significance validation** (p < 0.0001)
4. **Production-ready system**: Sub-millisecond CPU inference, ~1MB model weights

### Why cs.CL?

This paper addresses core NLP/CL questions:
- Cross-speaker generalization in sequence labeling
- Multimodal representation learning (audio + text)
- Robustness under distribution shift (held-out evaluation)
- Language-agnostic acoustic representation learning

---

## Gate 1: Verified LinkedIn Profile

**Profile**: [https://www.linkedin.com/in/subhajitd/](https://www.linkedin.com/in/subhajitd/)

✓ Identity verified through LinkedIn's verification system

---

## Gate 2: Complete Paper Draft

The full paper draft is available in this repository:
- **[paper_pdf.pdf](paper_pdf.pdf)** — Complete paper draft (327KB)

### Paper Summary

**Problem**: Current laughter detection systems fail catastrophically when deployed on new, unseen comedians. This is the **comedian generalization problem**.

**Approach**: Audio-first design using WavLM + prosody features. Audio captures laughter's universal acoustic signature rather than comedian-specific word patterns.

**Key Results**:
| Model | Held-Out F1 | vs Text |
|-------|-------------|---------|
| XLM-R text-only | 0.152 | baseline |
| WavLM audio-only | 0.280 | +84% |
| **Ensemble** | **0.587** | **+286%** |

**Statistical Significance**: All improvements p < 0.0001 via bootstrap permutation testing (10,000 iterations).

---

## Gate 3: Academic References

This work builds on established research:

- **Bertero & Fung (2016)**: Deep Learning of Audio and Language Features for Humor Prediction. LREC 2016.
- **Gillick et al. (2019)**: Learning to Detect Laughter. Interspeech 2019.
- **Barriere et al. (2025)**: StandUp4AI Dataset. ACL 2025.
- **Callejas et al. (2026)**: MultiLinguahah. arXiv:2605.06309.
- **Hasan et al. (2019)**: UR-FUNNY. EMNLP 2019.

---

## Outreach Targets

Qualified ArXiv endorsers for cs.CL being contacted:

| Name | Affiliation | Status |
|------|-------------|--------|
| (pending) | | |

---

## Contact

- **Author**: Subhajit Dey
- **LinkedIn**: [linkedin.com/in/subhajitd](https://www.linkedin.com/in/subhajitd/)
- **GitHub**: [github.com/Das-rebel](https://github.com/Das-rebel)
- **Project**: [ChuckleNet - Autonomous Laughter Prediction](https://github.com/Das-rebel/ChuckleNet)

---

*Science must walk in the light — this release verifies outreach to qualified endorsers and documents author legitimacy.*
