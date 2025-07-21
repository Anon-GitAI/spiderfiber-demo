# SpiderFiber Inference Demo

This notebook demonstrates how to run inference using SpiderGPT model hosted on Hugging Face.

## Data
Sample data with detailed usage is provided in Data folder

## HuggingFace model
Model name: anon-genAI/SpiderGPT

## Usage: 
The exceptional mechanical performance of spider silk—characterized by its high tensile strength and extensibility—is largely attributed to the repetitive domains within major ampullate spidroin (MaSp) proteins. Despite this, uncovering clear relationships between these mechanical properties and the underlying repeat sequences remains a significant challenge, owing to the complex interplay among sequence, structure, and function, as well as the scarcity of comprehensive annotated datasets.

In this work, we introduce a computational approach for the design of MaSp repeat sequences with tunable mechanical characteristics. Our framework is built upon a compact GPT-style generative model, derived by distilling the ProtGPT2 protein language model. The resulting model underwent a two-stage fine-tuning process using curated data from the Spider Silkome resource. First, it was trained on 6,000 repeat sequences to learn MaSp-specific patterns. It was then fine-tuned through cross-validation on 592 repeats annotated with experimentally measured fiber-level mechanical properties.

This generative model is capable of producing biologically relevant repeat sequences aligned with target mechanical attributes, while also enabling property prediction from given sequences. Model validation was performed through analyses of sequence motifs, physicochemical properties, and secondary structure trends. In addition, predictive performance was benchmarked by aligning generated sequences against natural sequences using BLAST, and by evaluating prediction accuracy on a test set with known mechanical properties.

Overall, our framework provides a new avenue for the rational design of spider silk-inspired proteins, offering a flexible tool for engineering MaSp repeats with desired mechanical functions.
