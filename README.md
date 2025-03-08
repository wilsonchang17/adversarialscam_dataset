## Dataset Description

### 1. **Fine-tuning Dataset**
- **Filename:** `training.csv`
- **Purpose:** Used for fine-tuning the language model.
- **Content:**
  - Contains **approximately 20,000 messages**, including:
    - Adversarial scam messages
    - Regular scam messages
    - Non-scam messages
- **Note:** Messages are carefully balanced and augmented to enhance model robustness.

---

### 2. **Testing Dataset**
- **Filename:** `testing.xlsx`
- **Purpose:** Used for evaluating model performance.
- **Content:**
  - Contains **approximately 1,200 messages**, including:
    - Adversarial scam messages
    - Regular scam messages
    - Non-scam messages
- **Note:** Ensures no overlap with the fine-tuning dataset to provide an unbiased assessment of model generalization.
