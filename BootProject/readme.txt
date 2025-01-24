#AI 이미지 생성앱(python 3.10.11)

새로운 PC에서 다음 명령어 실행(cmd):
pip install flask flask_cors pillow torch torchvision torchaudio diffusers huggingface-hub transformers rembg onnxruntime
패키지 일괄다운로드

GPU 사용시
cmd nvidia-smi
맨오른쪽 상단 CUDA 버전 확인 (예: CUDA Version: 12.7 )

cmd explorer.exe
바탕화면으로 가는 명령어
이후 팝업창 출력 후 폴더 선택 후 app.py 실행

!!절대 app.py를 IDLE로 실행하지말것.안돌아감

http://127.0.0.1:5000
접속