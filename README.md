# MLeVLM
MLeVLM: Improve Multi-level Progressive Capabilities based on Multimodal Large Language Model for Medical Visual Question Answering

<div align=center>
<img width="100%" src="imgs/model.pdf"/>
</div>

# Data

- **Stage I Pretrain Data** 
    - [MediCaT](https://github.com/allenai/medicat)
    - [ROCO](https://github.com/razorx89/roco-dataset)
    - [PMC-VQA](https://github.com/xiaoman-zhang/PMC-VQA)
    - [MIMIC-CXR](https://www.physionet.org/content/mimic-cxr/2.0.0/)
- **Stage II Fine-tuning Data**
    - [LLaVA-Med](https://github.com/microsoft/LLaVA-Med)
- **Stage III Level-tuning Data**
    - Preparing.

# Model Checkpoints

- Preparing.

# Acknowledgement

We would like to thank the following repos for their great work:

- This work is built upon [LLaVA](https://github.com/haotian-liu/LLaVA), [LLaMA-VID](https://github.com/dvlab-research/LLaMA-VID) and [LaVIT](https://github.com/jy0205/LaVIT).
- This work utilizes pretrained weights from [Vicuna](https://github.com/lm-sys/FastChat) and [InstructBLIP](https://github.com/salesforce/LAVIS).

# License

The data and checkpoint is intended and licensed for research use only. They are also restricted to uses that follow the license agreement of LLaVA, LLaMA, Vicuna and GPT-4. The dataset is CC BY NC 4.0 (allowing only non-commercial use) and models trained using the dataset should not be used outside of research purposes.