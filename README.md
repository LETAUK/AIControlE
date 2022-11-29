손의 좌표를 [mediapipe](https://google.github.io/mediapipe/) 모듈로 손의 마디를 좌표로 인식한후  
인공지능(AI)으로 학습시켜서 램프를 키는 프로젝트입니다.

아래 유사 프로젝트들의 소스코드를 적극 활용하였습니다.

* [gesture-recognition by kairess](https://github.com/kairess/gesture-recognition)

# 프로젝트 실행 과정

학습
1. 데이터셋.py 를 실행시킨후 웹캠으로 0도 90도 180도에 대한 데이터셋을 만듭니다.
2. 머신러닝.ipynb를 순서대로 실행시켜 ai를 학습합니다.

실행
1. 웹캠과 아두이노를 연결한후 손가락 방향을 바꾸면서 각도가 바뀌면 램프가 바뀌는지 확인한다.
<img src="https://github.com/LETAUK/AIControlE/blob/main/img/0s.JPG" width="300" height="200">
<img src="https://github.com/LETAUK/AIControlE/blob/main/img/90s.JPG" width="300" height="200">
<img src="https://github.com/LETAUK/AIControlE/blob/main/img/180s.JPG" width="300" height="200">

|파일명|설명|
|------|---|
|dataset폴더|데이터셋을 저장하는 폴더입니다|
|models.h5|학습시킨 AI 모델입니다|
|sketch_nov15a폴더|아두이노 파일입니다|
|데이터셋.py|데이터셋을 만드는 실행파일입니다|
|머신러닝.ipynb|AI학습을 시키는파일입니다|
|실행.py|AI를 실행시키는 파일입니다|
