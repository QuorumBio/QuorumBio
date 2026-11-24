<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/QuorumBio/quorum-bio/main/brand/wordmark-dark.png">
  <img alt="Quorum Bio" src="https://raw.githubusercontent.com/QuorumBio/quorum-bio/main/brand/wordmark.png" width="420">
</picture>

Small, permissively licensed biology models with reproducible training, ONNX exports and model cards that say where the models are weak.

**Models**
- [biomedical-ner-chemical-disease](https://huggingface.co/quorumbio/biomedical-ner-chemical-disease): Chemical and Disease NER for biomedical text (Apache-2.0). [Browser demo](https://huggingface.co/spaces/quorumbio/biomed-ner-demo)
- [esm2-protein-subcellular-localization-signal-peptide](https://huggingface.co/quorumbio/esm2-protein-subcellular-localization-signal-peptide): protein localization and signal peptide prediction (Apache-2.0). [Browser demo](https://huggingface.co/spaces/quorumbio/protein-localization-demo)
- [esm2-650m-protein-subcellular-localization-signal-peptide](https://huggingface.co/quorumbio/esm2-650m-protein-subcellular-localization-signal-peptide): larger ESM-2 650M version (slightly better location ranking, about 4x larger)
- [biomedical-ner-gene-chemical-disease-species](https://huggingface.co/quorumbio/biomedical-ner-gene-chemical-disease-species): one model for genes, chemicals, diseases, species, variants and cell lines (Apache-2.0). [Browser demo](https://huggingface.co/spaces/quorumbio/biomedical-ner-6-types-demo)
- [biomedical-ner-gene-chemical-disease-species-small](https://huggingface.co/quorumbio/biomedical-ner-gene-chemical-disease-species-small): 6-layer distilled version (66.8 MB int8, about 2x faster)

**Data**
- [swissprot-subcellular-localization-signal-peptide](https://huggingface.co/datasets/quorumbio/swissprot-subcellular-localization-signal-peptide): homology-partitioned Swiss-Prot split (CC BY 4.0)

Code, training scripts and the technical report draft: [quorum-bio](https://github.com/QuorumBio/quorum-bio). Everything on Hugging Face: [collection](https://huggingface.co/collections/quorumbio/quorum-bio-open-biology-models-6b03617169bc86a3fd82656b).
