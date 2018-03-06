# Text-to-Speech Synthesis
딥러닝을 이용한 음성합성 관련 자료 모음

## Lectures & Seminars
* [책 읽어주는 딥러닝 (김태훈, 2017.11)](http://tv.naver.com/v/2292650)
  * Tacotron에 대해 쉽게 이해할 수 있도록 DEVIEW 2017에서 발표한 영상
* [모두의 연구소 WaveNet 스터디 영상 (김승일, 2017.10)](https://youtu.be/GyQnex_DK2k)
  * WaveNet에 대해 이해한 것을 설명 및 온라인 토론내용이 담긴 영상
* [Generative Model-Based Text-to-Speech Synthesis (Heiga Zen, 2017.02)](https://youtu.be/nsrSrYtKkT8)
  * WaveNet 논문 저자 중 1명인 Heiga Zen이 소개하는 TTS 전반적인 기술 및 WaveNet 소개 영상
  
## Dataset
* [CMU_ARCTIC (en)](http://festvox.org/cmu_arctic/)
  * CMU의 Language Technologies Institute에서 음성합성 연구를 위해 만든 US English 데이터셋
* [The LJ Speech Dataset (en)](https://keithito.com/LJ-Speech-Dataset/)
  * Keith Ito란 사람의 웹사이트에 올라와 있지만 어디서, 왜 만들었는지에 대한 내용은 찾지 못함
* [Blizzard 2012 (en)](http://www.cstr.ed.ac.uk/projects/blizzard/2012/phase_one/)
  * Blizzard Challenge 2012라는 코퍼스기반 음성합성 챌린지에서 사용된 데이터셋
* [CSTR VCTK Corpus (en)](http://homepages.inf.ed.ac.uk/jyamagis/page3/page58/page58.html)
  * English Multi-speaker Corpus for CSTR Voice Cloning Toolkit 
  
## WaveNet
### Paper
* [WaveNet: A Generative Model for Raw Audio (2016.09)](https://arxiv.org/abs/1609.03499)

### Articles
* [WaveNet: A Generative Model for Raw Audio (DeepMind Blog)](https://deepmind.com/blog/wavenet-generative-model-raw-audio/)

### Source Code
* https://github.com/ibab/tensorflow-wavenet
* https://github.com/r9y9/wavenet_vocoder (PyTorch)
* https://github.com/kan-bayashi/PytorchWaveNetVocoder (PyTorch)
  * [WaveNet Vocoder Samples](https://kan-bayashi.github.io/WaveNetVocoderSamples/)

## Fast WaveNet
### Paper
* [Fast Wavenet Generation Algorithm (2016.11)](https://arxiv.org/abs/1611.09482)

### Articles

### Source Code
* https://github.com/tomlepaine/fast-wavenet
* https://github.com/dhpollack/fast-wavenet.pytorch (PyTorch)

## Parallel WaveNet 
### Paper
* [Parallel WaveNet: Fast High-Fidelity Speech Synthesis (2017.11)](https://arxiv.org/abs/1711.10433)

### Articles
* [High-fidelity speech synthesis with WaveNet (DeepMind Blog)](https://deepmind.com/blog/high-fidelity-speech-synthesis-wavenet/) 
### Source Code
* https://github.com/kensun0/Parallel-Wavenet (not a complete implement)


## Deep Voice
### Paper
* [Deep Voice: Real-time Neural Text-to-Speech (2017.02)](https://arxiv.org/abs/1702.07825)

## Deep Voice 2
### Paper
* [Deep Voice 2: Multi-Speaker Neural Text-to-Speech (2017.05)](https://arxiv.org/abs/1705.08947)

## Deep Voice 3
### Paper
* [Deep Voice 3: Scaling Text-to-Speech with Convolutional Sequence Learning (2017.10)](https://arxiv.org/abs/1710.07654)

### Source Code
* https://github.com/Kyubyong/deepvoice3

## Tacotron
### Paper
* [Tacotron: Towards End-to-End Speech Synthesis (2017.05)](https://arxiv.org/abs/1703.10135)

### Source Code
* https://github.com/keithito/tacotron
* https://github.com/Kyubyong/tacotron
* https://github.com/barronalex/Tacotron

## Tacotron 2
### Paper
* [Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions (2017.12)](https://arxiv.org/abs/1712.05884)

### Source Code
* https://carpedm20.github.io/tacotron/ (한국어 버전)
* https://github.com/riverphoenix/tacotron2 (구현됨)
* https://github.com/Rayhane-mamah/Tacotron-2 (구현중)
* https://github.com/selap91/Tacotron2 (구현중)
* https://github.com/maozhiqiang/tacotron_cn (구현 확인 필요/중국어)
* https://github.com/LGizkde/Tacotron2_Tao_Shujie (체크 필요)
* https://github.com/ruclion/tacotron_with_style_control (Style Control)

