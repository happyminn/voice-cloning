# Voice Cloning

- Works with the following commit of Real-Time-Voice-Cloning: https://github.com/CorentinJ/Real-Time-Voice-Cloning/commit/95adc699c1deb637f485e85a5107d40da0ad94fc

**Video demonstration**
# ![image](https://github.com/happyminn/voice-cloning/assets/156920075/55c54909-77af-49ed-99ab-e62a6237ead4)

- https://www.youtube.com/watch?v=CVSaByECUYI (Unclear Voice)
- https://www.youtube.com/watch?v=4cmCo3XSVyg (High tone with intonation)
- https://www.youtube.com/watch?v=8XJfo0bYpAM (English to English)

## Setup

### 1. Install Requirements
1. Python 3.7 is recommended. Python 3.5 or greater should work.
3. Install [ffmpeg](https://ffmpeg.org/download.html#get-packages). This is necessary for reading audio files.
4. Install [PyTorch](https://pytorch.org/get-started/locally/).
5. Install the remaining requirements with `pip install -r requirements.txt`

## requirements
﻿inflect==5.3.0
librosa==0.8.1
matplotlib==3.5.1
numpy==1.20.3
Pillow==8.4.0
PyQt5==5.15.6
scikit-learn==1.0.2
scipy==1.7.3
sounddevice==0.4.3
SoundFile==0.10.3.post1
tqdm==4.62.3
umap-learn==0.5.2
Unidecode==1.3.2
urllib3==1.26.7
visdom==0.1.8.9
webrtcvad==2.0.10
