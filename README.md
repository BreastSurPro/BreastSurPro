BreastSurPro: A multimodal deep survival model for breast cancer
🧬 Model Architecture
Input (n features)
   ↓
Dense (256) → BatchNorm → ReLU → Dropout(0.4)
   ↓
Dense (128) → BatchNorm → ReLU → Dropout(0.3)
   ↓
Dense (64) → ReLU
   ↓
Output (T time bins, softmax)
