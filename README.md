# VoiceMeeter를 이용한 시스템 소리 녹음 코드

이 프로그램은 스테레오 믹스가 존재하지 않거나 USB 헤드셋을 사용하여 시스템 소리 녹화가 불가능할 때 VoiceMeeter를 사용하여 시스템 오디오를 녹음하는 방법을 제공합니다.

## 필수 요구사항

- VoiceMeeter 설치 필요
- Python 설치

## VoiceMeeter 설치 및 설정

1. [VoiceMeeter 다운로드 및 설치](https://www.vb-audio.com/Voicemeeter/index.htm)
2. 설치 후 소리 설정:
   - 기본 출력 장치를 "Voicemeeter AUX Input"으로 설정
   - VoiceMeeter 내 설정:
     - Hardware OUT: A1, A2, A3 중 하나 선택하여 출력 장치 설정
     - Stereo Input 1, 2, 3 중 하나 사용하여 입력 장치 설정
   - Stereo Input 설정을 통해 마이크 소리 녹음 여부 결정 가능

## 프로그램 사용법

1. 필요한 라이브러리 설치:
   ```
   pip install -r requirements.txt
   ```

2. 녹음 시작:
   ```
   python recordSysSound.py
   ```

3. 녹음이 완료되면 저장된 파일이 생성됩니다.

## 주의사항

VoiceMeeter 설치 후 소리가 나오지 않는다면 추가적인 소리 설정이 필요할 수 있습니다.
