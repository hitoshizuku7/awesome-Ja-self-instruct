# Awesome Japanese Self-Instruct.

This is a Japanese dataset with Alpaca format. 
And the approach to generate this dataset is described by the paper: [Rapidly Developing High-quality Instruction Data and Evaluation Benchmark for Large Language Models with Minimal Human Effort: A Case Study on Japanese](https://arxiv.org/pdf/2010.12812.pdf).


## Process

We revisited the original self-instruct method.

Our method translates that small number of seed tasks into Japanese and manually post-edits them to achieve native-level quality. 
Then we utilize GPT-4 to generate high-quality Japanese data directly.


## References
[Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca)

## Citation
If you use our code in your research, please cite our work:
```bibtex
@inproceedings{sun2024rapidly,
   title={Rapidly Developing High-quality Instruction Data and Evaluation Benchmark for Large Language Models with Minimal Human Effort: A Case Study on Japanese},
   author={Sun, Yikun and Wan, Zhen and Ueda, Nobuhiro and Yahata, Sakiko and Cheng, Fei and Chu, Chenhui and Kurohashi, Sadao},
   booktitle={The 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)},
   year={2024}
}
```

