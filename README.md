# Cross-speaker Emotion Intensity Control Using Speaker-agnostic Emotion Vector

**Paper**: [arxiv]()  
**Authors**: Masato Murata, Koichi Miyazaki, Tomoki Koriyama  
**Affiliation**: CyberAgent, Japan

**Abstract**: In this paper, we focus on a task in emotion intensity control,  
referred to as "cross-speaker emotion intensity control."  
This task aims to generate emotional speech with various intensities  
using only the neutral reading-style speech of target speakers.  
For this task, we propose a method based on "Emotion Arithmetic,"  
which directly edits model parameters to control emotion intensity.  
While Emotion Arithmetic could control the same-speaker emotion intensity  
using a single-speaker emotion vector, it lost speaker consistency in the cross-speaker setting.  
To address this issue, we propose a speaker-agnostic emotion vector  
created by pre-trained and fine-tuned multi-speaker text-to-speech (TTS) models.  
Additionally, we introduce an x-vector-based multi-speaker TTS model  
to the speaker-agnostic emotion vector to achieve unseen cross-speaker emotion intensity control.  
Our experimental results demonstrate that the proposed method can perform  
cross-speaker emotion intensity control while maintaining speech quality,  
speaker consistency, and controllability, even in the unseen cross-speaker case.

## Speech Samples
