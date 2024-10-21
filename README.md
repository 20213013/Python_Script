# 인간과컴퓨터상호작용(01)
## Python Script 활용
### 20213013 컴퓨터공학과 김어진


#### Colab환경

1. Visual Studio Code(VSC)를 자신의 로컬 컴퓨터(노트북)에 설치
2. VSC를 활용해서 파이썬 스크립트(py) 작성
3. 해당 스크립트(py)를 Colab에 업로드
4. 실행해보기

//원 드라이브로 공유된 zip 파일을 Colab(혹은 Kaggle)에서 직접 다운로드
!wget "https://glosoriaimy.sharepoint.com/personal/cjchun_glosori_com/_layouts/15/download.as
px?share=EfMOsIgfjadEgVK_y8f3gAMBcUfLBsM-QyMIZtHGrOIp3A" -O data.zip
//data.zip 파일을 data라는 폴더에 압축풀기
!unzip -q data.zip -d data
//data.zip 파일 및 data 폴더가 다운로드 및 생성되었는지 확인
!ls -al


#### Kaggle(Git)활용

1. Visual Studio Code(VSC)를 자신의 로컬 컴퓨터(노트북)에 설치
2. VSC를 활용해서 파이썬 스크립트(py) 작성
3. 자신의 git repository 생성 후, 파이썬 스크립트(py) 커밋(commit) 및 푸쉬(push)
4. 해당 스크립트(py)를 Kaggle에서 clone함
• !git clone https://github.com/amclchosun/acoustic_scene_classification.git src
5. 실행해보기
• !python src/main.py

//해당 레포지토리에 있는 내용(파일)을 src 폴더에 다운로드(clone)
//본 레포지토리 주소는 삭제하였으니, 자신의 주소로 변경하자!
!git clone https://github.com/20213013/Python_Script.git src
//제대로 다운로드가 되었는지 확인
!ls -R -l src
//파이썬 스크립트 실행
!python src/main.py


#### 정확도 91.8
