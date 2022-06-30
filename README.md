# GrooVAE

## 과제 개요
Groove MIDI Dataset을 이용하여 4마디에 해당하는 드럼 샘플을 뽑아내는 과정을 수행하였습니다.

- 깃헙 코드: https://github.com/magenta/magenta/tree/master/magenta/models/music_vae
- 관련 논문: https://arxiv.org/pdf/1803.05428.pdf
- 관련 데이터: https://magenta.tensorflow.org/datasets/groove

## 논문 리뷰 & 참고자료
노션 페이지에 논문 리뷰, 참고자료를 정리해놓았습니다.

https://rustic-force-2ee.notion.site/MusicVAE-a299f45c426e4383a414eb51a2db5e32

## 드럼 샘플 audio play
생성한 드럼 샘플의 연주가는 colab 페이지를 통해 들을실 수 있습니다!
- groove/4bar-midionly 데이터로 학습한 케이스
  - https://colab.research.google.com/drive/1niRPF2B58azemJa5So27BPmCs5vynVDt?usp=sharing
- groove/full-midionly 데이터로 학습한 케이스
  - https://colab.research.google.com/drive/1WKH7IpU62LN1JUtkR3m89HyRMrLO6FPB?usp=sharing

## 문제사항
- groove/full-midionly 데이터로 학습한 케이스에서 처음에 재생할 떄 ValueError가 발생했지만 아직 해결하지 못하였습니다.
