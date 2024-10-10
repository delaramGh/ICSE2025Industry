# Test Input Validation for Vision-based DL Systems: An Active Learning Approach

## Abstract

Testing deep learning (DL) systems requires extensive and diverse, yet valid, test inputs. While synthetic test input generation methods, such as metamorphic testing, are widely used for DL testing, they risk introducing invalid inputs that do not accurately reflect real-world scenarios. Invalid test inputs can lead to misleading results. Hence, there is a need for automated validation of test inputs to ensure effective assessment of DL systems. In this paper, we propose a test input validation approach for vision-based DL systems. Our approach uses active learning to balance the trade-off between accuracy and the manual effort required for test input validation. Further, by employing multiple image-comparison metrics, it achieves better results in classifying valid and invalid test inputs compared to methods that rely on single metrics. We evaluate our approach using an industrial and a public-domain dataset. Our evaluation shows that our multi-metric, active learning-based approach produces several optimal accuracy-effort trade-offs, including those deemed practical and desirable by our industry partner. Furthermore, provided with the same level of manual effort, our approach is significantly more accurate than two state-of-the-art test input validation methods, achieving an average accuracy of 97%. Specifically, the use of multiple metrics, rather than a single metric, results in an average improvement of at least 5.4% in overall accuracy compared to the state-of-the-art baselines. Incorporating an active learning loop for test input validation yields an additional 7.5% improvement in average accuracy, bringing the overall average improvement of our approach to at least 12.9% compared to the baselines.

## Getting Started

This repository contains the code and resources for our research on test input validation for vision-based deep learning systems.

- **Experiments for Research Question 1 (RQ1):** Located in the `RQ1` folder.
- **Experiments for Research Question 2 (RQ2):** Located in the `RQ2` folder.
- **Experiments for Research Question 3 (RQ3):** Located in the `RQ3` folder.
- **Experiments for Baselines:** Located in the `baseline` folder.
- **CIFAR-10 Dataset:** Included as `Cifar10.zip` in the root directory.
