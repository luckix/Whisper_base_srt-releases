# 초벌 스탬프 — 설치 파일 배포

Whisper 기반 초벌 타임스탬프 추출기 **초벌 스탬프**의 Windows 설치 파일을 배포하는 저장소입니다.

## 내려받기

[최신 릴리즈](https://github.com/luckix/Whisper_base_srt-releases/releases/latest)에서 `ChobeolStamp-Setup-<버전>.exe` 를 내려받아 실행하세요.

- Windows 10/11 64비트, 관리자 권한 없이 설치됩니다.
- Whisper 모델은 처음 쓸 때 내려받습니다 (tiny 75MB ~ large-v3 3GB).
- NVIDIA GPU 가 있으면 처음 쓸 때 GPU 가속 구성요소(약 570MB)를 한 번 내려받습니다. 없으면 CPU 로 동작합니다.
- 설정·모델·작업 결과는 `%LOCALAPPDATA%\ChobeolStamp` 에 저장되며 제거해도 남습니다.
- 앱은 시작할 때 이 저장소의 최신 릴리즈를 확인해 업데이트를 알려 줍니다.

각 릴리즈 설명의 `SHA-256` 으로 내려받은 파일을 검증할 수 있습니다.
