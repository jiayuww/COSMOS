## Results Breakdown on Task Hellaswag

#### Table A.1: Predicted performance and cost given by COSMOS and actual performance and cost corresponding to each strategy within the low cost level

| Cost Level | Strategy | Data Portion | Iter | # shots | Pred. Acc | Act. Acc | Predicted Cost | Act. Cost |
|------------|---------------|---------|------------|---------|-------------------|----------------|----------------|-------------|
| Low | QLoRA | 0.1 | 4 | - | 0.894 | 0.894 | 0.181 | 0.181 |
| Low | QLoRA | 0.1 | 5 | - | 0.890 | 0.890 | 0.201 | 0.200 |
| Low | QLoRA | 0.1 | 6 | - | 0.885 | 0.885 | 0.221 | 0.220 |
| Low | QLoRA | 0.1 | 7 | - | 0.882 | 0.882 | 0.240 | 0.239 |
| Low | QLoRA | 0.1 | 8 | - | 0.875 | 0.875 | 0.260 | 0.259 |
| Low | QLoRA | 0.2 | 4 | - | 0.898 | 0.922 | 0.259 | 0.258 |
| Low | QLoRA | 0.2 | 5 | - | 0.893 | 0.907 | 0.298 | 0.297 |
| Low | QLoRA | 0.2 | 6 | - | 0.888 | 0.909 | 0.337 | 0.336 |
| Low | QLoRA | 0.2 | 7 | - | 0.885 | 0.910 | 0.376 | 0.375 |
| Low | QLoRA | 0.2 | 8 | - | 0.878 | 0.907 | 0.415 | 0.413 |
| Low | QLoRA | 0.3 | 4 | - | 0.905 | 0.923 | 0.337 | 0.335 |
| Low | QLoRA | 0.3 | 5 | - | 0.900 | 0.921 | 0.395 | 0.393 |
| Low | QLoRA | 0.3 | 6 | - | 0.895 | 0.916 | 0.454 | 0.452 |
| Low | QLoRA | 0.3 | 7 | - | 0.892 | 0.912 | 0.512 | 0.510 |
| Low | QLoRA | 0.3 | 8 | - | 0.885 | 0.914 | 0.571 | 0.567 |
| Low | QLoRA | 0.4 | 4 | - | 0.908 | 0.934 | 0.415 | 0.414 |
| Low | QLoRA | 0.4 | 5 | - | 0.903 | 0.931 | 0.494 | 0.491 |
| Low | QLoRA | 0.4 | 6 | - | 0.898 | 0.927 | 0.572 | 0.569 |
| Low | QLoRA | 0.4 | 7 | - | 0.895 | 0.927 | 0.650 | 0.647 |
| Low | QLoRA | 0.4 | 8 | - | 0.888 | 0.919 | 0.728 | 0.724 |
| Low | QLoRA | 0.5 | 4 | - | 0.910 | 0.930 | 0.494 | 0.477 |
| Low | QLoRA | 0.5 | 5 | - | 0.906 | 0.933 | 0.592 | 0.570 |
| Low | QLoRA | 0.5 | 6 | - | 0.901 | 0.928 | 0.690 | 0.664 |
| Low | QLoRA | 0.6 | 4 | - | 0.915 | 0.940 | 0.573 | 0.570 |
| Low | QLoRA | 0.6 | 5 | - | 0.911 | 0.930 | 0.690 | 0.687 |
| Low | QLoRA | 0.7 | 4 | - | 0.921 | 0.937 | 0.651 | 0.648 |
| **Low** | **QLoRA** | **0.8** | **4** | - | **0.921** | **0.944** | **0.728** | **0.725** |
| Low | ICL | - | - | 1 | 0.526 | 0.526 | 0.177 | 0.219 |
| Low | ICL | - | - | 2 | 0.591 | 0.627 | 0.262 | 0.326 |
| Low | ICL | - | - | 4 | 0.617 | 0.604 | 0.432 | 0.538 |

COSMOS accurately predicts that QLoRA finetuning with 0.8 portion of data for 4 iterations yields optimal performance within the low cost budget. This strategy achieves the highest predicted accuracy (0.921) among all 30 available strategies, and validation confirms it indeed delivers the best actual performance (0.944). COSMOS predicts this strategy will cost 0.728, closely matching the actual cost of 0.725.

#### Table A.2: Predicted performance and cost given by COSMOS and actual performance and cost corresponding to each strategy within the medium cost level

| Cost Level | Strategy | Data Portion | Iter | # shots | Pred. Acc | Act. Acc | Predicted Cost | Act. Cost |
|------------|---------------|---------|------------|---------|-------------------|----------------|----------------|-------------|
| Medium | QLoRA | 0.5 | 7 | - | 0.898 | 0.926 | 0.787 | 0.758 |
| Medium | QLoRA | 0.5 | 8 | - | 0.891 | 0.919 | 0.885 | 0.851 |
| Medium | QLoRA | 0.6 | 6 | - | 0.906 | 0.933 | 0.807 | 0.803 |
| Medium | QLoRA | 0.6 | 7 | - | 0.903 | 0.926 | 0.925 | 0.920 |
| Medium | QLoRA | 0.6 | 8 | - | 0.896 | 0.922 | 1.042 | 1.037 |
| Medium | QLoRA | 0.7 | 5 | - | 0.917 | 0.933 | 0.788 | 0.784 |
| Medium | QLoRA | 0.7 | 6 | - | 0.911 | 0.928 | 0.924 | 0.920 |
| Medium | QLoRA | 0.7 | 7 | - | 0.908 | 0.929 | 1.061 | 1.056 |
| Medium | QLoRA | 0.7 | 8 | - | 0.901 | 0.926 | 1.198 | 1.192 |
| Medium | QLoRA | 0.8 | 5 | - | 0.917 | 0.936 | 0.884 | 0.880 |
| Medium | QLoRA | 0.8 | 6 | - | 0.912 | 0.934 | 1.041 | 1.036 |
| Medium | QLoRA | 0.8 | 7 | - | 0.909 | 0.930 | 1.197 | 1.191 |
| Medium | QLoRA | 0.9 | 4 | - | 0.925 | 0.941 | 0.807 | 0.803 |
| Medium | QLoRA | 0.9 | 5 | - | 0.921 | 0.936 | 0.983 | 0.978 |
| Medium | QLoRA | 0.9 | 6 | - | 0.915 | 0.929 | 1.158 | 1.153 |
| Medium | QLoRA | 1 | 4 | - | 0.931 | 0.937 | 0.886 | 0.881 |
| Medium | QLoRA | 1 | 5 | - | 0.928 | 0.939 | 1.081 | 1.076 |
| Medium | ICL | - | - | 8 | 0.620 | 0.620 | 0.772 | 0.965 |

#### Table A.3: Predicted performance and cost given by COSMOS and actual performance and cost corresponding to each strategy within the high cost level

| Cost Level | Strategy | Data Portion | Iter | # shots | Pred. Acc | Act. Acc | Predicted Cost | Act. Cost |
|------------|---------------|---------|------------|---------|-------------------|----------------|----------------|-------------|
| High | QLoRA | 0.8 | 8 | - | 0.902 | 0.927 | 1.353 | 1.346 |
| High | QLoRA | 0.9 | 7 | - | 0.913 | 0.926 | 1.334 | 1.327 |
| High | QLoRA | 0.9 | 8 | - | 0.906 | 0.926 | 1.510 | 1.502 |
| High | QLoRA | 1 | 6 | - | 0.920 | 0.931 | 1.277 | 1.270 |
| High | QLoRA | 1 | 7 | - | 0.917 | 0.933 | 1.472 | 1.465 |
| High | QLoRA | 1 | 8 | - | 0.910 | 0.929 | 1.668 | 1.659 |
| High | ICL | - | - | 16 | 0.620 | 0.611 | 1.452 | 1.815 |