### Selected Models and Augmentation Strategies

#### 📌 Final Submission: `Starter_Notebook_8625.ipynb`
- **Public Score Selected**: Yes
- **Final Test Accuracy**: **0.84375**
- **Augmentation Methods Used**:
  1. Synonym replacement
  2. Deletion
  3. Word swap
  4. Paraphrasing
  5. Noise injection

#### 🧪 Alternative Model: `Starter_Notebook_sentiment.ipynb`
- **Slightly Higher Public Score**
- **Final Test Accuracy**: **0.84425**
- **Augmentation Methods Used**:
  1. Synonym replacement
  2. Deletion
  3. Word swap
  4. Paraphrasing
  5. Noise injection
  6. Sentiment-based augmentation

#### 🔀 Experimental Model: `Starter_Notebook_shuffle.ipynb`
- **Final Test Accuracy**: **0.84325**
- **Augmentation Methods Used**:
  1. Synonym replacement
  2. Deletion
  3. Word swap
  4. Sentence shuffling
  5. Noise injection

#### /Experiments: `Version1_r4_lora8.ipynb`
- **Final Test Accuracy**: **0.91719**
- **Parameters Used**:
   1. r=4,
   2. lora_alpha=8,

#### /Experiments: `Version1_r4_lora16.ipynb`
- **Final Test Accuracy**: **0.92344**
- **Parameters Used**:
   1. r=4,
   2. lora_alpha=16

#### /Experiments: `Version1_r8_lora32.ipynb`
- **Final Test Accuracy**: **0.91875**
- **Parameters Used**:
   1. r=8,
   2. lora_alpha=32

> ⚠️ *Incorporating sentiment-based augmentation did **not** lead to further improvement in performance for this model.*




> 💡 *All notebooks in this section focus entirely on data augmentation to boost performance.*
