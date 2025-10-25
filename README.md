# MediaEval-Medico-2025 PaliGemma Submissions

This repository contains notebooks for submissions to the **MediaEval-Medico-2025** challenge, focusing on Subtask 1 (GI Image VQA) and Subtask 2 (Visual Answer Localization) using the `google/paligemma-3b-pt-224` model.

**Main Challenge Repo:** 🌐 [MediaEval-Medico-2025](https://github.com/simula/MediaEval-Medico-2025)

---

## 🏥 Subtask 1: GI Image VQA

This notebook fine-tunes **`google/paligemma-3b-pt-224`** on the **Kvasir-VQA-x1** dataset using `ms-swift` for the Gastrointestinal (GI) Image Visual Question Answering (VQA) task.

* **Notebook:** [Task_1_Sample_Notebook_mediaEval.ipynb](https://github.com/sujata-gaihre/MediaEval-Medico-2025-paligemma/blob/master/Task_1_Sample_Notebook_mediaEval.ipynb)
* **Description:** The notebook covers data preparation, a T4-friendly training configuration (QLoRA + LoRA), validation, and inference.

---

## 🏥 Subtask 2: Visual Answer Localization (VAL)

This notebook fine-tunes **`google/paligemma-3b-pt-224`** on the **Kvasir-VQA-L** dataset for the Visual Answer Localization (VAL) task.

* **Notebook:** [sujatagaihre-medico2025-subtask2-teamnepal.ipynb](https://github.com/sujata-gaihre/MediaEval-Medico-2025-paligemma/blob/master/sujatagaihre-medico2025-subtask2-teamnepal.ipynb)
* **Description:** This task focuses on identifying the specific regions in an image that correspond to the answer of a given medical question.

---

## 🚀 How to Run

1.  Open either of the notebooks in a compatible environment (like Google Colab with a T4 GPU or a local Jupyter instance).
2.  Install the required dependencies, including `ms-swift`, `bitsandbytes`, and `wandb`, as specified in the notebooks.
3.  Follow the steps within each notebook for data preparation, authentication (Hugging Face, W&B), training, and inference.
