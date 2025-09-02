# Sports, Politics, and Social Media: A Human-AI Collaborative Analysis of Consumer Reactions to Trump’s Break 50 Appearance

Thanks for your interest! This repository contains the code, prompts, fine-tuning data, and outputs associated with the paper *"Sports, Politics, and Social Media: A Human-AI Collaborative Analysis of Consumer Reactions to Trump’s Break 50 Appearance."* The study examined audience discourse surrounding Bryson DeChambeau and Donald Trump’s Break 50 video using a human–AI collaborative framework.

## Repository Structure

The repository is organized into the following directories:

| File/Folder                | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `BERTopic/BERTopic_hierarchical_clustering` | Hierarchical clustering outputs from BERTopic modeling. |
| `BERTopic/BERTopic_topic_results`           | Topic modeling results, including topic distributions and keywords. |
| `Fine-tuning/prompt_gpt-4.1`                | Prompt used with GPT-4.1 for generating fine-tuning data. |
| `Fine-tuning/ft_gpt-4o-mini_training`       | Training dataset used for fine-tuning GPT-4o-mini. |
| `Fine-tuning/ft_gpt-4o-mini_validation`     | Validation dataset used for fine-tuning GPT-4o-mini. |
| `Reasoning/prompt_o4-mini`                  | Prompt used with o4-mini for reasoning runs. |
| `Reasoning/output_o4-mini`                  | Outputs generated using the o4-mini model in reasoning runs. |
| `Appendix/`                                 | Supplementary files provided as an appendix to support verification and replication. |

## Usage

1. Clone the repository and navigate into the desired folder.
2. Explore the `BERTopic` folder for topic modeling outputs and hierarchical clustering files.
3. Use the `Fine-tuning` folder if you wish to replicate or adapt the fine-tuning of GPT-4o-mini with the provided training and validation sets.
4. Refer to the `Reasoning` folder for prompt templates and example outputs from reasoning experiments.
5. Supplementary details and additional resources are available in the `Appendix`.

These resources are designed to provide transparency, replicability, and adaptability for future research at the intersection of sport, politics, and AI-assisted analysis.

## Citation

If you use this repository or build upon this work, please cite the associated paper:

```bibtex
@article{qian2025break50,
  title={Sports, Politics, and Social Media: A Human-AI Collaborative Analysis of Consumer Reactions to Trump’s Break 50 Appearance},
  author={Qian, Tyreal Yzihou and Gong, Hua and Xu, Chenglong},
  journal={},
  year={2025},
}
```

## Contact

For questions, suggestions, or collaboration opportunities, please contact: Tyreal Yizhou Qian (yqian@lsu.edu)
