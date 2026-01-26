## Pipeline

```bash
Image → |Face detection| → Resize → Flatten
→ PCA projection (Eigenfaces)
→ SVM Classifier
→ Distance to class centroid
→ Threshold → Known (with label) / Unknown
```
