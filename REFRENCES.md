
## 🔬 References
1. Park et al. (2023)
   
  "Periodontal Disease Classification with Color Teeth Images Using Convolutional Neural Networks." Electronics, 12(7), 1518.
                                    [https://www.mdpi.com/2079-9292/12/7/1518]
   
A) Dataset & Preprocessing
  - Collected 220 frontal RGB images of teeth (82 healthy, 138 with calculus/inflammation) from the internet.
  - Labeled and cropped single-tooth regions using manual annotation tools, verified by dental experts

B) Model Architecture
  - Proposed a custom CNN incorporating parallel 1D convolutional filters alongside traditional 2D conv layers.
  - Compared performance against standard models like ResNet152.

C) Results
  -Achieved 11.45% higher accuracy than ResNet152 — a significant improvement on a small dataset
  - Demonstrated that 1D-2D parallel convs enhance learning efficiency when data is limited.


D) Contributions & Relevance
  - Pioneers use of RGB-only tooth images (vs X-rays), opening avenues for mobile applications in oral healthcare.
  - Validation on a modest dataset underscores the practicality of lightweight CNNs in real-world settings



-------------------------------------------------------------------------------------------------


2. Lee et al. (2018)
   
  "Diagnosis and Prediction of Periodontally Compromised Teeth Using a Deep Learning‑Based Convolutional Neural Network Algorithm." Journal of Periodontal & Implant Science, 48(2), 114–123 
  [https://pubmed.ncbi.nlm.nih.gov/38179345/]
   
A) Dataset & Context
  - Used periapical radiographic images of 224 premolars and molars, clinically diagnosed for periodontally compromised teeth (PCT).
  - Dataset split into train/validation/test: 1,044 / 348 / 348 images

B)  Model Architecture
  - Combined a pretrained backbone with custom CNN layers featuring ReLU, dropout, max-pooling, and three fully connected layers (1,024, 1,024, 512 neurons).
  - Final output was multi-class ROC via softmax.

C) Results
  - Diagnostic accuracy: 81.0% for premolars, 76.7% for molars.
  - Extraction prediction accuracy: 82.8% (premolars), 73.4% (molars) 
  - CNN performance was comparable to expert clinicians, with strong ROC, sensitivity, specificity, and 95% CIs.

E) Contributions & Relevance
  - Demonstrated that a CNN-based CAD system can reliably diagnose and predict outcomes for PCT from radiographs.
  - Provided a basis for evaluation metrics and model validation strategies, including dataset split protocols and clinical comparators, which can inform rigorous training and assessment in your project.

