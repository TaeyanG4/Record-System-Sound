스트레오 믹스가 존재하지 않거나, USB헤드셋을 사용하여 시스템 소리녹화가 불가능할 때 녹음하기 위한 코드입니다.
VoiceMeeter를 사용하여 시스템 오디오를 녹음하는 방법이므로 필수적으로 voiceMeeter가 설치되어 있어야 합니다.
VoiceMeeter 설치 후 VoiceMeeter 가상 입력 장치를 찾아서 녹음을 진행합니다. 설치 및 설정은 아래 링크를 참조하세요.
VoiceMeeter 설치: https://www.vb-audio.com/Voicemeeter/index.htm
VoiceMetter 설치 후 소리가 나오지 않는다면 소리 설정을 따로 해주셔야 합니다.
소리출력을 위한 출력 장치는 기본적으로 Voicemeeter AUX Input으로 설정합니다.
VoiceMetter 내에서의 설정은 Hardware OUT에서 A1, A2, A3중 하나를 선택하여 출력 장치를 설정하고, 
Stereo Input1, 2, 3중 하나를 사용하여 입력 장치를 설정합니다.
Stereo Input 설정을 통해 본인의 마이크 소리를 같이 녹음할지 안할지 설정할 수 있습니다.

프로그램 사용법은 cmd 창에서 파이썬이 설치되어 있다는 가정하에 진행합니다.
'pip install -r requirements.txt'를 입력하여 필요한 라이브러리를 설치합니다.
cmd창에서 python recordSysSound.py를 입력하면 녹음이 시작되고, 녹음이 완료되면 저장된 파일이 생성됩니다.