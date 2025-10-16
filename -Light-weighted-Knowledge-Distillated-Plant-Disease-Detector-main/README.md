# -Light-weighted-Knowledge-Distillated-Plant-Disease-Detector

 Abstract :
 Plant disease detection is critical for sustainable agriculture
 and food security, yet deploying deep learning models in real-world set
tings remains challenging due to domain shifts between laboratory and
 field conditions and the computational burden of large architectures. We
 present AgroXact, a lightweight and deployable framework that lever
ages knowledge distillation for robust plant disease detection and sever
ity estimation on edge devices. To capture diverse visual conditions,
 we construct a hybrid benchmark by merging PlantVillage (lab) and
 PlantDoc (field) datasets. A high-capacity teacher model (EfficientNet
B4) is trained, and its knowledge is distilled into a compact student
 model (EfficientNet-B0), optimized for real-time performance. We sys
tematically evaluate multiple distillation strategies—cross-entropy, KL
divergence, feature-based, attention-based, relational KD, and hybrid ap
proaches—identifying Attention+CE as the optimal trade-off, achieving
 95.6% accuracy with substantial model size and latency reductions. Ad
ditionally, a novel confidence-based severity estimation module predicts
 disease progression without extra labels. AgroXact demonstrates how
 leveraging object-text relationships can boost baseline performance with
 minimal architectural changes, enabling practical deployment in agricul
ture.

The source code for the android application can be accessed [here](https://drive.google.com/drive/folders/1yb2gMtevWZHMMeDI-DEq4O4iJCcoRI_h?usp=sharing).
