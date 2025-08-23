# *FineEdit*: Bridging the Editing Gap in LLMs
Large Language Models (LLMs) have transformed natural language processing, yet they still struggle with direct text editing tasks that demand precise, context-aware modifications. While models like ChatGPT excel in text generation and analysis, their editing abilities often fall short, addressing only superficial issues rather than deeper structural or logical inconsistencies. In this work, we introduce a dual approach to enhance LLMs editing performance. First, we present InstrEditBench, a high-quality benchmark dataset comprising over 20,000 structured editing tasks spanning Wiki articles, LaTeX documents, code, and database Domain-specific Languages (DSL). InstrEditBench is generated using an innovative automated workflow that accurately identifies and evaluates targeted edits, ensuring that modifications adhere strictly to specified instructions without altering unrelated content. Second, we propose FineEdit, a specialized model trained on this curated benchmark. Experimental results demonstrate that FineEdit achieves significant improvements around {10%} compared with Gemini on direct editing tasks, convincingly validating its effectiveness.


The code for **EMNLP 2025** paper: [Bridging the Editing Gap in LLMs: FineEdit for Precise and Targeted Text Modifications](https://arxiv.org/abs/2502.13358).

📄 [Paper](https://arxiv.org/abs/2502.13358) · 💻 [Github](https://github.com/StuRinDQB/FineEdit) · 🤗 [Huggingface](https://example.com)

---

**If you find our project helpful, please give us a star ⭐ on GitHub to stay updated.**

---

![FineEdit Framework](https://github.com/user-attachments/assets/dde2c4d6-60be-4cbe-90b2-b3764f67410a)

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
