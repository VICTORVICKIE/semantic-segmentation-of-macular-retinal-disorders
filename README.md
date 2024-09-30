# **OCT image segmentation**


1.   U-Net
  *   Optimizer - Adam with Learning Rate = 0.0001 (i.e) 1 * $e^{-4}$
  *   Loss - Categorical Focal Loss with Gamma ($\gamma$) = 2.8

2.   Attention Residual U-Net
  *   Optimizer - Adam with Leraning Rate = 0.001 (i.e) 1 * $e^{-3}$
  *   Loss - Categorical Focal Loss with Gamma ($\gamma$) = 3.0

3.   Attention Residual U-Net++
  *   Optimizer - SGD with Leraning Rate = 0.1 (i.e) 1 * $e^{-1}$
  *   Loss - Categorical Focal Loss with Gamma ($\gamma$) = 3.0

Image Resolution = 512 x 256

Batch size = 2

---
