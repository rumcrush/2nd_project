# 2nd_project
## 약용작물 내 흰 곰팡이 탐지 프로그램 

##### 딥러닝의 YOLOv5 모델을 탑재한
##### 재배중인 약용작물 내의 흰 곰팡이 이미지를 탐지하는 프로그램을 
##### 파이썬 스크립트 파일로 만들었습니다. 

##### 프로그램 다운로드 : https://drive.google.com/file/d/16FdL7--Mutgx6eBo0n71wbTkfBtLdiHt/view?usp=sharing

## How to Run

###### 1. Anaconda(www.anaconda.com) Individual Edition을 다운로드 후 설치합니다
###### 테스트에 사용한 버전 : 2021.05버전입니다.

###### 2. 아나콘다 프롬프트를 실행 후 필요한 라이브러를 설치합니다.
###### 아래와 같이 명령어를 입력해주세요.
###### pip install -r requirements.txt

###### 3. 파이썬으로 detect.py를 실행합니다. 
###### yolov3/images 디렉토리에 탐지할 원본이미지를 넣고 다음과 같이 실행시키면 현재 폴더에 result 디렉토리가 만들어집니다. 
###### 그 폴더 안에 곰팡이가 탐지된 이미지가 생성됩니다.

###### --source 옵션은 이미지 파일이 있는 디렉토리를 입력.
###### --project 옵션은 결과 파일이 저장될 디렉토리를 입력.
###### -- conf 옵션은 곰팡이 탐지 신뢰도의 threshold를 의미. 기본값은 0.25.

###### python yolov5/detect.py --source ./yolov5/images --project ./
