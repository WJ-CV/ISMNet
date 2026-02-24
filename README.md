# ISMNet
	
Intra-modality self-enhancement mirror network for RGB-T salient object detection
---
This paper has been online published by IEEE Transactions on Circuits and Systems for Video Technology.

[Paper link](https://ieeexplore.ieee.org/abstract/document/10740324)  DOI: 10.1109/TCSVT.2024.3489440

Abstract
---
The inherent imaging properties of sensors result in two distinct differences between the data from the two modalities in RGB-T Salient Object Detection (SOD) tasks. Namely, differences in imaging effectiveness due to varying sensitivities to specific scenes and fundamental domain differences resulting from differences in reflecting scene characteristics. Existing methods primarily focus on pursuing unique cross-modal fusion designs to enhance model performance. However, not only do direct cross-modal fusion modes fail to improve the effectiveness of original features, but intricate cross-modal fusion designs also increase the domain differences between modalities, thereby resulting in suboptimal performance. Therefore, in this paper, we no longer insist on pursuing unique cross-modal fusion designs but instead contemplate how to enhance the effectiveness of original features within modalities (mitigating differences in imaging effectiveness) and utilize a concise cross-modal fusion mechanism (alleviating the impact of domain differences) to achieve satisfactory performance. In this spirit, we propose the Intra-modality Self-enhancement Mirror Network (ISMNet) for RGB-T salient object detection. The core of ISMNet is the proposed Intra-modality Cross-scale Self-enhancement Module (ICSM). The main insight of ICSM is to exploit saliency clues by modeling the correlation between intra-modality cross-scale features (which exhibit strong correlations and small domain differences), thereby enhancing the effectiveness of original multi-scale features within modalities. We employ the proposed novel paradigm to mirror-expand existing typical paradigms to obtain a more robust model architecture. Extensive experiments demonstrate that our proposed new architecture and the introduced universal Intra-modality Cross-scale Self-enhancement Module effectively improve the effectiveness of original features and promote the achievement of state-of-the-art performance.

Network Architecture
---
<img width="3406" height="1457" alt="fig 3" src="https://github.com/user-attachments/assets/cda1b3d1-d249-4786-ba29-cbed7047ef9a" />

Intra-modality Cross-scale Self-enhancement Module
---
<img width="1269" height="1672" alt="fig 4" src="https://github.com/user-attachments/assets/e879325f-e62e-47ae-bf1c-7253acdf3015" />

Citation
===
```
@article{wang2024intra,
  title={Intra-modality self-enhancement mirror network for RGB-T salient object detection},
  author={Wang, Jie and Li, Guoqiang and Yu, Hongjie and Xi, Jinwen and Shi, Jie and Wu, Xueying},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  volume={35},
  number={3},
  pages={2513--2525},
  year={2024},
  publisher={IEEE}
}
```
