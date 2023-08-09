#  RWKV-Notebooks

Uses jsonl and binidx instead of the garbage RAM-intensive scripts.

Example.jsonl file contents:
```json
{"text": "This is a sentence"}
{"text": "Instruction: a\n\nInput: b\n\nResponse: c"}
{"text": "Question: a\n\nAnswer: b"}
```
The tokenizer will combine all jsonl files inside your dataset folder into two files the train script will read. Read the outputs of the cells to know what to do.

---


## RWKV-infctx:
Only tested 0.4B-World

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/h-a-s-k/RWKV-Notebooks/blob/master/RWKV-infctx.ipynb)

## RWKV-LorA:
Soon™