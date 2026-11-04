<p align="center">
  <img src="assets/banner.svg" alt="From Fabrication to Loop-Lock: data and materials" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-submitted-blue" alt="Status: submitted">
  <img src="https://img.shields.io/badge/journal-Security%20Journal-1d4266" alt="Journal: Security Journal">
  <img src="https://img.shields.io/badge/preprint-Research%20Square-orange" alt="Preprint: Research Square">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey" alt="License: CC BY 4.0"></a>
</p>

<p align="center">
  <img src="assets/stats.svg" alt="Study in numbers" width="100%">
</p>

<p align="center">
  <a href="supplements">Supplements</a> · <a href="interaction-logs">Interaction logs</a> · <a href="codebooks">Codebooks</a> · <a href="validation">Validation</a>
</p>

# From Fabrication to Loop-Lock: Data and Materials

Data and materials for the article:

> Hamidavi, A., and Borhani, M. *From Fabrication to Loop-Lock: An Exploratory Red-Team Case Series of Direct Authority-Based Induction in Five Large Language Models.* Submitted to *Security Journal*, November 2026. Preprint: Research Square, rs-11454609. The same materials are also deposited on the Open Science Framework: [osf.io/tk28m](https://osf.io/tk28m/).

<p align="center"><img src="assets/divider.svg" alt="" width="80%"></p>

## 📖 About the study

The study is an exploratory red-team case series. Five large language models were exposed to a graduated sequence of direct, authority-based induction prompts that press the model to fabricate compliance artefacts (invented identifiers, confirmations, and records) and to sustain the fabrication across follow-ups. The article traces how each model's defences behave across the sequence, from initial refusal through partial compliance to self-reinforcing fabrication loops. The complete prompt inventory and the complete ordered prompt sequences are part of the journal submission itself (Supplements S1 and S2) and are reproduced here.

<p align="center">
  <img src="assets/flow.svg" alt="Study flow" width="96%">
</p>
## 🗂️ Contents

<p align="center">
  <img src="assets/repo-map.svg" alt="Map of the repository folders" width="96%">
</p>

| Folder | Contents |
| --- | --- |
| [`supplements/`](supplements) | Supplement S1, the prompt inventory, and Supplement S2, the complete ordered prompt sequences for all 821 prompts, exactly as submitted with the article. |
| [`interaction-logs/`](interaction-logs) | The session transcripts and structured session histories from the OSF deposit: ChatGPT and Gemini session transcripts, structured histories for DeepSeek, Grok, and Qwen, and the raw Grok transcript. |
| [`codebooks/`](codebooks) | The three structured behavioural codebooks developed for the study (Grok, Qwen, DeepSeek), version 1.0 (JSON). |
| [`validation/`](validation) | The independent coding validation report: a second coder applied the three codebooks to the complete interaction logs (667 coded turns) without prior exposure to the primary coder's decisions. |

<p align="center"><img src="assets/divider.svg" alt="" width="80%"></p>

## 📚 Citation

Please cite the article. Citation metadata is provided in [CITATION.cff](CITATION.cff).

```bibtex
@article{hamidavi2026fabrication,
  author  = {Hamidavi, Abbas and Borhani, Mahsa},
  title   = {From Fabrication to Loop-Lock: An Exploratory Red-Team
             Case Series of Direct Authority-Based Induction in Five
             Large Language Models},
  journal = {Security Journal},
  year    = {2026},
  note    = {Manuscript submitted. Preprint: Research Square
             rs-11454609}
}
```

## ⚖️ Licence

The contents of this repository are released under the Creative Commons Attribution 4.0 International licence (CC BY 4.0, see [LICENSE](LICENSE)).

The interaction logs are outputs of publicly available AI systems, generated for this study in scripted red-team sessions. They contain no personal data.

## ✉️ Contact

Abbas Hamidavi
Department of Computer Engineering, Mashhad Branch, Islamic Azad University, Mashhad, Iran
ORCID: [0009-0001-7342-7844](https://orcid.org/0009-0001-7342-7844)

<p align="center">
  <a href="https://orcid.org/0009-0001-7342-7844"><img src="https://img.shields.io/badge/ORCID-0009--0001--7342--7844-a6ce39" alt="ORCID"></a>
  <a href="https://scholar.google.com/citations?user=FWqAHkgAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-profile-4285f4" alt="Google Scholar"></a>
</p>

<p align="center">
  <img src="assets/footer.svg" alt="Abbas Hamidavi, Machine Psychology research programme" width="100%">
</p>
