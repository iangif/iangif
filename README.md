## Hi, I'm Ian

I study Computer Science and AI at McGill, with a minor in Linguistics. I'm currently doing research on how language models learn and represent linguistic structure, and I build the software those experiments run on: annotation platforms, benchmarks, and data pipelines.

**Co-first-authored paper at [CoNLL 2026](https://aclanthology.org/2026.conll-main.40/)** · Research at Mila, MCQLL and McGill AI Lab · Full-stack tools used by lab researchers

[Website](https://iangif.github.io) · [LinkedIn](https://linkedin.com/in/ian-gifford88) · [Email](mailto:ian.gifford@mail.mcgill.ca)

---

### MCQLL: research infrastructure
*Software Engineering Research Assistant, Montréal Computational & Quantitative Linguistics Lab · 2026–present*

I build the lab's pipeline for a hand-verified, multilingual formant dataset, from annotation to benchmarking.

<table>
<tr>
<td width="55%"><a href="https://github.com/iangif/formant-annotation-tool"><img src="https://raw.githubusercontent.com/iangif/formant-annotation-tool/main/docs/media/annotate-demo.gif" alt="Formant annotation tool demo"></a></td>
<td>

**[formant-annotation-tool](https://github.com/iangif/formant-annotation-tool)**<br>
A keyboard-first FastAPI and JavaScript app, plus server sync, reconciliation, and adjudication. It replaced a manual workflow: **5,000+ tokens** labelled, and batch management cut from **~40 to ~10 hours**.

**[formant-benchmark](https://github.com/iangif/formant-benchmark)**<br>
An extensible benchmark for formant trackers. Datasets and trackers plug in through adapters, runs are digest-cached and reproducible, and the evaluation is frame-level.

</td>
</tr>
</table>

### McGill AI Lab: NLP research
*Student Researcher → Team Lead · 2025–present*

- **[age-of-acquisition](https://github.com/McGill-AI-Lab/age-of-acquisition)**: Does learning words in the order children do shape word embeddings? Built on an ≈18M-sentence curriculum pipeline and 40+ Word2Vec experiments. AoA-ordered training predicts human acquisition norms with ρ = 0.93, compared with 0.56 for shuffled training. [Paper, CoNLL 2026 →](https://aclanthology.org/2026.conll-main.40/)
- **Diffusion LM probing** *(in progress)*: I lead a team of 4 tracing how syntactic and semantic knowledge emerges during diffusion language model denoising, using linear probes. Code coming soon.

### Mila: interpretability
*Research Intern · 2026–present*

- **Induced grammar categories** *(in progress)*: An analysis framework for the categories learned by visually grounded grammar induction models. It covers 300K+ tokens and ~10 models, and compares lexical and contextual feature profiles across models.


<sub>Python · PyTorch · FastAPI · SQLAlchemy · pandas / Parquet · JavaScript · SLURM · AWS</sub>
