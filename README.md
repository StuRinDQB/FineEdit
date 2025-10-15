# Bridging the Editing Gap in LLMs: *FineEdit* for Precise and Targeted Text Modifications

Large Language Models (LLMs) have significantly advanced natural language processing, demonstrating strong capabilities in tasks such as text generation, summarization, and reasoning. Recently, their potential for automating precise text editing tasks across specialized domains, such as programming code, LaTeX, and structured database languages, has gained attention. However, current state-of-the-art LLMs still struggle with executing precise, instruction-driven edits, particularly when structural accuracy and strict adherence to domain conventions are required. To address these challenges, we introduce InstrEditBench, an automated benchmark dataset comprising over 30,000 structured editing tasks spanning diverse domains, including Wikipedia articles, LaTeX documents, source code, and database languages. Using this benchmark, we develop FineEdit, a specialized editing model explicitly trained for accurate, context-aware text modifications. Experimental evaluations demonstrate that FineEdit outperforms state-of-the-art models, achieving improvements of approximately 10\% over Gemini models on single-turn edits, up to 30\% over Llama-3.2-3B, and exceeding Mistral-7B-OpenOrca performance by over 40\% on direct editing tasks. FineEdit also effectively generalizes to realistic multi-turn editing scenarios, highlighting its practical applicability. 


The code for **EMNLP 2025** paper: [Bridging the Editing Gap in LLMs: FineEdit for Precise and Targeted Text Modifications](https://arxiv.org/abs/2502.13358).

📄 [Paper](https://arxiv.org/abs/2502.13358) · 💻 [Github](https://github.com/StuRinDQB/FineEdit) · 🤗 [Huggingface](https://huggingface.co/datasets/Yiming1001/FineEdit_bench)

---

**If you find our project helpful, please give us a star ⭐ on GitHub to stay updated.**

---

![FineEdit Framework](https://github.com/user-attachments/assets/dde2c4d6-60be-4cbe-90b2-b3764f67410a)


## 🚀 How to Use the Dataset

### 1️⃣ Install and Login to Hugging Face

Make sure you have the Hugging Face Hub and Datasets libraries installed:

```bash
pip install huggingface_hub datasets
```
Then log in with your Hugging Face account:
```bash
huggingface-cli login
```
### 2️⃣ Load Data
```bash
from datasets import load_dataset
ds = load_dataset("YimingZeng/FineEdit_bench")
```

## Citation

If you find this work useful, please cite our paper:

```bibtex
@misc{zeng2025fineeditunlockinstructionbasedtext,
      title={FineEdit: Unlock Instruction-Based Text Editing for LLMs}, 
      author={Yiming Zeng and Wanhao Yu and Zexin Li and Tao Ren and Yu Ma and Jinghan Cao and Xiyan Chen and Tingting Yu},
      year={2025},
      eprint={2502.13358},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2502.13358}, 
}
