# Efficient LLM for Summarization

A study on pruning and fine-tuning large language models (LLMs) for summarization tasks using the BillSum dataset.

## Features

- Compares structured (N:M) and unstructured pruning on OPT models (125M, 350M)
- Implements Wanda, Magnitude, and SparseGPT pruning methods
- Fine-tunes pruned models with QLoRA for summarization
- Evaluates performance using ROUGE-L, BERTScore, and resource usage metrics

## License

[MIT](LICENSE) © 2025 Chris Lee
